FROM ubuntu:16.10
MAINTAINER Leandro Costa version: 0.1
RUN apt-get update && apt-get install -y iputils-ping traceroute apache2
EXPOSE 80
ENTRYPOINT ["apache2ctl"]
CDM["-D", "FOREGROUND"]
 