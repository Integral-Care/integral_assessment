# Assessment

The following assessment will test your knowledge in an array of languages and frameworks and API architectures.
The assessment will require 2 separate projects.

## 1st project: Python / SQL

Write a python script that queries [Rfam's Public Mysql Database](https://docs.rfam.org/en/latest/database.html) database and prints the results to the console.

- The schema of the tables can be viewed at the above link
- Credentials to the database are also included in the above link
- Please utilize the `Rfam` database
- Please utilize any python package that you seem fit for the project

Data to be returned from query:
    - Please return all rows who's author includes `Griffiths-Jones Sr` and who's number of species is greater than `500` from the family table
    - Please return the family.description, family.number_of_species, clan.description, and family.author 

- Please make sure your code is on github and provide us the url. 

## 2nd project: Node.js / Express

Write a Node.js Express server that has 3 routes

- Please utilize any node packages/modules that you seem fit for the project

1st route) This route queries the Number Conversion SOAP Api [NumberConversion API](https://www.dataaccess.com/webservicesserver/NumberConversion.wso?op=NumberToWords) and returns the value returned from the api
    - This route requires 1 paramater.
        - Paramater named 'num' : The value of this param will be an int (e.g. 5)
    - This route should return the value returned from the NumberConversion api.

2nd route) This route queries [Covid 19 API](https://github.com/M-Media-Group/Covid-19-API) and returns the value of the `Confirmed` cases for `Texas`.
    - This route required no paramaters.
    - This route should return the number of confirmed cases returned from the Covid 19 API

3rd route) This route calculates the confirmed covid 19 cases for the state paramater passed and returns the value in word format.
    - This route requires 1 paramater
        - Paramater named `state` : This will be any state within the United States.
    - This route will utilize the same NumberConversion Api from the 1st route and the Covid 19 API that was used in the 2nd route.
    - The value returned from this route will be the value of the state's confirmed cases in word format. 

- Using Heroku's free platform, host this server application and provide the url for the server.
- Please make sure your code is on github and provide us the url.
