## Estudos de Java Web
![GitHub language count](https://img.shields.io/github/languages/count/iuridev/aluraJavaWeb?style=plastic) ![GitHub top language](https://img.shields.io/github/languages/top/iuridev/aluraJavaWeb?style=plastic) 

Iniciando estudos com java para web, usando o JPA como uma especificação e Hibernate como implementação.
 
 Arquivo XML com configurações do projeto:

    pom.xml

Incluindo a dependência do Hibernate no arquivo `pom.xml`, automaticamente a biblioteca JPA será  inclusa nas dependências do projeto. 

        <dependency>
            <groupId>org.hibernate</groupId>
            <artifactId>hibernate-entitymanager</artifactId>
            <version>5.4.27.Final</version>
        </dependency>

Incluindo a dependência do Driver do Banco de Dados, pelo qual será usado nesse projeto de estudo:

    <dependency>  
	     <groupId>com.h2database</groupId>  
	     <artifactId>h2</artifactId>  
	     <version>1.4.200</version>  
    </dependency>
