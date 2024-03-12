# `whois <name>`

A domain name translates into an IP address so that we don't need to remember it (e.g. you can type tryhackme.com, rather than the TryHackMe IP address).
Domains are leased out by companies called Domain Registrars.
If you want a domain, you go and register with a registrar, then lease the domain for a certain length of time. 

`whois` essentially allows you to query who a domain name is registered to.
In Europe personal details are redacted; however, elsewhere you can potentially get a great deal of information from a `whois` query.

There is a web version of the `whois` tool if you're particularly averse to the command line.

(Note: You may need to install `whois` before using it. Refer to your distribution documentation)

Use `whois <name>` to get a list of available information about the domain registration:

![Performing a whois lookup on bbc.co.uk](https://github.com/vinni3th3d4/CTF/assets/157951678/081c3ba7-61be-4038-9f05-e607f06ddd67)

This is comparatively a very small amount of information as can often be found.
Notice that we've got the domain name, the company that registered the domain, the last renewal, and when it's next due, and a bunch of information about nameservers.
