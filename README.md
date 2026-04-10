# 🔍 OSINT Investigation - sp1ritfyre

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

![Twitter](images/1-twitter.png)

---

### 🔹 Step 2: Base64 Decoding
Found encoded link and decoded it.

Result → redhunt.net

![Base64](images/2-base64.png)

---

### 🔹 Step 3: URL Analysis
Analyzed using:
- urlscan.io
- VirusTotal

Findings:
- Hosted on AWS EC2 (UK)
- No malicious activity

![URL Scan](images/3-urlscan.png)

---

### 🔹 Step 4: Google Dorking
Used:
intext:@sp1ritfyre

Found Blogger account.

![Google](images/4-google.png)

---

### 🔹 Step 5: Blogger Analysis
Found hidden hex value.

![Blogger](images/5-blogger.png)

---

### 🔹 Step 6: Hex Decoding
Decoded hex → new blog URL

![Hex](images/6-hex.png)

---

### 🔹 Step 7: Final Profiling
Collected full data from multiple sources.

![Final](images/7-final-profile.png)

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

---

## ⚠️ Disclaimer
This project is based on a fictional scenario for educational purposes only.
