# Disable multicast DNS

Multicast DNS is part of ZeroConf / Apple Bonjour standard; the mdnsd daemon sends discovery packets to the local multicast group and (on some devicesat least) also to internet addresses.

To avoid leaks, this module replaces the service definition in order not to start the daemon at all.
