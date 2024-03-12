# `traceroute`

The logical follow-up to the `ping` command is `traceroute`.
`traceroute` can be used to map the path your request takes as it heads to the target machine.

The internet is made up of many, many different servers and end-points, all networked up to each other.
This means that, in order to get to the content you actually want, you first need to go through a bunch of other servers.
`traceroute` allows you to see each of these connections -- it allows you to see every intermediate step between your computer and the resource that you requested.
The basic syntax for traceroute on Linux is this: `traceroute <host>`

By default, the Windows `traceroute` utility (tracert) operates using the same ICMP protocol that ping utilises, and the Unix equivalent operates over UDP.
This can be altered with switches in both instances.

![Performing a traceroute to Google.com](https://github.com/vinni3th3d4/CTF/assets/157951678/97c2d669-6ab7-48c7-b37c-fdc2efa27269)

You can see that it took 13 hops to get from my router (_gateway) to the Google server at 216.58.205.46

Also see: `man traceroute`

###### Source: [Introductory Networking](https://tryhackme.com/room/introtonetworking)
