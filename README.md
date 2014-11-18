## Spring Security 使用的简单例子

---
跟之前的 `spring-security` 例子相比，本例没有使用`spring`的配置文件，也不要在 `web.xml` 里配置 `spring` 上下文环境。而是通过两个类来启动。

`Spring Security Maven`依赖项,`pom.xml`：

    

-----
    <dependencies>
      <!-- ... other dependency elements ... -->
      <dependency>
        <groupId>org.springframework.security</groupId>
        <artifactId>spring-security-web</artifactId>
        <version>3.2.5.RELEASE</version>
      </dependency>
      <dependency>
        <groupId>org.springframework.security</groupId>
        <artifactId>spring-security-config</artifactId>
        <version>3.2.5.RELEASE</version>
      </dependency>
    </dependencies>
    





