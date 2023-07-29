### MMOCore官方仓库

#### 使用MMOCore作为依赖项
注册PhoenixDev仓库：
```xml
<repository>
    <id>phoenix</id>
    <url>https://nexus.phoenixdevt.fr/repository/maven-public/</url>
</repository>
```

然后将MMOCore-API添加为依赖项：
```xml
<dependency>
    <groupId>net.Indyuce</groupId>
    <artifactId>MMOCore-API</artifactId>
    <version>1.12-SNAPSHOT</version>
    <scope>provided</scope>
</dependency>
```

以上是在您的项目中使用MMOCore作为依赖项的步骤。请将上述XML代码添加到您项目的pom.xml文件中。通过这样的配置，您的项目将能够使用MMOCore-API作为提供的依赖项，这意味着MMOCore库将在运行时由服务器提供。确保将`1.12-SNAPSHOT`替换为您想要使用的MMOCore-API的适当版本。

有了这些配置，您现在可以在项目中使用MMOCore，并访问其API以创建自定义的RPG功能和游戏机制。