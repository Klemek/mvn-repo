# mvn-repo

Import my librairies into your projects easily in your `pom.xml`

```XML
<repositories>
    ...
    <repository>
        <id>fr.klemek</id>
        <url>https://github.com/klemek/mvn-repo/raw/master</url>
    </repository>
</repositories>

<dependencies>
    ...
    <dependency>
        <groupId>fr.klemek</groupId>
        <artifactId>betterlists</artifactId>
        <version>1.4</version>
    </dependency>
    <dependency>
        <groupId>fr.klemek</groupId>
        <artifactId>french-sentences-gen</artifactId>
        <version>1.0</version>
    </dependency>
</dependencies>
```
