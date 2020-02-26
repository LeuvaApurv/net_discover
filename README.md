# Net_discover
net_discover - discover your Network and see who connected your wifi network.(EASIER and FASTER than EVER).

## Desclaimer
net_discover is intented ONLY for EDUCATIONAL PURPOSES.

## Requirements
Python

## Installation
Instructions on how to install *net_discover*
```bash
sudo git clone https://github.com/LeuvaApurv/net_discover.git
cd net_discover
sudo python net_discover.py -t [Target_ip]

```

## Help
```bash
sudo python net_discover.py -h

usage: net_discover.py [-h] [-t TARGET]

optional arguments:
  -h, --help            show this help message and exit
  -t TARGET, --target TARGET
                        Target IP / IP range.

```

## Sample output:
```bash
sudo python net_discover.py -t 10.0.2.1/24

IP Address		MAC Address
-------------------------------------------------
10.0.2.2		52:54:00:12:35:02
10.0.2.3		52:54:00:12:35:03
10.0.2.4		52:54:00:12:35:04

```
