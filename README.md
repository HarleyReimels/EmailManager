# Email Manager

#### This program uses Google's Gmail API to print out each unique email address from your inbox.
<hr/>

## Why would I want to know about unique email addresses in my inbox?
If you are like me, you probably receive many emails every day, from companies you do not care about. If not dealt with immediately your inbox can quickly pile into the thousands. Within these thousands
of useless emails, you probably have some that you want to save. By looking at who sent you the email, you can easily decide which emails you want to keep and which ones you would like to erase.
<hr/>

## How it's made
##### Gmail API
In order for this program to work for you, first you must follow these steps to grant your email permission to connect. <a href="https://developers.google.com/gmail/api/quickstart/python">How to grant your email
permission</a> Now that your email has permission, inside the code on line 19, you must replace "Your Email Here" with your email address. An example would be "LoremIpsum@gmail.com".

###### How is this version different than the Python quickstart?
The Python Quickstart version creates a folder for each email in your inbox and records the message and any attachments. In this version we are not saving any files, we are only taking a look at
who is sending us emails, and their email address. Looking through this list you can erase any emails from specific senders you wish to keep, everything else can then be purged. This is to help you get
an overwhelming number of emails under control, without deleting some emails that may hold importance to you.
<hr/>

## Features Coming Soon
All original emails will be saved into a Txt file in the same folder.

Once you are done erasing email addresses you wish to keep you can call the erase function.

All of the emails will then be removed from your account.
<hr/>

Author: Harley Reimels

Contact: Reimels.Harley@gmail.com

