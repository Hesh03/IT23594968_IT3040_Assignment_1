
Here is the updated, comprehensive README.md content specifically tailored for your repository. It includes all the necessary technical details, instructions, and project information required for your assignment submission.
IT3040 - IT Project Management | Assignment 01
Transliteration Accuracy Testing (Singlish to Sinhala)
1. Project Overview
This project focuses on evaluating the accuracy of the Singlish-to-Sinhala transliteration tool provided by PixelsSuite Chat Translator. The evaluation is performed through automated testing using the Playwright framework. The goal is to identify 50 specific scenarios (Negative Test Cases) where the system fails to correctly transliterate informal "Chat-style" Singlish into accurate Sinhala text.

2. Student Information
Student Name: [Your Name Here]
Registration Number: IT23594968
Module: IT3040 – IT Project Management
Assessment: Assignment 1 (Option 1)

3. Repository Information
GitHub URL: https://github.com/Hesh03/IT23594968_IT3040_Assignment_1

4. Project Structure
The repository contains the following essential files:
test_automation.py: The core Python automation script utilizing Playwright.
Assignment 1 - Test cases.xlsx: The completed Excel report containing 50 negative test cases, expected/actual outputs, and rationales.
requirements.txt: Contains the list of Python dependencies required to run the project.
README.md: This documentation file providing project guidance.

5. Technologies Used
Language: Python 3.x
Automation Tool: Playwright (Synchronous API)
Data Handling: Openpyxl (for Excel integration)
Browser: Chromium (Google Chrome)

6. Installation & Setup
Follow these steps to set up the environment:
Clone the Repository:
code
Bash
git clone https://github.com/Hesh03/IT23594968_IT3040_Assignment_1.git
cd IT23594968_IT3040_Assignment_1
Install Dependencies:
code
Bash
pip install -r requirements.txt
Install Playwright Browsers:
code
Bash
python -m playwright install

7. How to Run the Automation
To execute the test suite and update the Excel file with actual results, run the following command in your terminal:
code
Bash
python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 15000 --type-delay-ms 100 --save-every 1 --keep-open
Note: Ensure the Excel file is closed before running the script to allow the automation to write data. If you encounter "Failed to fetch" errors due to server limits, using a VPN or Mobile Hotspot is recommended.

8. Test Case Details
Total Test Cases: 50 (All Negative Scenarios)
Categories Covered: 24 Singlish Input Types (as per Appendix 1).
Failure Analysis: Each case includes a rationale explaining why the transliteration failed (e.g., punctuation handling, English word mixing, or non-standard romanization).
Total Test Cases: 50 (All Negative Scenarios)
Categories Covered: 24 Singlish Input Types (as per Appendix 1).
Failure Analysis: Each case includes a rationale explaining why the transliteration failed (e.g., punctuation handling, English word mixing, or non-standard romanization).
