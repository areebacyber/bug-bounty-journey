📄 Day 1 — HTTP Fundamentals & Burp Suite Interception
🎯 Objective

Understand how web traffic works (HTTP requests/responses) and perform my first request interception using Burp Suite.

🌐 What I Learned
🔹 HTTP Basics
HTTP is the protocol used for communication between browser (client) and server
Every web interaction is made of:
Request (sent by client)
Response (sent by server)
🔹 HTTP Methods
GET → Used to retrieve data from a server
POST → Used to send data to a server (like login forms)
🔹 Request Structure

A typical HTTP request includes:

Method (GET/POST)
URL / Path
Headers (User-Agent, Host, etc.)
Body (only in POST requests)
🧰 Tools Used
Burp Suite Community Edition
Google Chrome (Browser)
🛠️ Practical Work (First Interception)
Step I did:
Opened Burp Suite
Enabled Intercept
Configured browser proxy to Burp (127.0.0.1:8080)
Visited a website
Captured first HTTP request in Burp
📌 Key Observations
Every browser action sends a request in the background
Requests can be intercepted and modified before reaching the server
Headers like User-Agent and Host are always present
🧠 What This Means for Bug Bounty

Understanding HTTP traffic is the foundation of:

Request manipulation
Parameter testing
Authentication bypass attempts
Vulnerability discovery using tools like Burp Suite

Practical Evidence

Here is the intercepted request:

![Burp Suite Intercept](Screenshot%20(52).png)
🚀 Next Step
Practice intercepting login requests
Learn how to modify parameters in Burp Repeater
Explore more HTTP methods and headers
