# NeoNetwork
### A useless VPN network ready for peering!

Pull requests are welcomed!  
[Telegram Group](https://t.me/NeoNetworkVPN)

## Peers:
* caasih.nerdpol.ovh (10.127.0.1, AS: 4201048576)
* ucbvax.nerdpol.ovh (10.127.0.2, AS: 4201048576)

# IP Addresses
All IPv4 addresses are under the range 10.127.0.0/16,
see routes.txt for allocated domain.

# DNS
There's a bind9 server on NeoPDP-11 (10.127.1.1), all domain names are under "neonetwork.unix".

# Connection Graph
![NeoNetwork Nodes](https://gitlab.com/Neo_Chen/NeoNetwork/raw/master/nodes.png)

# Files:
	asn.txt:	BGP AS number allocation
	named.conf:	Bind9 DNS configuration example
	nodes.dot:	connection graph
	tinc.conf:	Tinc configuration example
	routes.txt:	network address allocation