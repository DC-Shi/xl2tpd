
This is an IPv6 version of xl2tpd.

The client and server are both communication with IPv6, but the internal communication protocol is still IPv4. Which means this is an IPv4-in-IPv6 tunnel.

The previous 'ipv6' branch used an old 1.2.8 version and cannot compile under some circumstances. This one is tested using Openwrt SDK Toolchain.

Due to different master versions, there are some other places need to be modified besides the patch below mentioned.

Source from : https://github.com/xelerance/xl2tpd	(branch ipv6)
patch from : http://blog.lifetoy.org/2009/vpn-over-ipv6


