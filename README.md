# 🛡️ Cyber Labs Portfolio

Welcome to my **Cybersecurity & Digital Forensics Portfolio**, showcasing hands-on labs in SOC analysis, digital forensics, and OSINT investigations.  

---

## 1️⃣ Wireshark Network Traffic Analysis Lab

**Objective:**  
Capture and analyze network traffic to identify DNS queries, HTTP requests, and plaintext credentials.

**Tools Used:**  
- Wireshark  
- Web Browser  

**Steps:**  
1. Started Wireshark capture on active network interface.  
2. Browsed multiple websites and performed test logins (HTTP for demo).  
3. Applied filters: `dns`, `http`, `http.request.method == "POST"`.  
4. Analyzed packets to identify DNS queries and login attempts.  

**Screenshots:**  
![DNS Query Example](images/wireshark_dns.png)  
![HTTP POST Example](images/wireshark_post.png)  

**Key Findings:**  
- Identified DNS queries and HTTP POST requests.  
- Observed plaintext credentials on unencrypted sites.  

**Resume Line:**  
*Conducted network packet analysis with Wireshark; identified DNS queries and plaintext credentials from HTTP POST requests.*

---

## 2️⃣ Digital Forensics Lab: USB Analysis with Autopsy

**Objective:**  
Recover deleted files and extract metadata from a USB drive using Autopsy.

**Tools Used:**  
- FTK Imager  
- Autopsy  

**Steps:**  
1. Created forensic image of USB drive using FTK Imager.  
2. Verified hash values to maintain integrity.  
3. Imported image into Autopsy and navigated file system artifacts.  
4. Recovered deleted files and extracted metadata (timestamps, author, geolocation).  

**Screenshots:**  
![Autopsy Recovered Files](images/autopsy_recovered_files.png)  
![Autopsy Metadata](images/autopsy_metadata.png)  

**Key Findings:**  
- Successfully recovered deleted files.  
- Extracted document metadata, including creation/modification timestamps.  

**Resume Line:**  
*Performed forensic imaging and analysis with FTK Imager and Autopsy, recovering deleted files and analyzing metadata artifacts.*

---

## 3️⃣ OSINT Lab: Domain Investigation

**Objective:**  
Investigate a suspicious domain using OSINT tools to assess threat indicators.

**Tools Used:**  
- WHOIS  
- VirusTotal  
- DNSdumpster  
- Shodan.io  

**Steps:**  
1. Performed WHOIS lookup to gather registration info.  
2. Conducted DNS mapping with DNSdumpster.  
3. Checked domain reputation with VirusTotal.  
4. Queried Shodan for exposed services and open ports.  

**Screenshots:**  
![WHOIS Lookup](images/osint_whois.png)  
![DNS Mapping](images/osint_dnsdumpster.png)  
![VirusTotal Report](images/osint_virustotal.png)  
![Shodan Service Scan](images/osint_shodan.png)  

**Key Findings:**  
- Anonymous registration with recent creation date.  
- Subdomain structure indicated possible phishing setup.  
- VirusTotal flagged domain as malicious.  
- Shodan revealed exposed RDP and FTP services.  

**Resume Line:**  
*Conducted OSINT investigation on suspicious domain using WHOIS, VirusTotal, DNS analysis, and Shodan to assess threat indicators.*

---

## 📂 Repository Structure

