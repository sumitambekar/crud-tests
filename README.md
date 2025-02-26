# crud-tests
###Project description:
**Automation test project for regression testing of "Computer database sample application".**    
Application location: https://computer-database.herokuapp.com/     
1. Java 8 + Maven + TestNG + Selenium + Selenide.  
2. TestNG suite location: \src\main\resources\testng\testng.xml  
3. By a default suite will be executed in 5 parallel threads > could be changed in testng.xml, property <thread-count>  
4. By default tests will be started on Chrome browser (chromedriver provided in project resources)   

###Resources location:  
1. Application: https://computer-database.herokuapp.com/  
2. Project: https://github.com/Vitalik549/crud-tests  
3. Test cases: https://goo.gl/A161XB   


###Maven installation:  
:warning: Maven is required to run regression tests from this project!   
*Please ensure than Maven is installed by execution of the next command in cmd or terminal:* ```  mvn --version  ```  
*Info how to install Maven is [here](https://maven.apache.org/install.html#)*  


###How to start test execution in IDE:  
1. To run full test suite: make right click on testng.xml file > Run with testNG  
2. To run separate package/class: make right click on package/class file > Run with testNG  


###How to start test execution in cmd or terminal:  
0. Open cmd or terminal :wink:  
1. go to local root project directory   
2. execute next command:  
```  mvn clean test  ```  - to run full suite   
```  mvn clean test -Dtest=%classname1,%classname2``` - to run specific tests   

Where:   
```%classname1,%classname2```  - names of the test classes you want to run separated with comma     
