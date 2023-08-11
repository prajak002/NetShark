# NetShark
Developed a user-centric Python app to enhance network analysis. Unlike Wireshark's complex GUI, this app offers an intuitive interface for beginners. It simplifies tasks like DNS resolution and packet capture, eliminating the need for external tutorials. Additionally, I enhanced filtering mechanisms for improved efficiency. With advanced data storage and visualization, users can explore network packets comprehensively.

*Install: **

All platforms supported, Prerequisites: Python <= 3.8 installed (recommended Python 3.7.9)

Presenting an intuitive Python app designed to streamline network analysis. Upon launch, it promptly lists your network interfaces. Select the desired one, keeping in mind that some might be inactive. After clicking, input the number of packets you wish to capture—note that an excessive amount might cause a brief freeze.

# Key Features:
- Simplified network packet display filtering by Protocol, Source, and Destination.
- In-depth packet details viewing, accessed via a simple double-click.
- Robust support for multiple protocols including HTTP, TLSV1.2, SSDP, and more.
- IPv6 compatibility for comprehensive network analysis.
- Easy pcap/pcapng file loading for comprehensive examination.
- User-friendly packet saving through the "Save As" option under the "File" menu.

# Filtering Process:
- Click the prominent filter button on the upper left corner.
- Choose Network Protocol, Source, or Destination.
- Input the specific parameter, e.g., TCP, HTTP, IP addresses, etc.
- Implement the filter by clicking the red filter button.

# Generating I/O Graphs:
- Access the "Statistics" section on the menu header.
- Select "Generate I/O Graph" to generate, zoom, and save packet graphs using MatPlotLib.

# DNS Host Name Resolution:
- Under the "View" section, choose "Resolve DNS Hostnames" for DNS response packet hostname resolution.

This user-centric app aims to simplify network analysis, ensuring efficient and insightful packet examination without the confusion associated with complex interfaces.
