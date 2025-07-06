**Email Preview (Thunderbird)**

![image](https://github.com/user-attachments/assets/7483d075-27ae-4515-9a9a-a25cbe9e931c)
<br><br>

**Executive Summary**

An email was received claiming to be a "Commercial Purchase Receipt" from erikajohana.lopez@uptc.edu.co, referencing a transaction of $625,000 pesos. The email contains a malicious link pointing to an executable file disguised as an invoice. This is a clear phishing attempt with the intent of malware delivery.
<br><br>

**Basic Details**

Timestamp:            9 Dec 2022, 14:28<br>
From:                 <erikajohana.lopez@uptc.edu.co> *(Likely Spoofed)*<br>
Display Name:         Erika Johana López Valiente<br>
Subject:              COMMERCIAL PURCHASE RECEIPT ONLINE 27 NOV<br>
Recipient:            *Undisclosed*
<br><br>

**Security Details**

SPF:                	4 Soft Fail<br>
DKIM:	                Neutral<br>
DMARC:                Fail
<br><br>

**Initial Malicious Indicators**

Urgent financial lure:	Mention of a large transaction to trigger curiosity or panic.

SPF/DKIM/DMARC Failures:	Indicates possible spoofing of sender's address.

Links to suspicious executable file: Possible Trojan Malware
<br><br>

**Links Analysis**

Hyperlink: http://107.175.247.199/loader/install.exe  ***(DO NOT CLICK)***

IP Address: 107.175.247.199  **(CONFIRMED MALICIOUS)**

File: install.exe **(CONFIRMED MALWARE/TROJAN)**
<br><br>

**Threat Assessment**

Threat Type:	Phishing/Malware Delivery

Impact:	Potential malware infection, system compromise

Likelihood:	Medium to High

Target:	*Undisclosed recipients*
<br><br>

**MITRE ATT&CK Mapping**

<table>
  <tr>
    <th>Tactic</th>
    <th>Technique</th>
    <th>ID</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>Initial Access</td>
    <td>Spearphishing Link</td>
    <td>T1566.002</td>
    <td>Adversaries may send spearphishing emails with a malicious link in an attempt to gain access to victim systems.</td>
  </tr>
  <tr>
    <td>Execution</td>
    <td>Malicious File</td>
    <td>T1204.002</td>
    <td>An adversary may rely upon a user opening a malicious file in order to gain execution. </td>
  </tr>
</table>
<br><br>

**Conclusion**

This is a confirmed phishing attempt aimed at delivering malware. The attacker used social engineering, identity impersonation and malware delivery via phishing link.



