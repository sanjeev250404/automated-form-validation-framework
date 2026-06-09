# Automated Form Validation Framework

A Python and Selenium based automation framework built during my internship at Palle Technologies, Bangalore.
Designed to validate web forms under multiple input conditions with automated reporting.

---

## What This Project Does

- Validates web forms under multiple input conditions
- Tests valid, invalid, empty, and boundary value inputs
- Detects and logs bugs automatically during test execution
- Generates automated test reports in HTML and Excel format
- Reduced manual testing time by 80%
- Improved bug detection with clear pass/fail logs for every test run

---

## Tools and Technologies

- Python
- Selenium WebDriver
- PyTest
- PyCharm
- HTML Reporting
- Excel Reporting

---

## Test Cases Covered

- Valid form submission with correct data
- Empty field validation
- Special characters in input fields
- Boundary value testing on character limits
- Duplicate entry handling
- Dropdown and checkbox validation
- Error message verification for each invalid input

---

## Project Structure

automated-form-validation-framework/
├── tests/
│   ├── test_form_valid_inputs.py
│   ├── test_form_invalid_inputs.py
│   └── test_boundary_values.py
├── pages/
│   └── form_page.py
├── reports/
│   ├── test_report.html
│   └── test_report.xlsx
└── README.md

---

## How to Run

1. Clone this repository
2. Install dependencies: `pip install selenium pytest openpyxl`
3. Run tests: `pytest tests/`

---

## About Me

QA Tester | Python | Selenium | Manual & Automation Testing
Internship: Palle Technologies, Bangalore (July 2025 – Jan 2026)
