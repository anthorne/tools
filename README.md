# tools
List of useful tools for random security, CTF stuff. An attempt to keep track of some useful tools I stumble upon along the way.


## Other collections!
* https://book.hacktricks.xyz/
* https://0xalwayslucky.gitbook.io/cybersecstack/


## Security frameworks and resources
* [Mitre ATT&CK](https://attack.mitre.org/)
* [OWASP](https://owasp.org/www-project-top-ten/)
* [OSINT Framework](https://osintframework.com/) (Gathering information from free tools or resources)


## Reconnaissance
### Web
* Online tools
  * [Domaintools Whois](https://whois.domaintools.com) (Whois lookups for domains)
	
* Programs
  * dirbuster (Look for subdomains)
  * Postman (API tool)
  * Burp Suite

### Port scanning
* nmap _(Active port scanning tool)_
* [Shodan.io](https://www.shodan.io/) _(Search engine of Internet-connected devices - Passive port scanning tool)_


## OSINT
_Tools for Open Source Intelligence_

### Images
* Online tools
  * https://www.remove.bg/ (Removing backgrounds in images)
  * https://cleanup.pictures/ (Remove details in images)
  * https://29a.ch/photo-forensics (Forensically image tool for checking images and access Exif info)
  * https://pimeyes.com/ (Face Search Engine Reverse Image Serach)
	
* Programs
  * exiftool (get Exif information from images)

### Connected devices and services
* [Shodan.io](https://www.shodan.io/) (Search engine of Internet-connected devices) - _TODO: Consider not having duplicates_

### Websites
* [Wayback Machine](https://web.archive.org/) (Explore more than 702 billion web pages saved over time)
* [_IntelligenceX](https://intelx.io/) (Search engine for leaked information)
* [OCCRP Research databases](https://id.occrp.org/databases/) (Collection of public data sources for investigative reporting)

### E-mails
* https://hunter.io/search (Search for e-mail addresses and patterns by domain name)
* https://phonebook.cz/ (Phonebook lists all domains, email addresses, or URLs for the given input domain.)
* Clearbit Connect (Google Chrome addon - Search for people in companies)
* https://tools.verifyemailaddress.io (Email address verification technology from Email Hippo that connects to mailboxes and checks wether an email address exists.)
* https://email-checker.net/ (Email address verification tool)

### Usernames
* https://whatsmyname.app (Enumerate usernames across many websites)
* https://namechk.com/ (Username availability lookup)
* https://namecheckup.com/ (Find Available Username)

### Passwords
* https://haveibeenpwned.com (Check if your email or phone is in a data breach)
* https://dehashed.com (Resource with compromised passwords from leaks - Paid subscription only)
* https://hashes.org (Tool for check-up hashes)
* https://scylla.so/ (Providing free access to the world's largest breach dataset) - _Will be comming up soon?_

### People
* https://webmii.com/ (Webmii seaches for public information available on the web.)
* https://www.infobel.com

### Phone
* https://truecaller.com

### Social media
#### Discord
* https://hugo.moe/discord/discord-id-creation-date.html (Discord Creation Date Check - Using your Discord ID, check when your account, server, message or channel got created!)


## Forensics
* https://github.com/skelsec/pypykatz (mimikatz implementation in Python)


## Steganography
### Image files
* Online tools
  * https://stylesuxx.github.io/steganography/ (Online tool for encoding and decoding messages in images)
  * https://stegonline.georgeom.net/image (Online Image Steganography Tool for Embedding and Extracting data through LSB techniques)

* Programs
  * binwalk (hide files within images)
  * StegSolve 1.3 (Image analysis tool)
  * StegSolve (https://github.com/eugenekolo/sec-tools/tree/master/stego/stegsolve/stegsolve)

### Audio files
* Programs
  * Audacity (Useful tool for audio files - Spectrum analyzer can be used to check for hidden messages)

### Video files
#### Matroska
* mkvinfo (Get info from Matroska files .mkv, might be hidden audio- and video tracks)
* mkvextract (Tool for extracting individual tracks from Matroska files .mkv)


## Cryptography
### RSA
* https://github.com/Ganapati/RsaCtfTool (RSA attack tool - uncipher data from weak public key and try to recover private key Automatic selection of best attack for the given public key)


## SQL-Injections
* https://portswigger.net/web-security/sql-injection/cheat-sheet (Cheat Sheet)


## Network
* Wireshark (Analyze recorded network traffic PCAP-files)
* netcat


## Other tools
* Online tools
  * [CyberChef](https://gchq.github.io/CyberChef/) (The Cyber Swiss Army Knife - a web app for encryption, encoding, compression and data analysis)
  * https://geojson.io/ (Online tool for viewing GeoJSON)

* https://asciinema.org/ (Record and share your terminal sessions, the simple way.)
