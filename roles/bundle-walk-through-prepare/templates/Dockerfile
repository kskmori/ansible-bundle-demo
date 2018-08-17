FROM centos:centos7

COPY status.conf /etc/httpd/conf.d/status.conf
RUN yum update -y
RUN yum install -y httpd bind-utils curl lsof wget which
RUN yum install -y pacemaker pacemaker-remote resource-agents
