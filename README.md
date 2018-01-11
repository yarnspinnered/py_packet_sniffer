# py_packet_sniffer
A simple packet sniffer written in python. Sniffs incoming IP packets for a specified duration, parses them into TCP and UDP packets. If a whitelist of source IPs and ports is provided, only those in the whitelist are processed. 

With the verbose option, basic information of every incoming packet that satisfies the rules of the whitelist is printed.  Some simple statistics about size and sources of incoming traffic are then displayed afterwards. Some tests are also included.
