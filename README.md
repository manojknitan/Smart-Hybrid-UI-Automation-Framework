# Smart-Hybrid-UI-Automation-Framework
This repo is complete framework for UI automation.
# Selenium TestNG POM Automation Framework

A scalable, maintainable, and modular **Selenium Automation Framework** built using:

* **Java 21**
* **Selenium WebDriver**
* **TestNG**
* **Page Object Model (Page Factory)**
* **Maven**
* **Log4j Logging**
* **Listeners & Retry Analyzer**
* **Utility Classes (Reusable Components)**

This repository is ideal for **SDET-level automation**, interview preparation, and real-world project use.

---

## 📁 Project Structure

```
project-root
│
├── src
│   ├── main
│   │   ├── java
│   │   │   ├── com.framework.base
│   │   │   ├── com.framework.pages
│   │   │   ├── com.framework.utilities
│   │   │   └── com.framework.listeners
│   │   └── resources
│   │       ├── config.properties
│   │       └── log4j2.xml
│   ├── test
│       └── java
│           └── com.framework.testcases
│
├── testng.xml
├── pom.xml
└── README.md
```

---

## 🚀 Features

### ✔ Page Object Model (Page Factory)

Improves readability and reduces duplication.

### ✔ TestNG Listeners

Captures:

* Test start/end
* Logs
* Screenshots on failure

### ✔ Retry Analyzer

Automatically retries failed test cases.

### ✔ Log4j Logging

Logging for:

* Test steps
* Exceptions
* Info/debug/error logs

### ✔ Utilities

* Browser factory
* Wait helpers
* Excel/Data utilities
* Config loader

### ✔ Maven Integration

* Dependency management
* Easy execution from CLI/Jenkins

---

## ⚙️ Prerequisites

* Java 17 or 21
* Maven 3+ installed
* Chrome/Edge browser

---

## ▶ How to Run Tests

### **Run using Maven**

```
mvn clean test
```

### **Run using TestNG file**

```
Right-click → Run `testng.xml`
```

---

## 🧪 Sample Test Workflow

1. Load configuration
2. Launch browser using BrowserFactory
3. Navigate to URL
4. Perform actions using POM classes
5. Validate results using TestNG assertions
6. Logs captured via Log4j
7. Screenshots captured on failure

---

## 📊 Reports

### TestNG Default Reports

Located under:

```
target/surefire-reports
```

### Custom HTML Reports (Optional)

You can integrate:

* ExtentReports
* Allure Reports

---

## 🛠 Technologies Used

| Technology         | Purpose                             |
| ------------------ | ----------------------------------- |
| Java               | Programming language                |
| Selenium WebDriver | UI automation                       |
| TestNG             | Test runner + assertions            |
| Maven              | Build + dependencies                |
| Log4j              | Logging                             |
| Page Factory       | POM implementation                  |
| Retry Analyzer     | Re-run failed tests                 |
| Listeners          | Logging and reporting customization |

---
