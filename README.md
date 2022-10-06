# Network

### Introduction

Network components used within NukkitX.

### Maven

##### Repository:

```xml

<repositories>
    <repository>
        <id>maven-powernukkitx-cn</id>
        <url>https://maven.powernukkitx.cn/repository/maven-public/</url>
        <releases>
            <enabled>true</enabled>
        </releases>
        <snapshots>
            <enabled>true</enabled>
        </snapshots>
    </repository>
</repositories>
```

##### Dependencies:

```xml
    <dependencies>
    <dependency>
        <groupId>org.powernukkit.bedrock.network</groupId>
        <artifactId>query</artifactId>
        <version>1.6.28-PNX.5</version>
        <scope>compile</scope>
        </dependency>
    <dependency>
        <groupId>org.powernukkit.bedrock.network</groupId>
        <artifactId>raknet</artifactId>
        <version>1.6.28-PNX.5</version>
        <scope>compile</scope>
        </dependency>
    <dependency>
        <groupId>org.powernukkit.bedrock.network</groupId>
        <artifactId>rcon</artifactId>
        <version>1.6.28-PNX.5</version>
        <scope>compile</scope>
        </dependency>
    </dependencies>
```