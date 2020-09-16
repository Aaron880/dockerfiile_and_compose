# docker-img-mysql
mysql各种docker镜像
查看数据库字符集
show variables like "%character%";show variables like "%collation%";
自定义的配置文件都需要挂载到/etc/mysql/conf.d
/TRS/APP/mysql/conf.d:/etc/mysql/conf.d
