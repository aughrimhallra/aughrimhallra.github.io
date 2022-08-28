## Pre-requisites

Before starting the process, I would suggest that you check you have the correct password for the email account by testing the same via the [webmail login](https://altmail.blacknight.com).

- The username is always the full email address, i.e. _commitee@ahra.ie_.
- The password is that of the email account as provided by the webmaster.

If you find that the login is not working via the webmail then the likelihood is you do not have the correct password, contact Stuart at #42.

## Setting up Mac Mail

Please ensure to follow these instructions carefully as Mac Mail will not accept the email address unless these settings are specified.

1. Open Up Mac Mail and browse to the following:
    - __Mail__ > __Add Account__ > __Other Mail Account__
2. Provide the following settings:
    - __Name__: What you would like others to see when you send them an email
    - __Email address__: The _&lt;name here&gt;@ahra.ie_  email address you are adding to Mac Mail
    - __Password__: The password for this specific _&lt;name here&gt;@ahra.ie_  email address you are adding
3. Click Next and the provide the server information as requested:
    - _Account Type_: Choose __IMAP__
    - __Incoming & Outgoing Mail Server__: both _mail.blacknight.com_
4. If you receive an error regarding 'Unable to verify account settings', proceed regardless.
5. Browse to the following:
    - __Mail > Preferences > Accounts > Select email account > Server Settings__
6. Ensure the following settings are applied:
    - __Disable__ 'Automatically manage connection settings' for both Incoming and Outgoing
    - __Host name__: _mail.blacknight.com_ for all host name fields
    - Type the full _&lt;name here&gt;@ahra.ie_  email address for the username, and put in the password. Fill these out for both incoming and outgoing.
    - __Authentication__: Password for both incoming and outgoing
    - __Use TLS/SSL__ _must_ be __enabled__ for both incoming and outgoing
7. Finally, browse to the following and ensure these settings are applied:
   __Mail > Preferences > Accounts > Outgoing Mail > Account: Edit SMTP Server List__
    - Ensure _Automatically manage connection settings_ is disabled in here also
    - Insert the same __username, password and host name__ as above
    - _Port number for the outgoing server should be 587_.
