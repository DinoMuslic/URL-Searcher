# URL Searcher

A command-line tool to open a specified URL in your web browser.

## Table of Contents

- [Installation](#installation)
  - [Linux & macOS](#installation-for-linux-&-macOS)
  - [macOS](#installation-for-macos)
  - [Windows](#installation-for-windows)
- [Usage](#usage)
- [Dependencies](#dependencies)

## Installation

### Installation for Linux & macOS

1. **Download the Script**:
   Open a terminal and run the following command:
    ```bash
   curl -L https://raw.githubusercontent.com/DinoMuslic/URL-Searcher/main/search -o /usr/local/bin/search
   chmod a+rx /usr/local/bin/search

### Installation for Windows

2. **Download the Script**
    Open a command prompt and run:
    ```bash
   curl -L -o %USERPROFILE%\search.py https://raw.githubusercontent.com/DinoMuslic/URL-Searcher/main/search.py

## Dependencies
    Install Required Dependencies: Navigate to the directory where you saved the search.py script, then run:
    ```bash
    pip install validators


## Usage 
To use the URL Searcher, run the following command in your terminal or command prompt:
    ```bash
    search https://www.example.com

Replace https://www.example.com with the URL you want to open.