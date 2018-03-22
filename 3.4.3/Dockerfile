FROM centos/python-36-centos7

USER root
RUN yum -y install epel-release &&\
    yum -y install R-core R-core-devel &&\
    yum -y clean all
USER 1001