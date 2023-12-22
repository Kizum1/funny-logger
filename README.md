# Xenotix Python Keylogger for Windows

## Introduction

This keylogger script is a modified version of the Xenotix Python Keylogger for Windows originally coded by Ajin Abraham ([Original GitHub Repository](https://github.com/ajinabraham/Xenotix-Python-Keylogger)) for educational purposes. The script has been adapted and enhanced to facilitate my learning about keylogger functionalities.

## Features of the logger

1. **Store Logs Locally:** Logs keystrokes locally in a file named `keylogs.txt`.
2. **Send Logs to Google Forms:** Sends logs to a Google Form. The Form URL and Field Name must be specified in the script.
3. **Send Logs to Email:** Sends logs to a specified email address. Server details (SMTP, port, username, password) must be provided.


## Minimum Requirements

- Python 2.7: [Download Python](http://www.python.org/getit/)
- pyHook Module: [Download pyHook](http://sourceforge.net/projects/pyhook/)
- pythoncom Module: [Download pythoncom](http://sourceforge.net/projects/pywin32/)
- pyHook Module: [Unofficial Windows Binaries](http://www.lfd.uci.edu/~gohlke/pythonlibs/)

## Usage

To use the keylogger, run the script with the desired mode as a command-line argument:

```bash
python xenotix_python_logger.py mode