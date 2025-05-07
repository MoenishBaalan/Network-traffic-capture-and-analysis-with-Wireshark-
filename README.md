# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.

## DESIGN STEPS:
### Step 1:
Install Wireshark using the command:

### Step 2:
Launch Wireshark and select the appropriate network interface for live traffic capture.

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.

## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
# . Captured Packets with Protocol Analysis and Detailed Packet Info

![440095317-76526405-c140-4b59-b5e2-d62f85dfb72e](https://github.com/user-attachments/assets/447fe628-e785-459d-a31d-ce0f56455e3f)



# Start Capturing Packets
• Click the blue shark fin icon or double-click the interface.

• Wireshark will start capturing all real-time traffic.
![440095375-8abf4806-98df-45a0-a6e9-48e4c9221402](https://github.com/user-attachments/assets/d26d59a9-a372-4260-8544-fb59d74a1c42)



# Apply Filters to Focus on Specific Traffic
• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter bar to narrow down results.
![440095445-159d16dc-1a77-47e9-9995-746d2c9676f4](https://github.com/user-attachments/assets/373ef3f5-b51a-4574-829f-d8fb6ef33c32)



# Analyze Packet Details
• Click on a packet to view its detailed breakdown including frame, Ethernet,IP, TCP/UDP layers, and data payload.
![440095412-73bc4f5c-f7ed-452f-8d8b-a3db27ee40aa](https://github.com/user-attachments/assets/a093cd31-97ac-44ce-b82e-154e374f854a)


## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
