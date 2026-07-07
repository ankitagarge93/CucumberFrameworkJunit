# Selenium Cucumber Automation Framework

## Overview
This project is a Selenium WebDriver automation framework built using Java, Cucumber (BDD), and Maven. It is designed for practicing automated UI testing using the Page Object Model (POM) and Cucumber feature files.

## Tech Stack
- Java
- Selenium WebDriver
- Cucumber
- Maven
- TestNG/JUnit (whichever you are using)
- Page Object Model (POM)

## Features
- Behaviour Driven Development (BDD) using Cucumber
- Page Object Model (POM)
- Reusable utility methods
- Configurable browser and environment
- Test execution through Maven
- Scenario reporting
- Easy maintenance and scalability

## Prerequisites
- Java 11 or above
- Maven
- IDE (IntelliJ IDEA/Eclipse)
- Chrome Browser
- ChromeDriver (if not managed automatically)

## Installation

1. Clone the repository:
```
git clone <repository-url>
```

2. Navigate to the project:
```
cd Selenium-Cucumber-Framework
```

3. Install dependencies:
```
mvn clean install
```

## Running Tests

Run all tests:
```
mvn test
```

Run a specific feature:
```
mvn test -Dcucumber.filter.tags="@Smoke"
```

## Reporting
After execution, reports can be found in the generated reports folder.

## Best Practices
- Follow Page Object Model.
- Keep feature files readable.
- Write reusable step definitions.
- Store test data separately.
- Use explicit waits wherever required.

## Author
Created for Selenium Cucumber framework practice.
