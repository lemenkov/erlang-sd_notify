FROM centos

RUN yum -y update

RUN yum install -y  \
  make \
  git  \
  wget \
  which \
  epel-release \
  nano

RUN yum install -y https://dl.bintray.com/rabbitmq-erlang/rpm/erlang/21/el/7/x86_64/erlang-21.3.8.16-1.el7.x86_64.rpm

RUN wget https://github.com/rebar/rebar/wiki/rebar && chmod +x rebar
