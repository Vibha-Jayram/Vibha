# Vibha
Given GIT  Lab link where i have uploaded the file .

Used Tools :-

Eclipse - Editor
Spring Boot Framework :- (No need to use server to run this application)
JPA :- for Database set up 
Database :-  used inbuilt Apache durby for time being (we can change it SQlite)
execution Through URL

Step to RUN this API:-
1. Unzip the Application
2. Import Application to eclipse
3.RUN the application

Then 
Through POSTMAN APP

HIT the url

http://localhost:8080/Users 

(To regiter as a User) by input as JSON messages .

Like below 

{
"userid":"Vibha123",
	"
email_id":"Vibhaabc@Gmail.com",

"name":"VIbha Jayram"
} 

Hit the 
http://localhost:8080/Users/Vibha123/messages   - to Post Messages 

{
"msg_id":"2",
	
"msg":"Test message from Yogesh to Vibha",

"authorname":"Yogesh"
}


Hit the 
http://localhost:8080/Users/Vibha123/messages
get  All the messages  from the user (Vibha123)






 
