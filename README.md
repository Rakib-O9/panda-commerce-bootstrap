# Microsoft Outlook
**Yandex Outlook seetings link: https://yandex.com/support/mail/mail-clients/microsoft-outlook.html**

# Step 1. Configure your mailbox
1.	Open the “Email clients” section in Yandex.Mail settings.
2.	Select the following options: From the imap.yandex.com server via IMAP and App passwords and OAuth tokens.
3.	Save changes.
Note. If you want the emails to be kept for some time after they are deleted in the mail client, select Don't automatically delete emails marked as deleted in IMAP. Please note that they will be permanently deleted from the mailbox immediately after restarting the mail client.

# Step 2. Create an app password

1.	Go to [Account Management](https://passport.yandex.com/profile/).
2.	Under Passwords and authorization, click Enable app passwords. Confirm the action and click Create a new password.
If you have [two-factor authentication](https://yandex.com/support/passport/authorization/twofa.html) enabled, just click Create an app password.
3.	Select the application type Mail.
4.	Come up with a password name. For example, you may enter the name of the app you're creating the password for. The password will be displayed in the list under this name.
5.	Click Create. The app password will be displayed in a pop-up window.
Restriction. You can only see the created password once. If you entered it incorrectly and closed the window, delete the current password and create a new one.

# Step 3. Configure IMAP-based client

•	Outlook 2016
Launch the program. Enter your email address, select Advanced parameters → Set up an account manually and click Connect.
1.	Enter the app password that you [created](https://yandex.com/support/mail/mail-clients/microsoft-outlook.html#app-pass) for Yandex.Mail. Click Enable.
2.	Select IMAP.
3.	Set the following account settings:
Incoming mail:
o	Server: imap.yandex.com.
o	Port: 993
Outgoing mail:
o	Server: smtp.yandex.com.
o	Port: 465
Leave default values for other parameters and click Next to test the account settings. If all the settings are correct and confirmed, click Finish. If not, make sure that all the details are entered properly.
Changing the server settings
1.	Launch the program and click Next in the welcome screen.
2.	In the Account setup window, leave Yes as the default value and click Next.
If you already have an Outlook account and want to add another one, click File → Details → Add a new account.
3.	Select Manual setup or additional server types and click Next.
4.	Select POP or IMAP and click Next.
5.	Set the following account settings:
o	Your Name — user name (for example, “Alice Little”)
o	Email address — your Yandex email address (for example, “alice.the.girl@yandex.ru”)
o	Type of account — IMAP.
o	Incoming mail server — imap.yandex.com
o	Outgoing email server (SMTP) — smtp.yandex.com
o	User — your Yandex username
o	Password: The app password you [created](https://yandex.com/support/mail/mail-clients/microsoft-outlook.html#app-pass) for Yandex.Mail.
Attention. If you are configuring email delivery from a mailbox such as “login@yandex.com”, your username is the first part of the address before the “@” symbol. If you're using [Yandex 360 for Business](https://business.yandex.com/mail360), enter your full email address as the username.
Leave default values for other parameters and click Other settings.
6.	Go to the Outgoing mail server tab, enable the SMTP server requires authentication checkbox, and select the Same as incoming mail server value.
7.	Go to the Advanced tab. For the Use the following type of encrypted connection option, select SSL for the IMAP and SMTP servers. Set the following parameters:
o	IMAP server — 993
o	SMTP server — 465
Leave default values for other parameters and click OK.
8.	To finish account configuration, click Next in the Add a new account window to test the account settings. If all the settings are correct and confirmed, click Finish. If not, make sure that all the details are entered properly.
