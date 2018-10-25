# Scanning hosts

```text
admin@alight:~$ nmap dbserv1 webserv1

Starting Nmap 4.10 ( http://www.insecure.org/nmap/ ) at 2007-04-01 15:56 EDT
Interesting ports on 192.168.40.11:
Not shown: 1667 closed ports
PORT     STATE    SERVICE
22/tcp   close     ssh
135/tcp  filtered msrpc
136/tcp  filtered profile
137/tcp  filtered netbios-ns
138/tcp  filtered netbios-dgm
139/tcp  filtered netbios-ssn
199/tcp  open     smux
445/tcp  filtered microsoft-ds
1720/tcp filtered H.323/Q.931
3306/tcp open     mysql
3389/tcp filtered ms-term-serv
5631/tcp filtered pcanywheredata

Interesting ports on webserv1 (192.168.30.11):
Not shown: 1644 closed ports, 28 filtered ports
PORT     STATE SERVICE
21/tcp   close  ftp
22/tcp   close  ssh
80/tcp   close  http
111/tcp  close  rpcbind
199/tcp  close  smux
443/tcp  open  https
1008/tcp close  ufsd

Nmap finished: 2 IP addresses (2 hosts up) scanned in 17.001 seconds
```

