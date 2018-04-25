FROM ubuntu
MAINTAINER        eastgreatwolf <eastgreatwolf@aliyun.com>
RUN  echo "USER_NAME=\`cat /etc/nginx/nginx.conf |grep ^user|awk "{printf \$2}"\`">>startNgxPhp.sh  \
&&  echo "chown -R \${USER_NAME}:\${USER_NAME} /Apps"            >>startNgxPhp.sh \ 
