# sensible-algo-blocklist
A sensible blocklist for the Algo VPN project.

## What is Algo?

Algo VPN is a set of Ansible scripts that simplify the setup of a personal IPSEC VPN. It uses the most secure defaults available, works with common cloud providers, and does not require client software on most devices. See the Github project here: https://github.com/trailofbits/algo

## What is the Sensible Algo blocklist?

A DNS blocklist is unique in that it it shouldn't be overly restrictive. For example, clicking through a deal on a website should work without issue. \

This list consists mainly of the default Algo blocklists - slowly curated to whitelist URLs that shouldn't be blocked on a DNS system.

To use this list, it is recommended to delete the default blocklists in config.cfg and replace it with this list.

## Can I request an addition to the whitelist?

Yes. Please file a Github ticket.
