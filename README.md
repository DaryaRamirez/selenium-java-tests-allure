🧪 Selenium Java UI Automation Tests with Allure Reporting

This project contains automated UI tests implemented using Java, Selenium WebDriver, TestNG, Maven, and Allure Reports, with GitHub Actions CI for continuous integration.

The framework follows industry-standard automation practices (POM, reusable utilities, structured test suites).

⚙️ Tech Stack

Java 17

Selenium WebDriver

TestNG

Maven

Allure Report

GitHub Actions (CI/CD)

Page Object Model (POM)

🚀 How to Run Tests Locally

1️⃣ Clone the repository
git clone https://github.com/DaryaRamirez/selenium-java-tests-allure.git

cd selenium-java-tests-allure

2️⃣ Run tests using Maven
mvn clean test

3️⃣ Generate Allure report
allure serve allure-results


⚠️ Make sure Allure CLI is installed:

https://docs.qameta.io/allure/#_installing_a_commandline

🧩 Implemented Test Scenarios

🔐 Login Test

Validates successful login using valid credentials

Verifies UI elements, navigation, and system responses

Includes before/after hooks, screenshots, and detailed steps in Allure

🔄 Continuous Integration (GitHub Actions)

The CI workflow:

Runs tests on every push and pull request

Generates Allure results

Ensures code stability and fast feedback

Demonstrates ability to run tests in cloud CI without local setup

📸 Sample Allure Report

Allure generates:

Interactive test history

Screenshots on failure

Step-by-step execution logs

Attachments & environment details


👩‍💻 Author

Darya Ramirez
QA Automation Engineer

LinkedIn: https://www.linkedin.com/in/daryaramirez7

GitHub: https://github.com/DaryaRamirez
