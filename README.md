# SpringBootWSProducer
* http://localhost:8080/soapws/articles.wsdl
* CREATE USER concretepage WITH PASSWORD 'concretepage'; 
* ALTER ROLE concretepage WITH CREATEDB;
* CREATE DATABASE  concretepagedb;
* GRANT ALL PRIVILEGES ON DATABASE  concretepagedb to concretepage;
* ALTER DATABASE concretepagedb OWNER to concretepage;

* netstat -ano | findstr :8080
* taskkill /PID 52036 /F
* mvn tomcat7:deploy
