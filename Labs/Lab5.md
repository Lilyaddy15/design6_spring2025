# Lab 5

## Paho-MQTT

### Install Paho-MQTT
Below are the steps taken to install Paho-MQTT 

`brew install mosquitto`

`brew services start mosquitto`

`pip3 install paho-mqtt`

### Setting Up Terminals

Below are the two terminals I set up, and the commands used to navigate to the correct folder. 

<img width="920" alt="Screenshot 2025-04-15 at 7 54 23 PM" src="https://github.com/user-attachments/assets/0a08270a-9581-4bb0-acd3-e94fa1bea636" />

### Running the Scripts

In one terminal I ran the script ` subcpu.py ` , and in the other I ran ` pubcpu.py `.

<img width="1139" alt="Screenshot 2025-04-15 at 7 56 46 PM" src="https://github.com/user-attachments/assets/951221ec-e8be-43c7-8240-0964b1c30dc1" />

After watching these scripts run, I could tell that ` pubcpu.py ` publishes the CPU usage data, and ` subcpu.py ` is subscribing to it and prints the data it recieves. 
