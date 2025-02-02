# Homework-1
## Overview
The purpose of the "A Simple Browser" Project is to gain more knowledge of using Socket.io and familiarize ourselves with node.js and client.py. It also allows us to understand how the webpage, client.py and server all interact with each other.
## Installation
### Installing Node.JS
- Visit https://nodejs.org/en
- Click Download Node.js (LTS)
- Open Downloads in Finder
- Click node-v22.13.1.pkg file
- When it says, This package will install: Node.js v22.13.1 to /usr/local/bin/node npm v10.9.2 to /usr/local/bin/npm, press continue
- Agree to the Software License by pressing continue and then Agree
- Then Press install and wait for Node.js to install onto your laptop
### Downloading the Repository
- Go to https://github.com/IE-482-582/spring2025
- Click the Green Code Button and Download the ZIP File
- Open the ZIP File in Downloads folder
## How to Run the System
### Create Terminal 1- Server
- Open a new terminal
- Type and press enter:
```
cd Downloads/spring2025-main/Projects/simple_browser_socket
```
- Then, type and press enter:
```
node server_secure.cjs
```
### Create Terminal 2- Client
- Open a new terminal
- Make sure the following is open
```
cd Downloads/spring2025-main/Projects/simple_browser_socket
```
- Then, type and press enter:
```
python3 client.py
```
- Then, type and press enter to import socketio:
```
import socketio
```
- Socketio may need to be installed onto your machine so use the following code to obtain it:
```
pip install python-socketio
```
- Once you import socketio, a sid code will be provided
- If you are allowing access to your phone type the following:
```
node server_secure.cjs --public
```
### Create Terminal 3- Phone
- Open a new terminal
- Type and press enter to obtain the IP address
```
ifconfig
```
- The IP address can be found under lo0: inet: XXX.X.X.X

### Visiting the Browser
- If you are going to the browser from your laptop go to https://localhost:8080/
- If you are going to the browser from your phone go to https://localhost:XXX.X.X.X/

## Explanation of Code and System

### Server

Defines the Program:
```
server_ secure.cjs
```
Server code:
```
package-lock.json
```
```
package.json
```
```
node.js
```
- SSL(Secure Sockets Layer): important for https
```
ca.crt
```
```
ca.der.crt
```
```
ca.key
```
### Webpage
https://localhost:8080/
Use the following code to design the front end of what user sees on the webpage:
```
index.html
```
Use CSS language to design the HTML

### Connecting Server to Webpage/Holds the Data
- Socketio:
```
import socketio
```
```
pip install python-socketio
```
-Client:
```
python3 client.py
```
