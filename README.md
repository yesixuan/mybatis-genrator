# 命令行生成 mybatis 所需的文件


## 命令

java -jar mybatis-generator-core-1.3.7.jar -configfile generatorConfig.xml


## 注意

1. bean 实体类中的 toString 方法需要自己实现

2. SpringBoot 中使用 mapper 接口，需要自行添加 `@Repository` 注解

3. 工具根目录下必须要有 src 文件夹