# Automated-Information-Gathering
Python program to gather information of a network connection.

run python-nmap on terminal and run these commands :

import nmap
nm_scan = nmap.PortScanner()
nm_scanner = nm_scan.scan(sys.argv[1],'80',arguments='-O') #O is just a guess.

Look at the info and add variables in the program accordingly.
run script as : python automatedpython.py <ipaddress>
