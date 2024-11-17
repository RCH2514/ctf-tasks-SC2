# ctf-tasks-by-me-SC2
This repo contains CTF tasks I created for the Sup'Com Cybersecurity Club, along with my writeups and solutions. Explore the challenges, test your skills, and review detailed explanations for each task to learn and improve your cybersecurity knowledge.

Task 1: Comments

Task Overview

![image](https://github.com/user-attachments/assets/a058289b-3707-4b00-b45f-8a757eee8824)

At first glance, this seemed like a straightforward social engineering challenge but with a twist. The key was to analyze the comments on the person’s social media posts.
Approach
To solve the challenge, I first used Google Lens on the provided photo, which led me to the person’s Twitter account. After browsing through their tweets, I found one where they asked if anyone wanted to get drunk with them. I then checked the comments on that tweet and discovered a conversation where the person mentioned they both liked the band Cinderella.
![image](https://github.com/user-attachments/assets/6d4ce9b9-56c8-45c9-a142-4d02967817bd)
![image](https://github.com/user-attachments/assets/bf9986cf-442a-40dd-be2c-48e511f3c1d2)


The flag is: SC2{Cinderella}

Task 2: Hammami's Car
Task Overview

![image](https://github.com/user-attachments/assets/0c4c4975-098b-4727-9601-fa660ec18bdc)

Approach
I started by examining the photo, where the car's serial number was visible. I did a quick search using the serial number and found several websites that could provide information about the car. After testing a few, I found that vidange.tn was the only site that provided all the required details, including the car's brand, first registration date, and fiscal power.

![image](https://github.com/user-attachments/assets/37892bed-5447-4a6e-aa7e-56822a3ecb4d)

![image](https://github.com/user-attachments/assets/e8ee1af8-05f6-48df-84c7-2d5b283306aa)

the flag is : SC2{ISUZU_02_04_1999_10}
Task 3: Legendary Domain "supcom.tn"

Task Overview

![image](https://github.com/user-attachments/assets/9d430946-ede0-4cb3-9634-4b1fcd64ac77)

Approach

To solve this task, I performed a domain lookup to retrieve the registration details for the domain "supcom.tn." There are several websites available for performing domain lookups, so I tested a few of them. After some trials, I found that whois.domaintools.com and whois.net both returned the needed information.

![image](https://github.com/user-attachments/assets/e3539e1d-44c1-4dc4-aa01-6857e3156444)

the flag is : SC2{14_12_2022_16_31_30}

Task 4: Insider_Threat_0

Task Overview

![image](https://github.com/user-attachments/assets/30be38cc-262f-42c6-a95e-7a23527d9c6e)

Approach

This task focuses on Insider Threats, which refer to situations where someone with authorized access to an organization’s systems or information misuses that access to cause harm. To solve the task, I recognized that the term Insider_Threat directly corresponds to the nature of the issue being described. Given the flag format SC2{The_Answer}, the correct flag is simply Insider_Threat.

the flag is : SC2{Insider_Threat}

Task 5: Insider_Threat_1

Task Overview

![image](https://github.com/user-attachments/assets/1b43abbe-01ca-425b-af13-df74acbc8af5)

Approach

By analyzing the image, I recognized the Chase Center, which is located in San Francisco, California. I used Google Lens to search for the building and found that the building next to it belongs to Uber, the well-known ride-sharing company. A quick search revealed that Uber was founded in 2009. The flag format requires all these details, so I formatted them as SC2{Uber_San_Francisco_California_2009}.


![image](https://github.com/user-attachments/assets/10b9cf11-a917-4c4c-ac0d-26330753b1bf)

![image](https://github.com/user-attachments/assets/6bb15656-b542-4951-b03c-a32374822d3e)




the flag is : SC2{Uber_San_Francisco_California_2009}

Task 6: Insider_Threat_2

Task Overview


![image](https://github.com/user-attachments/assets/bd3440b2-2f84-478b-9f73-80d687f869c2)

Approach 

I downloaded the zip file containing multiple files and folders, which was too large to check manually. To efficiently search for the flag, I used the grep command, a powerful tool to search for specific text within files. Since I knew the flag started with SC2, I ran a simple command to search for this pattern across all the files and here is the flag : 

![image](https://github.com/user-attachments/assets/ad47d039-8a03-4459-bc11-0baf4fff86d7)

Task 7: Insider_Threat_3


Task Overview

![image](https://github.com/user-attachments/assets/61cc02cd-2b7e-47ef-a213-43b376bb700f)

Approach 

Inside the zip file, I found two images and three sound files. After analyzing the sound files, I noticed that two of them seemed to contain changing frequencies, which appeared to be common hearing test tones that could be easily identified through a quick search on social media. However, it was the third sound file that caught my attention, as it seemed unusual.

To extract potential hidden information from this file, I decided to analyze it using a spectrogram, a visual representation of the frequencies within an audio signal. I used Sonic Visualiser, a tool commonly used for spectrogram analysis, to open the third sound file.

Upon analyzing the spectrogram, I found a series of patterns that looked like a hidden message, which was the flag for this task.

![image](https://github.com/user-attachments/assets/e82de5c2-1366-4106-802e-2c2975b90b44)

Task 8: Insider_Threat_4


Task Overview

![image](https://github.com/user-attachments/assets/dad2723d-1e5a-45ab-8343-7ffbee9e1287)

Approach
This task required some in-depth research to find the relevant article that mentions the cybersecurity firm hired by Uber. After reading through multiple articles and sources, I found a key mention in an article from Relativity, titled "Report Disclosed in Fight Between Uber and Waymo Now Public," which can be found here: https://www.relativity.com/blog/report-disclosed-in-fight-between-uber-waymo-now-public/. According to this article, the firm Uber hired was Stroz Friedberg, a well-known cybersecurity and forensics firm.

![image](https://github.com/user-attachments/assets/e1af1d09-4cfb-49e4-8b27-75ee62de137c)

Next, I searched for the foundation year and founders of Stroz Friedberg. A quick lookup on LinkedIn confirmed that the firm was founded in 2000
![image](https://github.com/user-attachments/assets/8259c966-896d-427d-a4ab-985c1da6291c)

and searching for the founders : 

![image](https://github.com/user-attachments/assets/47fc4256-a66e-4339-9d95-27a665687dc1)

the flag is : Flag: SC2{Stroz_Friedberg_2000_Edward_Stroz_Eric_Friedberg}

Task 9: Insider_Threat_5


Task Overview



Approach










