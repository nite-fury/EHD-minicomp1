# Tools Cheat Sheet

## BurpeSuite

[Burp-Suite-Cheat-Sheet.pdf](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/Burp-Suite-Cheat-Sheet.pdf)

[Burp-Suite-Cheat-Sheet.pdf](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/Burp-Suite-Cheat-Sheet%201.pdf)

## EXIF Tool

[https://exif.tools/](https://exif.tools/)

## HXD

[File Signatures.html](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/File_Signatures.html)

[File Signatures.html](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/File_Signatures%201.html)

## General

[imousrf_enumeration.bw.pdf](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/imousrf_enumeration.bw.pdf)

[https://www.kali.org/tools/](https://www.kali.org/tools/)

[imousrf_enumeration.bw.pdf](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/imousrf_enumeration.bw%201.pdf)

## John The Ripper

[Untitled.pdf](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/Untitled.pdf)

[Untitled](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/Untitled%201.pdf)

## Nmap

[nmap_cheet_sheet_v7 (1).pdf](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/nmap_cheet_sheet_v7_(1).pdf)

[nmap_cheet_sheet_v7.pdf](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/nmap_cheet_sheet_v7.pdf)

## Fping

[heymensh_pentest-command-tools-gpen-based.bw.pdf](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/heymensh_pentest-command-tools-gpen-based.bw.pdf)

[heymensh_pentest-command-tools-gpen-based.bw.pdf](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/heymensh_pentest-command-tools-gpen-based.bw%201.pdf)

## Hping3

[hping3_cheatsheet_v1.0-ENG.pdf](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/hping3_cheatsheet_v1.0-ENG.pdf)

[hping3_cheatsheet_v1.0-ENG.pdf](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/hping3_cheatsheet_v1.0-ENG%201.pdf)

## Advanced Web Searches (Google Dorking)

- Google allows different forms of advanced searches
- Examples
    - To find a certain word or file on a website
        
        <aside>
        <img src="https://www.notion.so/icons/command-line_gray.svg" alt="https://www.notion.so/icons/command-line_gray.svg" width="40px" /> Eg: site:*sitename* *keyword*
        
        </aside>
        
    - To find certain filetypes containing keywords
        
        <aside>
        <img src="https://www.notion.so/icons/command-line_gray.svg" alt="https://www.notion.so/icons/command-line_gray.svg" width="40px" /> Eg: filetype:*filetype* site:*sitename* *keyword*
        
        </aside>
        
    - To find webpages with a certain string in its URL
        
        <aside>
        <img src="https://www.notion.so/icons/command-line_gray.svg" alt="https://www.notion.so/icons/command-line_gray.svg" width="40px" /> Eg: inurl:*string* site:*sitename*
        
        </aside>
        
    - To find webpages with a certain string anywhere in
        
        <aside>
        <img src="https://www.notion.so/icons/command-line_gray.svg" alt="https://www.notion.so/icons/command-line_gray.svg" width="40px" /> Eg: intext:*string* site:*sitename*
        
        </aside>
        
        [Google Advanced Search](https://www.google.com/advanced_search)
        
    
    [Google Search Operators - Google Guide](http://www.googleguide.com/advanced_operators_reference.html)
    

## WHOIS

- Domain names are registered with NICs (Network Information Centre)
- Regional Internet Registries handle IP allocation
    - American Registry for Internet Numbers (ARIN)
    - Asia-Pacific Network Information Centre (APNIC)
- WHOIS databases allow queries on who owns a domain, contact information, IP range, etc.

<aside>
<img src="https://www.notion.so/icons/link_gray.svg" alt="https://www.notion.so/icons/link_gray.svg" width="40px" /> [www.whois.com/whois/*domainname* or *ip address*](http://www.whois.com/whois/)

</aside>

## Analyzing a Company’s Web Site

- Web pages are an easy source of information, eg. preferred web technologies, type of OS, webserver, etc
- Simplest tool is browser
- View source — sometimes useful information can be found in comments

![Untitled](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/Untitled.png)

## Finding information about connected devices

- Shodan
    
    <aside>
    <img src="https://www.notion.so/icons/link_gray.svg" alt="https://www.notion.so/icons/link_gray.svg" width="40px" /> [www.shodan.io](http://www.shodan.io)
    
    </aside>
    
- Search engine for online devices

## DNS

- Resolves host names to IP addresses
- People prefer using URLs to IP addresses
- Can be vulnerable to attacks
- DNS query tools
    - nslookup (windows)
    - dig (linux)
    - host (linux)
    - whois (linux/windows/web)
    - [www.whois.com](http://www.whois.com)
    - [spiderfoot](https://github.com/smicallef/spiderfoot)
    - [www.dnsstuff.com](https://www.dnsstuff.com/)
    - [www.mxtoolbox.com](http://www.mxtoolbox.com) (for email)

## DNS zone transfers

- Determining company’s primary DNS server
    - Look for the Start of Authority (SOA) record
    - Shows zones or IP addresses
- Zone transfer
    - Enables you to see all hosts on a network
    - Gives you organization’s network diagram

## Traceroute/tracert

- used to trace route of packets from the source to the destination
- may be used to find out the gateways/routers used by the target
- uses ICMP (windows) or UDP (linux)
- TTL values is used to trace the route
- However, routers may block the packets from a traceroute
- Perform traceroute from different countries
    - use online traceroute tool
    - [https://traceroute-online.com/](https://traceroute-online.com/)
    

## Analyzing a company’s website

- tools like intercepting proxies can be used
    - Paros
    - Webscarab
    - BurpSuite
- Developer Tools feature on web browsers (press F12)

## Copying who websites

- Tools are available to copy the whole website
- The pages of the website can then be inspected and analyzed offline
    - HTTrack Website Copier ([www.httrack.com](http://www.httrack.com))

## HTTP basics

- HTTP on port 80
- use HTTP language to pull information from a web server
- Basic understanding of HTTP is beneficial for security testers
- Return code
    - May reveal information about system
- HTTP methods
    - GET / HTTP/1.1 is the most basic method
    - May be able to determine information about the web server from the server’s http response packet

![Untitled](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/Untitled%201.png)

## HTTP headers

- Every HTTP packet (request, response) contains a set of header fields
- HTTP headers may contain information on
    - Web browser of the client making the request
    - Operating system of the client
    - Web server returning the response
    - Cookies

## Social Engineering

- Using knowledge of human nature to get information from other people
    - Example: Attacker poses as IT helpdesk and calls unsuspecting staff to get information about the company network
- Can be the biggest security threat to networks
- Most difficult to protect against

### Techniques of Social Engineering

- Urgency
    - “I need the information now or the project will fail!”
- Help with problems
    - “I can solve your Internet connection speed problem if you can tell me ..”
- Everyone else is doing it
    - “John has already given me is account information so …”
- Kindness and charm
- Authority
    - “The Director needs this information now!”

### Shoulder Surfing

- Look at what the user is entering on the keyboard, especially usernames and passwords
- Shoulder surfers may stand behind people at the ATMs to see the PINs being entered
- Use of camera phone to take photo and videos increase this threat

### Dumpster Diving

- Going through the trash
- Lots of valuable information can be found
    - Discarded windows CP manuals — the company has upgraded their Windows OS?
    - Company organizational charts
    - Printouts of emails
    - Discarded hard disks, USB drives — deleted data may still be retrieved from them
- Documents should be shredded
- Use disk-cleaning software to wipe out all data before discarding disk (DBAN)

### Piggybacking

- Trailing authorized staff closely to enter restricted areas
- Many carry a fake staff card or badge and rely on the kindness of people to hold the door open for them
- Many carry big boxes and rely on people to open secured doors for them

### Phishing

- Phishing emails are urgent emails that seem to be from legitimate companies asking you to click on a link to provide information
- The link usually leads to the attacker’s website
- Spear phishing
    - Send to specific people in an organization
- Smishing
    - Sending of sms with phishing links
- Vishing
    - calling of victims’ to collect information
    

## Viewing of Email Headers

- Header contain valuable information about the sender
    - Unique identifying numbers, IP address of sending server, and sending time
    - [https://www.arclab.com/en/kb/email/how-to-read-and-analyze-the-email-header-fields-spf-dkim.html](https://www.arclab.com/en/kb/email/how-to-read-and-analyze-the-email-header-fields-spf-dkim.html)
- Information to look out for
    - Return path
    - recipient’s the e-mail address
    - Type of sending e-mail service
    - IP address of sending server
    - Name of the e-mail server
    - Unique message number
    - Date and time e-mail was sent
    - Attachment files information
- Use whois or other databases to find out true source of email

## OSCP guide (all in one)

[1648761582305.pdf](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/1648761582305.pdf)

[1648761582305.pdf](Tools%20Cheat%20Sheet%20bb22d60d155c4f2eba4b8dc646ac55e5/1648761582305%201.pdf)