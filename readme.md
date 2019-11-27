## java

下载jdk : jdk-8u231-windows-x64.exe 

感谢分享 : 2696671285@qq.com Oracle123 (https://www.cnblogs.com/wangcl97/p/11333115.html)

运行, 安装到 C:\Program Files\Java\jdk1.8.0_231\ 

新建JAVA_HOME 值为jdk的安装地址"C:\Program Files\Java\jdk1.8.0_231"

新建CLASSPATH 值为".;%JAVA_HOME%\lib\dt.jar;%JAVA_HOME%\lib\tools.jar"

在Path中添加 "%JAVA_HOME%\bin"

## neo4j

下载 neo4j-community-3.5.12-windows.zip

解压到 D:\neo4j-community-3.5.12

执行 D:\neo4j-community-3.5.12\bin>neo4j install-service

执行 D:\neo4j-community-3.5.12\bin>neo4j start

访问 localhost:7474 初始密码为neo4j
