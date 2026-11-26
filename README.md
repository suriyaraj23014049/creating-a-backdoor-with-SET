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
<img width="697" height="842" alt="image" src="https://github.com/user-attachments/assets/dfeec224-ebde-445e-8221-1a562bc12d2a" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT
<img width="376" height="270" alt="image" src="https://github.com/user-attachments/assets/a6b64d3b-8a56-42c0-8167-5b927c9ed0c5" />



It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT
<img width="367" height="325" alt="image" src="https://github.com/user-attachments/assets/27f48045-1ab0-4da4-8797-aec0d6fbd1f9" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT
<img width="365" height="217" alt="image" src="https://github.com/user-attachments/assets/5d634191-8f7f-4a43-86f0-441ac03c364f" />



It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT
<img width="760" height="552" alt="image" src="https://github.com/user-attachments/assets/b6bd772f-2c95-4fb1-8b86-aed44b29be2c" />




It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="697" height="480" alt="image" src="https://github.com/user-attachments/assets/63b1357c-f9a0-4b85-b507-ce37ec687839" />




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT
<img width="1155" height="196" alt="image" src="https://github.com/user-attachments/assets/249d0dac-9163-49ea-ad7d-7edffde8f957" />




In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="997" height="770" alt="image" src="https://github.com/user-attachments/assets/0c36d73a-d67e-4f6a-8755-29ec46c99e1e" />


SET logs the information regarding the Google credentials:
## OUTPUT
<img width="1268" height="572" alt="image" src="https://github.com/user-attachments/assets/2e21edf5-a0d0-44ec-bb42-ad8b5f22aaff" />



SET logs the information in the xml file under /root/.set directory:
## OUTPUT

<img width="1323" height="806" alt="image" src="https://github.com/user-attachments/assets/fe501e82-f08b-4b2e-82cb-f399c542f477" />












## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
