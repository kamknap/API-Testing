# 🌐 API Testing (Postman)

## Description

This repository contains API tests created using Postman. The tests are organized into collections and cover various endpoints of a Trello application. The exported collections can be easily imported into Postman for local testing.

## Contents

### 1. Postman Collections

- **File:** [Trello.postman_collection.json](https://github.com/kamknap/API-Testing/blob/main/Trello.postman_collection.json)

- **Description:** This file contains the exported Postman collection for Trello API tests, including detailed requests, parameters, and expected responses for each API endpoint.

### 2. Postman Environment

- **File:** [Production.postman_environment.json](https://github.com/kamknap/API-Testing/blob/main/Production.postman_environment.json)

- **Description:** This file contains the environment settings required for the API tests, including base URLs and authentication tokens.

## Test Cases

### Trello API Tests

- **GET table list:** Verifies that the endpoint returns a list of tables and checks if the list is not empty.

- **POST create table:** Creates a new table and verifies the response status and table details.

- **PUT edit table:** Edits the table and checks if the name and description are updated correctly.

- **DELETE delete table:** Deletes the table and verifies the response status.

## Purpose

The goal of this repository is to demonstrate my ability to create, organize, and document API tests using Postman. The tests cover various scenarios and endpoints of a web application, showcasing my skills in API testing and automation.

Feel free to explore the contents of each file for more details.
