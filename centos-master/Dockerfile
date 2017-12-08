FROM centos:6
# Centos7 ssh有问题，换用centos6镜像
MAINTAINER hipeace86 <hipeace86@gmail.com>
RUN yum install https://repo.saltstack.com/yum/redhat/salt-repo-latest-2.el6.noarch.rpm -y && \
    yum update -y && \
    yum install salt-master salt-api salt-minion -y  && \
    /etc/init.d/salt-minion start && \
    chkconfig salt-minion on && \
    yum clean all
