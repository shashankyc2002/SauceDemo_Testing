# SauceDemo_Testing
README: SauceDemo Selenium Test Suite
This project automates key workflows on https://www.saucedemo.com using Selenium with Python. The automated scripts cover:
- Login
- Adding a product to cart
- Completing the checkout process
🔧 Setup Instructions
1. Ensure you have Python 3.7+ installed.
2. Install Google Chrome and download the matching version of ChromeDriver from https://chromedriver.chromium.org/downloads
3. Install required Python packages:
pip install selenium
📁 Folder Structure

saucedemo-automation/
│
├── test_login.py
├── test_add_to_cart.py
├── test_checkout.py
├── README.docx
└── screenshots/ (optional)

🚀 Run Instructions
To run the scripts, open your terminal or command prompt in the project folder and execute:
python test_login.py
python test_add_to_cart.py
python test_checkout.py
📌 Notes
- Make sure chromedriver is added to your PATH or located in the script directory.
- Screenshots will be saved if there is a failure during execution for easier debugging.
- Tests are built for the standard_user login with password: secret_sauce
