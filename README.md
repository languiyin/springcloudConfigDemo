# config-repo
Spring-Config配置文件存放目录

访问路径的写法也有多种方式：
（1）
/{application}/{profile}/[label]

（2）
/{application}-{profile}.yml

（3）
/{label}/{application}-{profile}.yml

（4）
/{application}-{profile}.properties

（5）
/{label}/{application}-{profile}.properties
其中{label}是指分支，默认是master。

最好的方式为第二个，比如这个
http://localhost:8888/spring-boot-ehcache-dev.yml
