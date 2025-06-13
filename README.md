# Cyber-Project-Elevate-Lab

---

# 🔍 Web Vulnerability Scanner

A Python-based web application to scan websites for common vulnerabilities like **Cross-Site Scripting (XSS)** and **SQL Injection (SQLi)**. Built using **Flask**, **Requests**, and **BeautifulSoup**, with a web interface to input targets and view results.

---

## 🚀 Features

- ✅ Crawl target domain (limited to avoid deep crawling)
- ✅ Detect XSS and SQL Injection vulnerabilities
- ✅ Submit malicious payloads in form inputs
- ✅ View scan results via web interface
- ✅ Multithreaded scanning for faster results
- ✅ Severity-based reporting

---

## 🛠️ Technologies Used

- Python 3.8+
- Flask
- Requests
- BeautifulSoup
- HTML (via Flask templates)
- Concurrency (ThreadPoolExecutor)

---

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/web-vuln-scanner.git
   cd web-vuln-scanner
   ```

2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

---

## 🧪 Usage

1. **Start the Flask server:**

   ```bash
   python app.py
   ```

2. **Visit the web interface:**

   ```
   http://localhost:5000
   ```

3. **Enter the target website URL and click "Scan Now"**

---

## 📝 Example Output

* **Type:** SQL Injection
* **URL:** `https://example.com/search`
* **Payload:** `' OR 1=1 --`
* **Severity:** Critical

---

## ⚠️ Disclaimer

This tool is intended **for educational and authorized security testing only**. Unauthorized scanning or testing of websites without explicit permission is illegal and unethical.

---
