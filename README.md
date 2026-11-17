# 1. Introduction
This report covers the task of Password Cracking with JTR and NetworkWalks tools. <br><br>
Password cracking is the process of recovering a password from stored data or a protected file. Security
professionals use it to test how strong a password is and to show why weak passwords are risky. If a
password is short or common, it can be found quickly, which proves the need for strong passwords.<br><br>
John the Ripper (JTR) is a popular password cracking tool used by security professionals to test how strong
passwords are. It started as a tool for Unix systems but now works on Windows, Linux, and Mac. It can
check many types of password hashes and also unlock password protected files like PDF, ZIP, and Office
documents. And, Johnny is the graphical version of John the Ripper.<br><br>
In case of tools from networkwalks, first I have used the Hash Calculator to take the hash out of a locked PDF file. Then, I've used the Password Cracker to find the real password from that hash. Both tools run in  web browser, so no need to install anything.


# 2. Tools Used
The table below lists each tool used in this report and its purpose.
| Tool | Purpose |
|---|---|
| Kali Linux & Windows | Operating systems used for recon activities             |
| whois                | Finds domain registration details (owner, dates, name servers).   |
| whatweb              | Fingerprints web technologies (server, CMS, plugins, IP).         |
| nslookup             | Resolves the domain name to its IP address using DNS.             |
| curl -I              | Reads the HTTP response headers of the website.                   |
| wafw00f              | Detects whether a Web Application Firewall protects the site.     |
| dnsrecon             | Enumerates all DNS records (NS, MX, SPF, TXT, SRV).               |
| Zenmap (Nmap GUI)    | Scans the local subnet to find live hosts, IPs and MAC addresses. |
| Windows CMD          | Local IP and MAC address identification                          |

# 3. Activities Performed
