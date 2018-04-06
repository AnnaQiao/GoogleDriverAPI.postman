# Google Driver API automation testing 
##### Google Driver API automation testing
##### Rest API Testing - This project was tested Google Driver API by using postman
## Getting started
### prerequisites
- Git Source Code Manangement
- Postman tool - for API testing
### Install Postman APP
##### Postman is available as a native APP for Mac, Windows, and Linux operating system.
- go to the apps pages https://www.getpostman.com/apps, and download for MAC/WINDOWS/LINUX depending on your platform.
![](https://github.com/AnnaQiao/GoogleDriverAPI.postman/blob/master/pictures/download%20postman%20app.png)
### how to create a test suit and test cases
### Creating a collection(test suit) and request(test case)
  1. create and save new collections and requests from the :
   - Workspaces build view
   - New button
   - Launch screen
   ![](https://github.com/AnnaQiao/GoogleDriverAPI.postman/blob/master/pictures/launch%20screen.PNG)
   ###### reference:https://www.getpostman.com/docs/v6/
 ### creating new case for API call in 'New Tab'.
   ##### STEP1 enter the request URL "https://www.googleapis.com/drive/v2/files/"in the URL input field.
   ##### STEP2 Select request method (GET/Put/POST/DELETE),chosing GET method.
   ##### STEP3 Set Params Authorization, Header, Body Information accordingly your API call (Please refer for details).
   ![](https://github.com/AnnaQiao/GoogleDriverAPI.postman/blob/master/pictures/demo-.PNG)
   ##### STEP4 Set Tests to verify according your API.
   ##### STEP5 Click on send to perform your API call.
   ![](https://github.com/AnnaQiao/GoogleDriverAPI.postman/blob/master/pictures/testresult.PNG)
   ##### STEP6 Save this case, and add Each API call in collection. 
   ![](https://github.com/AnnaQiao/GoogleDriverAPI.postman/blob/master/pictures/requests%20in%20collection.PNG)
 ### Example for using A's Response to B's Parameter
       1. For this Files:Get API, eg: if you want to get this response "id" to use for other test case's data 
   ![](https://github.com/AnnaQiao/GoogleDriverAPI.postman/blob/master/pictures/response.PNG)
       2. add Environment for this collection,after adding, the environment like this:
     ![](https://github.com/AnnaQiao/GoogleDriverAPI.postman/blob/master/pictures/environment.PNG)
       3. coding for capture this id in Test Tab.
     ![](https://github.com/AnnaQiao/GoogleDriverAPI.postman/blob/master/pictures/Capture.PNG)
       4. Click "Send" to excute this case, them click "Eye", You will see the fileId recorded.
     ![](https://github.com/AnnaQiao/GoogleDriverAPI.postman/blob/master/pictures/GetID.PNG)
 ### How to get autoriztion value of Google Driver API
   ##### STEP1 Go to https://developers.google.com/oauthplayground/ 
   ##### STEP2 Select & authorize APIs, eg： "https://www.googleapis.com/auth/drive" to "input  your own scope" 
 ![](https://github.com/AnnaQiao/GoogleDriverAPI.postman/blob/master/pictures/authorization-1.PNG)
   ##### STEP3 Click "Authorize API" button and choose google account and allow the access
   ##### STEP4 Click the "Exchange authorization code for tokens" button
 ![](https://github.com/AnnaQiao/GoogleDriverAPI.postman/blob/master/pictures/authorization-2.PNG)
  ##### STEP5 Copy the ACCESS_CODE like from the right pane
 ![](https://github.com/AnnaQiao/GoogleDriverAPI.postman/blob/master/pictures/autorization-3.PNG)
  ##### STEP6 Open PostMan, input the "Authorization" key in the headers, and input "Bearer ACCESS_CODE"(the ACCESS_CODE is copied from last step)
 ![](https://github.com/AnnaQiao/GoogleDriverAPI.postman/blob/master/pictures/autorization-4.PNG)
 ### run this test suite 
  ![](https://github.com/AnnaQiao/GoogleDriverAPI.postman/blob/master/pictures/autorization-4.PNG)
 ### testing report
   ![](https://github.com/AnnaQiao/GoogleDriverAPI.postman/blob/master/pictures/autorization-4.PNG)
