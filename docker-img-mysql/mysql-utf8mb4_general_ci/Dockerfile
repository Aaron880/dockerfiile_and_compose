from mysql:5.7
COPY my.cnf /etc/mysql/mysql.conf.d/mysqlutf8mb4.conf
COPY mysql-clients.cnf /etc/mysql/mysql.conf.d
COPY client.cnf /etc/mysql/mysql.conf.d
COPY mysql.cnf /etc/mysql/mysql.conf.d

CMD ["mysqld", "--character-set-server=utf8mb4", "--collation-server=utf8mb4_general_ci"]
