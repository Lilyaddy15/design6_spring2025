# Lab 10

## Blockchain

### Hash Function With Randomization

I ran the functions below to move into the correct folder, view the script, and run the program twice. 
```
cd ~/iot/lesson10
cat hash_value.py     
python3 hash_value.py
python3 hash_value.py
```

Below are my results from running the program twice, and the randomness with different values is shown. 
<img width="460" alt="Screenshot 2025-04-28 at 1 36 00 PM" src="https://github.com/user-attachments/assets/b996f882-10cc-474d-871c-0ce50bcc76ee" /> <br>

### SHA-2 Secure Hash Algorithm

I entered the Python interpreter, and typed commands one by one. Below shows the commands used, and the results from the functions. <br>
<img width="572" alt="Screenshot 2025-04-28 at 1 40 29 PM" src="https://github.com/user-attachments/assets/171a4d8a-8d87-482a-861b-7fd7a5a84da6" /><br>

### Snakecoin

The first thing I did was move into the Lesson 10 folder, and I viewed the snakecoin.py script. I then ran it, as shown below. <br>
<img width="543" alt="Screenshot 2025-04-28 at 1 46 32 PM" src="https://github.com/user-attachments/assets/e9082833-f552-4467-8bfc-fff0ce268f9a" /> <br>

Then, I viewed the full server script, and ran the program. I opened the server up on my browser, as shown below. <br>
<img width="1210" alt="Screenshot 2025-04-28 at 1 50 36 PM" src="https://github.com/user-attachments/assets/241587a1-be58-47aa-8e7a-238f077f9246" /> <br>

I then opened another terminal and ran the code below:
```
$ curl "localhost:5000/txion" \
     -H "Content-Type: application/json" \
     -d '{"from": "akjflw", "to":"fjlakdj", "amount": 3}'
$ curl localhost:5000/mine
```

Here is the result: <br>
<img width="1397" alt="Screenshot 2025-04-28 at 1 53 47 PM" src="https://github.com/user-attachments/assets/19f8f6f1-4ad6-4d2e-af58-8de700bb5a37" /> <br>


### Python Blockchain App

To copy the repository and move to the correct folder, I ran the commands shown below. <br>
<img width="570" alt="Screenshot 2025-04-28 at 1 57 52 PM" src="https://github.com/user-attachments/assets/f665be89-9c2c-4782-853c-a514fe11ada3" /> <br>

I then opened node_server.py and edited it. <br>
<img width="568" alt="Screenshot 2025-04-28 at 2 01 00 PM" src="https://github.com/user-attachments/assets/d35f8f55-4d1a-431b-afbe-47a881def5c1" /> <br>

I ran the program. I also opened a second terminal and ran the app. <br>
<img width="567" alt="Screenshot 2025-04-28 at 2 01 46 PM" src="https://github.com/user-attachments/assets/5706b65a-c2de-4f9a-922c-6425e6dc4ea5" /> <br>
<img width="569" alt="Screenshot 2025-04-28 at 2 04 56 PM" src="https://github.com/user-attachments/assets/b2d8a400-543e-4a6f-a30e-eef2750668fb" /> <br>

Then, by going to the app server I could see the app running. <br>
<img width="1221" alt="Screenshot 2025-04-28 at 2 05 55 PM" src="https://github.com/user-attachments/assets/206ba778-d97d-45d7-8636-9adea4aa1a2a" /> <br>

I then posted and and resynced to see that Block #1 was added on the blockchain. <br>
<img width="1725" alt="Screenshot 2025-04-28 at 2 07 40 PM" src="https://github.com/user-attachments/assets/30d22134-21bc-465f-8f91-5073c59b9932" />

