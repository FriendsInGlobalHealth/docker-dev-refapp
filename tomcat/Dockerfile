FROM tomcat:8-jre8-temurin
LABEL maintainer=mmhawila@juutech.co.tz

RUN mkdir -p /usr/local/tomcat/.OpenMRS

COPY openmrs-runtime.properties /usr/local/tomcat/openmrs-runtime.properties
#ADD setenv.sh /usr/local/tomcat/bin/setenv.sh
COPY localtime /etc/localtime
#ADD logging.properties /usr/local/tomcat/conf/logging.properties
#ADD server.xml /usr/local/tomcat/conf/server.xml

#VOLUME /usr/local/tomcat

EXPOSE 8080
EXPOSE 465
