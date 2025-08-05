# Task 2: Phishing Email Analysis

**Internship Task**  
📅 Date: August 5, 2025  
🔍 Objective: Identify phishing characteristics in a suspicious email sample.

---

## 🧰 Tools Used
- Google Admin Toolbox (Email Header Analyzer)
- Manual email body inspection

---



## 📝 Summary of Analysis

- **Sender Email**: `no-reply@onedrive.com` ✅
- **SPF / DKIM / DMARC**: All passed ✅
- **Subject**: "Many files were recently deleted from your OneDrive"
- **Attachments**: PNG images only (seem safe)
- **Headers**: All hops and routing info look legitimate (Microsoft + Google)

---

## 🧠 Conclusion

This email shows no signs of phishing. All authentication mechanisms (SPF, DKIM, DMARC) passed, and the sender domain appears to be legitimate (OneDrive - Microsoft).  
⚠️ However, always be cautious with attachments and links in real emails.

📌 **Verdict:** **Legitimate email** – not a phishing attempt.

