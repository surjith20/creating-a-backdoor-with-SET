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

<img width="1062" height="517" alt="image" src="https://github.com/user-attachments/assets/4ea7f50a-9ea4-4967-a097-e7d8e23dfb7f" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="1050" height="512" alt="image" src="https://github.com/user-attachments/assets/ef272388-5278-4927-949c-63789b469769" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="1066" height="518" alt="image" src="https://github.com/user-attachments/assets/3d776f46-2756-4953-aef5-177f9aac2535" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="1067" height="422" alt="image" src="https://github.com/user-attachments/assets/98027ee0-8b76-42b3-adfd-5e80080b5b02" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT
<img width="1087" height="652" alt="image" src="https://github.com/user-attachments/assets/24ef1e7a-0837-4cd1-8186-6abfc7d8a65e" />




It shows the following screen in which the option Google can be selected:
## OUTPUT
<img width="1065" height="532" alt="image" src="https://github.com/user-attachments/assets/e69d7f66-c294-4c2d-ac3a-65367c149dd9" />





SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT
<img width="1080" height="530" alt="image" src="https://github.com/user-attachments/assets/dd418427-cf7d-41e1-8633-198798d958a5" />




In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="1085" height="530" alt="image" src="https://github.com/user-attachments/assets/ca4d6806-a021-4761-9638-24b2a6811df4" />


SET logs the information regarding the Google credentials:
## OUTPUT
<img width="1067" height="361" alt="image" src="https://github.com/user-attachments/assets/24d1f877-0a59-4e22-8b29-75fe5bc7bf86" />



SET logs the information in the xml file under /root/.set directory:
## OUTPUT

<img width="1072" height="522" alt="image" src="https://github.com/user-attachments/assets/9176cd84-98ca-4561-8cb4-30c3cfda52fa" />


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is examined successfully








## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
