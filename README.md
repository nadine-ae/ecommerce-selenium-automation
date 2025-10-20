# Ecommerce-Selenium-Automation

This project contains automated UI test scripts for an e-commerce web application, built with **Java, Selenium WebDriver, and TestNG**.  
It demonstrates core functional test cases such as user registration, login, product browsing, and cart management — focusing on UI validation only, without database verification.

## Overview
The purpose of this project is to practice and showcase automation testing skills:
- Using Selenium WebDriver for browser automation.
- Structuring tests with TestNG annotations.
- Applying assertions to validate expected outcomes.
- Running tests on a sample e-commerce web application.

## Setup
### Prerequisites
- Java JDK 8 or later  
- Maven  
- TestNG  
- A supported browser (e.g., Chrome, Edge) with the appropriate WebDriver

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/nadine-ae/ecommerce-selenium-automation.git
   ```
2. Import the project into your IDE (e.g., Eclipse or IntelliJ) as a Maven project.  
3. Ensure dependencies are installed (see `pom.xml`).

## Running the Tests
- To run tests with Maven:
  ```bash
  mvn clean test
  ```
- Or run individual tests directly from your IDE via TestNG.

## Test Coverage
Current test cases include:
- User registration and login flow.  
- Product browsing and search functionality.  
- Adding and removing products from the cart.  
- Validating UI messages and navigation elements.

## Project Structure
- `src/test/java` → contains TestNG test classes and Selenium logic  
- `pom.xml` → Maven configuration with dependencies (Selenium, TestNG)  
- `README.md` → project documentation

## Notes
- This project focuses on **UI-based functional testing** only — no database or API validation.
