# SCIA & SPT Testing Portfolio

## 📌 Project Overview
This repository contains a full testing portfolio for two real-time projects:

1. **SCIA API Automation (SoapUI + Jenkins)**  
   - API testing using SoapUI (SOAP & REST)  
   - Data-driven testing, property transfers, environment switching (Dev/QA/Prod)  
   - Groovy scripts for response validation  
   - Jenkins CI/CD integration with HTML & JUnit reports  

2. **SPT Manual Testing (Postman + Excel)**  
   - Manual testing: Functional, Regression, Smoke  
   - Test cases documented in Excel  
   - Postman collections for manual API testing  
   - Bug templates and sample screenshots  

---

## 🗂 Repository Structure

SCIA_SPT_Full_Project_Fresh/
├── SCIA-API-Automation/
│ ├── SoapUI/
│ │ ├── SCIA-Project.xml
│ │ ├── Environments/
│ │ │ ├── dev.properties
│ │ │ ├── qa.properties
│ │ │ └── prod.properties
│ │ └── Data/client_data.csv
│ ├── Scripts/groovy_assertions.groovy
│ ├── Reports/test-report.html
│ ├── Reports/junit-report.xml
│ └── Jenkinsfile
│
├── SPT-Manual-Testing/
│ ├── TestCases/Smoke_TestCases.xlsx
│ ├── TestCases/Functional_TestCases.xlsx
│ ├── TestCases/Regression_TestCases.xlsx
│ ├── Postman_Collections/SPT_API_Collection.json
│ ├── Bugs/Bug_Report_Template.docx
│ └── Screenshots/
│
├── Diagrams/
│ ├── scia_architecture.png
│ ├── spt_testing_workflow.png
│ ├── api_testing_lifecycle.png
│ └── cicd_pipeline.png
│
└── Tools/
├── Postman/Environment.postman_environment.json
├── SoapUI/SoapUI-Installation-Steps.md
└── Jenkins/Setup_Guide.md


---

## 🛠 Tools Used
- **SoapUI**: API testing (SOAP & REST)  
- **Postman**: Manual API testing for SPT project  
- **Jenkins**: CI/CD pipeline for SCIA API Automation  
- **Excel**: Test case documentation  
- **Groovy**: Custom assertions in SoapUI  

---

## 📈 Features
- Full API automation with SoapUI for SCIA  
- Manual testing for SPT: Functional, Regression, Smoke  
- Data-driven testing using CSV  
- Environment switching (Dev / QA / Prod)  
- Jenkins pipeline automation with reports  
- Detailed test cases and bug reports  

---

## 📸 Screenshots & Diagrams
- `Diagrams/scia_architecture.png` → SCIA API architecture  
- `Diagrams/spt_testing_workflow.png` → SPT manual testing workflow  
- `Diagrams/api_testing_lifecycle.png` → Testing lifecycle  
- `Diagrams/cicd_pipeline.png` → Jenkins CI/CD pipeline  

---

## 📥 How to Use
1. **SCIA API Automation**
   - Open `SoapUI/SCIA-Project.xml`  
   - Set environment in `Environments/*.properties`  
   - Run test suites in SoapUI or via `Jenkinsfile`

2. **SPT Manual Testing**
   - Open Excel files in `SPT-Manual-Testing/TestCases`  
   - Use `Postman_Collections/SPT_API_Collection.json` for API testing  
   - Log bugs using `Bugs/Bug_Report_Template.docx`  

---

## 💻 GitHub Repository URL


https://github.com/
<nemani1997>/scia-spt-testing-portfolio


---

