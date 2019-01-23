FROM tomcat

MAINTAINER yusk.iida <yusk.iida@gmail.com>

ADD time4.war /usr/local/tomcat/webapps/time4.war

RUN rm -rf /usr/local/tomcat/webapps/ROOT

CMD ["catalina.sh", "run"]
