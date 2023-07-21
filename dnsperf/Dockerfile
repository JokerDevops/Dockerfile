FROM centos
WORKDIR /usr/local
RUN yum -y install epel-release
RUN yum -y install dnsperf
RUN yum clean all 
COPY a_recored.sh a_recored.sh
