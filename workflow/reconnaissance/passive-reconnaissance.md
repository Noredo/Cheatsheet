# Passive reconnaissance

#### whois

The "whois" command is a command-line tool that allows you to query public databases for information about domain names, IP addresses, and organizations associated with these Internet resources.

It is possible to collect information such as the name of the holder of the domain, the postal address, the telephone number and the e-mail address. The whois command can also be used to obtain information about the registration of an IP address, such as the name of the Internet service provider and the associated technical contacts.

```sh
whois <domain.com>
```

#### nslookup

The "nslookup" command (short for "name server lookup") is a command-line tool that performs Domain Name System (DNS) lookups for information about domain names, IP addresses, and records DNS associated with a specific domain address.

It is possible to resolve domain names to IP addresses and vice versa. It is also possible to query DNS records such as type A records (IP address), type MX records (mail servers), type CNAME records (domain name alias) and many more .

```sh
nslookup <domain.com>
```

#### dig

The "dig" command (short for "domain information groper") is a command-line tool that performs Domain Name System (DNS) queries for information about domain names, IP addresses, and registrations DNS associated with a specific domain address.

It is possible to obtain information about the configuration and topology of a network, as well as about the mail servers and other services associated with a specific domain.

#### traceroute

The "traceroute" command is a command-line tool that tracks the path taken by data packets through an Internet Protocol (IP) network. This command sends data packets to a destination IP address and displays the names and IP addresses of intermediate routers the data packets pass through to reach their destination.

