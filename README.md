# springboot-email-verification-with-spring-security

POST http://localhost:9191/register

{
    "firstName":"Akash",
    "lastName":"Gayke",
    "email":"akashgayke3355@gmail.com",
    "password":"123",
    "role":"ADMIN"
}

Success!  Please, check your email for to complete your registration

GET http://localhost:9191/users

[
  {
    "id": 1,
    "firstName": "Akash",
    "lastName": "Gayke",
    "email": "akashgayke3355@gmail.com",
    "password": "$2a$10$j1sF45LCjX8HuKM/1Ivwr.v928hLJILusoZ16DSWVFVxIr9UFoTda",
    "role": "ADMIN",
    "enabled": true
  },
  {
    "id": 2,
    "firstName": "vrunda",
    "lastName": "yadav",
    "email": "akash.gayke@humancloud.co.in",
    "password": "$2a$10$I6cbUm6kgj4afoTkIGKze.INfhlycmXtmvNCCuNcwec01D18noMRC",
    "role": "MANAGER",
    "enabled": true
  }
 ]
