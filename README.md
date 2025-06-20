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
   git clone https://github.com/Ola-Mohamed/Postman_project_RESTFUL_Booker.git
   ```

2. Import the Postman collection and environment from the `/Postman` folder into your Postman application.

3. Run the collection manually in Postman or via **Newman** for automation:
   ```bash
   newman run Restful_Booker_Collection.json -e Restful_Booker_Environment.json
   ```

## Next Steps

- Integrate this testing suite with a CI/CD pipeline for automated test execution.
- Expand test cases to cover edge cases and additional scenarios.
  
## Contributions

Feel free to contribute to this project by creating pull requests, submitting issues, or suggesting enhancements.

---
