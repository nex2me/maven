maven
=====
nex2me maven repository 

Uso de dependências do repositório Maven no seu projeto
-------------------------------------------------------

A seguir um exemplo de uso da dependência *controle-acesso* do repositório Maven na nex2me. 
Basta configurar a API como dependência do seu projeto no arquivo pom.xml:

```xml
<project xmlns="http://maven.apache.org/POM/4.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
	xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 http://maven.apache.org/xsd/maven-4.0.0.xsd">
  ...
  <!-- In Project repository -->
  <repositories>
    <repository>
      <id>npi-mvn-repo</id>
      <url>http://nex2me.github.io/maven/</url>
    </repository>
  </repositories>
  ...
  <dependencies>
    ...
    <dependency>
      <groupId>seguranca</groupId>
      <artifactId>controle-acesso</artifactId>
      <version>5.0</version>
    </dependency>
    ...
  </dependencies>
  ...
</project>
```
