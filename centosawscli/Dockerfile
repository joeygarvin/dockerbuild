FROM centos:7

MAINTAINER centos7

RUN yum -y install epel-release &&\
    yum -y install python-pip  

RUN pip install awscli &&\
    echo "This is Joe" > /root/Joe
