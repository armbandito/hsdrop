# 2. Windows Firewall Manual  
 This method creates a rule in windows firewall that you manually enable then disable to disrupt the game connection. 
 

### First open up Windows Defender Firewall with Advanced Security:  
![image1](1.png)  
### Select Outbound rules, Create a new rule  
![image2](2.png)  
### Rule type is Port  
![image3](3.png)  
### Rule Applies to TCP and the specific port is 3724  
![image4](4.png)  
### Choose to block the connection  
![image5](5.png)  
### It should apply to Domain, Private, and Public  
![image6](6.png)  
### Name it something like "Hearthstone Skip Battle"  
![image7](7.png)  
It should now show at the top of the list.  

When you want to skip combat, you will enable the rule, and wait a few seconds, then disable the rule
This is what it will look like when you want to use it:  
![image2](SkipCombat.gif)  
