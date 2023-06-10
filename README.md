# II Edition Cybersecurity Bootcamp (42 Barcelona)

This repository contains the documentation and projects completed during my participation in the Cybersecurity Bootcamp at 42 Barcelona Campus, which took place from April 11th to June 2nd, 2023.

## **Overview**

Throughout the bootcamp, I had the opportunity to delve into various cybersecurity topics and engage in practical exercises and projects. Some of the key areas covered include:

· Ethical Hacking and Offensive Security.

· Penetration Testing.

· Reverse Engineering.

· Linux Hardening.

· Incident Response and Forensics.

· OSINT (Open Source Intelligence).

· Data Extraction and Recovery.

The curriculum provided a hands-on approach to tackle the evolving landscape of digital threats and protect critical systems and data.

## **Projects**

Throughout the bootcamp, I completed several projects, each demonstrating different aspects of cybersecurity. Here are some notable ones:

**arachnida:** This project consists of two tools, spider and scorpion, designed to perform specific tasks related to web scraping and image metadata analysis. 
The spider tool is capable of recursively extracting all images from a given website, it offers various flags for customization.
The scorpion tool takes image files as parameters and analyzes them for EXIF and other metadata, displaying the results on the screen. It supports the same file extensions managed by the spider tool. The scorpion tool showcases basic attributes such as creation date and additional EXIF data. The format in which the metadata is presented is left to the user's choice.

**ft_otp:** This project provides a secure One-Time Password (OTP) generator implemented in C. It enables users to register an initial key and generates a new password each time it is requested. The program ensures the safe storage of the key in an encrypted file and utilizes system time for password generation. It also includes features such as generating a new password and the flexibility to specify an encryption password for enhanced security.

**ft_onion:** This project focuses on the creation of a webpage that is accessible through the Tor network as a hidden service. The hidden service provides a secure and private web service that remains concealed within the Tor network. The main objective is to set up a static webpage using Nginx as the web server, which can be accessed via a .onion URL. Additionally, the project includes the implementation of additional security features, such as SSH fortification.

**coRSAir:** This project explores the strength and vulnerabilities of the RSA algorithm. While RSA is considered robust against current computational power, certain usage patterns can lead to severe security issues. Implemented in C language, the program utilizes specific functions and libraries to perform cryptographic operations and decrypt a message. It reads the public key from certificates, calculates necessary data, constructs the private key from primes, and decrypts the message using the symmetric key.

**ft_blockchain:** This project focuses on building a Proof of Work-based blockchain and an interactive server. The blockchain logic and server are implemented in Python. Transactions are added to blocks, which are then mined and added to the chain. The Proof of Work algorithm involves finding a number that, when concatenated with the previous Proof of Work, results in a SHA-256 hash ending in 4242. Interaction with the blockchain is through HTTP requests, dynamically adjusting the Proof of Work difficulty based on mined blocks or elapsed time. Additional features includes decentralized communication and Proof of Stake consensus.

**tsunami:** This project developed in C demonstrates a simple buffer overflow vulnerability in a 32-bit Windows XP environment. By utilizing the strcpy function, the program intentionally triggers the buffer overflow. The project involves creating a vulnerable executable and constructing a payload to exploit the vulnerability. It also implies setting up a virtual machine using tools such as Vagrant, to run the exploit in a vulnerable enviroment.

**stockholm:** This project is a small program developed for Linux platform (Ubuntu), designed to demonstrate the potential damage caused by ransomware. The program operates within a virtual machine or docker container and selectively targets files with specific extensions (extensions targeted by wannacry's ransonmware) within the user's "infection" folder in the HOME directory. It encrypts the files using a secure algorithm, adds the ".ft" extension to the filenames, and ensures the encryption key used is at least 16 characters long.

**iron_dome:** This project is a program that proactively detects anomalous activity in the user's system, with a specific focus on identifying vulnerabilities and weak points susceptible to ransomware infections. Operating as a background daemon, it continuously monitors critical paths, files, and disk read activity. It also identifies intensive cryptographic activity and changes in file entropy. With minimal memory usage, it provides detailed alerts logged in a designated file. Additionally, facilitates incremental backups at customizable intervals.

**recovery:** This project is a Windows 10 data gathering and forensic analysis tool, implemented in Python, that empowers users to extract and analyze crucial information for forensic investigations (capture registry changes, recent files, installed programs, connected devices, and log events). The program enables users to define custom time ranges or utilize default ranges. Additionally, it includes a graphical timeline feature that presents categorized evidence in chronological order and provides a visual representation of the user's directory tree.

**extraction:** This project focuses on developing a program to recover deleted files from the NTFS file system, specifically targeting the Master File Table (MFT) structure. By understanding the MFT and leveraging the fact that deleted files are often recoverable, the program aims to scan and retrieve recently deleted files. The program performs full disk scanning, display a list of found files, indicate recoverability (full or partial), and allow for the selection and recovery of available files. Additionally, includes the ability to specify a starting directory for recovery instead of scanning the entire system.

**inquisitor:** This project focus on targeting ARP spoofing, a technique used for intercepting and manipulating network traffic. With the ability to impersonate network gateways, it grants control over traffic, potentially enabling eavesdropping and data modification. The program runs within a container or virtual machine, utilizes raw sockets and requires low-level permissions. The project includes a signature file for verification and takes four parameters to initiate bidirectional ARP poisoning. It also features the capability to intercept and display real-time filenames exchanged during FTP server login.

**vaccine:** This project is designed to detect and perform SQL injection by providing a URL as a parameter. It includes a set of tests to launch against the specified URL, aiming to identify SQL injections based on different techniques such as union, error, boolean, time, and blind-based methods. The program can determine the vulnerable parameters, the payload used, database names, table names, column names, and even extract a complete database dump if the website is confirmed as vulnerable. The program allows for optional storage of the data in a specified file or a default file if not specified. It supports different request types, with GET being the default. 

## **Technologies and Tools**

Throughout the bootcamp, I utilized a variety of technologies and tools, including:

· Operating Systems: Linux (Ubuntu & Alpine), MacOS, Windows (XP & 10).

· Networking Tools: Wireshark & Nmap.

· Programming Languages: Python & C.

· Virtualization: VirtualBox & Vagrant.

· Containerization: Docker.

## **Methodology**

Each project was developed in a separate branch and folder, which were later merged with the main branch upon completing the bootcamp.

## **Acknowledgments**

I would like to express my gratitude to the mentors and colleagues at 42 Barcelona Campus, as well as the cybersecurity league and staff at 42 Madrid Campus, for providing an exceptional learning environment and valuable guidance throughout the bootcamp.

## **Contact Information**

For any inquiries related to the projects feel free to reach me at bavbagithub@gmail.com.

**Note:** _The materials in this repository are for educational purposes only and should not be used maliciously or in any unauthorized manner._
