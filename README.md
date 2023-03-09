### REST-API-for-the-Customer-Relationship-Management Introduction

The Rest clients should be able to 

* Get a list of customers
* Get a single customers
* Add a new customer
* Upldate a new customer
* Delete a list of customers

Therefore, HTTP methods will include GET, POST, PUT and DELETE respectively.

### Run and Test

You will need to install and configure eclipse, MySQL and POSTMAN

### Project Demonstration

![Homepage](https://user-images.githubusercontent.com/70967683/223885308-fd5a5174-ccc7-4564-9f00-19c7b8f26362.jpg)

* Get all customers
![getAll](https://user-images.githubusercontent.com/70967683/223885678-75b97869-5281-45cc-84ca-ce2e911b524d.jpg)

* Get a single customer
![GET](https://user-images.githubusercontent.com/70967683/223885410-f579ac45-a02e-46a7-9aaa-d62aaef5e5df.jpg)
![GET2](https://user-images.githubusercontent.com/70967683/223885413-e8263409-b546-483f-abcf-961c34d91127.jpg)

* Handle Exceptions, e.g. retrieve a customer ID that does not exist
![handle exception](https://user-images.githubusercontent.com/70967683/223888123-f8ada643-905d-484d-8cca-6b283c376980.jpg)


* Add a single customer, e.g. adding a new customer is successful. new id 9 is created
![POST1](https://user-images.githubusercontent.com/70967683/223904930-a450de57-7a20-4768-87b7-1122bc5ef192.jpg)
![POST2](https://user-images.githubusercontent.com/70967683/223904931-c6a23f5a-c211-45b8-a3a1-391ac4c02ed9.jpg)

* Update a single customer, e.g. modify customer's firstName field from "Changqing" to "Louis"
![put1](https://user-images.githubusercontent.com/70967683/223906236-21718dd4-4d67-41a9-aff4-38681e0ceae6.jpg)
![put2](https://user-images.githubusercontent.com/70967683/223906239-3e5d8493-17f8-4a3d-b5e2-b4d5ed598a44.jpg)

* Delete a single customer, e.g. remove the customer with ID 9 from the database.
![delete1](https://user-images.githubusercontent.com/70967683/223907782-4154317a-6c8a-4ced-8a2d-e7e8161d9f95.jpg)
![delete2](https://user-images.githubusercontent.com/70967683/223907786-985862e0-9222-4d41-b42d-4a8b14cd8243.jpg)

