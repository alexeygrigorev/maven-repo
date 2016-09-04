# maven-repo

Artifacts not available on Maven Central. To use it, add the following to the `<repository>` section:

    <repository>
      <id>java-ds</id>
      <url>https://raw.githubusercontent.com/alexeygrigorev/maven-repo/master/</url>
    </repository>

It has the following artifacts:

JavaML:

    <dependency>
      <groupId>net.sourceforge</groupId>
      <artifactId>javaml</artifactId>
      <version>0.1.7</version>
    </dependency>


Abeel Java Toolkit: (a dependency for JavaML)

    <dependency>
      <groupId>be.abeel</groupId>
      <artifactId>ajt</artifactId>
      <version>2.9</version>
    </dependency>
