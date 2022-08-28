# Outlook, on Windows

This is a guide on how to set up AHRA email on various Microsoft Outlook flavours.

## Pre-requisites

Before starting the process, I would suggest that you check you have the correct password for the email account by testing the same via the [webmail login](https://altmail.blacknight.com).

- The username is always the full email address, i.e. _commitee@ahra.ie_.
- The password is that of the email account as provided by the webmaster.

If you find that the login is not working via the webmail then the likelihood is you do not have the correct password, contact Stuart at #42.

## Setting up Email on Outlook 2019

Outlook will try to fetch setup information automatically but will be unable to do so, as such you need to keep clicking Connect (or Next) until it lets you proceed to the next step to enter details manually.

Open Outlook and go to __File__ >> __Add Account__  and type in your _&lt;name here&gt;@ahra.ie_  email address.  _Ensure you tick "Let me set up my account manually" and then click Connect._

![Connect new account](/img/outlook-2019-1.png)

Choose __IMAP__ from the list shown.

![Advanced Setup](/img/outlook-2019-2.png)

Type in your __password__.

![Enter Password](/img/outlook-2019-3.png)

You will be presented with this screen, enter the information as per the image below.
!!! note
    You _must_ use __mail.blacknight.com__ as the Incoming and Outgoing Server hostnames.

Enable Encryption:

- Use 993 and SSL/TLS for the Incoming Connection.
- Use 587 and STARTTLS (or TLS) for the Outgoing connection.

Once ready, click __Next__.

![Enter account settings](/img/outlook-2019-4.png)

The account should then be added.

!!! recommendation
    We recommend ___unchecking___ the box for "Outlook Mobile" and then click __OK__ to finish the process.

![Enter account settings](/img/outlook-2019-5.png)

## Setting up Email on Outlook 2016

!!! note
    As of August 2017, Microsoft updated the interface on Outlook 2016. As a result, you need to ensure you "Manually Configure" the mailbox in Outlook - where the "Auto Configuration" will not work/complete.

You would carry out the following steps within the "Control Panel".

1. Click Start and then type "Control Panel" and press enter on the keyboard.
1. Choose "Mail (Microsoft Outlook 2016)"
1. Click on "Email accounts".
1. Click on "File"
1. Click on "Account Settings" (On the info section)
1. Click on "New" ("Change" if the account already exists)
1. Click on "Microsoft Exchange, POP3, IMAP, or HTTP" and press Next (If creating new)
1. Click on "Manually configure server settings or additional server types" and press Next
1. Click on "Internet E-Mail" and press "Next" (If creating new)

Fill in the various fields as follows:

- __Your Name__: Whatever name you want to appear on your Emails.
- __E-Mail Address__: Your AHRA email address.
- __Account Type__: IMAP
- _Incoming Mail Server_: mail.blacknight.com.
- _Outgoing Mail Server_ (SMTP): mail.blacknight.com.
- _User Name_: Your AHRA email address.
- __Password__: The password you assigned to the email account when you created it.

Then to complete the configuration of the "Outgoing Server" settings:

- Press "More Settings" and go to "Outgoing Server".
- Select "My outgoing server (SMTP) requires authentication".
- You can set it to "Use same settings as my incoming mail server".
- Press "Advanced" and change the outgoing server port from 25 to 587 and press OK.

Press Next and Finish to finish setting up the email account.

## Setting up Email on Outlook 2010/2013

You would carry out the following steps within Outlook.

1. Click on "File"
1. Click on "Account Settings" (On the info section)
1. Click on "New" ("Change" if the account already exists)
1. Click on "Microsoft Exchange, POP3, IMAP, or HTTP" and press Next (If creating new)
1. Click on "Manually configure server settings or additional server types" and press Next
1. Click on "Internet E-Mail" and press "Next" (If creating new)

Fill in the various fields as follows:

- __Your Name__: Whatever name you want to appear on your Emails.
- __E-Mail Address__: Your AHRA email address.
- __Account Type__: IMAP
- _Incoming Mail Server_: mail.blacknight.com.
- _Outgoing Mail Server_ (SMTP): mail.blacknight.com.
- _User Name_: Your AHRA email address.
- __Password__: The password you assigned to the email account when you created it.

Then to complete the configuration of the "Outgoing Server" settings:

1. Press "More Settings" and go to "Outgoing Server".
1. Select "My outgoing server (SMTP) requires authentication".
1. You can set it to "Use same settings as my incoming mail server".
1. Press "Advanced" and change the outgoing server port from 25 to 587 and press OK.

Press Next and Finish to finish setting up the email account.
