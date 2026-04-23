# 🔍 OSINT Investigation Blueteam - sp1ritfyre

## 🧠 Overview
This project is part of an OSINT capstone challenge from Security Blue Team.

The objective was to track a fictional Person of Interest (POI) using only publicly available information.

---

## 🎯 Initial Clue
- Twitter Handle: @sp1ritfyre

---

## 🪜 Investigation Process

### 🔹 Step 1: Twitter Recon
Used Google dork:
inurl:@sp1ritfyre site:twitter.com

![Twitter](twitter)

---

### 🔹 Step 2: Base64 Decoding
Found encoded link and decoded it.

Result → redhunt.net

![Base64](base64)

---

### 🔹 Step 3: URL Analysis
Analyzed using:
- urlscan.io
- VirusTotal

Findings:
- Hosted on AWS EC2 (UK)
- No malicious activity

![URL Scan](urlscan)

---

### 🔹 Step 4: Google Dorking
Used:
intext:@sp1ritfyre

Found Blogger account.

![Google](google)

---

### 🔹 Step 5: Blogger Analysis
Found hidden hex value.

![Blogger](blogger)

---

### 🔹 Step 6: Hex Decoding
Decoded hex → new blog URL

![Hex](hex)

---

### 🔹 Step 7: Final Profiling
Collected full data from multiple sources.

![Final](profile)

---

## 🧾 Final Findings

- Name: Sam Woods  
- Age: 23  
- Country: United Kingdom  
- Role: Junior Penetration Tester  
- Interests: Security, gaming, malware analysis  

---

## 🛠️ Tools Used
- Google Dorking  
- Base64 Decoder  
- Hex Decoder  
- urlscan.io  
- VirusTotal  
![Report](report)
---

## ⚠️ Disclaimer
This project is based on a fictional scenario for educational purposes only.
