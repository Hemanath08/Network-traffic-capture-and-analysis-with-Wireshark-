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

## PROCEDURE:
Open Wireshark and Select a Network Interface • Launch Wireshark. • Select an active interface (like Wi-Fi or Ethernet) to start capturing packets.<br/>

Start Capturing Packets • Click the blue shark fin icon or double-click the interface. • Wireshark will start capturing all real-time traffic.<br/>

Apply Filters to Focus on Specific Traffic • Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter bar to narrow down results.<br/>

Analyze Packet Details • Click on a packet to view its detailed breakdown including frame, Ethernet, IP, TCP/UDP layers, and data payload.<br/>

Export or Save the Capture • Go to File > Save As to store the capture in .pcap format for future analysis.<br/>

## OUTPUT:
# Open Wireshark and Select a Network Interface 

![Screenshot 2025-05-02 083856](https://github.com/user-attachments/assets/92175ff9-2671-4ae3-af3f-8836a497e7af)

# Start Capturing Packets

![Screenshot 2025-05-02 083729](https://github.com/user-attachments/assets/40e2607b-b265-4528-9692-9cc0fca117e1)

# Apply Filters to Focus on Specific Traffic

![Screenshot 2025-05-02 090441](https://github.com/user-attachments/assets/b71423a8-f8b8-4c9e-8e62-5df97d557e2c)

# Analyze Packet Details

![Screenshot 2025-05-02 090441](https://github.com/user-attachments/assets/818afba3-e4ad-445a-b3e5-5fbb03f3e3d1)

![Screenshot 2025-05-02 083815](https://github.com/user-attachments/assets/91af9441-6dfd-4d3e-89f8-4a02bd2cb73f)

# save and export the capture

![Screenshot 2025-05-02 090531](https://github.com/user-attachments/assets/731f4abb-2246-4fd1-9764-2cbf6874e71e)

## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
