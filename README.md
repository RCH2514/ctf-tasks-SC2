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


