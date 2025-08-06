# Phishing-Email-Analysis

# 📧 Sample Phishing Email Content:

From: account-security@micros0ft-support.com
To: user@example.com
Subject: Urgent Action Required - Your Account Has Been Compromised!

Dear Customer,

We have detected unusual activity in your Microsoft account. Immediate action is required to secure your data.

Please confirm your identity by clicking the secure link below:

🔗 https://micros0ft-support.com/security-check

Failure to verify your account within 24 hours will result in permanent suspension.

Thank you,
Microsoft Security Team

Examine Sender’s Email Address for Spoofing
• Sender: account-security@micros0ft-support.com • Suspicious? Yes. • The domain looks like “Microsoft” at a glance but is misspelled: micros0ft uses a zero (0) instead of the letter “o” – a classic spoofing tactic.

Check email Headers for Discrepancies
Using an email header analyzer, we’d look for: • Return-Path: Might differ from the “From” address. • Received paths: If the IP address is from a suspicious country or not related to Microsoft. • SPF, DKIM, or DMARC failures.

🛑 Suspicious finding

• SPF failed – sender not authorized. • Originating IP address resolves to a hosting service, not Microsoft.

Identify Suspecious Links or Attachments
• URL provided: https://micros0ft-support.com/security-check • Looks like Microsoft, but hover shows spoofed domain. • No attachments, but link is malicious.

🛑 Suspicious:

Link is meant to steal credentials.

Look for Urgent or Threatening Language
Phrases like: • “Urgent Action Required” • “Immediate action is required” • “Failure to verify… will result in permanent suspension”

🛑 Suspicious:

Uses fear and urgency to prompt user action.

Note Any Mismatched URLs (Hover to See Real Link)
•	Displayed as a secure Microsoft site
•	But actually leads to: https://micros0ft-support.com/...

🛑 Suspicious:

Mismatch in display vs. actual link.

Verify Presence of Spelling or Grammar Errors
•	“micros0ft” misspelling
•	“Your account has been compromised!” – sounds alarmist
•	Otherwise, grammar is decent (phishers often use spell check now)

🛑 Suspicious:

Minor errors and branding inconsistency.

Summarize Phishing Traits Found in the Email
Trait Description
🔍 Spoofed Sender micros0ft-support.com instead of official domain 🔗 Malicious Link URL designed to steal credentials ⚠ Urgency Language Threatens suspension within 24 hours ❓ Domain Mismatch Hover link doesn’t match official Microsoft domain 🧠 Social Engineering Uses fear to drive hasty action ✍ Spelling Mistake Misspelled “Microsoft” using a zero

# 🧾 Conclusion:
This email contains multiple indicators of phishing, including: • Spoofed sender address • Malicious link disguised as a security check • Use of urgency and fear tactics • Minor spelling tricks • Failed SPF check in headers

# 🛡 Advice:
Never click suspicious links, verify with official support, and report to your security team.

