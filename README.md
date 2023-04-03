# docker-tomcat
docker run -dt -p 8080:8080 -v ./docker-tomcat/context.xml:/usr/local/tomcat/webapps/manager/META-INF/context.xml -v ./docker-tomcat/tomcat-users.xml:/usr/local/tomcat/conf/tomcat-users.xml --restart always tomcat:8.0
