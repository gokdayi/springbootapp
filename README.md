# springbootapp
Restful Service based on Spring Boot and a Client Page using Angular1.x
Demo
---
[Live Working Application](https://fierce-refuge-75047.herokuapp.com/home)

__Get All Companies__ --

`curl https://fierce-refuge-75047.herokuapp.com/companies` 

Add New Company
--------
`curl -X POST -H "Accept: application/vnd.heroku+json; version=3" -H "Content-Type: application/json" -d "{\"companyname\" : \"same company\",\"adress\":\"same adress\",\"city\":\"same city\",\"country\":\"same country\",\"phone\": \"123123\", \"email\":\"same email\"}" https://fierce-refuge-75047.herokuapp.com/newcompany`

Get Details of a Company
--------
`curl https://fierce-refuge-75047.herokuapp.com/companito/3`


