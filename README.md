
# 🖥️ Python Scripts to EXE Converter

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Stable-success)]()

A simple and intuitive **GUI tool** built with Python and Tkinter to convert `.py` scripts into standalone `.exe` applications using **PyInstaller**.  
Perfect for developers who want to distribute Python programs without requiring users to install Python.

---

## ✨ Features

✅ **Browse & Select** Python scripts easily  
✅ **Optional Icon Support** – Use `.ico` files for branding  
✅ **Custom Output Name** for the `.exe`  
✅ **One-File Bundle Option** (`--onefile`)  
✅ **No Console Option** (`--noconsole`) for cleaner UI  
✅ **Dark Theme Modern Interface**  
✅ **Quick Conversion** powered by PyInstaller  

---

## 🛠 Built With
- **Python 3.x**
- **Tkinter** – Graphical user interface
- **PyInstaller** – Creating `.exe` files
- **OS & Subprocess Modules** – File handling & execution

---

## 📜 How It Works
The app dynamically generates and runs a **PyInstaller** command based on your selected options.

Example:
```bash
pyinstaller --onefile --noconsole --icon=myicon.ico --name MyApp myscript.py
````

---

## 🚀 Installation & Usage

### 1️⃣ Run via Python

```bash
python script_to_EXE_converter.py
```

### 2️⃣ Run via Executable

* Open the compiled `.exe` directly.

---

## ▶ Using the Application

1. **Select Python Script** – Choose your `.py` file.
2. *(Optional)* Select an `.ico` file for your app icon.
3. *(Optional)* Enter a custom name for your `.exe`.
4. Choose options:

   * ✅ One file bundle
   * ✅ No console
5. Click **Convert to EXE**.
6. Your `.exe` will be available in the `dist/` folder.

---

## 📷 Demo Screenshots

### Main Interface

<img width="692" height="515" alt="image" src="https://github.com/user-attachments/assets/fd23d568-39ac-4dec-9fe8-4f1ecc8b1330" />
<img width="692" height="517" alt="image" src="https://github.com/user-attachments/assets/63fe0f70-f416-4517-af9e-2e16aba1c48c" />

### Conversion Result

<img width="698" height="525" alt="image" src="https://github.com/user-attachments/assets/6c29a45c-6a57-4eaf-b39b-b60fbd1edc61" />


---

## ⚠ Requirements

* **Python 3.x**
* **PyInstaller** installed:

```bash
pip install pyinstaller
```

---
