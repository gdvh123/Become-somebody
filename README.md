# Become-somebody

开始入门Spring-boot
已完成Hellow Spring-boot

├── README.md 
├── img  -- 放了一些README.md文档所需要的图片，没有实际意义
├── pom.xml
└── src
    └── main
        ├── java
        │   └── cn
        │       └── tycoding
        │           ├── controller  -- SpringMVC-WEB层控制器
        │           ├── mapper  -- Mybatis接口和映射文件。本项目采用了mybatis的接口开发，所以接口和映射文件放在同一目录下，并且名称相同。
        │           ├── pojo  -- JavaBean实体类
        │           └── service  -- service业务层
        ├── resources  -- maven项目存放配置文件的根目录(classpath:)
        │   ├── sys_schema.sql  -- 项目数据库创建和表创建的SQL语句
        │   ├── resource  -- 日志打印和数据源配置文件
        │   └── spring  -- spring和springmvc的配置文件
        └── webapp  -- 项目的根目录
            ├── WEB-INF
            ├── fonts  -- 字体的配置文件
            └── lib  -- 前端静态资源
