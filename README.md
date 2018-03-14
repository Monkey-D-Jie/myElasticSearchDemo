# myElasticSearchDemo
集成环境说明:<br>
(核心jar包说明)<br>
spring4.3.7.RELEASE+spring-data-commons1.13.10.RELEASE+spring-data-elasticsearch2.0.4.RELEASE；<br>
运行方法：<br>
首先你得把2.4.0版本的elasticSearch运行起来。<br>
然后将项目导入进IDEA，待pom加载完成后，部署项目至tomcat，并加上路径名/myEsDemo。<br>
项目启动成功后，跟着在浏览器的地址栏中输入EsController类中的示例链接，<br>
若成功访问，则能看到返回的数据。<br>
目前实现的功能有：简单的CURD操作，以及字段部分匹配/完全匹配的操作。<br>
如果有问题，请发送信息至642815736@qq.com
