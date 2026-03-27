+++
date = '2026-03-27T18:12:33+01:00'
draft = false
title = 'Priv Esc Lab'
+++

FUZZING

DIFFERENT TYPES OF FUZZING:

Directory fuzzing
File fuzzing
Extension fuzzing
Parameter (GET) fuzzing
Parameter (POST) fuzzing
Value fuzzing
Subdomain fuzzing
Virtual host (vhost) fuzzing
Header fuzzing
Cookie fuzzing
JSON fuzzing
XML fuzzing
GraphQL fuzzing
API endpoint fuzzing
Authentication fuzzing
ID fuzzing (IDOR testing)
Path traversal fuzzing
File upload fuzzing
Method fuzzing (HTTP verbs)
Rate-limit fuzzing



🧠 What is “Fuzzing”?

Fuzzing = sending many unexpected or different inputs to a target to discover hidden functionality or vulnerabilities.

👉 In simple terms:

You are guessing inputs at scale to see how the system reacts.

💡 Everyday Analogy

Imagine a locked building and you try:

front door 🚪
back door 🚪
windows 🪟
basement entrance
roof access

👉 That process = fuzzing

⚙️ What is ffuf?

ffuf = Fuzz Faster U Fool

👉 It’s a tool used to:

Discover hidden files
Find endpoints
Test parameters
Identify vulnerabilities
🔥 What “FUZZ” Means in ffuf

Example:

ffuf -u https://api.sophy.com/FUZZ -w wordlist.txt
