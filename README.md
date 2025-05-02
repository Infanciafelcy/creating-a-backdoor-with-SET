# Ex-07-Creating-a-backdoor-with-SET
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

## OUTPUT:
![image](https://github.com/user-attachments/assets/d52ccf91-ea36-4ce1-acb0-3fe05b051d52)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu 1 for Social Engineering Attacks.
It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/user-attachments/assets/4eb0fda1-877c-470e-bcfc-c87ace915b5f)


![image](https://github.com/user-attachments/assets/7872db22-f7ef-4478-bf70-e7b509beed3e)

The website Attack Vectors displays the following menu. In this menu, 3 for Credential Harvester Attack Method is selected:

![image](https://github.com/user-attachments/assets/9a35360e-58ed-4f6d-bb9b-c548acba0b84)

The Credential Harvester Attack Method displays the following menu. In this menu, 1 for Web Templates is selected:

![image](https://github.com/user-attachments/assets/8613d2f2-8d43-49c4-8f3f-b37e360861c1)

The Credential Harvester Attack Method displays the following menu. In this menu, 1 for Web Templates is selected.
It shows the following screen in which the IP address of the attacker needs to be given (default value):

![image](https://github.com/user-attachments/assets/8c9ef014-dc62-454b-8956-4b69878ebddf)


It shows the following screen in which the option Google can be selected:

![image](https://github.com/user-attachments/assets/0ca5670d-ac7d-457a-a128-c49818a2cec1)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/user-attachments/assets/7d332d00-33d2-4148-a416-9b83bc6e9610)

In Windows IE, on giving the URL http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password.

![image](https://github.com/user-attachments/assets/c686b1f7-7edb-4a25-903d-552abc8b7d2e)


SET logs the information regarding the Google credentials:
![image](https://github.com/user-attachments/assets/267dce2e-8c6b-4699-afe1-2767f36f21c6)

SET logs the information in the XML file under /root/.set directory:

![image](https://github.com/user-attachments/assets/7e938928-153b-41cd-8932-0f5fac1e4939)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
