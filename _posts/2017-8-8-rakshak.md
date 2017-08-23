---
layout: post
title: Rakshak for Smart India Hackathon
description: Secure Email Client
image: assets/images/rakshak1.jpg
permalink: work/rakshak
---

A PGP end-to-end **encrypted generic email client** developed for Smart India Hackathon.
It uses standard mail protocols - *IMAP and SMTP, Java Mail, Cryptography and Security API*. The app provides security from email service providers 
who reads users private emails for analytical and ad purposes. It provides a generic interface, which allows the user to use their existing email 
service provider, or use our mail service to get an encrypted email channel. Our mail service used *Mail-in-a-Box* software bundle.

<center> <span  style="font-size:20pt; text-decoration:underline" align="middle"> Rakshak app screens </span> </center>
<center> <span  style="font-size:15pt;" align="middle"> The app was built in a 36 hour hackathon, and thus doesn't have good UI.</span> </center>
<center> <span align="middle" class="image"><img src="/assets/images/rakshak2.png" alt="" /></span> </center>

The app uses Java Security and Cryptography APIs to encrypt the email using **AES** (Advanced Encryption Standard) and **RSA** ( Asymmetric Key 
Algorithm) algorithm. It also uses *Java Mail API* to send and receive emails. It implements a *'just-in-time'* approach to decrypt emails, meaning 
that the emails were decrypted when they were opened but are never stored as decrypted data on the device. The decryption key was stored in 
Android's hardware-backed keystore.


