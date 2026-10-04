# $\textcolor{blue}{\text{ PASSWORD CRACKING .}}$
 ## $\textcolor{blue}{\text{ PASSWORD CRACKING WITH JOHN THE RIPPER AND NETWORKWALKS TOOLS.}}$
  ### W3-PM-FINAL | CYBERSECURITY | NETWORKWALKS

  
 |Field  | Details |
|---|---
|Pentester name| Halimah Daramola|
| Program/Batch | B083F-Networkwalks |
| Date | 02 October 2026 |
| Modules completed | W3-PM1 ( Password cracking with JTR) & W3-PM2 (Password cracking with NW tools) |
| Client/Target |  Networkwalks My Locked pdf files|
| Permission secured from client | Yes |
| Phases covered | Password cracking with JTR and NW tools |

---

### $\textcolor{blue}{\text{1. Liability Disclaimer.}}$
   
I have performed these activities only on the systems & devices where I had secured written permission or the devices/systems that I own myself. All these materials are for education and research purpose only. Do not use anything from here to break the law. The instructor, the authors and Networkwalks are not responsible for what you do with this knowledge. Every action you take is your own responsibility. Misuse can lead to criminal charges, heavy fines, loss of your job and a permanent record. In most countries unauthorised access is a crime even when nothing is damaged

---

### $\textcolor{blue}{\text{2. Introduction.}}$
This reports covers password cracking using JTR and NW tools (W3-PM1 & PM2). Both modules show how attackers recover passwords from protected files by taking the hash out and running it through John the ripper and other tools (NW tools). All cracking was done on a windows PC with JTR Johnny & JTR john installed and with browser for the NW tools. 

---

### $\textcolor{blue}{\text{3. Tools Used.}}$
|Tools | Purpose| 
|---|---|
| Windows | Operating system used for password cracking |
| onlinehashcrack.com | hash website for hash extraction |
| JTR John (CLI) & JTR Johnny (GUI)| crack all hashed files to reveal the passwords |
| Networkwalks Hash Calculator | hash out all encrypted files |
| Networkwalks Password Cracker | crack all hashed files to reveal the passwords|

---

### $\textcolor{blue}{\text{4. Activities Conducted.}}$
**4.1 Password Cracking With JTR**
- I used **onlinehashcrack.com** to find the hash of the encrypted file. The result showed the hashed value of the file $pdf$4*4*128*-1028*1*16*ca7f72f11459cba469f1005a8765ed51*32*f32d8fa1bfbe2648226dffc39f7909ea0021446990b9e4114071a4d9104984c1*32*9322f50c29569712067a775264635e4954ccb1b99e209d664984054ffad30a6a for My locked pdf 1 )
- I then selected and copied the hash value in my notepad, saved it as a text file with **hash 1.txt**
- I added the hash file in the Open password file on Johnny and started new attack. The result revealed the password of the encrypted file as **good-luck**
- I then used the password to open the file. The result showed a congratulatory page showing the file has been successfully opened.

**4.2 Password Cracking with NW Tools**
- I used **Networkwalks hash calculator** to extract the hash of the encryped file. The result showed the hashed values of the file (same as for JTR)
- I then copied the full hash value and and ran it in networkwalk password cracker. The result revealed the password of the encrypted file (same as with JTR)
- I then used the password to open the file. The result showed a congratulatory page showing the file has been successfully opened.

---

### $\textcolor{blue}{\text{5. Risk Analysis / Impact}}$

| # | Risk | Evidence | Potential Impact | Risk Level |
|---|---|---|---|---|
|1| Weak passwords | Password hashes obtained were successfully tested with JTR and NW tool using appropriate wordlist | Attackers may recover valid credentials from obtained password hashes and use them to access the affected account or system | High |
|2| Credential re-use risk | The encrypted files permitted passwords that did not meet recommended complexity and length requirements | Successful credential reuse can lead to unauthorized access to additional accounts or services | High |
|3| Susceptibility to Dictionary Attacks | A dictionary/wordlist attack was performed against the collected passwords hashes on JTR and NW tool, resulting in one or more successful matches | Attackers can gain access without exploiting a technical vulnerability in the application itself | Medium - High |

---

### $\textcolor{blue}{\text{6. Recommendations.}}$ 
1. A minimum password length of at least 12 characters should be enforced.
2. The use of different unique passwords for different services should be encouraged.
3. Multi-factor authentication (MFA) should be implemented.
4. Store passwords using strong, modern password-hashing mechanisms such as Argon2id, bcrypt or scrypt with appropriate configuration.
5. password policies regularly.


---

### $\textcolor{blue}{\text{7. Conclusion}}$
During Week 3 of the Cybersecurity & Ethical Hacking internship, I successfully conducted hands-on password cracking exercises using both John the Ripper (JTR) and Networkwalks tools. The successful recovery of plaintext passwords highlighted critical security vulnerabilities associated with weak password complexity and dict-attack susceptibility. Implementing the recommended password policies, modern hashing algorithms (such as Argon2id), and Multi-Factor Authentication (MFA) will significantly improve the overall security posture against credential-based attacks. 
Through this practical lab exercise, I gained essential experience in credential analysis, extracting cryptographic hash signatures from protected files, and executing offline dictionary attacks. I also verified that different hash calculation and cracking utilities yield consistent, identical results when processing the same parameters. 


### $\textcolor{blue}{\text{8. Evidences Collected.}}$ 

<img width="1262" height="753" alt="Screenshot 2026-10-03 125358" src="https://github.com/user-attachments/assets/29c5612e-eb1f-4e34-9473-9aed6604cbef" />

<img width="1865" height="876" alt="Screenshot 2026-10-03 125416" src="https://github.com/user-attachments/assets/5c1c9b8f-3f70-4797-b2a9-4ede0d2c7dfb" />

<img width="1419" height="562" alt="Screenshot 2026-10-03 125540" src="https://github.com/user-attachments/assets/dc80a6e5-df8b-4053-ae33-4e710aec98ab" />

<img width="869" height="703" alt="Screenshot 2026-10-03 125712" src="https://github.com/user-attachments/assets/d5fd30af-1810-47c0-a00c-4dfb29062fd8" />

<img width="930" height="736" alt="Screenshot 2026-10-03 125747" src="https://github.com/user-attachments/assets/8442b053-2a1a-452d-a978-05eaa04d732a" />

<img width="856" height="689" alt="Screenshot 2026-10-03 125806" src="https://github.com/user-attachments/assets/4ef30d41-8516-4ce5-be19-43cef8218458" />

<img width="1217" height="896" alt="Screenshot 2026-10-03 125917" src="https://github.com/user-attachments/assets/0a5f5d4e-96b9-403e-bcf5-7079dfce84fc" />

<img width="1900" height="1003" alt="Screenshot 2026-09-28 152107" src="https://github.com/user-attachments/assets/94fd2c2c-a543-4000-af34-76876d0cf7b1" />

























**Author**
**Halimah Daramola**
 | Cybersecurity Professional B082 |
 Linkedln: https://www.linkedin.com/in/halimah-daramola-63663a194?utm_source=share_via&utm_content=profile&utm_medium=member_ios

---
- Project Information
  Program Name : Cybersecurity program at Networkwalks | Week:3 |
