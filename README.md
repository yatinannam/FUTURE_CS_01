# 🔐 DVWA Web Application Vulnerability Testing

This project was developed as **Task 1** of the **Future Interns Internship Program**.  
It involved testing a sample vulnerable web application (**DVWA**) hosted on **Kali Linux** to identify and document real-world security vulnerabilities based on the **OWASP Top 10**.

---

## 🚀 Features

- Tested DVWA vulnerabilities manually using browser input  
- Demonstrated:
  - SQL Injection  
  - Reflected XSS  
  - Broken Authentication (Brute Force)  
  - CSRF (Cross-Site Request Forgery)  
- Mapped each finding to **OWASP Top 10**  
- Documented report with **screenshots, impact, and mitigation**

---

## 🛠️ Tech Stack & Tools

- **OS**: Kali Linux (VirtualBox)  
- **Target**: DVWA (Damn Vulnerable Web App via Docker)  
- **Tools**: Manual input, Firefox, Docker  

**Vulnerabilities Tested**:
- SQL Injection (A1)  
- XSS (A7)  
- Broken Authentication (A2)  
- CSRF (A5)

---

## 🧪 How It Works

1. DVWA was run locally in a Docker container on Kali Linux  
2. Security level was set to **Low** for easier testing  
3. Each vulnerability was tested manually:
   - SQL Injection via login/input fields  
   - XSS via reflected scripts in query parameters  
   - Brute force tested with default/weak credentials  
   - CSRF tested through password change without validation  
4. Screenshots were taken for each vulnerability and compiled into a detailed report

---

## 📄 Report Included

> The project includes a **PDF report** detailing each vulnerability, its OWASP mapping, screenshots, and suggested mitigations.

📄 **File:** [`DVWA_Report.pdf`](./DVWA_Report.pdf)

---

## 📁 Folders

- `screenshots/` – Proof-of-concept images  
- `DVWA_Report.pdf` – Final vulnerability assessment report

---
