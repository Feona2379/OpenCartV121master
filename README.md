
---

```markdown
# 🛒 OpenCart Automation Testing Framework

A Selenium Test Automation Framework built with **Java** and **TestNG** to validate core user flows on the [OpenCart](https://demo.opencart.com/) e-commerce platform.

## ✨ Features

- ✅ Account Creation Test
- ✅ User Login Test
- ✅ Add-to-Cart and Cart Validation Test

This project demonstrates real-world test case automation using Selenium WebDriver, with a scalable Page Object Model and TestNG for test organization.

---

## 🧰 Tech Stack

| Tool/Library      | Purpose                           |
|-------------------|------------------------------------|
| Java              | Core programming language          |
| Selenium WebDriver| UI automation                      |
| TestNG            | Test execution framework           |
| Maven             | Dependency management & build tool |
| POM               | Design pattern for test structure  |
| Extent Reports*   | Test reporting (optional)          |

---

## 📁 Project Structure

```

OpenCartAutomation/
├── src/
│   └── test/java/
│       ├── base/           # Test setup & teardown
│       ├── pages/          # Page classes (e.g., LoginPage, CartPage)
│       ├── tests/          # TestNG test classes
│       └── utils/          # Utilities (e.g., waits, configs)
├── testng.xml              # TestNG suite configuration
├── pom.xml                 # Maven project file
└── README.md               # Project documentation

````

---

## ✅ Test Cases Overview

### 🧾 Account Creation
- Navigate to registration
- Fill mandatory fields
- Submit and verify registration confirmation

### 🔐 Login
- Input valid credentials
- Verify dashboard access and logout flow

### 🛒 Cart Items
- Add product to cart
- Validate item count, price, and removal

---

## 🚀 Getting Started

### Prerequisites
- Java JDK 8+
- Maven
- Chrome browser
- ChromeDriver (in your system PATH)

### Clone and Run

```bash
git clone https://github.com/yourusername/OpenCartAutomation.git
cd OpenCartAutomation
mvn clean test
````

### Run with TestNG XML

Right-click `testng.xml` → **Run As > TestNG Suite** (in your IDE)

---

## 📊 Reports

* Default TestNG reports available in `/test-output`
* Optionally integrate **ExtentReports** for enhanced visuals

---

## 📌 Best Practices Used

* Page Object Model (POM)
* TestNG groups and prioritization
* Clean code and reusable test methods
* Separation of test data and logic

---

## 🤝 Contributing

Contributions are welcome! Open a PR or issue to suggest improvements.

---

## 📞 Contact

**Feona Donnal**
📍 Ontario, Canada
📧 [feonadonnal@gmail.com](mailto:feonadonnal@gmail.com)
[LinkedIn](https://www.linkedin.com/in/yourprofile)

---

*This is an educational testing project and not affiliated with OpenCart officially.*

```



