
first prepare account use https://github.com/wanghaisheng/persona-account-genius/tree/master



# social account genius


This project automates the creation of accounts on Instagram, Reddit, and TikTok using drissionpage and uiautomator2

you will need android phone+sim for rotate proxy

## Requirements

Make sure you have the following requirements installed:

- Python 3.x
- Chromedriver (for Selenium automation)

You can install the Python dependencies using `pip`:

```bash
pip install -r requirements.txt
```

Getting Started
Follow these steps to set up and run the project:

1. Clone the repository:

```bash
git clone https://github.com/<username>/<project_name>.git
cd <project_name>
```
2. Create a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the project dependencies:

```bash
pip install -r requirements.txt
```
4. Download and install Chromedriver:

Download the Chromedriver executable suitable for your system from the official website https://sites.google.com/chromium.org/driver/.
Place the Chromedriver executable in your system's PATH or specify its path in the relevant script.

5. Prepare your account and proxy data:

Create a text file named accounts.txt containing the account data in the following format: username,password,email (one account per line).
If you want to use proxies, create a text file named proxy.txt containing the list of proxy addresses (one proxy per line). If not, you can omit this file.

6. Run the project:

Execute the interaction.py script to start the account creation process:
```bash
python interaction.py
```
7. Monitor the output:
The script will create accounts on Instagram, Reddit, and TikTok (based on your settings) and provide feedback on the account creation process.

8. Check the results:
Account credentials (email, username, password) will be saved to a file named accounts.csv upon successful account creation.

- Configuration

You can modify the settings and customize the account creation logic in the following files:

create_accounts.py: Contains account creation and proxy handling functions for Instagram, Reddit, and TikTok.
main_gui.py: Contains the GUI interface for specifying the number of accounts to generate.

- Troubleshooting
If you encounter any issues, refer to the error messages provided by the script for debugging.

Ensure that Chromedriver is correctly installed and accessible in your system's PATH.

- Acknowledgments
Selenium - Web automation framework used for account creation.
Webdriver Manager - Used for Chromedriver management.
vbnet
Copy code


This is Still not finished feel free to contribute and let us stay better than Chat GPT!

inspired

https://github.com/wanghaisheng/Spotify-Account-Generator


https://github.com/wanghaisheng/create_appleid

https://github.com/wanghaisheng/auto-gen-apple-ids

https://github.com/wanghaisheng/cloudflare-email

https://github.com/wanghaisheng/Auto-Gmail-Creator

https://github.com/wanghaisheng/google-account

https://github.com/wanghaisheng/Outlook-Account-Creator

https://github.com/wanghaisheng/OutlookGen

https://github.com/wanghaisheng/edu-mail-auto-generator

https://github.com/wanghaisheng/YandexMail-Account-Creator

https://github.com/wanghaisheng/Fake-Person-Generator



https://github.com/wanghaisheng/microsoft-account-creator
