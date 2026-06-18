<p align="center">
  <img src="Frontend/logo.png" width="120">
</p>

# Whisper-WA

Whisper-WA is a digital forensics platform designed for extracting, decrypting, and analyzing WhatsApp data from Android devices.

The system helps investigators perform WhatsApp forensic investigations through a simplified workflow and an investigator-focused interface.

---

## Purpose

The purpose of Whisper-WA is to simplify WhatsApp forensic investigations and help investigators analyze digital evidence in a more organized and efficient way.

---

## Features

* WhatsApp data extraction using ADB
* WhatsApp database decryption
* Chat and artifact analysis
* Suspicious links and keyword detection
* PDF and CSV forensic reports
* Arabic and English language support

---

## Tools & Technologies

* Python
* Flask
* SQLite
* HTML, CSS, JavaScript
* ADB
* wadecrypt

---

## Workflow

1. Connect Android device
2. Extract WhatsApp database and encryption key
3. Decrypt the database
4. Analyze chats and digital artifacts
5. Generate forensic reports

---

## Whisper-WA Workflow Demonstration

[Watch Workflow Demo](https://drive.google.com/file/d/1MdLJ_7HvEpfltd8PUHPxMmr648Ud81Wi/view?usp=sharing)

---

## Project Poster

[View Poster PDF](Whisper-WA_Poster.pdf)

---

## Demo Video

[Watch Demo](https://drive.google.com/file/d/14Q1XjRKwIANJPaPd_XlTTlvyng1xaxCz/view?usp=sharing)

---

## System Interfaces

[View Interfaces PDF](interface1.pdf)

---

## Source Code

The project source code is publicly available on GitHub:

```text
https://github.com/emtnansaadmhm-lang/whisper-wa2
```

The full project folder can be downloaded directly from the repository using the **Code** button and tested locally inside a secure forensic environment.

---

## Requirements

* Android device
* **Rooted Android device**
* Python 3.8+
* USB Debugging enabled
* ADB installed or included with the project
* wadecrypt tool

---

## Important Notes

> Whisper-WA requires a rooted Android device in order to access protected WhatsApp directories and encryption keys.

> The forensic acquisition and decryption functions will not work on non-rooted devices.

> USB Debugging must be enabled before connecting the device.

> Some `wadecrypt` versions may differ depending on the source or testing environment configuration.
