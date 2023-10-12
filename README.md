**SpringBoot Buggy API Services**

The SpringBoot Buggy API Service, has endpoints designed to simulate Java performance problems for tool testing and analysis.

---

** Pre-Requiste **

To run this, you need the following installed and configured in your path.

1. Java 1.8 or higher
2. Maven 3.0 or higher


---

** Run the application **
Please navigate to the folder and execute the following commands in your terminal.

1. cd {cloneed-projeect-folder}
2. mvn clean
3. mvn install
4. java -jar  -Xss512k -Xloggc:spring-boot-buggy-api-gc.log   target/*.jar
5. Open the application in the browser http://{your-host}:8090/swagger-ui.html to invoke the java performance problems using UI or curl command example 
curl http://{your-host:8090}/v1/invoke/blocked-state


---

