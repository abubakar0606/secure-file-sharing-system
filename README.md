 **Secure File Sharing System**

 📌 **Project Overview**

This project aims at developing a secure file sharing system to enable the safe exchange of
files between Internee.pk and third parties. The primary aim of this task is to
This will ensure that the files are kept confidential during the upload, storage, and download processes.
This task was accomplished as **Task 4** of the **Cybersecurity Internship at Internee.pk**.


 🎯 **Objective**
The goal of this activity is to:
Encrypted file transfers
Organize files in cloud storage properly
Offer controlled and temporary access to shared files
Prevent unauthorized or public access to sensitive data


 🔐 **Security Approach Used**
**1️⃣ File Encryption**

All files are encrypted with **AES-256 encryption** before being uploaded to the cloud.
This is to ensure that even if a person manages to get access to the file, the information will still be unreadable
without the proper decryption key.

 2️⃣ **Cloud Storage (AWS)**
The encrypted files are stored in a **private Amazon S3 bucket**.
There is no public access, and only the bucket owner has permissions to
read or write files. This ensures that the storage is secure.

**3️⃣ Signed URLs for Secure Access**
For securely transferring files, **pre-signed URLs** are used.
These URLs allow temporary access to private files without making them public. After the expiration time is reached, the link automatically becomes invalid.

### 4️⃣ Secure Download and Decryption
The files are downloaded through signed URLs and are encrypted throughout the transfer process.
Only those who have the right AES-256 key can decrypt and view the
content of the original file.

**Data Sources**
Sample reports available on Internee.pk
Test datasets downloaded from Kaggle
All the data used in this project is for testing purposes only.

**Tools & Technologies**
 AES-256 Encryption
  Amazon S3 (Cloud Storage)
AWS Pre-Signed URLs - Kaggle (Test Datasets)

**Documentation**

This repository contains:
Screenshots of encryption, cloud upload, permissions, and signed URLs
Explanatory notes for each security phase
A PDF report that explains the entire secure file sharing process


**Conclusion**

This exercise illustrates how secure file sharing can be achieved through encryption,
cloud storage, and access control mechanisms. By integrating AES-256 encryption,
private cloud storage, and signed URLs, files can be shared securely without exposing
sensitive data to unauthorized users.
Overall, this task gave hands-on experience in how file security can be applied in the real world.
concepts applied in professional settings.
 
 **Internship : This project is a part of the Cybersecurity Internship Program at Internee.pk**
