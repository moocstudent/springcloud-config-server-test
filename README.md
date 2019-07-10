# springcloud-config-server-test
test for config server
config server 的配置文件

访问配置信息的URL与配置文件的映射关系如下所示:
	
/{application}/{profile}[/{label}]
	
/{application}-{profile}.yml
	
/{label}/{application}-{profile}.yml
	
/{application}-{profile}.properties
	
/{label}/{application}-{profile}.properties

version中40位字符串是在对应的Git上的commit号
