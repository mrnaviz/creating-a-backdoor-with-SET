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

## OUTPUT:

![image](https://github.com/mrnaviz/creating-a-backdoor-with-SET/assets/123350791/b76d0d16-c17b-421d-9b42-dd971887d6c3)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT:

![image](https://github.com/mrnaviz/creating-a-backdoor-with-SET/assets/123350791/db17a2be-1857-46ed-9384-714836eeabf9)


It displays the following menu and select 2 for Website Attack Vectors:


## OUTPUT:

![image](https://github.com/mrnaviz/creating-a-backdoor-with-SET/assets/123350791/c1cced19-88a2-4a9b-a10a-255d1ef7d0b2)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

## OUTPUT:

![image](https://github.com/mrnaviz/creating-a-backdoor-with-SET/assets/123350791/c0461b14-dfcf-4ce3-b75b-2fcaaccd6688)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:


## OUTPUT:

![image](https://github.com/mrnaviz/creating-a-backdoor-with-SET/assets/123350791/1a1734a5-e600-460c-8320-7c04c6a5b8fa)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT:

![image](https://github.com/mrnaviz/creating-a-backdoor-with-SET/assets/123350791/50dbc6aa-48b0-4767-a317-9c765e354c74)

It shows the following screen in which the option Google can be selected:


## OUTPUT:

![image](https://github.com/mrnaviz/creating-a-backdoor-with-SET/assets/123350791/35001982-09d0-4252-908a-2ec6447e1ddb)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT:

![image](https://github.com/mrnaviz/creating-a-backdoor-with-SET/assets/123350791/bda658f6-8094-4575-ac8d-8749e26d4999)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password


## OUTPUT:

![image](https://github.com/mrnaviz/creating-a-backdoor-with-SET/assets/123350791/6a780975-bf10-446d-9c59-266e98be82a6)

SET logs the information regarding the Google credentials:

## OUTPUT:

![image](https://github.com/mrnaviz/creating-a-backdoor-with-SET/assets/123350791/7a339eef-206b-4358-85e6-49d6c0ef287b)

SET logs the information in the xml file under /root/.set directory:

## OUTPUT:

![image](https://github.com/mrnaviz/creating-a-backdoor-with-SET/assets/123350791/edfc43a2-62f4-4c29-99c7-d376754f4b0c)




## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
