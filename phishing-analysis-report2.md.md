
# 📄 Phishing Email Analysis Report

**Internship Task 2 - Sample 2**  
📅 **Date:** August 4, 2025  
🎯 **Objective:** Analyze a suspicious promotional email and identify phishing characteristics.

---

## 🧰 Tools Used

- **Email Header Analyzer**: Google Admin Toolbox  
  ([https://toolbox.googleapps.com/apps/messageheader/](https://toolbox.googleapps.com/apps/messageheader/))
- Manual inspection of email headers

---

## ✉️ Email Details

| Field | Value |
|-------|-------|
| **From** | Neha at Edureka `<neha@edureka.co>` |
| **To** | [Redacted for Privacy] |
| **Subject** | Top Tech Certifications to Stay Ahead of the Competition |
| **Delivery Time** | Delivered in 1 second |
| **Email Service** | Amazon SES (Simple Email Service) |

---

## 📤 Authentication Results

| Authentication Method | Result | Notes |
|-----------------------|--------|-------|
| **SPF** | ✅ Pass | IP `54.240.27.163` is authorized |
| **DKIM** | ✅ Pass | DKIM signatures valid for `edureka.co` and `amazonses.com` |
| **DMARC** | ✅ Pass | Domain policy successfully enforced |

---

## 🧪 Phishing Indicators Checklist

| Indicator | Present? | Comments |
|-----------|----------|----------|
| **Spoofed sender domain** | ❌ No | Sender matches legitimate Edureka domain |
| **Failed SPF/DKIM/DMARC** | ❌ No | All checks passed |
| **Mismatched links or suspicious URLs** | ⚠️ Cannot determine | Not included in header view |
| **Urgent/Threatening language** | ❌ No | Promotional and informative subject |
| **Poor grammar or spelling errors** | ❌ No | Language appears professional |
| **Unexpected or risky attachments** | ❌ No | No attachments visible |

---

## 🧠 Conclusion

This appears to be a **legitimate marketing email** from Edureka via Amazon SES. All authentication protocols passed, and the sender domain is not spoofed.

> ✅ **Verdict:** **Legitimate** promotional email.

---

**Analyst:** Disha Varshney  
**Submission Mode:** GitHub Repository (Cybersecurity Internship Task)
