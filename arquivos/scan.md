PORT      STATE  SERVICE  VERSION
20/tcp    closed ftp-data
21/tcp    open   ftp      vsftpd 3.0.5
| ftp-syst: 
|   STAT: 
| FTP server status:
|      Connected to 45.65.157.187
|      Logged in as ftp
|      TYPE: ASCII
|      No session bandwidth limit
|      Session timeout in seconds is 300
|      Control connection is plain text
|      Data connections will be plain text
|      At session startup, client count was 4
|      vsFTPd 3.0.5 - secure, fast, stable
|_End of status
| ftp-anon: Anonymous FTP login allowed (FTP code 230)
|_Can't get directory listing: PASV IP 172.20.0.20 is not the same as 98.95.207.28
80/tcp    open   http     Apache httpd 2.4.54 ((Debian))
|_http-server-header: Apache/2.4.54 (Debian)
|_http-title: TechCorp Solutions - Solu\xC3\xA7\xC3\xB5es Empresariais
| http-robots.txt: 4 disallowed entries 
|_/admin/ /backup/ /.git/ /config/
| http-cookie-flags: 
|   /: 
|     PHPSESSID: 
|_      httponly flag not set
2222/tcp  open   ssh      OpenSSH 8.2p1 Ubuntu 4ubuntu0.13 (Ubuntu Linux; protocol 2.0)
| ssh-hostkey: 
|   3072 2c:d4:33:a1:e1:a6:4f:4f:c5:42:f5:98:b2:cc:79:a8 (RSA)
|   256 d6:9f:da:54:8d:db:a6:33:15:64:b4:42:e2:ee:c0:d4 (ECDSA)
|_  256 ae:f3:eb:cc:6d:cc:29:31:05:06:e1:c6:9b:dd:19:51 (ED25519)
3306/tcp  open   mysql    MySQL 8.0.44
| ssl-cert: Subject: commonName=MySQL_Server_8.0.44_Auto_Generated_Server_Certificate
| Not valid before: 2025-11-17T14:30:28
|_Not valid after:  2035-11-15T14:30:28
|_ssl-date: TLS randomness does not represent time
| mysql-info: 
|   Protocol: 10
|   Version: 8.0.44
|   Thread ID: 814
|   Capabilities flags: 65535
|   Some Capabilities: ConnectWithDatabase, SwitchToSSLAfterHandshake, Support41Auth, Speaks41ProtocolOld, SupportsTransactions, DontAllowDatabaseTableColumn, IgnoreSigpipes, InteractiveClient, Speaks41ProtocolNew, LongPassword, LongColumnFlag, IgnoreSpaceBeforeParenthesis, SupportsCompression, SupportsLoadDataLocal, ODBCClient, FoundRows, SupportsMultipleResults, SupportsAuthPlugins, SupportsMultipleStatments
|   Status: Autocommit
|   Salt: #	U\x0B@\x1D\x0E\x03yaSxq\W\x0E\x11_6l
|_  Auth Plugin Name: caching_sha2_password
8080/tcp  open   http     Apache httpd 2.4.65 ((Debian))
|_http-server-header: Apache/2.4.65 (Debian)
| http-open-proxy: Potentially OPEN proxy.
|_Methods supported:CONNECTION
| http-robots.txt: 1 disallowed entry 
|_/
|_http-title: phpMyAdmin
21100/tcp closed unknown
21101/tcp closed unknown
21102/tcp closed unknown
21103/tcp closed unknown
21104/tcp closed unknown
21105/tcp closed unknown
21106/tcp closed unknown
21107/tcp closed unknown
21108/tcp closed unknown
21109/tcp closed unknown
21110/tcp closed unknown
Service Info: OSs: Unix, Linux; CPE: cpe:/o:linux:linux_kernel

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 1170.86 seconds
