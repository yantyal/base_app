# base_app

mvn clean package  
docker run -p 8080:8080 -v path/base_app/target:/var/lib/jetty/webapps jetty:11
