compile & execute :<br/>
mvn spring-boot:run<br/>
<br/>
compile into fat jar then execute :<br/>
mvn clean package<br/>
java -jar target/simpleSetupConnectionH2-0.0.1-SNAPSHOT.jar<br/>


During the execution, the console shows : <br/>

Customers found with findAll():<br/>
-------------------------------<br/>
Customer[id=1, firstName='Jack', lastName='Bauer']<br/>
Customer[id=2, firstName='Chloe', lastName='O'Brian']<br/>
Customer[id=3, firstName='Kim', lastName='Bauer']<br/>
Customer[id=4, firstName='David', lastName='Palmer']<br/>
Customer[id=5, firstName='Michelle', lastName='Dessler']<br/>
<br/>
Customer found with findById(1L):<br/>
--------------------------------<br/>
Customer[id=1, firstName='Jack', lastName='Bauer']<br/>
<br/>
Customer found with findByLastName('Bauer'):<br/>
--------------------------------------------<br/>
Customer[id=1, firstName='Jack', lastName='Bauer']<br/>
Customer[id=3, firstName='Kim', lastName='Bauer']<br/>
