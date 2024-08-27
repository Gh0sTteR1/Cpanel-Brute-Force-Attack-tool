I am innocent before God of any person who uses this tool to harm others.

# CPANEL-WHM Checker

This script is designed to check the validity of login credentials for CPANEL-WHM instances. It takes a list of URLs, usernames, and passwords as input and verifies whether the credentials are valid.

## Features
- Multithreaded for faster processing.
- Outputs valid credentials to a `good.txt` file.
- Sends notifications of valid credentials via a bot (presumably a Telegram bot).

## Requirements

- Python 3.8+
- The following Python packages:
  - `requests`
  - `colorama`
  - `multiprocessing` (part of Python standard library)

## Installation

1. Clone the repository or download the script.

   ```bash
   git clone https://github.com/yourusername/repository-name.git
   cd repository-name

## Usage
Prepare your list of CPANEL-WHM credentials in a text file (list.txt). The file should have one line per account, with each line in the following format:

url|username|password

