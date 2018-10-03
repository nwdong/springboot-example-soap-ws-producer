# it's based on https://github.com/spring-guides/gs-producing-web-service/tree/master/complete

# how to run
generate the jars (mvn clean install)

java -jar target/gs-producing-web-service-0.1.0.jar

# wsdl url
http://localhost:8080/ws/countries.wsdl

Ntoe: to find context from WebServiceConfig through below code
	@Bean(name = "countries")
  	wsdl11Definition.setLocationUri("/ws");
  