=============================
How to Set Up Roadrunner Email on Android?
=============================

Setting up your RoadRunner email on an Android device lets you access your messages on the go.

.. image:: https://img.shields.io/badge/Setup%20Now-blue?style=for-the-badge&logo=sign-in-alt&logoColor=white
   :width: 200px
   :align: center
   :target: https://getchatsupport.net/
   :alt: Get Help Button

Because RoadRunner is now managed by Spectrum, you will need to manually enter the correct server settings .

This guide provides step-by-step instructions for the setup process, the necessary server details, and solutions for common issues.

What You Need Before You Start
==============================

Before you begin the setup, make sure you have the following information ready:

- **Your full RoadRunner email address:** This is your complete email address.
- **Your RoadRunner email password:** This is the password for your email account .
- **A stable internet connection:** Connect your Android device to a secure Wi-Fi network or ensure you have a strong cellular data signal.

Step-by-Step Setup Guide
========================

The setup process involves adding your account to your Android device's email app. The exact steps and menu names may vary slightly depending on your device manufacturer and Android version .

**Step 1: Open Your Email App**
--------------------------------
Locate and open the default "Email" or "Mail" app on your Android device . Do not use the Gmail app for this initial setup, as it is intended for a different account type .

**Step 2: Add a New Account**
------------------------------
In the email app, navigate to the settings or menu to find the option to add a new account. This is often labeled "Add Account," "Add Email Account," or found under "Accounts" in the device's main Settings app .

**Step 3: Select "Other" or "Manual Setup"**
--------------------------------------------
When prompted to choose your email provider, select "Other" or "Manual Setup." RoadRunner is not listed among the automatic setup options, so you must configure the settings manually .

**Step 4: Enter Your Email Address and Password**
--------------------------------------------------
Type in your full RoadRunner email address and password. After entering them, tap "Manual Setup" or "Next" to proceed .

**Step 5: Choose IMAP as the Account Type**
-------------------------------------------
Select "IMAP" as the account type . IMAP is recommended because it synchronizes your emails across all your devices .

**Step 6: Configure the Incoming Server Settings**
--------------------------------------------------
In the incoming server settings section, enter the following information :

- **Server/Hostname:** The official Spectrum mail server address
- **Port:** 993
- **Security Type:** SSL/TLS
- **Username:** Your full RoadRunner email address
- **Password:** Your RoadRunner email password

**Step 7: Configure the Outgoing Server Settings**
--------------------------------------------------
In the outgoing server settings section, enter the following information :

- **Server/Hostname:** The official Spectrum mail server address
- **Port:** 587
- **Security Type:** STARTTLS or TLS
- **Username:** Your full RoadRunner email address
- **Password:** Your RoadRunner email password
- **Authentication:** Ensure this is enabled and set to "Password"

**Step 8: Complete the Setup**
-------------------------------
Tap "Next" or "Finish" to complete the setup. Your Android device will attempt to verify the settings . Once verified, you can customize your sync preferences, such as how often the app checks for new emails, and then tap "Done" .

Troubleshooting Common Setup Problems
=====================================

If you encounter issues during setup or after, try the following solutions.

"Incorrect Password" or "Authentication Failed" Error
-----------------------------------------------------
This is often due to entering the wrong credentials or a recent password change.

- Double-check that you are using your full email address and the correct password .
- If you recently changed your password, update it in the email app settings .

Cannot Verify Server Settings
-----------------------------
This usually indicates a mistake in the server details.

- Verify that the server addresses and port numbers are entered correctly .
- Ensure you selected IMAP and that SSL/TLS is enabled for both incoming and outgoing servers .
- If the problem persists, try deleting the account and re-adding it with the correct information .

App-Specific Issues
-------------------
- **Use the Correct App:** Make sure you are setting up the account in the "Email" app, not the "Gmail" app .
- **Clear App Cache:** If the app is not syncing, try clearing the app's cache in your device settings.
- **Update the App:** Ensure your email app is updated to the latest version .

Account Locked or Other Issues
------------------------------
If you have tried multiple times and your account becomes locked or you continue to experience problems, it is best to contact official support resources for assistance .

Frequently Asked Questions
==========================

Why do I need to use "Other" or "Manual Setup"?
------------------------------------------------
RoadRunner is a legacy service now managed by Spectrum. It is not a default provider in most Android email apps, so you must manually enter the server settings .

What are the correct server settings for RoadRunner email on Android?
----------------------------------------------------------------------
For most accounts, use the following settings:
- **Incoming Server (IMAP):** The official Spectrum mail server address, Port 993, SSL/TLS enabled.
- **Outgoing Server (SMTP):** The official Spectrum mail server address, Port 587, STARTTLS/TLS enabled.
- **Username for both:** Your full RoadRunner email address .

Can I use POP instead of IMAP?
-------------------------------
Yes, but IMAP is recommended. If you must use POP, ensure you use the correct POP server address and secure port settings .

Conclusion
==========

Setting up your RoadRunner email on an Android device is a straightforward process when you have the correct server settings. By following the manual setup steps and using the IMAP and SMTP server details provided, you can successfully configure your account on the native email app and access your messages on the go. If you encounter issues, double-check your server settings, ensure your credentials are correct, and consider re-adding the account.
