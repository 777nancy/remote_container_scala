FROM hseeberger/scala-sbt:graalvm-ce-20.3.0-java8_1.4.6_2.13.4

RUN yum -y install https://packages.endpoint.com/rhel/7/os/x86_64/endpoint-repo-1.7-1.x86_64.rpm \
    && yum -y update \
    && yum -y upgrade \
    && yum -y install git