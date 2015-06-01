From java

Maintainer Thomas Abraham

run apt-get update \
	&& apt-get install -y openssh-server

run mkdir /var/run/sshd

expose 22

cmd ["/usr/sbin/sshd", "-D"]
