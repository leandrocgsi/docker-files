FROM ubuntu:16.10
MAINTAINER Leandro Costa version: 0.1
RUN apt-get update && apt-get install -y \
		apache2 \
		apache2-utils \
		vim \
		&& apt-get clean \
		&& rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp*
EXPOSE 80
CMD ["apache2ctl", "-D", "FOREGROUND"]
