FROM ubuntu:16.10
MAINTAINER Leandro Costa version: 0.1
RUN apt-get update && apt-get install -y iputils-ping apache2
ENV var1=ping var2=8.8.8.8
CMD $var1 $var2
# ENTRYPOINT ["apache2ctl"]