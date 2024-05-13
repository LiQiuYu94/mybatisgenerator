# mybatisgenerator
mybatis反向生成工程，简单配置，不需修改其他代码

## 实现功能
1. 通过配置将数据库中的表信息反向生成mybatis对应的java类，mapper，和xml。
2. java类的各个属性生成和数据库表的comment对应的注释
3. 对自增主键，在insert语句中返回插入后的主键的配置

## 配置
都在generatorConfig.xml中，主要配置mysql的链接，java类，mapper存放的位置，以及表名