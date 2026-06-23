# How to install Python

A simple guide to install Python on your PC.

---
## Windows

### Step 1: Download 
1. Go to [https://www.python.org/downloads/] 
2. Click on the yellow button: **Download Python**

### Step 2: Installation
1. Open the installer file (.exe)
2. **IMPORTANT:** Check the box **"Add Python to PATH"** 
3. Click on **"Install Now"** and wait for it to finish.

### Step 3: Verification
1. Open the terminal (CMD)
2. Run `python --version` (this should show you something like "Python 3.13.x")

---
## Mac

### Step 1: Download 
1. Go to [https://www.python.org/downloads/] 
2. Click on the yellow button: **Download Python**

### Step 2: Installation
1. Open the installer file (.pkg) and follow the steps.
2. Click on **"Continue"** and wait for the installation to finish.

### Step 3: Verification
1. Open the terminal.
2. Run `python3 --version` (this should show you something like "Python 3.13.x")

---
## Linux (Ubuntu/Debian)

### Step 1: Installation
1. Open your terminal and run the following commands:
```bash
   sudo apt update
   sudo apt install python3 python3-pip python3-venv
   ```
2. In your terminal run the following command:
```bash
   python3 --version
   ```
   this should show you something like "Python 3.13.x"