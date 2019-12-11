# nodemailer-app

Ultimate email debugging tool.

See [Releases](https://github.com/nodemailer/nodemailer-app/releases) for release info or [nodemailer.com/app](https://nodemailer.com/app/) for specific downloads and additional info.

## Description

NodemailerApp is the ultimate cross platform email debugging app.

App includes local SMTP and POP3 servers, a sendmail replacement, and it imports emails from EML files, EMLX files, large MBOX files from Gmail takeout, Maildir folders and Postfix queue files for inspection and preview. Ever wanted to view the actual HTML source of a nicely designed email instead of some garbled rfc822 text? Just open the HTML tab of an email to see it.

Features:

* **Preview emails** either in rich text or plain text mode. View the source of the entire message or the decoded HTML content
* **Sendmail replacement** to catch emails from applications that pipe to sendmail (eg. PHP `mail(…)`).
* **Local development server** to catch emails from applications that send via SMTP (Nodemailer, PHPMailer etc.).
* **Message upload** to relay a caught message either to next SMTP server or to an IMAP server.
* **Extensive search** to find long lost emails.
* **Large mailbox import.** Received a 10GB mbox takeout file from Gmail? No problem, just import it to NodemailerApp.
* **Catchall service** to accept messages from the internet.
* **Multi platform** to run in Windows, Linux and OSX.
