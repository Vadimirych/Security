|PORT|SERVICE| PROTOCOL | Top 20 NMAP | DESCRIPTION|
|---|---|---|---|---|
21 | FTP | | Y | File Transfer Protocol
22 | SSH | TCP | Y | Shell requires reliability
23 | TELNET | | Y | Telnet 
25 | SMTP | TCP | Y |Simple Mail Transfer Protocol, non-encrypted, used between Recipient and Sender servers
53 | DNS|| Y |Domain Name Services
80 | HTTP | TCP | Y |Hyper Text Transfer Protocol requires reliability
110 | POP3 | TCP | Y |Post Office Protocol 3, used to retrieve messages from Recipient's server by Recipient mail client
111 | RPCBIND | | Y | Remote Procedure 
135 | MSRPC | | Y | Microsoft RPC
139 | NetBIOS-SSN ||Y| NetBIOS-SSN
143 | IMAP | TCP | Y | The Internet Message Access Protocol (IMAP) is an incoming email protocol that allows email synchronization on multiple devices.
443 | HTTPS | | Y | Hyper-Text Transfer Protocol over TLS/SSL 
445 | MICROSOFT-DS | TCP | Y |direct TCP/IP MS Networking access without the need for a NetBIOS layer.
465 | SMTPs| TCP | |SMTP over TLS/SSL.This port was previously used for Secure SMTP (SMTPS). It has now been deprecated by the Internet Engineering Task Force (IETF), and its use is not recommended. However, some legacy email systems may still use Port 465 for SMTP with SSL/TLS encryption
587 | SMTPs | TCP | |SMTP over TLS/SSL. This port is typically used for email submission by mail clients (e.g., Outlook, Thunderbird) to a mail server. It is part of the standards defined in the Simple Mail Transfer Protocol (SMTP) for email transmission. Port 587 usually requires authentication and encryption, providing a secure connection for sending emails. It is commonly used for the submission of outgoing mail
993 | IMAPs | TCP | Y |IMAP over TLS/SSL
995 | POP3s | TCP | Y |POP3 over TLS/SSL
1723 | PPTP | | Y | PPTP
3306 | MySQL || Y|Default MySQL port
3389 | MS-WBT-SERVER | | Y | MS-WBT-SERVER
5900 | VNC || Y | VNC
5986 | WINRM || |windows remoute management protocol
5987 | WINRM || |Running via SSL
8080 | HTTP-proxy | | Y | HTTP Proxy
