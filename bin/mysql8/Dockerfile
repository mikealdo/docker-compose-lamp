FROM mysql:8
RUN echo "[mysqld]" >> /etc/mysql/my.cnf
RUN echo "mysql_native_password=ON" >> /etc/mysql/my.cnf
RUN echo "collation-server=utf8_unicode_ci" >> /etc/mysql/my.cnf
RUN echo "character-set-server=utf8" >> /etc/mysql/my.cnf
RUN echo "default_authentication_plugin=mysql_native_password" >> /etc/mysql/my.cnf

RUN echo "[client]" >> /etc/mysql/my.cnf
RUN echo "default-character-set=utf8" >> /etc/mysql/my.cnf
#
#RUN echo "[mysql]" >> /etc/mysql/my.cnf
#RUN echo "default-character-set=utf8" >> /etc/mysql/my.cnf
