# 💬 ChatApp – Python Tkinter Chat Application

A simple chat interface built in Python using Tkinter.  
It includes a login and registration system with password validation and secure local storage via JSON.  

---

## 🌟 Features

✅ Create an account with username & password  
✅ Password validation (uppercase, lowercase, digits, special chars)  
✅ Save and load accounts in a local JSON file  
✅ Login and access a personal chat window  
✅ Send and display messages in a chat interface  
✅ User-friendly GUI built entirely with **Tkinter**  

---

## 🧠 Project Overview

ChatApp is a local GUI application that allows users to create accounts and chat within the app.  
Account data is stored locally in a JSON file (`accounts.json`), and password security rules ensure strong credentials.

The interface includes:
- A login window  
- A registration system  
- A chat window with message input and display  

---

## ⚙️ Requirements

- Python 3.x
- Tkinter (included in most Python installations)
- JSON module (included by default)

Check Tkinter installation:
```bash
python -m tkinter

---

## Run the App

- python chatapp.py

## 💡 How It Works

- Create Account
- Enter a username and password
- Password must contain:
  - At least 8 characters
  - Uppercase, lowercase, digits, and special symbols
- The account is saved in accounts.json
- Login
  - Enter your credentials
  - If valid, the chat window opens
- Chat Window
  - Type your message and click “Send”
  - Messages are displayed in the text area above


