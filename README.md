# 💳 UPI QR Code Generator

# 📖 About

A Python project that generates UPI payment QR codes from a UPI ID using the `qrcode` library.

## ✨ Features

- Generate QR codes for UPI IDs
- Supports Google Pay, PhonePe, Paytm
- Simple CLI
- Beginner friendly

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

## 👨‍💻 Author

**Dipan Mondal**


