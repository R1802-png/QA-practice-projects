# QA Practice Projects

Manual testing practice work by **Ravikumar Kalburki**, built to develop and demonstrate hands-on QA skills — test case design, execution, and defect logging — using public demo applications.

📧 kalburkiravikumar@gmail.com | 📍 Bangalore, Karnataka

---

## About

I'm an aspiring Software Tester building practical experience in manual testing, test case design, and defect tracking. These projects were self-driven — I picked publicly available demo sites, wrote structured test cases against them, executed the tests, and logged any defects I found using an industry-style bug report format.

---

## Projects

### 1. Login Authentication Testing
**File:** `Practice_QA_Test_Cases_Login.xlsx`
**Site under test:** [the-internet.herokuapp.com/login](https://the-internet.herokuapp.com/login)

10 manual test cases covering:
- Valid and invalid login scenarios
- Empty field validation
- Username case sensitivity
- Password masking
- Logout flow
- SQL injection input safety
- Session behavior after logout (browser back button)

Includes a companion **Bug Report Log** tab with a real defect I identified during execution (username case-sensitivity behavior).

### 2. Dropdown, Checkbox & Form Validation Testing
**File:** `Practice_QA_Test_Cases_Dropdown_Checkbox_Form.xlsx`
**Site under test:** [the-internet.herokuapp.com/dropdown](https://the-internet.herokuapp.com/dropdown) & [/checkboxes](https://the-internet.herokuapp.com/checkboxes)

12 manual test cases covering:
- Dropdown default state and selection persistence
- Checkbox default states and independent toggling
- State reset behavior on page refresh
- Whitespace-only input handling
- Script-injection input safety

---

## Test Case Format

Each spreadsheet follows a standard manual test case structure:

| Field | Description |
|---|---|
| Test Case ID | Unique identifier (e.g., TC_LOGIN_001) |
| Module | Feature area under test |
| Test Scenario | What is being validated |
| Preconditions | State required before executing the test |
| Test Steps | Numbered steps to reproduce |
| Test Data | Input values used |
| Expected Result | What should happen |
| Priority | High / Medium / Low |
| Status | Pass / Fail / Not Executed |

Defects are logged with: Bug ID, related test case, summary, steps to reproduce, expected vs. actual result, severity, and status.

---

## Skills Demonstrated

- Manual test case design and documentation
- Functional, boundary, and negative testing
- Basic security-aware testing (input validation, injection handling)
- Defect logging and severity classification
- Structured QA documentation practices

## Tools & Concepts (currently learning)

Selenium WebDriver · TestNG · API Testing (Postman) · ISTQB Foundation concepts

---

*These are self-directed practice projects created to build real testing experience, not part of paid or professional work.*
