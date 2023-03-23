# Exercise sheet 3

## Network Security

1. Investigate the network access control scheme used at your school or place of employment (if you work somewhere). Draw a diagram and describe the principal components. **This question has an aim to make you investigate and there is no uniform answer. You are strongly encouraged to ask our guest lecturer about our University access control.**

2. Explain DNS cache poisoning.
DNS cache poisoning is putting the wrong IP address for the DNS server cache, so when you want to go to google or wikipedia, you are not actually going to the correct one, instead, you might connect to a malware web server.
3. What is SamSam malware? How deos it work? What are the famous ransomware attacks in the UK?

4. Should I use DoH or DoT? Convince me!
DoH is running DNS over Https, while DoT is running DNS over TLS. DoH uses same port as HTTPS does(443), so DNS requests are cameflauged giving users more privacy, however, DoT uses TLS port, which is 853. 
*https://www.cloudflare.com/learning/dns/dns-over-tls/#:~:text=Which%20is%20better%2C%20DoT%20or,identifying%20and%20stopping%20malicious%20traffic.*
This is up for debate. From a network security standpoint, DoT is arguably better. It gives network administrators the ability to monitor and block DNS queries, which is important for identifying and stopping malicious traffic. DoH queries, meanwhile, are hidden in regular HTTPS traffic, meaning they cannot easily be blocked without blocking all other HTTPS traffic as well.
However, from a privacy perspective, DoH is arguably preferable. With DoH, DNS queries are hidden within the larger flow of HTTPS traffic. This gives network administrators less visibility but provides users with more privacy.
5. What is the purpose of HTTPS?
*A safe version of HTTP, HTTP has become decrepted*
6. What is the goal of the TCP session hijacker? How can we prevent it? 
Getting the session ID. 
7. For what applications is SSH useful?
For login and perfrom operations on remote computers, can also be used for transderring data.
8. What is the difference between SYN Flooding Attack and TCP session hijacking? Can we prevent them? How? 
SYN flooding attack is for amplifying messages, the hacker pretend to be victim and ping the servers, then the server respond with massive information causing a denial of serice at hte victim's end. We can prevent this by setting the server to not allow request if there are too many request from the person in a period. 
TCP session hijacking is typically a man in the middle 
10. Where does IPsec reside in a protocol stack?

11. What is DHCP? How useful is it to help achieve security of IP addresses?

12. How does ARP Spoofing facilitate MITM attack?  

13. Is Wireless networking more susceptible to eavesdropping and jamming than wired networks? Elaborate! Why/why not?

14. What was the largest DDoS attack of all time? Is it still the largest? Investigate! What are other famous DDoS attack? Can you explain how they were performed?

15. In IEEE 802.11, open system authentication simply consists of two communications. An authentication is requested by the client, which contains the station ID (typically the MAC address). This is followed by an authentication response from the AP/router containing a success or failure message. An example of when a failure may occur is if the client’s MAC address is explicitly excluded in the AP/router configuration.
a. What are the benefits of this authentication scheme?
b. What are the security vulnerabilities of this authentication scheme?
