# SkullDoS

A UDP flooding tool for network stress testing and educational purposes.

## Description

SkullDoS is a multi-threaded UDP flood tool written in Python that allows network administrators and security researchers to perform stress tests on their own networks. The tool features an ASCII art interface and provides real-time statistics about the attack including bandwidth usage and total data sent.

## Features

- 💀 Multi-threaded UDP flood attacks
- 🎯 Target specific ports or attack all ports randomly
- 📊 Real-time bandwidth and data transfer statistics
- 🎨 Stylized terminal interface with colored output
- ⚙️ Configurable packet size and thread count
- 🚀 High-performance network stress testing

## Requirements

- Python 3.x
- pystyle library

## Installation

### Windows

Run the included setup batch file:

```bash
setup.bat
```

### Linux/Mac

Install dependencies manually:

```bash
pip install -U -r requirements.txt
```

## Usage

Run the script:

```bash
python skullDoS.py
```

Follow the interactive prompts:

1. **Enter target IP**: The IP address to test
2. **Enter port**: Specify a port or press Enter to attack all ports randomly
3. **Bytes per packet**: Customize packet size or press Enter for default (1250 bytes)
4. **Threads**: Set number of threads or press Enter for default (100 threads)

Press `Ctrl+C` to stop the attack and view statistics.

### Example

```
Enter the IP to Brutalize -> 192.168.1.1
Enter port [press enter to attack all ports] -> 80
Bytes per packet [press enter for 1250] -> 
Threads [press enter for 100] -> 
```

## ⚠️ Disclaimer

**IMPORTANT: This tool is for educational and authorized testing purposes only.**

- Only use this tool on networks and systems you own or have explicit permission to test
- Unauthorized use of this tool against systems you do not own is illegal and unethical
- The author is not responsible for any misuse or damage caused by this tool
- Denial of Service attacks are illegal in most jurisdictions without proper authorization
- This tool should only be used for legitimate security testing, research, or educational purposes

## Legal Notice

Performing DoS/DDoS attacks without authorization is a criminal offense in most countries. Always ensure you have written permission before testing any network or system that you do not own.

## Author

Created by billythego4t356

## License

Use at your own risk. Educational purposes only.
