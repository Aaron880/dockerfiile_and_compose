from mariadb:10.3.15
COPY my.cnf /etc/mysql/mariadb.conf.d/mysqlutf8mb4.conf
COPY mysql-clients.cnf /etc/mysql/mariadb.conf.d
COPY client.cnf /etc/mysql/mariadb.conf.d
COPY mysql.cnf /etc/mysql/mariadb.conf.d

CMD ["mysqld", "--character-set-server=utf8mb4", "--collation-server=utf8mb4_general_ci"]
