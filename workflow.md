# Workflow

## Scan&#x20;

### Nmap

* \-p : Port ranges can be specified using the hyphen (e.g. 1-1023). The beginning and/or end values of a range may be omitted, causing Nmap to use 1 and 65535, respectively. So you can specify -p- to scan ports from 1 through 65535.
* \-sC : Performs a script scan using the default set of scripts. It is equivalent to --script=default. Someof the scripts in this category are considered intrusive and should not be run against a target network without permission.
* \-T4 : Set a timing template. The template names are paranoid (0), sneaky (1), polite (2), normal (3), aggressive (4), and insane (5). The first two are for IDS evasion.
* \-sT : TCP scan
* \-sU : UDP scan
* \-sV : Enables version detection
* \-n   : (No DNS resolution)
* \--script \<nom-du-script>



### Masscan

* \--rate : specify the desired rate of packet transmission
* \-e : specify the raw network interface to use
* \--router-ip : specify the IP address for the appropriate gateway



Post exploitation

