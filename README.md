# key_logger

NOTE: This project should be used for authorized testing or educational purposes only. You are free to copy, modify and reuse the source code at your own risk.

Uses
Some uses of a keylogger are:

>Security Testing: improving the protection against hidden key loggers;
>Business Administration: Monitor what employees are doing (with their consent);
>School/Institutions: Track keystrokes and log banned words in a file;
>Personal Control and File Backup: Make sure no one is using your computer when you are away;
>Parental Control: Track what your children are doing;
>Self-analysis and assessment.


# Getting started

System requirements
MS Windows (tested on 10). TODO: test Linux (requires sudo) and macOS support;
Python 3 (tested on v. 3.7.4).

# Usage

# Quick start

git clone https://github.com/harickshan1234/key_logger.git
cd key_logger

# Run as a Python script

python keylogger.py
Run as an executable (7 MB)
pip install pyinstaller
pyinstaller --onefile --noconsole keylogger.py
dist\keylogger.exe
