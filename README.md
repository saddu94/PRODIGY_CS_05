# PRODIGY_CS_05

This project, completed as part of an internship at Prodigy InfoTech, involves a cybersecurity tool for network packet analysis.

## Description

This cybersecurity project was developed independently, utilizing various references and self-study. The primary goal was to create a tool capable of network packet manipulation, analysis, and forging using Python.

## Prerequisites

To run this code, ensure you have the following installed:

- **Scapy:** A Python library used for network packet manipulation.
  ```sh
  pip install scapy
  ```

- **Npcap:** A packet capture and injection library for Windows, developed by the Nmap Project. It is the modern replacement for the older WinPcap library, which is no longer maintained. Download and install Npcap from the [official site](https://nmap.org/npcap/).
  - If you are using older Windows versions like Windows 7 or below, you can opt for WinPcap instead.

## Installation

1. **Install Scapy**
   ```sh
   pip install scapy
   ```

2. **Install Npcap**
   Download and install from the [Npcap website](https://nmap.org/npcap/).

## Usage

Once the prerequisites are installed, you are ready to run the code and start sniffing packets.

```sh
python 'Packet Analyzer'
```

## Notes

- Ensure Npcap is installed in WinPcap API-compatible mode if prompted during installation.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Feel free to add any additional sections or modify the content as needed!
