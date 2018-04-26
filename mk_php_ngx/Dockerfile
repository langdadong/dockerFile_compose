#FROM        mysql
#MAINTAINER        eastgreatwolf <eastgreatwolf@aliyun.com>
#RUN         mkdir  /etc/mysql/mysql.conf.d

FROM        centos
MAINTAINER        eastgreatwolf <eastgreatwolf@aliyun.com>
RUN        rpm -Uvh https://dev.mysql.com/get/mysql80-community-release-el7-1.noarch.rpm \
        && yum install -y mysql

CMD mysqld
