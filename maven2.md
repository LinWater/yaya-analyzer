#maven pom config .
# 在maven中使用 yaya-analyer #

## 添加dependency ##
```
<dependency>
			<groupId>om.googlecode.yayaanalyzer</groupId>
			<artifactId>yaya-analyzer-core</artifactId>
			<version>0.1-SNAPSHOT</version>
			<type>jar</type>
</dependency>
```
## 添加repository ##
```
<repository>
			<id>maven2-repository.yaya-analyzer</id>
			<name>Yaya Analyzer Repository for Maven on googlecode</name>
			<url>http://yaya-analyzer.googlecode.com/svn/repo</url>
</repository>
```