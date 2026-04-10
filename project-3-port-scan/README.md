# Snort Project 3: Port Scan Detection

## Objective

Detect port scanning activity using a custom Snort rule.

---

## Tools

* Snort on linux device
* Nmap on mac device

---

## Rule Created

alert tcp any any -> any any (flags:S; msg:"Possible SYN Scan Detected"; sid:1000002; rev:1;)

---

## Activities

* Added custom rule to detect SYN packets
* Ran Snort in monitoring mode
* Performed port scan using Nmap
* Observed multiple alerts

---

## Command Used

nmap 127.0.0.1

---

## Observation

Multiple SYN packets triggered repeated alerts, indicating scanning behavior.

---

## Screenshots

* multiple screenshots

---

## Conclusion

Port scanning can be detected by monitoring SYN packet patterns, allowing early identification of reconnaissance activity.

