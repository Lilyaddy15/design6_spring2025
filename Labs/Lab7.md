# Lab 7

## ThingSpeak and Google Sheets

### ThingSpeak
I logged into ThingSpeak with my already existing MathWorks account. Then I created the channel with the two fields. 
<img width="644" alt="Screenshot 2025-04-16 at 6 42 20 PM" src="https://github.com/user-attachments/assets/e4de726a-78ab-4f6c-ad89-c82dd6611fd9" />

<img width="565" alt="Screenshot 2025-04-16 at 6 45 40 PM" src="https://github.com/user-attachments/assets/06eda80e-1705-4565-903d-42501f33b9d7" />

<img width="536" alt="Screenshot 2025-04-16 at 6 46 22 PM" src="https://github.com/user-attachments/assets/e7435c90-0c23-4d4e-bc7f-2c9d0d220e54" />

<img width="554" alt="Screenshot 2025-04-16 at 6 47 09 PM" src="https://github.com/user-attachments/assets/a8137d98-c1bc-4c57-84c1-4015958cb70a" />

<img width="539" alt="Screenshot 2025-04-16 at 6 48 00 PM" src="https://github.com/user-attachments/assets/d3bc7490-27ab-4dfa-a956-9c5b56d9acf9" />

After letting the program run for a while, below shows what the output looked like in the terminal and on the ThingSpeak website. 

<img width="227" alt="Screenshot 2025-04-16 at 6 54 03 PM" src="https://github.com/user-attachments/assets/dab6c272-6cb8-456b-a7a2-5d3081af4bdc" />

<img width="1033" alt="Screenshot 2025-04-16 at 6 54 12 PM" src="https://github.com/user-attachments/assets/8b2caaf8-765e-49be-ba6d-0c812a7affd1" />

---

### Google Sheets

Using ` sudo pip3 install -U gspread oauth2client `, I installed gspread and oauth3client on my computer. Then I followed the steps on Google Cloud Platform Identity and Access Management.

<img width="536" alt="Screenshot 2025-04-16 at 7 45 39 PM" src="https://github.com/user-attachments/assets/306845b3-dfd4-4215-96aa-7d72f686b7c3" />

These are the following commands I ran in my terminal to get everything set up:
```
$ cd demo
$ cp ~/iot/lesson3/system_info.py .
$ cp ~/iot/lesson7/cpu_spreadsheet.py .
$ mv ~/Downloads/cpudata-*.json ~/demo 
```

<img width="570" alt="Screenshot 2025-04-16 at 7 51 02 PM" src="https://github.com/user-attachments/assets/2dd8eb1b-b30e-44b3-8254-5c05a75bfa9d" />

<img width="478" alt="Screenshot 2025-04-16 at 7 52 11 PM" src="https://github.com/user-attachments/assets/4cfb4274-fb71-497d-96b8-7a078010106e" />

<img width="441" alt="Screenshot 2025-04-16 at 7 52 24 PM" src="https://github.com/user-attachments/assets/87d606fa-435a-4f7c-847b-e50ccb97edf0" />





