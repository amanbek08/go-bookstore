# Book store on Golang

This application is used to create, retrieve, update and delete books. 

For now i couldn't connect it to mysql, but i have contrtollers and book instances ready.

Config directory contains file for connection with mySql. I'm planning to use it as my database

In routes directory i have handlers for 5 request types: Get by ID, Get all books, add book, update book and delete book. Functions that handle this requests are in controllers directory. 

Models directory contains file that clarifies Book instance and has functions that send requests to database. JSON is used to send and recieve information. 