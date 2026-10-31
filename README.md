# Wireshark SOC Analyst Incident Response Labs

Completed practical security investigation modules as part of the Networkwalks SOC Internship program.

## Overview of Labs Completed

### 1. Lab 3: Identify the Attacker's IP (Port Scanning & Reconnaissance)
- **Score:** 100/100
- **Skills:** TCP 3-way handshake analysis (`tcp.flags.syn == 1`), identifying scanning patterns, isolating attacker source IP (`192.168.10.66`), identifying open/closed ports via `SYN-ACK` and `RST-ACK`.

### 2. Lab 4: Follow TCP Stream (Plain-Text Chat Inspection)
- **Score:** 90/100
- **Skills:** Filtering non-standard ports (`tcp.port != 80 and tcp.port != 443`), reconstructing TCP conversations via `Follow TCP Stream`, extracting plain-text credentials and sensitive internal notes.

### 3. Lab 5: Hidden Data in Intranet Traffic
- **Score:** 100/100
- **Skills:** HTTP traffic filtering, detecting sensitive access tokens embedded within hidden HTML comments, HTTP response status code analysis (`200 OK`).

### 4. Lab 6: HTTP Plain-Text Credentials
- **Score:** 100/100
- **Skills:** Identifying unencrypted authentication sessions (`POST /login`), inspecting `application/x-www-form-urlencoded` payloads, and recognizing the security necessity of HTTPS over HTTP.

### 5. Lab 7: Catch the Brute Force Attacker (FTP)
- **Score:** 100/100
- **Skills:** Protocol hierarchy analysis, filtering FTP reply codes (`530 Login incorrect` vs `230 Login successful`), determining the attacker's brute-force attack vectors and identifying compromised passwords.

### 6. Lab 8: Catch the Call Scammer (VoIP Call Replay)
- **Score:** 100/100
- **Skills:** VoIP analysis using Wireshark's Telephony tools (`Telephony > VoIP Calls`), extracting and replaying audio streams (RTP/SIP) to identify fraudulent communications.

## Tools Used
- **Wireshark** (Display Filters, TCP Stream Reconstruction, Protocol Hierarchy, VoIP Telephony Analysis)<img width="1080" height="1700" alt="Lab 3 Result - Fortunate Dube " src="https://github.com/user-attachments/assets/20889199-3f2c-4717-89dd-c2e726e70a37" />
<img width="1080" height="1700" alt="Lab 4 Result - Fortunate Dube" src="https://github.com/user-attachments/assets/88563771-0217-4dd3-bbea-211e5042ead5" />
<img width="1080" height="1700" alt="Lab 5 Result - Fortunate Dube" src="https://github.com/user-attachments/assets/937f766c-3dd4-438f-9bef-03ed3498e928" />
<img width="1080" height="1700" alt="Lab 6 Result - Fortunate Dube" src="https://github.com/user-attachments/assets/19d4c75a-73a1-4077-a48a-859ac442e41f" />
<img width="1080" height="1700" alt="Lab 7 Result - Fortunate Dube" src="https://github.com/user-attachments/assets/196f7814-3c2c-4e7d-b037-7b4075b1532b" />
<img width="1080" height="1700" alt="Lab 8 Result - Fortunate Dube" src="https://github.com/user-attachments/assets/f9eeb96b-34d7-4f77-b432-0c44d4c5ddb2" />

