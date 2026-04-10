# Snort Project 4: HTTP Flood Detection

## Objective

Detect abnormal HTTP traffic patterns using Snort.

---

## Tools

* Snort
* curl

---

## Rule Created

alert tcp any any -> any any (msg:"HTTP Flood Detected"; detection_filter:track by_src, count 20, seconds 2; sid:1000005; rev:1;)

---

## Activities

* Created threshold-based HTTP detection rule
* Generated multiple HTTP requests
* Observed alert triggering

---

## Command Used

for i in {1..50}; do curl http://example.com; done

---

## Observation

Snort generated alerts when HTTP traffic exceeded normal behavior.

---

## Screenshots
multiple photos available

---

## Conclusion

Snort can detect abnormal web traffic patterns such as automated requests or flooding using behavior-based rules.

