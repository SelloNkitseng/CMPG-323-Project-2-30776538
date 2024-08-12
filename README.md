# CMPG-323-Project-2-30776538

In this project my objective was to create an automated solution thats hosted on Azure, that can determine how much time is saved each time one of Tech Tren's automations runs. I was tasked to utilise RESTful APIs for cloud management that consists of CRUD methods to allow the retrieval of data and the manipulation of data

This is implemented using Telemetry Management Functionality that operates as follows:

A GET method that retrieves all Telemetry entries from the database.
A GET method that will retrieve one Telemetry from the database based on the ID parsed through.
A POST method that will create a new Telemetry entry on the database.
A PATCH method that will update an existing Telemetry entry on the database.
A DELETE method that will delete an existing Telemetry entry on the database.
A private method in the API that checks if a Telemetry exists (based on the ID parsed through) before editing or deleting an item.
A GET method named GetSavings in the API that queries all telemetry per project and calculates the cumulative time and cost saved. The method should filter the data based on Project ID and the start and end date ranges parsed through as parameters.
A GET method named GetSavings in the API that queries all telemetry per client and calculates the cumulative time and cost saved. The method should filter the data based on Client ID and the start and end date ranges parsed through as parameters.

A big part of the project was also to ensure that authentication has been set up to restrict access to the API

referene list can be found here: https://github.com/SelloNkitseng/CMPG-323-Project-2-30776538/blob/main/Reference%20List.docx  
