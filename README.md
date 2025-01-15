Reqres API Testing Project using Postman
Overview
This project demonstrates comprehensive API testing for the Reqres API using Postman. It covers a variety of HTTP methods, test scenarios, and automated test cases, ensuring the reliability and functionality of the endpoints.

Features
🔍 Complete Coverage: Test cases for all endpoints provided by Reqres, including:
GET: Retrieve user and resource data.
POST: Create, register, and login users.
PUT/PATCH: Update existing resources.
DELETE: Remove resources.
🌐 Environment Configuration: Dynamic variables for cleaner and more efficient testing.
✅ Validation Tests: Automated checks for status codes, response structures, and field validations.
🛡️ Authentication: Integrated testing with token-based authentication.
🚀 100% Pass Rate: All test cases executed successfully.
Technologies Used
Postman: API testing and automation.
JavaScript: Scripting for test cases.
Reqres API: Mock API for testing and learning purposes.
Project Structure
Reqres-API-Testing.postman_collection.json: Postman collection containing all test cases.
Reqres-API-Environment.postman_environment.json: Environment file with dynamic variables.
screenshots/: Folder containing run result screenshots.
Key Test Scenarios
Verify Successful Login

Endpoint: POST /api/login
Expected Result: Status code 200, valid token in response.
Validate User Data Structure

Endpoint: GET /api/users/{id}
Expected Result: Fields id, email, first_name, last_name, avatar exist and have valid values.
Check Resource Not Found

Endpoint: GET /api/unknown/23
Expected Result: Status code 404.
...and many more!

Acknowledgments
This project is built using the Reqres API, a free service for testing and prototyping REST APIs.
Feel free to explore and use this repository as a learning resource! 🌟

