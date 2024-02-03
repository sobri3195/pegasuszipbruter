# pegasuszipbruter
Pegasus ZIP Bruter is a powerful command-line utility designed to crack encrypted ZIP files using a brute force attack. This tool requires a strong wordlist to function effectively, as it attempts to guess the correct password from a list of potential passwords.

# Features
## Brute Force Attack: Utilizes a brute force method to guess the password of encrypted ZIP files.
## Multithreading Support: Speeds up the cracking process by using multiple threads.
## Wordlist Flexibility: Allows the use of custom wordlists for password guessing.

# Installation
This tool is written in Python 3 and does not require any external libraries beyond what is included with Python. To use Pegasus ZIP Bruter, you must have Python 3 installed on your system.
Download the zipbruter.py script to your local machine.
Ensure Python 3 is installed by running python3 --version in your terminal. If Python 3 is not installed, download and install it from python.org.

# Usage
To use Pegasus ZIP Bruter, navigate to the directory containing zipbruter.py and run the following command in the terminal:
python3 zipbruter.py -f <encrypted_zip_file> -w <wordlist> -t <threads>

# Parameters
-f or --file: Path to the target encrypted ZIP file.
-w or --word-list: Path to the wordlist file to be used for the brute force attack.
-t or --threads: (Optional) Number of threads to use for the attack. Default is 4.

# Example
python3 zipbruter.py -f secret_files.zip -w wordlist.txt -t 8
This command attempts to crack the password for secret_files.zip using wordlist.txt and 8 threads.

# Disclaimer
Pegasus ZIP Bruter is intended for educational and legal use only. Unauthorized access to encrypted files may be illegal. The author or distributor of this tool is not responsible for any misuse or damage caused by this tool.

# Contribution
Contributions to Pegasus ZIP Bruter are welcome. Please feel free to submit pull requests or open issues to improve the tool or fix bugs.
