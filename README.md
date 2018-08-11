# SMTP Extension for Magento 2 - FREE SMTP module

Have you ever wondered why sometimes, if you have to send an email to address@example.com with your Gmail account, you send it to the smtp.gmail.com server; but then this server will send your message to the MX server of example.com, as a result, the mail is marked as a spam? That’s about time to learn more about SMTP to look back this.

### Install via composer

```
composer require mageplaza/module-smtp
```

![smtp configuration](https://i.imgur.com/VnCM6SB.png)


## Magento 2 SMTP Extension
SMTP module for Magento 2, which is well compatible with Magento 2’s platform scale, will assist you to resolve email sending issues. By available popular email server providers, our extension absolutely would like to support you with them in sending email with a huge amount of quanlity, faster speed along with high secure authentication. Hence, Mageplaza SMTP will also provide you a log diary which archive all the detail sent emails, makes it easier to keep track and checking problems. Be ready to say goodbye to Spam box issues.

### Support 20+ SMTP service providers
Not only your own custom SMTP server, but also Mageplaza STMP extension supports the customization from available email service providers, like:

- Mailgun
- Mandrill
- SendinBlue
- SendGrid
- Elastic Email
- SparkPost
- Mailjet
- Gmail
- Amazon SES
- Hotmail
- Office365
- Outlook
- Zoho Mail
- Mail.com
- Postmark
- AOL Mail
- Comcast
- GMX
- O2 Mail
- Orange
- Yahoo Mail
- Yahoo Mail Plus
- Yahoo AU/NZ
- AT&T
- NTL @ntlworld.com
- BT Connect
- Verizon
- BT Openworld
- O2 Online Deutschland
- Custom SMTP


### Autofill SMTP configuration button
The first ever start in configuring a SMTP server, is choosing your particular pre-defined email vendor you’re partner with. Then the Autofill button will take the second step that when you click it, Authentication and Protocol fields will be entered automatically with figures being valid with the SMTP provider you chose. This incredible function won’t fail to make you amazed by the cut off consuming time in typing section. 

### Self-testing email function
This function will allow you to manually check your email sending, with the defined SMTP providers, inputted Protocol and Host, to claim if your marketing mails can be sent to the correct Inbox.

Just a small note that with the testing email you’re choosing, especially with Gmail+ provider, a separate tutorial How to configure Gmail SMTP in Magento 2 conducted to adapt massive Gmail users in question how exactly they can manage to command Gmail+ server properly. The important key is, you should turn POP/IMAP to be enabled in the testing gmail account setting. For other email providers, the configuration will be similar.

### Logging sent emails
Poses as a cautiously function, all the sent email will be stored in a separated module from Configuration faculty, let you have an overview list about a sent mail status, creating day and its  particular preview.

Email logs can be scheduled to be cleaned after a customizable day(s) 


## How to configure
Here we go how to know detail in instructions and configuration in extension’s backend.

### Email logs
This can be accessed by the following Mageplaza > SMTP > Email Logs. From here you can look back all the sent email from the server to customers.
Email logs
By clicking View in each mail, you can have a general looking at the display which how your email will reach customer’s eyes. Hit the Clear red button to clear all the archived emails after checking carefully.
Order

### Configuration
#### General Configuration
Be sure you’re at Admin Panel, for general configuration Mageplaza > SMTP > Configuration > General Configuration

Choose Yes to enable Mageplaza SMTP on.

#### SMTP Configuration Options
Still from the same structure with SMTP General Configuration, scroll down to see SMTP Configuration Options

- In SMTP Provider field, at the moment we support provider nearly 30 SMTP email service providers so feel free to choose your appropriate provider. Click Auto Fill button to fill Host, Port, Authentication and Protocol automatically, which are compatible with the SMTP provider you had chosen.
- At Host field, type your Support Host name and ID Address. You can also custom STMP Provider’s Host name at here. If you had clicked Auto fill button at the above field, you can give this step a free pass.
- Port is a specific gate where emails will be sent through. You can also pass this step if you had choose Auto fill from the first place. In general, there will be 3 kinds of Default Port
- Port 25: Emails sent by other Protocol which different SSL will be sent through this portal
- Port 465: Emails sent by other Protocol SSL will be sent through this portal
- Port 578: Emails sent by other Protocol TLS will be sent through this portal
- Authentication field is place where you decide an authentication method. If you hadn’t clicked Auto fill button before, please note those basic methods
- Login: Authentication by login to the account through Username and Password that will be filled in the next field. Most of provider will require this method.
- Plain
- CRAM-MD5
- Account: where you enter the account name matching format of the SMTP Provider you had selected
- Password: password of the Username. After saving, the password will be encrypted into **
- Protocol: pass this step if you had chosen Auto fill, or you can select one of the providing protocol below here
- None: when you select this protocol, you have to accept all the risk may occur in the process of sending.
- SSL stands for Secure Socket Layer. This protocol ensures that all data exchanged between the web server and the browser is secure and stay safe.
- TLS means Transport Layer Security. This protocol secures data or messages and validates the integrity of messages through message authentication codes.
- Return-path email: leave it empty if you want to ignore this.
- Test email recipient: This is the field for you to test the operation of the extension. After filling all fields, click Test Now button. If the information entered is valid, a successful email notification will be sent from Username to Email Test. That email will have the following content:
smtp test result

#### Schedule Log Cleaner
This section is placed right under SMTP Configuration Options, which is from Admin Panel > Mageplaza > SMTP > Configuration > scroll down and expand to see Schedule Log Cleaner
smtp cleaner
The Clean Email Log Every field limits the storage time for the email you sent. After that limited number of days, Email will automatically delete. If you do not want to delete the emails, leave the field blank.

#### Developer mode
Log Email will supply two modes:
- Yes: Sent emails will be saved in the Emails Log, you can preview it and having it clean up follow fixed schedule.
- No: Sent emails won’t be archived.

**Developer Mode:**
- Yes: Magento will not deliver any email to receiver
- No: Magento will deliver email to receiver



Every email marketing moves need *SMTP* for their life. It’s the simplest form of email communicating; it’s the quickest way when comes to facilitate the internal technical transmission; it’s the most popular method in sending out electronic mail messages across networks that run on IP or the Internet Protocol; it’s the best choice thanks to the amazing flexibility that it can be well fitable with every e-commerce platform, such as great Magento.

Fundamentally, there are some highlight points what make SMTP become sought after by email marketing runners:

- The simplicity: Instead of requiring you to check (POP) your emails before being sent out through native servers, SMTP authentication accepts you to simply deliver them safely and the redundant check section will be remove conveniently.
- The advance: If you are expecting an intermediate solution which can manage to send unlimited emails successfully; email list will be hidden as well as you still can have full control; the most saving efficient? Definitely learning how to configure SMTP your server will be a good practice to rock your business.
- The reliability: It will possess as a hard-working man, always try to re-send the same email until the process can be done. Cut down the time-consuming steps is one of a notable strength of SMTP that is truly welcomed by developers as well as marketers. They don’t have to be involved in all-around minor works but gravity toward the email content effectively.   

With its simple but very effective features, SMTP continues to become the most widely used messaging standard. Common steps such as modifying existing messages by adding a custom header to set the campaign for different message streams, or enabling the tracking of the opening or clicking tend to be significantly less complex than starting to use the API.

This troubleshoot still presents in Magento 2’s store when store owners use the default SMTP server of Magento, to launch their email marketing in these recent years. How to configure an available email provider SMTP is a thing, but how we can do that in a complicated platform with a limit of your budget and time? We’re really please to introduce another expert solution for Magento 2’s store

