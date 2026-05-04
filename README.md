# IT3040-Assignment-1

## Automated Testing for Singlish to Sinhala Transliteration

- **Registration Number:** IT23857858
- **Course:** IT3040 - ITPM (Semester 1)
- **Option:** 1 (Sinhala)

---

## Project Description

This project evaluates the accuracy of the **Chat Sinhala transliteration function** available at [PixelSuite Chat Translator](https://www.pixelsuite.com/chat-translator). It automates testing with **50 negative test cases** covering all **24 Singlish input types** specified in Appendix 1 of the assignment.

---

## Repository Structure
IT3040-Assignment-1/
│
├── IT23857858_test_automation.py → Playwright automation script
├── IT23857858 - Test cases.xlsx → Excel file with 50 test cases & results
├── requirements.txt → Python dependencies
└── README.md → Project documentation


---

## Technologies Used


Python 3.14.4 - Programming language
Playwright - Browser automation for UI testing
OpenPyXL - Excel file handling 
GitHub - Version control & submission 

---

## Test Results Summary


 Total Test Cases  -   50 
 FAIL - 50 
 PASS - 0 
 UI Errors - 0 
 Input Types Covered -   All 24 (2+ per type) 

---

## How to Run the Tests
### Prerequisites
- Python 3.11 or higher
- Google Chrome browser


### Setup Instructions

**Clone the repository**
   
   git clone https://github.com/GuwaniHazel/IT3040-Assignment-1.git
   cd IT3040-Assignment-1


Install dependencies :   pip install -r requirements.txt
                         playwright install

Run the automation script :     python IT23857858_test_automation.py --excel "IT23857858 - Test cases.xlsx" --url "https://www.pixelsuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
