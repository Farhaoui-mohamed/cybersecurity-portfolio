
# Network Port & Service Scanner

A Python-based network reconnaissance tool integrating Nmap to identify open TCP ports, detect services, and retrieve service version information.

## Project Overview

This project automates network port scanning and service identification.
It generates structured JSON and HTML reports to help visualize scan results.

## Features

- TCP port scanning
- Open port identification
- Service detection using Nmap
- Service version detection
- XML scan result parsing
- Automated JSON report generation
- Professional HTML report generation
- Input validation and error handling

## Technologies

| Technology | Purpose |
|---|---|
| Python 3 | Main programming language |
| Nmap | Network scanning and service detection |
| Linux / Kali Linux | Development and testing environment |
| JSON | Structured reporting |
| HTML / CSS | Report visualization |
| Git / GitHub | Version control |

## Project Structure

```text
network-vulnerability-scanner/
├── README.md
├── scanner.py
├── report.json
├── report.html
└── screenshots/
    └── report-preview.png
```

## Requirements

- Python 3
- Nmap
- Linux operating system

## Installation

Clone the repository:

```bash
git clone https://github.com/Farhaoui-mohamed/cybersecurity-portfolio.git
```

Navigate to the project:

```bash
cd cybersecurity-portfolio/network-vulnerability-scanner
```

Check Nmap:

```bash
nmap --version
```

## Usage

Example: scan localhost ports from 1 to 1024.

```bash
python3 scanner.py 127.0.0.1 --start 1 --end 1024
```

Example: scan port 8001 in a local testing lab.

```bash
python3 scanner.py 127.0.0.1 --start 8001 --end 8001
```

## Generated Reports

The scanner automatically generates:

- `report.json` – Structured scan information.
- `report.html` – Visual scan report.

## Screenshots

### HTML Security Scan Report

![Network Scanner Report](screenshots/report-preview.png)

## Learning Objectives

- Understand TCP port scanning.
- Practice network reconnaissance.
- Identify network services.
- Understand Nmap service detection.
- Parse XML scan output.
- Generate automated security reports.

## Limitations

This tool performs port scanning and service identification.
It does not currently perform automated vulnerability detection or exploitation.

## Author

**Mohamed Farhaoui**

Cybersecurity Engineering Student | CEH Certified

[LinkedIn](https://www.linkedin.com/in/mohamed-farhaoui-913754224)

[GitHub](https://github.com/Farhaoui-mohamed)

## Disclaimer

This tool is intended for authorized security testing and educational purposes only.
Only scan systems and networks for which you have explicit permission.
