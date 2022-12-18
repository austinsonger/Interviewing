# What are the steps in a DNS lookup?

1. Resolving: The DNS client sends a query to the DNS server, asking it to translate a domain name into an IP address.
2. Querying Root Nameservers: The DNS server then contacts a root nameserver to find out which Top Level Domain (TLD) nameserver is responsible for the domain name.
3. Querying TLD Nameservers: The root nameserver then responds with the address of the TLD nameserver responsible for the domain name. The DNS server then contacts the TLD nameserver.
4. Querying Authoritative Nameservers: The TLD nameserver then responds with the address of the authoritative nameserver responsible for the domain name. The DNS server then contacts the authoritative nameserver.
5. Responding: The authoritative nameserver responds with the IP address requested. The DNS server then passes on the IP address to the DNS client.
