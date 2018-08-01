This Project is developed based on reference Bob Webster's project **[RulesSDK](https://github.com/rdbwebster/RulesSDK)** and **[Car Rental Sample Application](http://docs.oracle.com/cd/E36909_01/user.1111/e10228/decision_point.htm#CHDJJDEB)**.

In my project I have added couple of functionality.

 1. Create a Dictionary
 2. Create a Decision Function
 

As of now this is complete executable code in Jdevloper 11.1.1.7 ide environment. No need to add any external jars. All libraries are with reference to Jdeveloper. 

Thanks. 

----------------------------------------

## Secnario
  - According to age and policy type of Person to caculate corresponding insurance product
  - Utilize Oracle Rules SDK to create business rule and excute this rule
## Load Libs
  - Rules Lib  
  ![Rules Lib](https://github.com/lzyowen/BusinessRules_Java/blob/master/images/rulelib.JPG)
  - ADF Model Runtime  
  ![Runtime Lib](https://github.com/lzyowen/BusinessRules_Java/blob/master/images/adfruntime.JPG)
## Running Step
  - Execute InsuranceProductsRules.java  
      running this Java file to create Dictionary, Decision Function,Decisiont Table ... of Insurance rule .   
      ![Decision Table](https://github.com/lzyowen/BusinessRules_Java/blob/master/images/decisiontable.JPG)
  - Execute InsuranceProductsRuleClient.java  
      running this Java file to to invoke Insurance rule through decision Point.
  - Running Output  
       ![Result](https://github.com/lzyowen/BusinessRules_Java/blob/master/images/result.JPG)

     
## Documentaion 
[SDK Docs](https://docs.oracle.com/cd/E28389_01/apirefs.1111/e10663/toc.htm)  
[Oracle Business Rule Docs](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.404.2350&rep=rep1&type=pdf)
