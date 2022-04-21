# Collector
Collector is a tool OSINT (open source intelligence) and information gathering. I build this tool for myself but you can use my tool for do OSINT and modify my script.

# Tested On
- Windows
- Kali Linux
- Termux

# Install
**Windows & Kali Linux**
```
git clone https://github.com/galihap76/collector.git
cd collector 
pip install -r requirements.txt
```
**Termux**
```
$pkg update && pkg upgrade
$pkg install python3
$pkg install git
$git clone https://github.com/galihap76/collector.git
$cd collector
$pip install -r requirements.txt
```

# Usage
**Windows**
```
main.py -h
```
**Kali Linux & Termux**
```
python3 main.py -h
```

# Features
- Information gathering in phone numbers
- Information gathering in account github
- Information gathering in ip address
- Information gathering in account instagram

# Example
**Osint Phonenumber**
```
main.py -n +6287848791960
           _ _           _
  ___ ___ | | | ___  ___| |_ ___  _ __
 / __/ _ \| | |/ _ \/ __| __/ _ \| '__|
| (_| (_) | | |  __/ (__| || (_) | |
 \___\___/|_|_|\___|\___|\__\___/|_|


[>] Coded By Galih Ap


[!] Fetching Phone Number : +6287848791960
[+] Country Code: 62 National Number: 87848791960
[+] International Format : +62 878-4879-1960
[+] National Format : 0878-4879-1960
[+] Time Zone : ('Asia/Jakarta',)
[+] ISP : XL
[+] Country Found : Indonesia
[+] Location : Indonesia
```

# Libraries & Api
- <a href="https://pypi.org/project/requests/">Requests</a>
- <a href="https://api.github.com/">Api github</a>
- <a href="https://pypi.org/project/phonenumbers/">Phone numbers</a>
- <a href="https://ipapi.co/">Ipapi</a>
- <a href="https://github.com/sc1341/InstagramOSINT">Instagram OSINT</a>
