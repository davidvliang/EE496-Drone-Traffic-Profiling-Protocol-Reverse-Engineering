# EE496-Drone-Traffic-Profiling-Protocol-Reverse-Engineering

# Setup
Using Wireshark,
1. decrypt packets with wpa-pwd
2. export udp packets as json

Developed in PyCharm.

## data_parser.py
This script parses the converted .json file and delimits the Mavlink 2.0 message within the data frame. It then tabulates this data and export it as a .xlsx file.
