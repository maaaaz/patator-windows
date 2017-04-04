patator-windows
=================

Description
-----------
The great `patator` tool compiled for Windows


Features
--------
* Latest `0.7-beta` version
* Compiled for `x86` so should work on `x86` and `x64` platforms
* Bundled with the following modules:
```
+ ftp_login     : Brute-force FTP
+ ssh_login     : Brute-force SSH
+ telnet_login  : Brute-force Telnet
+ smtp_login    : Brute-force SMTP
+ smtp_vrfy     : Enumerate valid users using SMTP VRFY
+ smtp_rcpt     : Enumerate valid users using SMTP RCPT TO
+ finger_lookup : Enumerate valid users using Finger
+ http_fuzz     : Brute-force HTTP
+ ajp_fuzz      : Brute-force AJP
+ pop_login     : Brute-force POP3
+ pop_passd     : Brute-force poppassd (http://netwinsite.com/poppassd/)
+ imap_login    : Brute-force IMAP4
+ ldap_login    : Brute-force LDAP
+ smb_login     : Brute-force SMB
+ smb_lookupsid : Brute-force SMB SID-lookup
+ rlogin_login  : Brute-force rlogin
+ vmauthd_login : Brute-force VMware Authentication Daemon
+ mssql_login   : Brute-force MSSQL
+ oracle_login  : Brute-force Oracle
+ mysql_login   : Brute-force MySQL
+ mysql_query   : Brute-force MySQL queries
+ rdp_login     : Brute-force RDP (NLA)
+ pgsql_login   : Brute-force PostgreSQL
+ vnc_login     : Brute-force VNC
+ dns_forward   : Forward DNS lookup
+ dns_reverse   : Reverse DNS lookup
+ snmp_login    : Brute-force SNMP v1/2/3
+ ike_enum      : Enumerate IKE transforms
+ unzip_pass    : Brute-force the password of encrypted ZIP files
+ keystore_pass : Brute-force the password of Java keystore files
+ umbraco_crack : Crack Umbraco HMAC-SHA1 password hashes
+ tcp_fuzz      : Fuzz TCP services
+ dummy_test    : Testing module
```


Usage
-----
1. Download the [whole archive](https://github.com/maaaaz/patator-windows/archive/master.zip)
2. Extract it and run `patator-windows.exe`. Note that the loading is a bit long as the resources have to be unbundled prior to execution
3. Profit


Older versions
--------------
* Browse the [release section](https://github.com/maaaaz/patator-windows/releases) to find some old versions


Disclaimer & licence 
---------------------
* Do not use it for illegal purposes
* I don't own anything on the patator brand or project
* Last but not least, antivirus softwares might report some binaries as hacktools or even malwares: this is a known and common issue. If you don't trust this compilation: 
  1. Just don't download it.
  2. Compile it yourself.


Credits
-------
* [lanjelot](https://github.com/lanjelot) for his awesome [patator tool](https://github.com/lanjelot/patator)