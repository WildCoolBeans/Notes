```elm
# Nmap 7.91 scan initiated Tue Apr 20 12:31:35 2021 as: nmap -Pn -v -sV -sC --script-timeout=30 -iL ../hosts.txt -oA tcp_top_1000_service
Increasing send delay for 40.69.101.196 from 0 to 5 due to 11 out of 31 dropped probes since last increase.
Increasing send delay for 52.156.8.101 from 0 to 5 due to 11 out of 31 dropped probes since last increase.
Increasing send delay for 52.235.34.122 from 0 to 5 due to 11 out of 36 dropped probes since last increase.
Increasing send delay for 99.79.129.39 from 0 to 5 due to 28 out of 91 dropped probes since last increase.
Increasing send delay for 40.69.101.196 from 5 to 10 due to 11 out of 11 dropped probes since last increase.
Increasing send delay for 52.156.8.101 from 5 to 10 due to 11 out of 12 dropped probes since last increase.
Increasing send delay for 52.235.34.122 from 5 to 10 due to 11 out of 12 dropped probes since last increase.
Increasing send delay for 99.79.129.39 from 5 to 10 due to 11 out of 11 dropped probes since last increase.
Increasing send delay for 52.156.8.101 from 10 to 20 due to 11 out of 28 dropped probes since last increase.
Increasing send delay for 52.235.34.122 from 10 to 20 due to 11 out of 36 dropped probes since last increase.
Nmap scan report for 52.155.25.213
Host is up (0.12s latency).
All 1000 scanned ports on 52.155.25.213 are filtered

Nmap scan report for 20.39.132.98
Host is up (2.8s latency).
All 1000 scanned ports on 20.39.132.98 are filtered

Nmap scan report for 40.80.240.139
Host is up (0.30s latency).
All 1000 scanned ports on 40.80.240.139 are filtered

Nmap scan report for 40.69.101.196
Host is up (0.16s latency).
Not shown: 997 filtered ports
PORT      STATE SERVICE          VERSION
8081/tcp  open  blackice-icecap?
8443/tcp  open  ssl/https-alt
| http-methods: 
|_  Supported Methods: GET
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Service
| ssl-cert: Subject: commonName=8f19d5aa-5831-4d44-9814-628955ea5299.gwt.cloudapp.net
| Subject Alternative Name: DNS:azuregateway-8f19d5aa-5831-4d44-9814-628955ea5299-4e67defc5220.gwt.cloudapp.net
| Issuer: commonName=AME INFRA CA 01
| Public Key type: rsa
| Public Key bits: 2048
| Signature Algorithm: sha256WithRSAEncryption
| Not valid before: 2021-03-11T01:04:47
| Not valid after:  2022-03-06T01:04:47
| MD5:   3b46 a638 b07e 32ea 9057 9ff0 5ca6 139b
|_SHA-1: f7b6 7f38 8f2c d2c4 9872 566d a266 6315 34b8 8db0
10001/tcp open  scp-config?

Nmap scan report for 40.69.97.141
Host is up (0.15s latency).
Not shown: 999 filtered ports
PORT     STATE SERVICE VERSION
8083/tcp open  us-srv?

Nmap scan report for 52.139.83.95
Host is up (0.24s latency).
All 1000 scanned ports on 52.139.83.95 are filtered

Nmap scan report for 52.139.83.106
Host is up (2.9s latency).
All 1000 scanned ports on 52.139.83.106 are filtered

Nmap scan report for 40.80.248.106
Host is up (3.0s latency).
All 1000 scanned ports on 40.80.248.106 are filtered

Nmap scan report for 52.232.130.89
Host is up (2.9s latency).
All 1000 scanned ports on 52.232.130.89 are filtered

Nmap scan report for 52.235.34.122
Host is up (0.16s latency).
Not shown: 996 filtered ports
PORT      STATE SERVICE          VERSION
8081/tcp  open  blackice-icecap?
8443/tcp  open  ssl/https-alt
| http-methods: 
|_  Supported Methods: GET
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Service
| ssl-cert: Subject: commonName=12ee0067-94b6-4fab-a135-1bb1b0377a3a.gwt.cloudapp.net
| Subject Alternative Name: DNS:azuregateway-12ee0067-94b6-4fab-a135-1bb1b0377a3a-5c695797e26d.gwt.cloudapp.net
| Issuer: commonName=AME Infra CA 02
| Public Key type: rsa
| Public Key bits: 2048
| Signature Algorithm: sha256WithRSAEncryption
| Not valid before: 2021-03-11T00:30:01
| Not valid after:  2022-03-06T00:30:01
| MD5:   7371 480e 4800 3dc4 43da 15f6 0177 355a
|_SHA-1: 6c29 73da e557 c771 f028 c2ba 2f58 e63e e6aa abde
10001/tcp open  scp-config?
10002/tcp open  documentum?

Nmap scan report for 52.235.42.123
Host is up (1.3s latency).
Not shown: 999 filtered ports
PORT     STATE SERVICE VERSION
8083/tcp open  us-srv?

Nmap scan report for 40.80.252.76
Host is up (0.14s latency).
All 1000 scanned ports on 40.80.252.76 are filtered

Nmap scan report for 40.80.254.164
Host is up (2.9s latency).
All 1000 scanned ports on 40.80.254.164 are filtered

Nmap scan report for 20.151.4.110
Host is up (0.33s latency).
All 1000 scanned ports on 20.151.4.110 are filtered

Nmap scan report for 52.156.8.101
Host is up (0.15s latency).
Not shown: 996 filtered ports
PORT      STATE SERVICE          VERSION
8081/tcp  open  blackice-icecap?
8443/tcp  open  ssl/https-alt
| http-methods: 
|_  Supported Methods: GET
|_http-server-header: Microsoft-HTTPAPI/2.0
|_http-title: Service
| ssl-cert: Subject: commonName=350b0066-84f4-4e68-87a7-ce3612195ce6.gwt.cloudapp.net
| Subject Alternative Name: DNS:azuregateway-350b0066-84f4-4e68-87a7-ce3612195ce6-3c8209aa3b90.gwt.cloudapp.net
| Issuer: commonName=AME INFRA CA 01
| Public Key type: rsa
| Public Key bits: 2048
| Signature Algorithm: sha256WithRSAEncryption
| Not valid before: 2021-03-08T21:52:11
| Not valid after:  2022-03-03T21:52:11
| MD5:   fe08 a7a9 d9e9 4600 70c4 2c4d 9ecc 0270
|_SHA-1: 4ab0 4dc1 77b1 5e19 3b6b f5cd 1302 4060 bd5e ee76
10001/tcp open  scp-config?
10002/tcp open  documentum?

Nmap scan report for 52.156.8.109
Host is up (1.1s latency).
Not shown: 999 filtered ports
PORT     STATE SERVICE VERSION
8083/tcp open  us-srv?

Nmap scan report for ec2-35-183-154-43.ca-central-1.compute.amazonaws.com (35.183.154.43)
Host is up (3.0s latency).
All 1000 scanned ports on ec2-35-183-154-43.ca-central-1.compute.amazonaws.com (35.183.154.43) are filtered

Nmap scan report for ec2-99-79-129-39.ca-central-1.compute.amazonaws.com (99.79.129.39)
Host is up (0.17s latency).
Not shown: 998 filtered ports
PORT    STATE SERVICE   VERSION
80/tcp  open  http
| fingerprint-strings: 
|   FourOhFourRequest: 
|     HTTP/1.1 302 Found
|     Date: Tue, 20 Apr 2021 16:43:49 GMT
|     Location: https://Fortigate:443/nice%20ports,/Trinity.txt.bak
|     Content-Length: 235
|     Connection: close
|     Content-Type: text/html; charset=iso-8859-1
|     <!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
|     <html><head>
|     <title>302 Found</title>
|     </head><body>
|     <h1>Found</h1>
|     <p>The document has moved <a href="https://Fortigate:443/nice%20ports,/Trinity.txt.bak">here</a>.</p>
|     </body></html>
|   GetRequest: 
|     HTTP/1.1 302 Found
|     Date: Tue, 20 Apr 2021 16:43:42 GMT
|     Location: https://Fortigate:443/
|     Content-Length: 206
|     Connection: close
|     Content-Type: text/html; charset=iso-8859-1
|     <!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
|     <html><head>
|     <title>302 Found</title>
|     </head><body>
|     <h1>Found</h1>
|     <p>The document has moved <a href="https://Fortigate:443/">here</a>.</p>
|     </body></html>
|   HTTPOptions: 
|     HTTP/1.1 302 Found
|     Date: Tue, 20 Apr 2021 16:43:43 GMT
|     Location: https://Fortigate:443/
|     Content-Length: 206
|     Connection: close
|     Content-Type: text/html; charset=iso-8859-1
|     <!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
|     <html><head>
|     <title>302 Found</title>
|     </head><body>
|     <h1>Found</h1>
|     <p>The document has moved <a href="https://Fortigate:443/">here</a>.</p>
|     </body></html>
|   RTSPRequest: 
|     HTTP/1.1 400 Bad Request
|     Date: Tue, 20 Apr 2021 16:43:43 GMT
|     Content-Length: 226
|     Connection: close
|     Content-Type: text/html; charset=iso-8859-1
|     <!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
|     <html><head>
|     <title>400 Bad Request</title>
|     </head><body>
|     <h1>Bad Request</h1>
|     <p>Your browser sent a request that this server could not understand.<br />
|     </p>
|_    </body></html>
| http-methods: 
|_  Supported Methods: GET HEAD POST OPTIONS
|_http-title: Did not follow redirect to https://ec2-99-79-129-39.ca-central-1.compute.amazonaws.com:443/
443/tcp open  ssl/https
| fingerprint-strings: 
|   FourOhFourRequest: 
|     HTTP/1.1 401 Unauthorized
|     Date: Tue, 20 Apr 2021 16:43:51 GMT
|     X-Frame-Options: SAMEORIGIN
|     Content-Security-Policy: frame-ancestors 'self'
|     X-XSS-Protection: 1; mode=block
|     Strict-Transport-Security: max-age=15552000
|     X-UA-Compatible: IE=Edge
|     Content-Length: 123
|     Connection: close
|     <!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN"><html><head><title>Error</title></head><body><h1>Error</h1></body></html>
|   GetRequest: 
|     HTTP/1.1 302 Found
|     Date: Tue, 20 Apr 2021 16:43:49 GMT
|     Location: https://Fortigate/ng
|     Content-Length: 204
|     Connection: close
|     Content-Type: text/html; charset=iso-8859-1
|     <!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
|     <html><head>
|     <title>302 Found</title>
|     </head><body>
|     <h1>Found</h1>
|     <p>The document has moved <a href="https://Fortigate/ng">here</a>.</p>
|     </body></html>
|   HTTPOptions: 
|     HTTP/1.1 302 Found
|     Date: Tue, 20 Apr 2021 16:43:50 GMT
|     Location: https://Fortigate/ng
|     Content-Length: 204
|     Connection: close
|     Content-Type: text/html; charset=iso-8859-1
|     <!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
|     <html><head>
|     <title>302 Found</title>
|     </head><body>
|     <h1>Found</h1>
|     <p>The document has moved <a href="https://Fortigate/ng">here</a>.</p>
|     </body></html>
|   RTSPRequest: 
|     HTTP/1.1 400 Bad Request
|     Date: Tue, 20 Apr 2021 16:44:03 GMT
|     Content-Length: 226
|     Connection: close
|     Content-Type: text/html; charset=iso-8859-1
|     <!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
|     <html><head>
|     <title>400 Bad Request</title>
|     </head><body>
|     <h1>Bad Request</h1>
|     <p>Your browser sent a request that this server could not understand.<br />
|     </p>
|_    </body></html>
|_http-favicon: Fortinet
| http-methods: 
|_  Supported Methods: GET POST OPTIONS
| http-title: Error
|_Requested resource was https://ec2-99-79-129-39.ca-central-1.compute.amazonaws.com/ng
| ssl-cert: Subject: commonName=FortiGate/organizationName=Fortinet Ltd.
| Issuer: commonName=FortiGate/organizationName=Fortinet Ltd.
| Public Key type: rsa
| Public Key bits: 2048
| Signature Algorithm: sha256WithRSAEncryption
| Not valid before: 2020-06-25T20:48:29
| Not valid after:  2022-09-28T20:48:29
| MD5:   9098 7be8 ee46 65f7 58ec bf9c a30b a50e
|_SHA-1: 3c43 49e5 d429 deb8 2da7 6a04 c2bc a4a1 14b4 875c
|_ssl-date: TLS randomness does not represent time
| tls-alpn: 
|_  http/1.1
2 services unrecognized despite returning data. If you know the service/version, please submit the following fingerprints at https://nmap.org/cgi-bin/submit.cgi?new-service :
==============NEXT SERVICE FINGERPRINT (SUBMIT INDIVIDUALLY)==============
SF-Port80-TCP:V=7.91%I=7%D=4/20%Time=607F04BF%P=x86_64-pc-linux-gnu%r(GetR
SF:equest,180,"HTTP/1\.1\x20302\x20Found\r\nDate:\x20Tue,\x2020\x20Apr\x20
SF:2021\x2016:43:42\x20GMT\r\nLocation:\x20https://Fortigate:443/\r\nConte
SF:nt-Length:\x20206\r\nConnection:\x20close\r\nContent-Type:\x20text/html
SF:;\x20charset=iso-8859-1\r\n\r\n<!DOCTYPE\x20HTML\x20PUBLIC\x20\"-//IETF
SF://DTD\x20HTML\x202\.0//EN\">\n<html><head>\n<title>302\x20Found</title>
SF:\n</head><body>\n<h1>Found</h1>\n<p>The\x20document\x20has\x20moved\x20
SF:<a\x20href=\"https://Fortigate:443/\">here</a>\.</p>\n</body></html>\n"
SF:)%r(HTTPOptions,180,"HTTP/1\.1\x20302\x20Found\r\nDate:\x20Tue,\x2020\x
SF:20Apr\x202021\x2016:43:43\x20GMT\r\nLocation:\x20https://Fortigate:443/
SF:\r\nContent-Length:\x20206\r\nConnection:\x20close\r\nContent-Type:\x20
SF:text/html;\x20charset=iso-8859-1\r\n\r\n<!DOCTYPE\x20HTML\x20PUBLIC\x20
SF:\"-//IETF//DTD\x20HTML\x202\.0//EN\">\n<html><head>\n<title>302\x20Foun
SF:d</title>\n</head><body>\n<h1>Found</h1>\n<p>The\x20document\x20has\x20
SF:moved\x20<a\x20href=\"https://Fortigate:443/\">here</a>\.</p>\n</body><
SF:/html>\n")%r(RTSPRequest,178,"HTTP/1\.1\x20400\x20Bad\x20Request\r\nDat
SF:e:\x20Tue,\x2020\x20Apr\x202021\x2016:43:43\x20GMT\r\nContent-Length:\x
SF:20226\r\nConnection:\x20close\r\nContent-Type:\x20text/html;\x20charset
SF:=iso-8859-1\r\n\r\n<!DOCTYPE\x20HTML\x20PUBLIC\x20\"-//IETF//DTD\x20HTM
SF:L\x202\.0//EN\">\n<html><head>\n<title>400\x20Bad\x20Request</title>\n<
SF:/head><body>\n<h1>Bad\x20Request</h1>\n<p>Your\x20browser\x20sent\x20a\
SF:x20request\x20that\x20this\x20server\x20could\x20not\x20understand\.<br
SF:\x20/>\n</p>\n</body></html>\n")%r(FourOhFourRequest,1BA,"HTTP/1\.1\x20
SF:302\x20Found\r\nDate:\x20Tue,\x2020\x20Apr\x202021\x2016:43:49\x20GMT\r
SF:\nLocation:\x20https://Fortigate:443/nice%20ports,/Trinity\.txt\.bak\r\
SF:nContent-Length:\x20235\r\nConnection:\x20close\r\nContent-Type:\x20tex
SF:t/html;\x20charset=iso-8859-1\r\n\r\n<!DOCTYPE\x20HTML\x20PUBLIC\x20\"-
SF://IETF//DTD\x20HTML\x202\.0//EN\">\n<html><head>\n<title>302\x20Found</
SF:title>\n</head><body>\n<h1>Found</h1>\n<p>The\x20document\x20has\x20mov
SF:ed\x20<a\x20href=\"https://Fortigate:443/nice%20ports,/Trinity\.txt\.ba
SF:k\">here</a>\.</p>\n</body></html>\n");
==============NEXT SERVICE FINGERPRINT (SUBMIT INDIVIDUALLY)==============
SF-Port443-TCP:V=7.91%T=SSL%I=7%D=4/20%Time=607F04C5%P=x86_64-pc-linux-gnu
SF:%r(GetRequest,17C,"HTTP/1\.1\x20302\x20Found\r\nDate:\x20Tue,\x2020\x20
SF:Apr\x202021\x2016:43:49\x20GMT\r\nLocation:\x20https://Fortigate/ng\r\n
SF:Content-Length:\x20204\r\nConnection:\x20close\r\nContent-Type:\x20text
SF:/html;\x20charset=iso-8859-1\r\n\r\n<!DOCTYPE\x20HTML\x20PUBLIC\x20\"-/
SF:/IETF//DTD\x20HTML\x202\.0//EN\">\n<html><head>\n<title>302\x20Found</t
SF:itle>\n</head><body>\n<h1>Found</h1>\n<p>The\x20document\x20has\x20move
SF:d\x20<a\x20href=\"https://Fortigate/ng\">here</a>\.</p>\n</body></html>
SF:\n")%r(HTTPOptions,17C,"HTTP/1\.1\x20302\x20Found\r\nDate:\x20Tue,\x202
SF:0\x20Apr\x202021\x2016:43:50\x20GMT\r\nLocation:\x20https://Fortigate/n
SF:g\r\nContent-Length:\x20204\r\nConnection:\x20close\r\nContent-Type:\x2
SF:0text/html;\x20charset=iso-8859-1\r\n\r\n<!DOCTYPE\x20HTML\x20PUBLIC\x2
SF:0\"-//IETF//DTD\x20HTML\x202\.0//EN\">\n<html><head>\n<title>302\x20Fou
SF:nd</title>\n</head><body>\n<h1>Found</h1>\n<p>The\x20document\x20has\x2
SF:0moved\x20<a\x20href=\"https://Fortigate/ng\">here</a>\.</p>\n</body></
SF:html>\n")%r(FourOhFourRequest,19B,"HTTP/1\.1\x20401\x20Unauthorized\r\n
SF:Date:\x20Tue,\x2020\x20Apr\x202021\x2016:43:51\x20GMT\r\nX-Frame-Option
SF:s:\x20SAMEORIGIN\r\nContent-Security-Policy:\x20frame-ancestors\x20'sel
SF:f'\r\nX-XSS-Protection:\x201;\x20mode=block\r\nStrict-Transport-Securit
SF:y:\x20max-age=15552000\r\nX-UA-Compatible:\x20IE=Edge\r\nContent-Length
SF::\x20123\r\nConnection:\x20close\r\n\r\n<!DOCTYPE\x20HTML\x20PUBLIC\x20
SF:\"-//IETF//DTD\x20HTML\x202\.0//EN\"><html><head><title>Error</title></
SF:head><body><h1>Error</h1></body></html>")%r(RTSPRequest,178,"HTTP/1\.1\
SF:x20400\x20Bad\x20Request\r\nDate:\x20Tue,\x2020\x20Apr\x202021\x2016:44
SF::03\x20GMT\r\nContent-Length:\x20226\r\nConnection:\x20close\r\nContent
SF:-Type:\x20text/html;\x20charset=iso-8859-1\r\n\r\n<!DOCTYPE\x20HTML\x20
SF:PUBLIC\x20\"-//IETF//DTD\x20HTML\x202\.0//EN\">\n<html><head>\n<title>4
SF:00\x20Bad\x20Request</title>\n</head><body>\n<h1>Bad\x20Request</h1>\n<
SF:p>Your\x20browser\x20sent\x20a\x20request\x20that\x20this\x20server\x20
SF:could\x20not\x20understand\.<br\x20/>\n</p>\n</body></html>\n");

Nmap scan report for ec2-99-79-168-188.ca-central-1.compute.amazonaws.com (99.79.168.188)
Host is up (0.010s latency).
All 1000 scanned ports on ec2-99-79-168-188.ca-central-1.compute.amazonaws.com (99.79.168.188) are filtered

Read data files from: /usr/bin/../share/nmap
Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
# Nmap done at Tue Apr 20 12:46:11 2021 -- 19 IP addresses (19 hosts up) scanned in 875.35 seconds
```