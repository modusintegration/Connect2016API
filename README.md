# Connect2016API
API that acts as a wrapper of the google form that saves all the data of each of the people that provides Modusbox with their information.

The API is implemented in Cloudhub. We’ve implemented a test self-signed certificate in the project. In order to make it easier to test the productive version is commented and we have replaced the https call with a unsecured http call. In case you want to use the https version, simple trust that certificate in order to make it work.

The credentials for Basic Authentication are:  
username: user  
password: password

To test it you can use this POSTMAN collection: 
https://www.getpostman.com/collections/dc3a2e175503c3cf3e58
