# RestAssured
Java/testNG/restAssured/lombok/allure/performance/

* Add request/response body to Allure report  

      run test:
        mvn clean test -Dtest=BodyToAllureTest
      generate report: 
        mvn allure:serve
    
* Contract testing 

      run test:
        mvn clean test -Dtest=ContractTest
      generate report: 
        mvn allure:serve
        
* Performance via RestAssured 

      run test:
        mvn clean test -Dtest=PerformanceTest
      generate report: 
        mvn allure:serve