# IT3040 Test Automation - Singlish to Sinhala Transliteration

## Prerequisites
- Python 3.11 or 3.12
- Install dependencies: `pip install playwright openpyxl`
- Playwright browsers: `playwright install`

## Running the Tests
`python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --input-col "Input" --expected-col "Expected output" --actual-col "Actual output" --status-col "Status" --wait-ms 3000`

## Test Cases
Excel file contains 50 negative test cases covering Singlish input types defined in the assignment appendix.
