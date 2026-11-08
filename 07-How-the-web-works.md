# How The Web Works

**Module:** [How The Web Works]
**Completed:** November 2026

## Room: [DNS in Detail](https://tryhackme.com/room/dnsindetail)
The "how does a name become an address" room. Your browser types google.com, but the computer doesn't know what that means until DNS translates it to an IP. Also learned the internet hierarchy within domain names aka URLs. (Top Level Domain, Second Level Domain, Subdomain)

## Room: [HTTP in Detail](https://tryhackme.com/room/httpindetail)
What actually happens between "I clicked the link" and "the page loaded." Requests, responses, status codes, and why your coffee order (see cafe bot) is technically an HTTP request.

## What Tripped Me Up
The "what happens when I make a DNS request" part confused me at first. I kept overthinking the root to TLD to authoritative chain and it just didn't click. Once it did, it was basically just your computer remembering what you've visited (the recursive server, usually from your ISP). The root server is the reception desk pointing you to the right department. The authoritative server is the one that actually has the answer, and the TTL is how long your computer keeps that memory before it expires.

## What I Learned
1. TLD (Top Level Domain) is on the right-hand part of a domain name like ".com".
2. There are two types of TLD. That's gTLD (Generic Top Level Domain) and ccTLD (Country Code Top Level Domain).
3. A gTLD is there to tell the user the domain's purpose (ex: ".com" is commercial).
4. A ccTLD is used for geographical purposes (ex: ".ca" means it's based in Canada)
5. Second Level Domain is the name you give your domain and gives it a personality ("tryhackme.com" it's the TryHackMe part).
6. Subdomain is the left-hand side of a Second Level Domain, separated by a period. (ex: www.tryhackme.com it's the "www." part)
7. DNS is more versatile than I thought. It can be used as an A Record, AAAA Record, CNAME Record, MX Record, and TXT Record. So many records!
8. A = sends a domain to an IPv4 address, AAAA = same thing but for IPv6, CNAME = sends a domain to another domain (an alias), MX = tells email where to go, and TXT = stores text, mostly for verification (like "this domain is owned by twinkletoes").

