#  Wireshark Packet Analysis

##  Task Overview
- Captured live network traffic using Wireshark.
- Identified HTTP, DNS, and ICMP protocols.
- Analyzed packet structures and flows.

##  Key Findings
### Protocols Identified
1. **HTTP**  
   - Example: `GET /` request to `http://example.com`  
2. **DNS**  
   - Query for `google.com` → Response with IP `142.250.190.46`  
3. **ICMP**  
   - Ping requests to `8.8.8.8` with reply times <50ms  

##  Tools Used
- Wireshark 4.0.8
- Command Prompt (`ping`, `nslookup`, `curl`)

##  Files
- `captures/task_capture.pcap` - Main capture file  
- Screenshots like http filter, icmp filter , dns filter

##  How to Reproduce
1. Open `task5_capture.pcap` in Wireshark.
2. Apply filters:
   - `http` for web traffic  
   - `dns` for domain lookups  
   - `icmp` for ping packets  
