# 🔐 File Encryptor/Decryptor GUI using Python & Tkinter

A simple yet powerful desktop application to **encrypt** and **decrypt** files using 🔒 **Fernet symmetric encryption** from the `cryptography` library.  
Built with ❤️ using Python and Tkinter!

---

## ✨ Features

- 📁 Encrypt any file using a **new or existing key**
- 🔑 Option to **generate a secure Fernet key**
- 📋 **Automatically copies** generated key to clipboard for easy saving
- 🔓 Decrypt encrypted files with the correct key
- 💾 Save encrypted and decrypted files at your desired location
- 🪟 Simple and user-friendly GUI

---

## 🚀 Getting Started

### 🔧 Requirements

- Python 3.6+
- `cryptography` library

Install the required package using pip:

```bash
pip3 install cryptography
````

---

### ▶️ How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/FileEncryptorApp.git
cd FileEncryptorApp
```

2. Run the script:

```bash
python app.py
```

---

## 🖼️ App Preview

- <img width="428" height="266" alt="image" src="https://github.com/user-attachments/assets/9e87a470-1c3b-4de0-95a7-735c6acac284" />
- <img width="444" height="326" alt="image" src="https://github.com/user-attachments/assets/ef2433d3-3370-4699-83e1-2f16d682d018" />
- <img width="367" height="176" alt="image" src="https://github.com/user-attachments/assets/18ad4643-db43-486c-ba0c-d1c14c16bb59" />
- <img width="380" height="199" alt="image" src="https://github.com/user-attachments/assets/4b95e675-a7ab-43ee-a736-f62bed385363" />
- <img width="286" height="162" alt="image" src="https://github.com/user-attachments/assets/86961e86-4741-4488-814e-b7150190e28f" />
- <img width="444" height="326" alt="image" src="https://github.com/user-attachments/assets/91606d31-cd03-40c5-a6e9-91ce1017130c" />
- <img width="444" height="326" alt="image" src="https://github.com/user-attachments/assets/d8762e78-468b-4761-ae63-b817e12634f8" />
- <img width="274" height="177" alt="image" src="https://github.com/user-attachments/assets/8dae9210-8e9a-4f8b-9816-117ee30014a1" />


---

## 🛡️ How It Works

### 🔐 Encryption Flow:

* Select a file 📂
* Choose to **generate a key** or **enter an existing one**
* File is encrypted and saved with `.encrypted` extension
* Key is copied to clipboard (if generated)

### 🔓 Decryption Flow:

* Select an encrypted `.encrypted` file
* Paste the correct Fernet key
* File is decrypted and saved 🎉

---

## 📂 File Structure

```
FileEncryptorApp/
│
├── app.py            # Main Python script for the app
├── README.md         # This README file
```

---

## 🧠 Tech Stack

* [x] Python 🐍
* [x] Tkinter 🪟
* [x] cryptography 🔒

---

## ❗ Important Notes

* 🔑 Always keep your **encryption key safe**. Without the correct key, decryption is impossible.
* 🧪 This app is for **educational & basic personal use** — not suited for highly sensitive or enterprise-level encryption tasks.

---

## 📜 License

MIT License. Feel free to use and modify!

---

## 🙌 Acknowledgments

Thanks to the open-source community for the amazing tools ❤️

---

## ✍️ Author

Made with ❤️ by [jakegithub24](https://github.com/jakegithub24)

---
