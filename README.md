# cassandra-trading-app-cloud-enabled
This Project clone of CWT building additional features

This project refers the git backed config from below location
https://github.com/Puneethkumarck/spring-cloud-config/tree/master/cwt

To run this application 
clone the following repo https://github.com/Puneethkumarck/spring-cloud-config-server.git , navigate to root folder run the
mvn spring-boot:run . Once the application started , query the config data using below command

curl -H "Authorization: Basic d29ya0Bob21lOndvcmtAaG9tZQ==" http://localhost:8888/cwt/dev

Once if you are able to see the config response .

clone this repo and run mvn spring-boot:run from root folder and launch the application using http://localhost:8082
