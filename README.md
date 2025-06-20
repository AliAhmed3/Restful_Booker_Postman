# Restful_Booker_Postman
API Testing Project using Postman
# About The Project

This project centers on testing the RESTful Booker API with Postman, Performing a range of API testing techniques to validate the functionality of essential endpoints and assess the system's reliability. The test suite features detailed test cases for creating, retrieving, updating, and deleting bookings.

## Link of the API website
https://restful-booker.herokuapp.com/


## Overview

The RESTful Booker API is a web service designed for booking scenarios, and this project uses Postman to automate and verify its various endpoints. The tests are structured to ensure the API performs as intended, adhering to best practices in both functional and automated testing.

## Key Features

- **Automated Test Cases**: Tests for CRUD (Create, Read, Update, Delete) operations.
- **Postman Collection & Environment**: Configured in advance for ease of use and scalability.
- **Dynamic Variables**: Utilized Postman’s scripting capabilities to handle dynamic variables.
- **Assertions**: Verified the status codes, response bodies, and headers using Postman assertions.
- **Dynamic Data**: Using Random data generation.
  
## API Scenarios Tested

- **Ping - HealthCheck**: A simple health check endpoint to confirm whether the API is up and running.
- **Create Booking**: Verified POST requests to create new bookings with varying data inputs.
- **Get Booking**: Verified GET requests to retrieve booking details.
- **Update Booking**: Verified PUT and PATCH requests for updating booking information.
- **Delete Booking**: Ensured DELETE requests effectively remove booking records as intended.
- **Authorization**: Tested requests requiring authentication with a valid token.
  
## How to Run the Tests

1. Clone the repository:
   ```bash
   git clone https://github.com/AliAhmed3/Restful_Booker_Postman.git
   ```

2. Import the Postman collection and environment from the `/Postman` folder into your Postman application.

3. Run the collection manually in Postman or by **Newman** for automation:
   ```bash
   newman run Restful-booker.postman_collection.json -e Restful-booker.postman_environment.json
   ```
   you can also add: -r htmlextra at the end of the previous command to generate a HTML reporter which enable users to view better custom templates and provide an Interactive Report.


------------
