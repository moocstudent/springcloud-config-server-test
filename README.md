# springcloud-config-server-test
test for config server
config server 的配置文件

访问配置信息的URL与配置文件的映射关系如下所示:
	
/{application}/{profile}[/{label}]
	
/{application}-{profile}.yml
	
/{label}/{application}-{profile}.yml
	
/{application}-{profile}.properties
	
/{label}/{application}-{profile}.properties

要访问config-label-test分支,helloukyo的prod环境, 就访问  http://localhost:8030/helloukyo/prod/config-label-test
这是访问的分支config-label-test, 如果访问主干master,以下两种方式都可以: (默认master)
http://localhost:8030/helloukyo/prod/master
http://localhost:8030/helloukyo/prod/



version中40位字符串是在对应的Git上的commit号
