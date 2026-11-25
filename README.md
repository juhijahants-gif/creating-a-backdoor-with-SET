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

<img width="490" height="687" alt="image" src="https://github.com/user-attachments/assets/b4016166-293f-4cf5-96c7-90e35ec20df7" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="459" height="281" alt="image" src="https://github.com/user-attachments/assets/aa90678a-ade3-46dc-b0b3-9b7f037f1778" />




It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT
<img width="692" height="435" alt="image" src="https://github.com/user-attachments/assets/fb4bef33-337c-41b0-8dba-e5d2454c419e" />





The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT
<img width="304" height="134" alt="image" src="https://github.com/user-attachments/assets/161e407f-9833-4622-be4c-cffc8b243084" />

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
##OUTPUT:
<img width="556" height="187" alt="image" src="https://github.com/user-attachments/assets/253b5731-80e0-4add-9eb8-56bbf032b218" />




It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="448" height="230" alt="image" src="https://github.com/user-attachments/assets/cddaf9b1-3fbc-43c6-a6ec-087311729440" />



It shows the following screen in which the option Google can be selected:
## OUTPUT
<img width="322" height="219" alt="image" src="https://github.com/user-attachments/assets/1371875c-5086-4dc9-8fbe-5750970a9750" />





SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT
<img width="664" height="127" alt="image" src="https://github.com/user-attachments/assets/9acd98cd-93a1-4fa2-a4d6-81a74d78c1b1" />




In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="599" height="574" alt="image" src="https://github.com/user-attachments/assets/afd746ef-2cfc-4def-82f9-763012af6b81" />



SET logs the information regarding the Google credentials:
## OUTPUT
<img width="646" height="168" alt="image" src="https://github.com/user-attachments/assets/4b39a913-9dbe-488c-80d1-58877dbf0568" />



SET logs the information in the xml file under /root/.set directory:
## OUTPUT
<img width="654" height="218" alt="image" src="https://github.com/user-attachments/assets/cfb6679e-06e3-4a02-bfa0-2eb32fbdea90" />












## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
