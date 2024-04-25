# WiFi Security Behaviour Enhancing Curriculum

Welcome to the WiFi security behaviour enhancing curriculum. This curriculum can assist an organization enhance WiFi Security behaviour by training users or staff on various WiFi concepts which have been established to influence positive user behavior.

The curriculum covers the following thematic topics.

1. Basic WiFi architecture.
2. Current WiFi threat landscape.
3. Personally identifiable information and card data.
4. WiFi Attacks Demostration.
5. WiFi system security measures and controls.
6. Basic cyber-attack recovery procedures.


## 1. Basic WiFi Architecture.
> Topics To Cover
```sh
(a) Overview of WiFi Architecture
(b) WiFi encryption and authentication.
(c) Understanding the different types of WiFi networks (e.g., WEP, WPA, WPA2, WPA3).
``` 
## 2. Current WiFi Threat Landscape.
> Topics To Cover

(a) WiFi Vulneralbilities
```sh
  i.   WEP Vulnerabilities
  ii.  WiFi Protected Setup WPS Protocol
  iii. WPA2 KRACKs Vulnerability
  iv.  FragAttacks vulnerabilities
 ``` 
(b) WiFi Attack Strategies
```sh
  i.   Rogue Access Points
  ii.  WiFi Frequency Jamming Denial of Service (DOS)
  iii. Sidejacking or Session Hijacking
  iv.  Packet Sniffing
  v.   MAC Address Spoofing
  vi.  Man-in-the-Middle (MITM) Attacks
  vii. Evil Twins
 ``` 
## 3. Personally Identifiable Information (PII) and Card Data.
> Topics To Cover
```sh
(a) Elements of PII and card data
(b) How PII and card data is monetized
``` 
## 4. WiFi Attacks Demonstrations.
> Topics To Cover
```sh
(a) Introduction to tools commonly used for WiFi MitM attacks (e.g., Wireshark, Ettercap, Bettercap, Aircrack-ng, Airgeddon).
(b) Hands-on demonstrations of how these tools work and their capabilities.
(c) Explanation of ARP spoofing and DNS spoofing techniques.
(d) Demonstration of how to detect the presence of rogue access points using WiFi analyzers.
(e) Demonstration of how encrypted vs unencrypted network traffic appears in transit using Wireshark.
(f) Emphasise on the impact of submitting sensitive and PII data such as login credentials or card transaction details on a webiste with no HTTPS, use case studies or examples.
(g) A demonstration of how evil twins are created using a USB WiFi adapter with Aircrack-ng / Airgeddon or use a WiFi Pineapple kit from Hack5.
(h) A demonstration of a man-in-the-middle website attack using Burp Suite application.
(i) A demonstration of a man-in-the-middle WiFi attack using Bettercap solution.

``` 
## 5. WiFi System Security Measures and Controls.
> Topics To Cover
```sh
(a) Strategies for defending against MitM attacks.
(b) Best practices for securing WiFi networks such as enabling network segmentation, using strong encryption and implementing MAC address filtering.
(c) Discuss the importance of keeping application software and device firmwares up to date.
(d) Discuss the importance of securely storing and encrypting data especially while in transit to prevent unauthorized access.
```
## 6. Basic Cyber-attack Recovery Procedures.
> Topics To Cover

If any personal or confidential information was inadvertently compromised in a WiFi attack, take appropriate steps to mitigate the risk of exposure and most importantly for organizations ensure you comply with data breach notification requirements in line with local regulations such as GDPR (Europe), Data Protection Act, 2019 (Kenya) among others.

(a) Immediate Containment Measures:
```sh
  i.    Disconnect the affected devices from the network as soon as suspicious activity or a confirmed attack is detected.
  ii.   Shut down any compromised devices to prevent further unauthorized access.
  iii.  If required, physically disconnect the affected networking devices from the network to isolate the attack.
  iv.   Change WiFi network passwords and SSIDs to revoke access for unauthorized users.
  v.    Implement network segmentation to isolate compromised segments.
  vi.   Disable any compromised access points or routers and replace them with secure, unaffected devices.
```
(b) Long-term Containment Measures:
```sh
  i.    Conduct a forensic investigation to establish the extent and the nature of compromise.
  ii.   Identify the vulnerabilities that were exploited and lead to a breach.
  iii.  Apply patches to vulnerabilities found such as installing updates or upgrades on applications and firmware. 
  iv.   Enable WiFi encryption by implementing WPA2/WPA3 with strong authentication key.
  v.    Enable monitoring of the WiFi infrastructure by implementing intrusion detection & prevention systems.
  vi.   Implement WiFi network segmentation to isolate sensitive networks.
  vii.  Enable access control measure by implementing MAC filtering.
```

### License
[CC BY](https://creativecommons.org/licenses/by/4.0/)
