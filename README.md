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

<img width="1920" height="944" alt="VirtualBox_kali_setoolkit" src="https://github.com/user-attachments/assets/37d4bcba-0819-4ecc-bbee-07626eebd0a4" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="1298" height="291" alt="VirtualBox_kali_social engineering" src="https://github.com/user-attachments/assets/3638d23a-a68f-47e7-a459-c634487376c1" />



It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="725" height="294" alt="Screenshot 2026-05-21 084510" src="https://github.com/user-attachments/assets/1a6f1dae-ea6d-4f0b-94ce-762d74772032" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="718" height="210" alt="Screenshot 2026-05-21 084900" src="https://github.com/user-attachments/assets/1e133bdb-eaa4-415d-8766-b057e139d986" />



<img width="722" height="131" alt="Screenshot 2026-05-21 084916" src="https://github.com/user-attachments/assets/bd2ae921-7c91-46b6-ae9c-e95b1f4c94da" />



It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT


<img width="940" height="481" alt="Screenshot 2026-05-21 091829" src="https://github.com/user-attachments/assets/8310e225-ca40-44a2-a9c0-f365db63c051" />



It shows the following screen in which the option Google can be selected:
## OUTPUT


<img width="958" height="356" alt="Screenshot 2026-05-21 091841" src="https://github.com/user-attachments/assets/eb16e4d8-008b-42cb-960d-d3eebbf707ac" />



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="958" height="356" alt="Screenshot 2026-05-21 091841" src="https://github.com/user-attachments/assets/8f4ffa44-4d60-42cc-8ee6-1476814f214c" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="956" height="913" alt="Screenshot 2026-05-21 091716" src="https://github.com/user-attachments/assets/1b412c9e-85f5-4fc0-86fe-1c2563b9c06e" />



SET logs the information regarding the Google credentials:
## OUTPUT


<img width="1920" height="944" alt="VirtualBox_kali_google username" src="https://github.com/user-attachments/assets/28edc207-bc66-4c4b-9913-23a1e832e9ea" />


<img width="1920" height="944" alt="VirtualBox_kali_firefox apple" src="https://github.com/user-attachments/assets/8d6fd183-b7c5-4c77-9a83-5bc048833d1f" />



<img width="953" height="265" alt="Screenshot 2026-05-21 091917" src="https://github.com/user-attachments/assets/626390c8-13b3-4f6b-b526-e95c4813a0e7" />


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
