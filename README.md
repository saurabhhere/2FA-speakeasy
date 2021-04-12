## TOTP using Speakeasy

#### Routes
```
/api/register -  to register user for first time and generate temporary secret
/api/verify - to verify user for the first time and make secret permanent
/api/validate - to validate using TOTP everytime user logged in
```

#### Setup
`nodemon index` will start the server 
You can check `locahost:5000/api` using Postman to check server is running
