# Phishing Attack Analysis

## Introduction

Phishing is a type of cyberattack where attackers impersonate legitimate organizations to trick individuals into revealing sensitive information such as passwords or financial details.

This report analyzes a simulated phishing email and identifies indicators of compromise.

---

## Phishing Scenario

A user receives an email claiming to be from PayPal.

Email Content Example:

Subject: Urgent: Your PayPal Account Will Be Suspended

Dear Customer,

We detected suspicious activity on your PayPal account. To avoid account suspension, please verify your account immediately.

Click the link below to verify your account:

http://paypal-verification-login.com

Thank you for your cooperation.

PayPal Security Team

---

## Indicators of Compromise (IOC)

### 1. Suspicious Sender Address

Phishing emails often come from email addresses that look similar to legitimate ones.

Example:

support@paypa1.com

Notice that the letter "l" in PayPal is replaced with the number "1".

---

### 2. Fake Domain Name

The phishing link directs users to a fake website designed to look like the legitimate PayPal website.

Legitimate Domain:

paypal.com

Phishing Domain:

paypal-verification-login.com

Attackers often register similar-looking domains to trick users.

---

### 3. Urgent or Threatening Language

Phishing emails often create a sense of urgency.

Examples include:

- "Your account will be suspended"
- "Immediate action required"
- "Verify your account now"

This psychological pressure encourages users to act quickly without verifying the authenticity of the message.

---

### 4. Suspicious Links

Phishing emails usually contain links that redirect users to malicious websites.

Users can check links by hovering over them to reveal the actual destination URL.

---

### 5. Request for Sensitive Information

Phishing websites often ask for:

- Account passwords
- Credit card information
- Personal identification numbers
- One-time passwords (OTP)

Legitimate organizations rarely request such information through email links.

---

## Conclusion

The phishing email analyzed in this scenario contains multiple indicators of compromise including a suspicious sender address, fake domain, urgent language, and attempts to collect sensitive information.

Users should always verify the authenticity of emails before clicking links or providing personal information.
