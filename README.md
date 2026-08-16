# QA Testing Restful-Booker API

## Project Overview
Project created to show the basic understanding of Postman, based on [Restful-Booker](https://restful-booker.herokuapp.com/) API.

The Collection also contains 'CreateBooking_RandomValues' endpoint with automated value creation. 
This request is only an addition to the whole Collection and it should only be used with the 'Restful_Booker_Environment_RandomValues' Environment.
When using Collection Runner while testing the Happy Path, make sure to uncheck this endpoint. 

## Tools & Technologies
- Postman
- REST API
- JSON
- JavaScript
- HTTP Methods

## Tested HTTP Methods and Endpoints
- GET /ping
- POST /auth
- PUT booking/id
- PATCH /booking/id
- DELETE /booking/id

## Tests
The project contains written tests for:
- HTTP status codes
- Response structure
- Required properties
- Data validation
- Created/Updated booking data
- Deleted booking validation

## How to Run
1. Download Collection and both Environment files
2. Import Collection to Postman
3. Import both Environments to Postman
4. Select Restful_Booker_Environment for basic endpoints
5. Select Restful_Booker_Environment for RandomValues endpoints

## Author
Jakub Drążyk
