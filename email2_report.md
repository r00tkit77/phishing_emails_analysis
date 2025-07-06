**Email Preview (Thunderbird)**

![image](https://github.com/user-attachments/assets/3af25c88-e156-4150-9cfe-64e34a6c7317)
<br><br>

**Executive Summary**

An email was received claiming to be an employment contract from theceojamessmith@Drurnbo.com, sent to Rafaiel@Drumbo.com. The email includes an attached .exe file disguised as a PDF contract. This is a clear phishing attempt designed to deliver malware through user execution of the attachment. The sender domain is spoofed and impersonates the legitimate Drumbo.com domain using a lookalike (Drurnbo.com).
<br><br>

**Basic Details**

Timestamp: 14 Dec 2024, 03:57

From: theceojamessmith@Drurnbo.com 

Display Name: Drumbó

Subject: Immediate Action Required: Your Employment Contract

Recipient: Rafaiel@Drumbo.com
<br><br>

**Security Details**

SPF: 3 Failures

DKIM: Neutral

DMARC: NA
<br><br>

**Initial Malicious Indicators**

Lookalike domain used: Drurnbo.com mimics Drumbo.com.

Fake employment urgency: Pressure to review an “important contract” by end of day.

Executable attachment disguised as PDF: Urgent Contract Action.pdf.exe

Inconsistent return-path: The 'Return-Path' domain alaho-akbar.dezoeteinval.co.za is inconsistent with the 'From' domain Drurnbo.com.
<br><br>

**Attachment Analysis**

Filename: Urgent Contract Action.pdf.exe

Type: Windows Executable

md5: fbbdc39af1139aebba4da004475e8839

Delivery Method: Email attachment

Status: ***CONFIMED MALWARE/TROJAN***
<br><br>

**Threat Assessment**

Threat Type: Phishing/Malware Delivery

Impact: Potential malware infection, system compromise

Likelihood: Medium to High

Target: Internal users at Drumbo.com
<br><br>

**MITRE ATT&CK Mapping**

<table>
  <thead>
    <tr>
      <th>Tactic</th>
      <th>Technique</th>
      <th>ID</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Initial Access</td>
      <td>Spearphishing Attachment</td>
      <td>T1566.001</td>
      <td>Adversaries may send spearphishing emails with a malicious attachment in an attempt to gain access to victim systems.</td>
    </tr>
    <tr>
      <td>Execution</td>
      <td>Malicious File</td>
      <td>T1204.002</td>
      <td>An adversary may rely upon a user opening a malicious file in order to gain execution.</td>
    </tr>
  </tbody>
</table>
<br><br>

**Conclusion**

This is a confirmed phishing attack crafted to deliver malware. The attacker uses domain spoofing, social engineering and malware delivery via file attachment.
