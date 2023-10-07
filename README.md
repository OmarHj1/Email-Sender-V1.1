**README.md**

**Email Sender**

**Version 1.1**

**New features:**

* Added support for command line arguments to specify the number of seconds to wait between sending emails and to exclude email addresses from the mailing list.

**Usage:**

1. Run the program and enter your SMTP server, port, sender email address, sender password, and email subject.
2. Select your "msg" file, which is the file containing the email body.
3. Select your "maillist" file, which is the file containing the recipient email addresses.
4. Optionally, specify the number of seconds to wait between sending emails and any email addresses to exclude from the mailing list using command line arguments.
5. The program will then send the emails to all of the recipients in the maillist file.

**Command line arguments:**

* `-w <seconds>`: Wait for the specified number of seconds between sending emails.
* `-e <email addresses>`: Exclude the specified email addresses from the mailing list. Multiple email addresses can be specified by separating them with commas.


**Note:** This program is for educational purposes only. Please use it responsibly.

**New update in this version:**

You can now specify the number of seconds to wait between sending emails and the email addresses to exclude from the mailing list using command line arguments, but these values are set in the code and cannot be changed by the user.

This is useful for preventing your email server from blocking you and for ensuring that your emails are delivered to all of the intended recipients.
