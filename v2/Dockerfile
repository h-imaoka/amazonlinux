FROM amazonlinux:2

COPY amzn2-extras.repo /etc/yum.repos.d/

RUN /bin/sh -c 'yum install -y witch sudo net-tools hostname shadow-utils util-linux tar procps-ng less nmap-ncat iproute'

CMD [ "/sbin/init" ]