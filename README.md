# UI Automation Framework - Java Selenium
Hi this is Sayantan Mukherjee. Thank you for visiting my profile. This project is a UI Test Automation Framework built using **Java**, **Selenium WebDriver**, and **TestNG/JUnit**, designed to automate end-to-end testing of web applications. It follows the **Page Object Model (POM)** for enhanced code maintainability and reusability.

## Features

- Java + Selenium WebDriver
- Page Object Model (POM) design pattern
- TestNG (or JUnit) for test orchestration
- Maven for project and dependency management
- Extent Reports or Allure Report integration
- Cross-browser support (Chrome, Firefox, Edge)
- Logging with Log4j or SLF4J
- Screenshot capture on test failure
- Easy scalability for large test suites
- CI/CD ready (Jenkins/GitHub Actions compatible)

## Technologies Used

- **Language**: Java  
- **Automation Tool**: Selenium WebDriver  
- **Build Tool**: Maven  
- **Test Runner**: TestNG / JUnit  
- **Reporting**: Extent Reports / Allure  
- **Logging**: Log4j  
- **Browser Drivers**: ChromeDriver, GeckoDriver, EdgeDriver  

## Project Structure

├── src
│ ├── main
│ │ └── java
│ │ └── pages # Page classes (POM)
│ │ └── utils # Utility classes
│ ├── test
│ │ └── java
│ │ └── tests # Test classes
│
├── testng.xml / junit.xml # Test suite config
├── pom.xml # Maven dependencies
├── logs # Logs folder
├── reports # Test reports
└── README.md

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven
- Chrome/Firefox/Edge installed
- IntelliJ IDEA / Eclipse

### Clone the Repository
bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

## Install Dependencies
bash
Copy code
mvn clean install

## Run Tests
1. Using Maven
bash
Copy code
mvn test

2. Using TestNG XML
bash
Copy code
mvn test -DsuiteXmlFile=testng.xml

## Reports and Logs
Test execution reports will be generated under the reports/ directory.

Execution logs will be available in the logs/ folder.

Screenshots of failed test cases will be saved automatically.

## CI/CD Integration
This framework can be easily integrated with Jenkins, GitHub Actions, or any CI/CD tool. Use the mvn test command as part of your pipeline.

## Contribution
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## Author
Name: Sayantan Mukherjee
GitHub: https://github.com/sayantanviky
LinkedIn: https://www.linkedin.com/in/sayantan-mukherjee-9975b3b7


