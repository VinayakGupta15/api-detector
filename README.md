
## ![](https://imgs.search.brave.com/cyLoZR0VnEWdiLhKZay58Fme90URRGkyHmxbTWK5Su0/rs:fit:500:0:0/g:ce/aHR0cHM6Ly90NC5m/dGNkbi5uZXQvanBn/LzA1LzUwLzUwLzUz/LzM2MF9GXzU1MDUw/NTMyOV9oSnRlVnlO/dUdDWXIwWFlNWUpm/Q0oweXg5dTFLS2ZG/eC5qcGc)

---

## Table of Contents
- [API Leak Detection Tool](#api-leak-detection-tool)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Example](#example)

---

## API Leak Detection Tool

This Python tool helps detect API leaks within web pages, including JavaScript files. It identifies various API formats by scanning the HTML and linked JavaScript files for common patterns of API keys and tokens.

### Features
- Fetches and scans HTML content from a given URL.
- Extracts and scans linked JavaScript files.
- Identifies common API key patterns such as Google API keys, AWS keys, and generic API keys.
- Generates a report of found keys.

### Requirements
- Python 3.x
- `requests` library
- `beautifulsoup4` library
- `regex` library

### Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/
    cd 
    /api-detector
    ```

2. **Install the required Python libraries**:
    ```bash
    pip install requests beautifulsoup4 regex
    ```

### Usage

1. **Run the tool**:
    ```bash
    python api-detector.py
    ```

2. **Enter the URL** you want to scan when prompted.

### Example

```bash
$ python api-detector.py
Enter the URL to scan: https://example.com

Scanning https://example.com...
Found API keys:
Google API Key:
  - AIzaSyD-3E4_aE6hMckjvP48e3FsdL3mDe
AWS Access Key ID:
  - AKIAIOSFODNN7EXAMPLE
