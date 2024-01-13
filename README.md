# LinkedIn Job Application Automation Script

This script automates the job application process on LinkedIn using Selenium.

## Prerequisites

- Python 3.x
- Selenium library (`pip install selenium`)
- Chrome WebDriver

## Usage

1. Open the script and update the following variables with your LinkedIn login credentials and phone number:

    ```python
    ACCOUNT_EMAIL = "YOUR LOGIN EMAIL"
    ACCOUNT_PASSWORD = "YOUR LOGIN PASSWORD"
    PHONE = "YOUR PHONE NUMBER"
    ```

2. Run the script:

    ```bash
    python script_name.py
    ```

3. Follow the instructions to manually solve the CAPTCHA when prompted.

4. The script will open the specified job search page, reject cookies, and sign in to your LinkedIn account.

5. It will then iterate through job listings, click on each listing, and attempt to apply for the job.

6. If a CAPTCHA is encountered during the application process, the script will pause and prompt you to solve it manually.

7. Review the script output for any skipped applications due to complex forms or missing application buttons.

8. Once all applications are attempted, the script will wait for a few seconds and then close the browser.

## Notes

- The script may need adjustments if there are changes to the LinkedIn website structure.

- Keep the browser window open if the script crashes to inspect the issue.

## Disclaimer

Use this script responsibly and in compliance with LinkedIn's terms of service. Automating interactions with websites may violate their policies.
