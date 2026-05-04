# IT3040 - ITPM Semester 1
## Assignment 1 - Option 1: Transliteration Accuracy Testing

This repository contains the automated testing script for evaluating the Sinhala transliteration function of the pixelssuite chat translator. 

### Instructions to install dependencies

1. Ensure you have Python 3 installed.
2. Install the required Python packages by running the following command in the terminal:
   ```bash
   pip install playwright openpyxl
   ```
3. Install the Playwright browsers:
   ```bash
   playwright install chromium
   ```

### Instructions to run tests

1. Open a terminal and navigate to the project directory containing the `test_automation.py` script.
2. Run the script using the following command:
   ```bash
   python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000
   ```
3. The script will automatically open a Chromium browser, execute the 50 test cases, and record the Actual Output and Status in the `Assignment 1 - Test cases.xlsx` file.
