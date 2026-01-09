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

Justification 

1. Attacker will use this "noreply" message phrase to appear legitimate and prvent user's interaction and making more social engineering more effective.
<img width="1005" height="155" alt="image" src="https://github.com/user-attachments/assets/369cdc4f-48f1-4bbf-a8da-93cdc48d761e" />


2. As a reciever, we should notice and be careful by checking that if its related to the contect or no. Images show that attacker use malicious major companies such as their producs and logo ; OneDrive and Adobe is a completely a different companies. Also we should be more carefull by the URL.
<img width="910" height="584" alt="image" src="https://github.com/user-attachments/assets/b498bf0d-8d25-44b2-9b2f-399eb2e784cc" />
<img width="911" height="588" alt="image" src="https://github.com/user-attachments/assets/d3883415-a1b3-46c4-a49f-19f13a7242ce" />

3. For more details we must read the message or email at the first place. Here show that the email does not match the email address at all. Also there are lot of misplealing in the email.
<img width="1003" height="291" alt="image" src="https://github.com/user-attachments/assets/70954a23-df67-4fb5-98e1-037c78949e43" />
<img width="971" height="290" alt="image" src="https://github.com/user-attachments/assets/ae82ed36-573b-4e6d-9ef4-11c4cf457b61" />


You will notice that the spealing of the email.
<img width="1413" height="34" alt="image" src="https://github.com/user-attachments/assets/bf30cdd7-f5f6-4e9d-95eb-54a31a8424c3" />

4. This email was from Apple Store but the email was gibberish@sumpremed.com. This is completely weird and we should notice this.
<img width="1006" height="153" alt="image" src="https://github.com/user-attachments/assets/2938988c-4f29-4576-b4b8-58fd6e9d42eb" />

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
