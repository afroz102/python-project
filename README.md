## BITCOIN NOTIFICATION ALERT APP
----------------------------------------------------------------------------------------------------------------------------

This is a python script package, bitcoin price notification to get notified for the regular updates of bitcoin price on slack, gmail and telegram. 
The aim is to push notifications when the price of bitcoin changes at certain time interval, user can specify the time interval. By default time interval and threshold are set to 1 in minutes and $10000 respectively.
When the conditions in the program are satisfied the trigger is fired and user will recieve notifications on slack, gmail  telegram and twitter.


----------------------------------------------------------------------------------------------------------------------------
## DESCRIPTION 
---------------------------------------------------------------------------------------------------------------------------

Bitcoin price is a fickle thing. You never really know where it’s going to be at the end of the day. So, instead of constantly checking various sites for the latest updates, let’s make a Python app to do the work for you.

We’re going to use the popular automation website IFTTT.

We’re going to create there IFTTT applets:

One for emergency notification when Bitcoin price falls under a certain threshold and
one for regular Telegram and one for Slack updates on the Bitcoin price.

These will be triggered by our Python app which will consume the data from the Coindesk API.

An IFTTT applet is composed of two parts: a trigger and an action.

Trigger will be a webhook service provided by IFTTT.

Our Python app will make an HTTP request to the webhook URL which will trigger an action. Now, this is the fun part—the action could be almost anything you want. IFTTT offers a multitude of actions like sending an email, updating a Google Spreadsheet and even calling your phone.


----------------------------------------------------------------------------------------------------------------------------
## INSTALLATION
----------------------------------------------------------------------------------------------------------------------------

You might need to do these installations

1. Install python version 3

This website will help you find all the versions available as per your system requirments.Install python3.

https://www.python.org/downloads/

2. Installation for PIP for windows

```
pip install 
```

Refer this website for further read
https://pip.pypa.io/en/stable/installing/


**Note:** Make sure you have pip3 installed. to check, run ``` pip3 --version``` on your terminal.

3. **Dependencies**

The only dependency is the requests library.


Install requests using ``` pip3 install requests ```

4. **Install bitcoin-notifier package/module**.

 Just run ```pip3 install afroz-bitcoin-price``` on your terminal.


----------------------------------------------------------------------------------------------------------------------------
## USAGE
----------------------------------------------------------------------------------------------------------------------------
Following query on terminal will provide you with all the help options 

### INPUT
```
afroz-bitcoin-price -h
```
### OUTPUT 
```
usage: afroz-bitcoin-price [-h] [--d decision] [--i interval]
                               [--u upper threshold]
```

Bitcoin Notification Alert
```
optional arguments:
  -h, --help           show this help message and exit
  --d decision         Enter (Y/N) - Yes will run the program
  --i interval         Enter time interval
  --u upper threshold  Set upper threshold limit in USD for notification
```

**Default value**:
 Command ``` afroz-bitcoin-price ``` will take parameters --d as Y, --i as 1 and --u as 10000 in USD.
 Or you can change 
``` afroz-bitcoin-price --d=Y --i=1 --u=10000 ```

This will provide 5 prices of Bitcoin, at the specified time interval according to the code.


-----------------------------------------------------------------------------------------------------------------------------------------------
## TELEGRAM GROUP INVITE LINK - 
----------------------------------------------------------------------------------------------------------------------------

Go to this link

https://t.me/joinchat/L5pJsBmFWhCQwtKVye4oDw



----------------------------------------------------------------------------------------------------------------------------
## FOLLOW THIS ACCOUNT FOR UPDATE ON TWITTER - 
---

https://twitter.com/sahil44375804

----------------------------------------------------------------------------------------------------------------------------## CONTRIBUTIONS

----------------------------------------------------------------------------------------------------------------------------
Updates are always welcome, feel free to drop your suggestions! 
Looking forward for your contribution. ❤️

-----------------------------------------------------------------------------------------------------------------------------------------------

