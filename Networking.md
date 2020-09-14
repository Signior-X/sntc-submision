## Question 1

## Question 2

Using the whois command, I found where the domain belongs and also using the website whois.domaintools.com
```
whois iitmandi.ac.in
```

It belongs to **ERNET India** wihth IANA ID 800068, URL: http://www.ernet.in
Name servers
- NS1.IITMANDI.NET.IN (has 1 domains)
- NS2.IITMANDI.NET.IN (has 1 domains)

## Question 3

I used the Ubuntu system to install the nmap command.
```
nmap -p 1-2000 iitmandi.co.in | grep open
```

The open sockets are 4
```
22/tcp   open     ssh
53/tcp   open     domain
80/tcp   open     http
443/tcp  open     https
```
