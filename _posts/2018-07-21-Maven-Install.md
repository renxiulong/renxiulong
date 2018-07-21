# Maven 环境配置 #
所需工具:  

* JDK
* Maven

---

JDK的JAVA_HOME，CLASSPATH和path等环境变量默认设置已经设置好。

---
下载Maven  
网址:http://maven.apache.org/download.cgi  
选择合适版本  
- 
* 解压zip文件，例如解压到文件夹D:\maven
* 配置环境变量
	* 添加M2_HOME
	* 添加MAVEN_HOME
	* 以上两个环境变量指向上面解压的文件夹M2_HOME=D:\maven
	* 添加到环境变量PATH，将%M2_HOME%\bin添加到PATH变量最后
	* 在任意目录下打开CMD窗口，测试mvn -version