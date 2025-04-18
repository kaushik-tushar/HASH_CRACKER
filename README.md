
Hash Cracker App

A lightweight web application built with HTML, CSS, Python, and Flask that helps users identify plaintext values from their hashed counterparts using various hashing algorithms.

Features:

Supports multiple hashing algorithms:

MD5, SHA-1, SHA-224, SHA-256, SHA-384, SHA-512

SHA3 variants: SHA3-224, SHA3-256, SHA3-384, SHA3-512

BLAKE2b, BLAKE2s, RIPEMD-160

SHAKE-128, SHAKE-256

SM3, MD5-SHA1, SHA-512/224, SHA-512/256

Simple and intuitive web interface

Fast hash comparison using a wordlist

Deployed on Vercel for public access

Tech Stack:

Frontend: HTML, CSS

Backend: Python (Flask)

Deployment: Vercel

Project Structure:

hash-cracker/ │ ├── static/ → CSS and static assets
├── templates/ → HTML templates
├── wordlist.txt → Wordlist used for cracking hashes
├── app.py → Flask app logic
└── README.txt → Project documentation

How It Works:

User selects a hashing algorithm.

User inputs the hash to be cracked.

The app compares the hash against a wordlist.

If a match is found, the corresponding string is returned.

Example:

Input Hash: 5d41402abc4b2a76b9719d911017c592

Algorithm: MD5

Output: hello

Requirements:

Python 3.x

Flask

Installation:

Clone the repository: git clone 
Navigate to the directory: cd hash-cracker
Install the dependencies: pip install -r requirements.txt
Run the application: python app.py
Open your browser and visit: http://localhost:5000

Live Demo:

Access the app here: [https://your-vercel-app.vercel.app](https://hash-cracker-git-main-tusharkaushik.vercel.app/)

Disclaimer:

This tool is intended for educational and ethical purposes only. Do not use it for unauthorized or illegal activities.

Author:

Tushar Kaushik
Cybersecurity & Forensics Enthusiast | Ethical Hacker | Developer
