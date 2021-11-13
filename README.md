# birthday-bot
Have you ever wished to automatically wish your friends on their birthdays, or send a set of messages to your friend ( or any Whastapp contact! ) automatically at a pre-set time, or send your friends by sending thousands of random text on whatsapp! Using Browser Automation you can do all of it and much more!
First you must install these:- 
1) Python Bindings for Selenium ( Browser Automation software ) 
 

pip install selenium
2) Chrome webdriver 
Download Chrome driver from here: Chromedriver download page( choose your specific version )
How the bot does it
The script uses PySelenium package to open a Chrome webdriver window on which all tasks are done. It checks if the current date and month matches the ones in a json file. If yes, the ‘name’ attribute of it is returned which is used to find the corresponding chat in Whatsapp web(finding by xpath). The script then simulates click on the chat, opens it, types the message in the chat box and simulates a click on the send button.
 
