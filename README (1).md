# Week 2 — Cybersecurity Internship

## Submission Package

This folder contains only the Week 2 deliverables required by the handbook:

1. `Sumit_Week2_OWASP_Top10_Summary.pdf`
2. `Sumit_Week2_Vulnerability_Findings_Log.pdf`
3. `Sumit_Week2_Authentication_Session_Analysis.pdf`
4. `Sumit_Week2_Penetration_Testing_Report.pdf`
5. `screenshots/` — supplied practical evidence

## Scope

- Target: Local OWASP Juice Shop
- Environment: Kali Linux
- Testing tools: Browser + Burp Suite Pro
- Assessment period: 28–29 September 2026
- Tester: Sumit Jaiswal

## Evidence Status

### Confirmed from supplied screenshots

- SQL Injection / authentication-bypass test — confirmed evidence in `screenshots/01_SQLi_Login_Bypass.png`
- Reflected XSS — confirmed evidence in `screenshots/02_XSS_Search_Alert.png`

### Evidence still required

- Broken Access Control / IDOR — capture a dedicated screenshot showing the tested object identifier and the resulting unauthorized access.
- Authentication/session analysis — capture Burp HTTP history/response evidence for cookie/token attributes, then record the exact observed values.
- Password-reset/session-invalidation checks — record the actual observed behavior; do not assume results.

## Recommended GitHub Structure

```text
Week2/
├── README.md
├── Sumit_Week2_OWASP_Top10_Summary.pdf
├── Sumit_Week2_Vulnerability_Findings_Log.pdf
├── Sumit_Week2_Authentication_Session_Analysis.pdf
├── Sumit_Week2_Penetration_Testing_Report.pdf
└── screenshots/
    ├── 01_SQLi_Login_Bypass.png
    ├── 02_XSS_Search_Alert.png
    ├── 03_SQLi_Payload_State.png
    └── 04_Authenticated_Product_View.png
```

## Before Submission

- Open every PDF once and check formatting.
- Add the missing broken-access-control proof screenshot.
- Complete the Burp-based authentication/session observations.
- Make sure the evidence filenames referenced in the PDFs match the GitHub files.
- Verify the GitHub repository and submitted links in an incognito/private browser window.
- Submit the four required Week 2 documents and their evidence through the coordinator's submission process.

## Evidence Integrity

Only observations supported by the supplied screenshots/material are presented as confirmed. Missing evidence is explicitly marked as pending rather than being invented.
