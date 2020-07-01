FROM centos

RUN \
  yum -y install openssh-server sudo

RUN \
  useradd guacamole && \
  /usr/bin/ssh-keygen -A

WORKDIR /home/guacamole

CMD /usr/sbin/sshd -D

