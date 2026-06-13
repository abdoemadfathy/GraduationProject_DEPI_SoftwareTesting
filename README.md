# OpenCart E-Commerce Full-Cycle QA & Automation Project

##  Project Overview
This repository showcases a comprehensive, end-to-end QA Audit independently executed on the OpenCart E-Commerce platform. The project spans the entire Software Testing Life Cycle (STLC), including strategic test planning, manual execution, API validation, database integrity checks, and building a scalable UI Automation framework from scratch.

---

##  Technologies Used
* **Automation:** Java, Selenium WebDriver, Cucumber BDD, TestNG, Maven, Page Object Model (POM)
* **API Testing:** Postman
* **Database Testing:** MySQL / SQL Server
* **Project Management & Tracking:** Jira, MS Excel
* **Version Control:** Git & GitHub

---

##  Testing Phases & Artifacts

### 1. Test Planning & Strategy
* Designed a thorough Test Plan defining the scope, environment configuration, test entry/exit criteria, and risk assessment for the E-Commerce platform.
* Developed comprehensive Test Scenarios and Test Cases covering core user journeys (Auth, Cart, Checkout, Account Management).

### 2. Manual Testing & Defect Management
* **Functional Testing:** Executed manual test runs for critical paths like product searching, filtering, and multi-shipping checkout workflows.
* **Regression & Smoke Testing:** Performed structured validation after changes to ensure core stability.
* **Defect Tracking:** Logged and tracked critical bugs (e.g., business logic flaws, edge cases) with detailed steps to reproduce, expected vs. actual results, and severity mapping.

### 3. API Testing (Postman)
* Validated core REST API endpoints ensuring accurate HTTP status codes, response times, and payload structures.
* Handled CRUD operations using **GET, POST, PUT, and DELETE** requests along with authentication token validation.

### 4. Database Testing (SQL)
* Performed backend data validation to ensure strict data integrity.
* Executed advanced SQL queries to verify user account creation records, inventory deductions post-checkout, and order state transitions in the database.

### 5. UI Automation Framework
* Built a robust, scalable **Behavior-Driven Development (BDD)** framework using **Selenium WebDriver with Java and Cucumber**.
* Implemented the **Page Object Model (POM)** to enhance code reusability and maintainability.
* **Key Framework Features:** Integrated global hooks, customized test runners, precise assertions, and automated failure screenshot capturing.

---

##  Automated Scenarios Covered
* Complete User Registration & Field Validation
* User Login / Logout (Positive & Negative flows)
* Dynamic Product Search & Filtering
* Shopping Cart Operations (Add, Update, Remove)
* Full End-to-End Checkout Workflow

---

##  Key Achievements
* Independently designed and executed the entire QA lifecycle for a complex E-Commerce platform.
* Developed and optimized **40+ automated test scripts** with clean, maintainable code.
* Uncovered critical functional and backend bugs through parallel manual and SQL database checks.
* Structured a modular GitHub repository layout dividing Manual, API, DB, and Automation phases seamlessly.

---

## 📁 Repository Structure
```text
OpenCart-Full-Cycle-QA-Project/
│
├── 📁 Automation-Testing/
│      ├── 📁 src/
│      │     ├── 📁 pages/              # Page Object Classes
│      │     ├── 📁 stepDefinitions/    # Cucumber Step Definitions
│      │     ├── 📁 runners/            # TestNG Runners
│      │     └── 📁 hooks/              # Setup/Teardown Methods
│      ├── 📁 features/                 # BDD Gherkin Feature Files
│      └── 📄 pom.xml                   # Maven Dependencies
│
├── 📁 Manual-Testing/                  # Test Cases & Defect Reports
├── 📁 API-Testing/                     # Postman Collections
└── 📁 Database-Testing/                # SQL Verification Scripts
