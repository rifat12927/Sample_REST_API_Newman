# Sample_REST_API_Newman


## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json 
```
- Run Command for Report: 
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/28551469/2s9Xy5LqHX


## Test case list:
1. ### Create 
	> Create Data Sets Using the Dynamic Random Variables.


2. ### Get
	> In the test case you need to validate the following field values:
   1. > Id
   2. > First Name 
   3. > Last Name 
   4. > Total Price
   5. > Deposite Paid
   6. > Check in
   7. > Check out
 	

3. ### Create Token
	> In the test case you need to validate the following field values:
	1. > Only Message

5. ### Update
	> In the test case you need to validate the following field values:
	1. > Only Message

6. ### Get Updated Details
   > In the test case you need to validate the following field values:
   1. > Id
   2. > First Name 
   3. > Last Name 
   4. > Total Price
   5. > Deposite Paid
   6. > Check in
   7. > Check out
3. ### Delete
	> In the test case you need to validate the following field values:
	1. > Only Message
    > 
## Newman Report Summary:
<img width="958" alt="image" src="https://github.com/rifat12927/Sample_REST_API_Newman/assets/66294509/a862c960-7a48-47ad-b2c2-bfc028e79451">

<img width="957" alt="image" src="https://github.com/rifat12927/Sample_REST_API_Newman/assets/66294509/0dc2dd46-5196-497f-a3f1-a3b6eb7a55fb">
