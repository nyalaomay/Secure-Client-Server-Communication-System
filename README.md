# Secure-Client-Server-Communication-System
This project implements a secure client-server communication system in Java, 
built as an honors-level cybersecurity project for COMP 320. The system 
encrypts both a text message and an image file using AES-128 symmetric 
encryption, transmits the encrypted data between two physical devices over 
a real WiFi network using TCP sockets, and decrypts it on the receiving 
device — reproducing the original content exactly.

Built to demonstrate real-world application of cryptographic principles 
including symmetric encryption, binary data handling, and secure network 
transmission. Tested live across two physical laptops connected over a 
phone hotspot.

Technologies: Java, AES/ECB/PKCS5Padding, Java Cryptography Architecture 
(JCA), TCP Sockets, Java Networking API
