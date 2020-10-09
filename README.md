# ldapscaner script - This master is juste for education

setup:
1. apt-get update
2. apt-get install gcc
3. put the file in /root/
4. gcc ldapscan.c -pthread -o ldapscaner

Launch attack command: ./ldapscan <class to start> <class to end> <file.txt> <threads> <delay>
the class must be an ipv4
