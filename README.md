# 💳 UPI QR Code Generator

# 📖 About

The **UPI QR Code Generator** is a Python-based application that allows users to instantly generate QR codes for UPI payments.

Simply enter a valid **UPI ID**, and the application creates QR codes that can be scanned using popular UPI payment apps like:

- 📱 Google Pay
- 📱 PhonePe
- 📱 Paytm

This project is beginner-friendly and demonstrates how QR codes can be generated using Python with minimal code.

## ✨ Features

- 💳 Generate QR Code using any UPI ID
- ⚡ Instant QR Code Generation
- 📱 Compatible with Google Pay
- 📱 Compatible with PhonePe
- 📱 Compatible with Paytm
- 🖥️ Simple Command Line Interface
- 🐍 Built entirely using Python
- 🎯 Easy to understand source code


# 🚀 How It Works

```text
User enters UPI ID
        │
        ▼
Python creates UPI Payment URL
        │
        ▼
QR Code is generated
        │
        ▼
QR Code opens automatically
        │
        ▼
Scan using any UPI App
```

---

# 🛠️ Built With

- Python 3
- qrcode Library
- Pillow Library

---

## 📂 Project Structure

```text
UPI_QR_Code_Generator/
│
├── .venv/
├── images/
├── QR_Code.py
├── requirements.txt
├── README.md
└── LICENSE
```

## ⚙️ Installation

### Clone

```bash
git clone https://github.com/Coder-Dipan/UPI_QR_Code_Generator.git
cd UPI_QR_Code_Generator
```

### Create Virtual Environment

**Windows**

```bash
python -m venv .venv
.venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install qrcode pillow
```

### Import Library

```python
import qrcode
```

### Run

```bash
python QR_Code.py
```

## 💻 Example

```text
Enter your UPI ID:

dipan@oksbi
```

The QR code opens automatically.

## 📦 Requirements

- Python 3.x
- qrcode
- pillow

# 🤝 Contributing

Contributions are welcome!

1. Fork this repository.

2. Create a feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added new feature"
```

4. Push to GitHub.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

# 👨‍💻 Author

**Dipan Mondal**

GitHub: https://github.com/Coder-Dipan

LinkedIn : https://www.linkedin.com/in/dipan-mondal-8b068025b

---

# ⭐ Show Your Support

If you found this project helpful,

⭐ Star this repository

🍴 Fork it

📢 Share it with others

---



