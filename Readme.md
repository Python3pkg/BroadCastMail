# BroadCastMail :outbox_tray:

### A Python Package which can be used to BroadCast email .

**To-Add Features**
  * HTML Email .
  * Support Attachments .
  * Support Images .

**Installation**
  * You'll need python3
  * Pip is recommended for installing

  ```
  $ pip install BroadCast
  ```

**Usage**
``` python

import BroadCast
send=BroadCast.mail("username","password") #login details
send.broadcast()
```

#### Description

* List of all packages used in above Scripts

>Smtplib - Simple Mail Transfer Protocol

>MimeMultipart-email - Breaking Message into To , From , Subject  & Body .

>[Validate_email](https://github.com/syrusakbary/validate_email) - Validate_email is a package for Python that check if an email is valid, properly formatted and really exists.

* List of SMTP servers

>Gmail smtp.gmail.com (port 465 or 587)

>Outlook.com/Hotmail.com smtp-mail.outlook.com

>Yahoo Mail smtp.mail.yahoo.com

>AT&T smpt.mail.att.net (port 465)

>Comcast smtp.comcast.net

>Verizon smtp.verizon.net (port 465)

**Note-** Do not Misuse .
