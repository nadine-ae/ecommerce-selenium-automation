# AutomationTestStore – UI Automation Tests

This project contains automated UI test scripts for [Automation Test Store](https://automationteststore.com/) built with **Java, Selenium WebDriver, and TestNG**.  
It demonstrates core functional test cases such as navigating the site, interacting with forms, and validating expected behaviors on the front end.

## Overview
The purpose of this project is to practice and showcase automation testing skills:
- Using Selenium WebDriver for browser automation.
- Structuring tests with TestNG annotations.
- Applying assertions to validate expected outcomes.
- Running tests on a sample e-commerce application.

## Setup
### Prerequisites
- Java JDK 8 or later
- Maven
- TestNG
- A supported browser (e.g., Chrome, Edge) with the appropriate WebDriver

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/nadine-ae/AutomationTestStore-Automation-UI.git
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
- Navigating to the Automation Test Store homepage.
- Account creation and login flow.
- Adding and removing products from the cart.
- Validating UI messages and page elements.

## Project Structure
- `src/test/java` → contains TestNG test classes and Selenium logic.
- `pom.xml` → Maven configuration with dependencies (Selenium, TestNG).
- `README.md` → project documentation.

## Notes
- This project does not connect to a database; tests validate UI functionality only.
- A companion project with UI + DB validation exists in [`AutomationTestStore-Automation-UI-Database`](https://github.com/nadine-ae/AutomationTestStore-Automation-UI-Database`).
