📘 API Automation Project
📌 Project Overview

This repository contains API automation test scripts for validating REST APIs using industry-standard tools and frameworks. The project is designed to perform functional, validation, and regression testing of RESTful services.

The automation covers endpoints from Restful Booker for demonstration and learning purposes.

🚀 Features

API Functional Testing

CRUD Operations Validation

Authentication Handling

Status Code Validation

Response Body Validation

JSON Schema Validation

Negative Test Scenarios

Automated Test Execution

🛠️ Tech Stack

Depending on your implementation, update accordingly:

Java / Python

RestAssured / Requests

TestNG / Pytest

Maven / Pip

Postman (for manual testing)

📂 Project Structure
API/
│
├── src/test/java/
│   ├── testcases/
│   ├── base/
│   ├── utils/
│
├── testdata/
├── reports/
├── pom.xml / requirements.txt
└── README.md
🔑 API Under Test

Base URL:

https://restful-booker.herokuapp.com
Endpoints Covered
Method	Endpoint	Description
GET	/ping	Health Check
POST	/auth	Generate Token
POST	/booking	Create Booking
GET	/booking/{id}	Get Booking
PUT	/booking/{id}	Update Booking
PATCH	/booking/{id}	Partial Update
DELETE	/booking/{id}	Delete Booking
▶️ How to Run Tests
🔹 Using Maven (Java)
mvn clean test
🔹 Using Pytest (Python)
pytest -v
📊 Reporting

Test execution reports are generated under /reports

Includes:

Passed/Failed tests

Execution time

Logs

Response validation details

🧪 Sample Test Flow

Generate Auth Token

Create Booking

Get Booking

Update Booking

Delete Booking

Validate Deletion

⚙️ Setup Instructions

Clone the repository:

git clone https://github.com/Vish123468/API.git

Navigate to project directory:

cd API

Install dependencies:

Maven auto-downloads dependencies

For Python:

pip install -r requirements.txt
🛡️ Best Practices Implemented

Reusable request specifications

Environment configuration handling

Modular test structure

Proper assertions and validations

Clean code principles

📌 Future Enhancements

CI/CD integration (GitHub Actions / Jenkins)

Docker support

Allure reporting

Performance testing integration

Data-driven testing

👨‍💻 Author

Vishakha Patil
vishakha98patil@gmail.com