# servlet3-maven-archetype
创建maven web servlet3.0 项目模板

1. 下载源码到本地环境。
2. 执行mvn install 命令。
3. 修改本地 archetype-catalog.xml文件,此文件是通过maven的setting.xml配置的,如果没配置一般在/.m2/文件夹在,如果没找到可以执行mvn archetype:crawl

```xml
    <archetype>
      <groupId>cc.tungsing</groupId>
      <artifactId>servlet3-maven-archetype</artifactId>
      <version>0.0.1-SNAPSHOT</version>
      <description>webapp</description>
    </archetype>
```
