## Overview

This Python-based Vulnerability Scanner is a comprehensive tool designed for security testing of web applications. It includes modules for testing various vulnerabilities such as Cross-Site Scripting (XSS), SQL Injection, Remote Code Execution (RCE), Server-Side Template Injection (SSTI), Open Redirection, and Clickjacking.

## Features

- **Modular Testing:** The tool includes separate functions for testing different types of vulnerabilities, allowing users to focus on specific security concerns.

- **Crawl and Test Functionality:** The tool can crawl web pages up to a specified depth and test each link found for vulnerabilities, providing a holistic approach to security testing.

- **Multithreading:** The tool uses multithreading to enhance efficiency, allowing concurrent testing of payloads and faster scanning.

- **User-Friendly Interface:** The interactive menu-driven interface enables users to choose specific vulnerability tests or initiate a comprehensive crawl and test operation.

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/softwarica-github/coursework1-GxbNt.git
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Scanner:**
   ```bash
   python Main.py
   ```

4. **Follow the On-Screen Instructions:**
   The tool provides a menu-driven interface for selecting specific vulnerability tests or initiating a crawl and test operation.

## Configuration

- Payloads for different vulnerabilities are stored in the `Payloads` directory.
- Modify the configuration files and banner in the `Config` directory according to your preferences.



