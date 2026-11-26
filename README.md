# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
## OUTPUT

![Alt text](<Screenshot at 2026-11-25 15-54-59.png>)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

![Alt text](<Screenshot at 2026-11-25 15-56-28.png>)

It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

![Alt text](<Screenshot at 2026-11-25 15-57-22.png>)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

![Alt text](<Screenshot at 2026-11-25 15-58-34.png>)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT
![Alt text](<Screenshot at 2026-11-25 16-14-28.png>)



It shows the following screen in which the option Google can be selected:
## OUTPUT
![Alt text](<Screenshot at 2026-11-25 16-16-03.png>)




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT
![Alt text](<Screenshot at 2026-11-25 16-31-19.png>)



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

![Alt text](<Screenshot at 2026-11-25 16-42-25.png>)

SET logs the information regarding the Google credentials:
## OUTPUT
![Alt text](<Screenshot at 2026-11-25 16-40-51.png>)


SET logs the information in the xml file under /root/.set directory:
## OUTPUT

![d ](<Screenshot at 2026-11-25 16-54-36.png>)










## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
