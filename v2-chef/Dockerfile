FROM amazonlinux:2

RUN /bin/sh -c 'yum install -y witch sudo net-tools hostname shadow-utils util-linux tar procps-ng; \
curl -L https://omnitruck.chef.io/install.sh | sudo bash'

CMD [ "/sbin/init" ]
