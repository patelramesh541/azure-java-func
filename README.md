**# _**Below are the steps to deploy java Azure serverless functions using maven.**_**

After cloning steps to run Serverless function on Azure :
1) `mvn clean package`
   
Test function locally.

1) `mvn azure-functions:run`

Deploy it on cloud
1) `mvn azure-functions:deploy`



Run the following command to view near real-time streaming logs:


`func azure functionapp logstream <APP_NAME> `


At the end delete resource group by using below command:

`az group delete --name java-functions-group`

for detail description please visit :
https://docs.microsoft.com/en-us/azure/azure-functions/create-first-function-cli-java?tabs=cmd%2Cazure-cli%2Cbrowser