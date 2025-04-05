# Network Reconnaissance Tool

## Introduction

Great Karigalan Portscanner is a simple Python-based port scanning tool created as a learning project. This is my first project in the field of cybersecurity, as I am new to this domain and eager to learn. The tool is designed to help understand the basics of network scanning and socket programming in Python. 

As a beginner in cybersecurity, I developed this project to gain hands-on experience and to better understand network protocols and security concepts. While it may not be as sophisticated as professional tools, it represents an important step in my learning journey.

Please note that this is for educational purposes only and should not be used for any unauthorized or malicious activities.

## Features

- Scan all ports (1-65535) on specified IP addresses
- Scan up to a specified maximum port number
- Support for scanning multiple IP addresses
- Color-coded output for better readability

## Requirements

- Python 3.12
- termcolor library
- socket library (usually comes pre-installed with Python)

## Installation

1. Clone or download this repository.
2. Run the script. It will automatically install the required dependencies.

## Usage

1. Run the script:
2. You will be prompted to enter a command:
- To scan all ports: Enter `scan--all`
- To scan up to a specific port: Enter `scan--<max_port>` (e.g., `scan--1000` to scan ports 1-1000)

3. After entering the command, you'll be prompted to enter one or more IP addresses, separated by commas.

4. The script will then scan the specified IP addresses and display the results.

## Example
Welcome to Great Karigalan Portscanner
[] Enter your command scan--100
[] Enter the IP address(es) as comma separated values 192.168.1.1, 10.0.0.1
Scanning ports up to 100 of 192.168.1.1
[+] Port 80 is open
[-] Port 81 is closed
...
Scanning ports up to 100 of 10.0.0.1
[+] Port 22 is open
[+] Port 80 is open
...
## Notes

- This tool uses a basic TCP connect scan and may be slow for large port ranges.
- Some systems or firewalls may block or rate-limit port scans, affecting results.
- Always ensure you have permission before scanning any network or system.

## Future Improvements

- Add more scanning techniques
- Implement multi-threading for faster scans
- Add option for custom port lists
- Improve error handling and reporting

Remember, this is a learning project and there's always room for improvement. Poitu va
