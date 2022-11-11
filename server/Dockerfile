FROM ubuntu
RUN apt-get update
RUN apt-get -y install rsyslog telnet
RUN sed -i '/imklog/s/^/#/' /etc/rsyslog.conf