
##### Spring Boot 2.0 SOAP Web Sphere Open Liberty

You can run it using
```` bash
mvn clean package liberty:run-server
````
http://localhost:9080/ws/countries.wsdl

update the path to your war file in the server.xml file

If you want to run open liberty separately, you can download open liberty and from bin folder run the startup file for your OS, then drop the war file in the dropins folder, that will be created when it starts.
