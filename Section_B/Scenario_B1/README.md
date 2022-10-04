How do you parametrize using JMeter with an example?

Solution:

We can parametrize in several ways using JMeter-

=>CSV Data Set Config(most commonly used)

=>User Defined(Used for test configuration parameters and global variables)

=>Other components:

    -JDBC Connection Configuration
    -JSR223 PreProcessor
    -Random Variable
    -Counter
    -Parameterized Controller
    
=>OS process sampler(Eg: Scenario A3- Create_CognitoUser.jmx)

In this Scenario_B1 scenario-PETStore_01_CreateUser.jmx covered parameterization using following JMeter components,

=>User Defined Variables: It involves global variables used across all the requests and test execution parameters(Users,Rampup,test duration and base directory) in Thread group

=>JSR223 PreProcessor   : It involves generating First Name,Last Name and email id for the large user load

=>Random Variable       : This component used to generate phone numbers and email id generation

=>CSV Data Set Config   : It is used to load the user name and password from csv file for the existing users

Reference: https://petstore.swagger.io/
