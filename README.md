Here’s your **complete README (text only)** for the **Web Automation with Selenium | BDD Framework** project:

---

# Web Automation with Selenium | BDD Framework (Java, Selenium, TestNG)

A real-world login + dashboard test automation project using Selenium WebDriver, Cucumber BDD, and TestNG. Built with the Page Object Model (POM) and CI/CD-ready architecture, this project ensures clear test coverage for both valid and invalid login flows.

---

## Features

* Automated login and dashboard test flows for a 2-page application
* BDD Framework with Cucumber and Gherkin syntax
* Test prioritization (P0, P1) with TestNG
* Page Object Model (POM) for reusable, clean code
* Valid & invalid login scenario coverage
* Bug analysis with scope and root cause documentation
* GitHub version control and CI/CD-ready structure

---

## Tech Stack

* Java
* Selenium WebDriver
* Cucumber (BDD)
* TestNG
* Maven
* Git & GitHub

---

## Folder Structure

Selenium-Login-Dashboard-Automation/
├── src/
│   ├── main/java/pages/             → POM: Page classes
│   └── test/java/
│       ├── stepDefinitions/         → Step Definitions for BDD
│       └── runners/                 → TestNG + Cucumber Runner classes
│
├── src/test/resources/features/     → Gherkin Feature Files
├── testng.xml                       → TestNG Configuration
├── pom.xml                          → Maven dependencies
└── README.md                        → Project Info

---

## Test Scenarios

| Test Case              | Description                        | Priority |
| ---------------------- | ---------------------------------- | -------- |
| Valid Login            | Correct username/password          | P0       |
| Invalid Login          | Wrong username or password         | P0       |
| Empty Fields           | Login with empty input fields      | P1       |
| Dashboard Verification | Post-login dashboard content check | P1       |

---

## How to Run Tests

1. Clone the Repository:

```bash
git clone https://github.com/mayankgaur0405/Selenium-Login-Dashboard-Automation.git  
cd Selenium-Login-Dashboard-Automation  
```

2. Install Dependencies via Maven:

```bash
mvn clean install  
```

3. Run Tests using TestNG:

```bash
mvn test  
```

---

## Bug & Test Plan

* **Scope**: Authentication and UI flow of login + dashboard.
* **Bugs**: Covered in invalid login attempts (e.g., blank input, incorrect credentials).
* **Root Cause**: Identified and documented in test reports.

---

## Future Scope

* Integrate with Jenkins for CI/CD
* Add Extent Reports for rich HTML reporting
* Cross-browser testing using TestNG XML
* Dockerized execution for scalable environments

---

## Author

**Mayank Gaur **
GitHub: [https://github.com/mayankgaur0405](https://github.com/mayankgaur0405)
Email: [mayankgaur1504@gmail.com](mailto:mayankgaur1504@gmail.com)

---

## License

This project is licensed under the MIT License – free to use and modify.

