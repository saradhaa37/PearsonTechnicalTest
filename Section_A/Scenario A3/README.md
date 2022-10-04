About this Scenario: a hypothetical JMeter script

Problem:We had a scenario where we need to create user for testing Mobile application that involves application API and AWS commands


Solution:

=>First step is to check how to create user from application

=>Second step is to check AWS cognito commands for setting users(set password)
  -Tried to check a way in JMeter how to do this and found a way through OS process sampler
  -Implemented OS process sampler for all the AWS commands

Now,this script will create users using application API and AWS Cognito users which can be used for the further data preparation(user login) and testing create user scenario

Note: 

=>This script doesn't contain any project related code

=>AWS Commands reference -> https://docs.aws.amazon.com/cli/latest/reference/cognito-idp/admin-set-user-password.html
