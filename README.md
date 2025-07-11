# Hearthstone Battlegrounds Combat Skip
Long combats in Hearthstone battlegrounds is a longstanding issue that has yet to be properly addressed.  
There are a few methods to skip combat, and this was created so that everyone can be aware of them.  
The methods below are equivalent to unplugging your internet cord for a few moments, so are not bannable.
Many streamers use equivalent methods, but they are paid, or not publicly accessible.  


## Method 1. AutoIt Macro  
This is the fastest method.  
This AutoIt program closes the game connection that hearthstone uses for the match.   
Hearthstone will then immediately reconnect. 
You will need admin privileges to run this.  
Install AutoIt here: https://www.autoitscript.com/site/  
Then run the .au3 file provided in the repository.  
When you're in a match, F5 is the hotkey to drop the connection.  

## Method 2. Windows Firewall Manual  
Use this method if you don't want to install/run any programs on your computer.  
This creates a rule in windows firewall that you manually enable then disable to disrupt the games connection.  
[Guide for this is here](Method%202.%20Firewall%20Manual/README.md)
  
## Method 3. Windows Firewall Batch File  
This method is the same as method 2 but automated.  
Run the batch file when you want to skip combat.  
The batch file will automatically create the firewall rule, wait 3 seconds and then delete the rule.

## Method 4. Close Out Method  
Simply closing the game and restarting it will put you at the end of combat. This is generally pretty inconvenient and slow.
  
  
## Other Notes  
The AutoIt script does the same thing as this https://github.com/haoruan/HDT-Reconnector but without the need of another program.  

Message me on Reddit if you need help: https://old.reddit.com/message/compose/?to=deathtorn   
