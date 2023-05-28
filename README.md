# panosen-super-version
Panosen Super Version

## 使用
```
    <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>com.panosen</groupId>
                <artifactId>super-version</artifactId>
                <version>1.0.0</version>
                <scope>import</scope>
                <type>pom</type>
            </dependency>
        </dependencies>
    </dependencyManagement>
```

## 不包含spring 相关版本的控制，如有需要，请添加如下依赖
```
    <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>org.springframework</groupId>
                <artifactId>spring-framework-bom</artifactId>
                <version>4.3.3.RELEASE</version>
                <type>pom</type>
                <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
```
或
```
    <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>org.springframework.boot</groupId>
                <artifactId>spring-boot-dependencies</artifactId>
                <version>2.6.0</version>
                <type>pom</type>
                <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
```

## 对于 spring-security 模块，请添加如下依赖
```
    <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>org.springframework.security</groupId>
                <artifactId>spring-security-bom</artifactId>
                <version>5.0.7.RELEASE</version>
                <type>pom</type>
                <scope>import</scope>
            </dependency>
        </dependencies>
    </dependencyManagement>
```

## 对于 spring-cloud 模块，添加如下依赖
```
    <dependencyManagement>
        <dependencies>
            <dependency>
                <groupId>org.springframework.cloud</groupId>
                <artifactId>spring-cloud-dependencies</artifactId>
                <version>Finchley.SR1</version>
                <scope>import</scope>
                <type>pom</type>
            </dependency>
        </dependencies>
    </dependencyManagement>
```


## JDK 11 及以上
```xml
    <!-- https://mvnrepository.com/artifact/org.apache.tomcat/tomcat-jdbc -->
    <dependency>
        <groupId>org.apache.tomcat</groupId>
        <artifactId>tomcat-jdbc</artifactId>
        <version>10.1.9</version>
    </dependency>
```

## JDK 8 及以上
```xml
    <!-- https://mvnrepository.com/artifact/org.apache.tomcat/tomcat-jdbc -->
    <dependency>
        <groupId>org.apache.tomcat</groupId>
        <artifactId>tomcat-jdbc</artifactId>
        <version>10.1.9</version>
    </dependency>
```