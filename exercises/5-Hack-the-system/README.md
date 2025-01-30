# 5. AI-Assisted Capture The Flag (CTF) Security Challenge

**What to Do**

Participants will be provided with a vulnerable Docker container or VM that contains security flaws. 
Your goal is to identify and exploit vulnerabilities with the help of **Cursor AI**, leveraging **Cursor Chat** for reasoning, analysis, and step-by-step guidance.

## Setup

1. **Download & Run the Vulnerable Environment:**
   - Use an existing intentionally vulnerable Docker image, such as:
     ```sh
     docker run -d -p 8080:80 vulnerables/web-dvwa
     ```
   - Alternatively, use a lightweight CTF-like image such as `bkimminich/juice-shop`:
     ```sh
     docker run -d -p 3000:3000 bkimminich/juice-shop
     ```
2. **Explore & Identify Vulnerabilities:**
   - Browse the running application and analyze its pages.
   - Look for common vulnerabilities (SQL injection, XSS, weak authentication, exposed secrets, etc.).
   - Use **Cursor Chat** to help analyze response headers, source code, and logs.
3. **Exploit the Vulnerabilities:**
   - Use AI guidance to craft and execute attack payloads.
   - Try different approaches such as brute-force, LFI, or authentication bypass.
   - Ask Cursor Chat: *“How do I exploit an SQL injection vulnerability in a login form?”*
4. **Patch & Mitigate:**
   - After successfully exploiting, attempt to fix the vulnerability using AI guidance.
   - Implement security best practices and verify if the issue is resolved.

**Expected Outcome**

- Familiarise yourself with:
  - Learn basic security vulnerabilities hands-on.
  - Use **Cursor AI** for security analysis, vulnerability identification, and exploitation techniques.
  - Understand how to patch vulnerabilities effectively.
  - Get a taste of ethical hacking and CTF-style problem-solving.

**Hint**

- If you’re new to security testing, start by using Cursor Chat to ask, *“How do I find vulnerabilities in a web app?”*
- Try simple payloads first before moving to more advanced techniques.
- Use **Cursor’s Terminal CMD+K** feature to quickly run curl requests, analyze headers, or test inputs.

**Estimated Time**

⏰ 30min - ∞
