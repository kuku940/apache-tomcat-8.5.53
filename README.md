## 编译源码
1. 下载[tomcat8源码](http://tomcat.apache.org/download-80.cgi)导入Idea；
2. 添加[pom.xml](./pom.xml)转换成maven项目；
3. 删除[webapps/examples](./webapps/examples)文件夹，防止出现ClassNotFoundException；
4. 启动[Bootstrap.main()](./java/org/apache/catalina/startup/Bootstrap.java)方法

##

Catalina.load()时序图
![Catalina.load()时序图](./resources/images/20180110010608836.jfif)