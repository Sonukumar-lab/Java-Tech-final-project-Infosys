# Java Batch Final Project – Milestone Four

## Project Description
This project is a **Java-based Test Automation Framework** developed as part of the **Java Batch Milestone Four assessment**.  
The framework follows **Agile methodology**, uses **Maven** for dependency management, and implements the **Page Object Model (POM)** design pattern to ensure maintainable, reusable, and scalable automation code.

---

##  Development Methodology
The project was developed using the **Agile Methodology** throughout its lifecycle.

Development was carried out iteratively across multiple sprints, including:
- Requirement Analysis  
- Automation Framework Setup  
- Test Case Implementation  
- Test Execution and Documentation  

 Detailed sprint-wise execution with dates is documented in **AGILE.md**.

---

## 🛠 Technology Stack
- Java  
- Maven  
- Selenium  
- TestNG  
- Git & GitHub  
- Eclipse IDE, IntelliJ IDEA  

---

##  Project Structure Overview
```text
Java-Batch-final-project/
│
├── Herokuapp/milestonefour/        # Main automation framework
│   ├── src/test/java/herokuapp/milestonefour
│   │   ├── basetest
│   │   ├── pages
│   │   ├── pagestest
│   │   ├── listeners
│   │   └── utility
│   │
│   ├── resources
│   │   └── config.properties
│   │
│   ├── pom.xml
│   └── testng.xml
│
├── four/                           # Maven setup & wrapper
├── AGILE.md                        # Agile execution document
├── LICENSE                         # MIT License
└── README.md                       # Project documentation

```
---
# Execution Instructions

## Prerequisites
---
Java JDK 11 or above

Maven

Git
---
# Run Test Suite

Navigate to the main project directory:

cd Herokuapp/milestonefour
mvn clean test
