# Phishing-Emails-in-Action-THM
Week 10 - Lab Task Social Engineering - Blue Team

## Introduction
Phishing Attack is a cybercrime where attackers impersonate trusted entities (like banks, companies, or colleagues) through fake emails, texts, or websites to trick people into revealing sensitive data (passwords, credit cards) or installing malware, using social engineering tactics like urgency or fear to bypass security. Not only that phishing emails are one of the most common social engineering attack vectors used by attackers to deceive users into revealing sensitive information. This write-up, documents the analysis of phishing emails conducted in the *Phishing Emails in Action* room on TryHackMe. As you should have already guessed, our focus is on email as the attack vector. The objective is to identify phishing indicators and understand common attacker techniques from a defensive perspective.

---

## Objective
- To analyze real phishing email samples
- To identify visible phishing indicators within an email client
- To understand how attackers manipulate users through email content
- To recognize common phishing attack patterns

---

## Environment
- Platform: TryHackMe
- Room: Phishing Emails in Action
- Email Client Used: Thunderbird

---

## Phishing Indicators Identified

### 1. Sender Impersonation
Although the sender name suggests a legitimate security company, the sender domain does not belong to the official organization. This indicates impersonation.

---

### 2. Mismatched Reply-To Address
The reply-to address differs from the displayed sender, which is a common phishing technique used to redirect responses to attacker-controlled accounts.

---

### 3. Psychological Manipulation
The subject line uses persuasive and fear-based language to influence the recipient into taking immediate action.

---

### 4. External Content Blocking
The email client blocked remote content, suggesting the presence of external resources often used for tracking or malicious purposes.

---

### 5. Suspicious Contact Method
The email includes a phone number, indicating a potential call-based phishing or tech support scam.

---

## Attack Classification
- Phishing
- Impersonation
- Social Engineering

---

## Potential Impact
If a victim interacts with this email, it could lead to:
- Disclosure of sensitive personal information
- Phone-based social engineering scams
- Financial loss

---

## Defensive Measures
- Verify sender domains carefully
- Avoid responding to unsolicited security-related emails
- Do not contact phone numbers provided in suspicious messages
- Enable phishing protection in email clients

---

## Conclusion
This exercise highlights how phishing attacks rely heavily on deceptive email content rather than technical exploits. By carefully examining sender details, message structure, and behavioral cues, users can identify phishing attempts and prevent potential security incidents.

---

## References
- TryHackMe – Phishing Emails in Action
