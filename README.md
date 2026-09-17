<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Version-1.0-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/License-Key%20Required-red?style=for-the-badge&logo=key&logoColor=white" />
  <img src="https://img.shields.io/badge/Author-krainium-blueviolet?style=for-the-badge" />
</p>

<h1 align="center">📧 Outlook Creation Tool</h1>

<p align="center">
  <b>The best Outlook email creation tool for 2026, currently working with a 100% success rate.</b><br>
  Beats all other tools. Handles signup, captcha, recovery email, and verification in one click.
</p>

---

## 🔑 License

A valid license key is required to use this tool. On first launch, you will be prompted to enter your key. Once activated, the key is saved locally and you will not be asked again.

```
License Key: krainium2026
```

```
create_outlook.exe --key krainium2026
```

## 📦 First Run Setup

When the tool runs for the first time, it will automatically detect that browser dependencies are missing and install them for you. This only happens once. No manual setup is required.

```
 FIRST RUN SETUP
 ________________________________________

 [*] Installing browser dependencies...
     This only happens once.

 [+] Browser installed successfully!
```

After the first run, the tool starts instantly on every launch.

## 🚀 Usage

### Interactive Menu

Double click the exe or run it from the command line with no arguments to open the interactive menu.

```
create_outlook.exe
```

You will see the main menu:

```
  1  Create account (no proxy)
  2  Create account with proxy
  3  View created accounts
  0  Exit
```

### Command Line

| Command | Description |
|---------|-------------|
| `create_outlook.exe --create` | Create one account |
| `create_outlook.exe --create --count 5` | Create 5 accounts |
| `create_outlook.exe --create --proxy host:port:user:pass` | Create with proxy |
| `create_outlook.exe --list` | View all created accounts |
| `create_outlook.exe --key YOUR_KEY` | Activate license |
| `create_outlook.exe --screenshot C:\screenshots` | Save browser screenshots during creation |
| `create_outlook.exe --output C:\myfile.txt` | Custom output file for accounts |
| `create_outlook.exe --no-banner` | Suppress the banner |

### Examples

**Create one account locally:**

```
create_outlook.exe --create
```

**Create 3 accounts with a proxy:**

```
create_outlook.exe --create --count 3 --proxy rp.scrapegw.com:6060:username:password
```

**Create with screenshots saved:**

```
create_outlook.exe --create --screenshot C:\Users\You\Desktop\screenshots
```

## ⚙️ How It Works

The tool goes through 8 automated steps:

| Step | Action |
|------|--------|
| 1 | Loads the Microsoft signup page |
| 2 | Enters a randomly generated username |
| 3 | Sets a strong random password |
| 4 | Fills in a random date of birth |
| 5 | Enters a random first and last name |
| 6 | Solves the Arkose press and hold captcha |
| 7 | Handles recovery email verification |
| 8 | Verifies the account was created |

Created accounts are saved in `created.txt` next to the exe in `email:password` format.

## 🌐 Proxy Support

The tool supports HTTP proxies in `host:port:user:pass` format. This is useful when creating multiple accounts or when you need accounts from a specific region.

```
create_outlook.exe --create --proxy host:port:user:pass
```

When creating multiple accounts, use a different proxy session for each to avoid detection.

## 📸 Screenshots

### 🖥️ Windows Exe (Without Proxy)

Account creation running on Windows Server 2025 with no proxy configured.

<p align="center">
  <img src="screenshots/win_noproxy_password.png" width="700" alt="Windows exe without proxy" />
</p>

### 🖥️ Windows Exe (With Proxy)

Account creation running on Windows Server 2025 through a US residential proxy.

<p align="center">
  <img src="screenshots/win_proxy_password.png" width="700" alt="Windows exe with proxy" />
</p>

### 🐍 Python Script

The tool was originally developed as a Python script. Below are screenshots from the Python version running on a cloud instance.

**Password entry step:**

<p align="center">
  <img src="screenshots/python_password.png" width="700" alt="Python script password step" />
</p>

**Name entry step:**

<p align="center">
  <img src="screenshots/python_name.png" width="700" alt="Python script name step" />
</p>

