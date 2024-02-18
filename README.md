# E-commerce API End-to-End Testing Suite
**Overview**

This repository contains a comprehensive suite of API requests and tests for end-to-end testing of an e-commerce platform. The purpose of this project is to thoroughly validate the functionality and reliability of the e-commerce platform's API endpoints across various stages of the product lifecycle, including product creation, order processing, and deletion.

**Technologies Used**

Postman: Utilized as the primary tool for sending API requests, organizing collections, and executing tests.
JSON Schema: Employed for validating the structure and format of API responses to ensure data integrity and compliance with expected specifications.
Getting Started
To utilize this API testing suite, follow the steps below:

**Installation and Setup**

Clone this repository to your local machine:
git clone **https://github.com/your-username/e-commerce-api-testing.git**
Install Postman from postman.com if not already installed.

Import the Postman collection (e-commerce-api-testing.postman_collection.json) into your Postman application.

Set up any necessary environment variables required for authentication or configuration. Refer to the collection's environment settings for guidance.

**Usage**

Run the collection in Postman to execute the API requests and tests.
Review the request descriptions and documentation for each request to understand their purpose and expected behavior.
Interpret the test results to ensure the API endpoints are functioning as expected.

**Troubleshooting**

If you encounter any issues, refer to the troubleshooting tips below:
Authentication Errors: Double-check your credentials and ensure they are correctly configured in the environment variables.
Schema Validation Failures: Review the JSON Schema validation rules and compare them against the response data to identify any discrepancies.
Network Connectivity Issues: Ensure your network connection is stable and not blocking the API requests.

**Collection Structure**

The Postman collection is organized into the following requests:

**Login:** Authenticate user access to the e-commerce platform.

**Create the Product:** Add a new product listing to the store inventory.

**Create the Order for That Product:** Place an order for a specific product.

**Get the Order Details:** Retrieve detailed information about a specific order.

**Delete the Order:** Cancel and remove a previously placed order.

**Delete the Product:** Remove a product listing from the store inventory.

**Testing Strategy**

The testing strategy for this collection involves thorough validation of the API endpoints across various scenarios to ensure reliability and functionality. Test cases are designed to cover critical functionalities such as product creation, order processing, and deletion.

**Contributing**

Contributions to this API testing project are welcome! If you encounter any issues, have suggestions for improvements, or would like to contribute new features or tests, please submit a pull request or open an issue on GitHub.
