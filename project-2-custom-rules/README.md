# Snort Project 2: Custom Rule Creation

## Objective
Create and test a custom Snort rule to detect ICMP traffic.

## Tools
- Snort
- Linux terminal

## Rule Created
alert icmp any any -> any any (msg:"Ping Detected"; sid:1000001; rev:1;)

## Activities
- Added a custom ICMP detection rule in `local.rules`
- Validated Snort configuration
- Ran Snort in console mode
- Generated ICMP traffic using ping
- Observed real-time alert output

## Traffic Generated
ping -4 -c 4 8.8.8.8

## Observation
Snort successfully generated alerts when ICMP traffic matched the custom rule.

## Screenshots
- screenshots/ping_rule_alert.png

## Conclusion
This project demonstrated how Snort rules can be written and used to detect specific network traffic in real time.
