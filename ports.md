|PORT|SERVICE| PROTOCOL | DESCRIPTION|
|---|---|---|---|
22 | SSH | TCP | Shell requires reliability
25 | SMTP | TCP | Simple Mail Transfer Protocol, non-encrypted, used between Recipient and Sender servers
53 | DNS|| Domain Name Services
80 | HTTP | TCP | Hyper Text Transfer Protocol requires reliability
110 | POP3 | TCP | Post Office Protocol 3, used to retrieve messages from Recipient's server by Recipient mail client
143 | IMAP | TCP | The Internet Message Access Protocol (IMAP) is an incoming email protocol that allows email synchronization on multiple devices.
445 | MICROSOFT-DS | TCP | direct TCP/IP MS Networking access without the need for a NetBIOS layer.
465 | SMTPs| TCP | SMTP over TLS/SSL.This port was previously used for Secure SMTP (SMTPS). It has now been deprecated by the Internet Engineering Task Force (IETF), and its use is not recommended. However, some legacy email systems may still use Port 465 for SMTP with SSL/TLS encryption
587 | SMTPs | TCP | SMTP over TLS/SSL. This port is typically used for email submission by mail clients (e.g., Outlook, Thunderbird) to a mail server. It is part of the standards defined in the Simple Mail Transfer Protocol (SMTP) for email transmission. Port 587 usually requires authentication and encryption, providing a secure connection for sending emails. It is commonly used for the submission of outgoing mail
993 | IMAPs | TCP | IMAP over TLS/SSL
995 | POP3s | TCP | POP3 over TLS/SSL
3306 | MySQL || Default MySQL port
5986 | WINRM || windows remoute management protocol
5987 | WINRM ||  Running via SSL
