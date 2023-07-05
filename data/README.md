# CICDDoS2019 Dataset

The CICDDoS2019 dataset contains both benign and various Distributed Denial of Service (DDoS) attacks, designed to resemble real-world network traffic captured in PCAPs (packet capture) format. The dataset includes labeled flows based on the time stamp, source and destination IPs, source and destination ports, protocols, and attack types in CSV files.

## Overview

- Dataset Name: CICDDoS2019
- Purpose: To provide realistic and up-to-date common DDoS attacks and benign network traffic for research and evaluation purposes.
- Source: Network traffic analysis using CICFlowMeter-V3 with labeled flows
- Background Traffic Generation: Utilized the B-Profile system (Sharafaldin, et al. 2016) to profile human interaction behaviors and generate naturalistic benign background traffic.
- Abstract Behavior: Abstract behavior of 25 users based on HTTP, HTTPS, FTP, SSH, and email protocols.

## Attacks Included

The dataset includes the following modern reflective DDoS attacks:
- PortMap
- NetBIOS
- LDAP
- MSSQL
- UDP
- UDP-Lag
- SYN
- NTP
- DNS
- SNMP

## Attack Execution

The attacks were executed during the dataset creation period, with the following distribution:
- Training Day: 12 DDoS attacks were executed, including NTP, DNS, LDAP, MSSQL, NetBIOS, SNMP, SSDP, UDP, UDP-Lag, WebDDoS, SYN, and TFTP.
- Testing Day: 7 DDoS attacks were executed, including PortScan, NetBIOS, LDAP, MSSQL, UDP, UDP-Lag, and SYN. WebDDoS had low traffic volume, and PortScan was only executed on the testing day, making it unavailable for evaluating the proposed model.

## License and Citation


## Download the Dataset

To download the entire CICDDoS2019 dataset, please visit the following link:

[Download CICDDoS2019 Dataset](http://205.174.165.80/CICDataset/CICDDoS2019/)

## Acknowledgments

