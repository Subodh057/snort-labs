# Snort Project 1: Basic Traffic Monitoring and Alert Observation

## Objective

Understand how Snort monitors network traffic and generates alerts for suspicious activity.

---

## Tools

* Snort
* Linux terminal

---

## Activities

* Ran Snort in console mode
* Generated network traffic (DNS, ICMP, web)
* Observed Snort alerts

---

## Observations

* Snort generated alerts for UPnP malformed advertisement traffic
* These alerts were triggered by broadcast traffic in the local network
* Normal traffic such as ping and DNS did not trigger alerts
* Snort only alerts on traffic that matches predefined rules

---

## Screenshots

* snort_alert_upnp.png

---

## Conclusion

Snort functions as an intrusion detection system by analyzing traffic and generating alerts for suspicious patterns, rather than displaying all network activity like Wireshark.

