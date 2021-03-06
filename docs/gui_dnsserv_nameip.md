---
Slug: dns-server-properties-dialog-server-name-ip
Keywords: DNS server properties,Server name / IP
---
# DNS server properties dialog - Server name / IP

In this section of the DNS server properties dialog, you specify the host name or IP address of the this DNS server:

![](https://jhsoftware.dk/is/f1299f6b7124.png)

Note: DNS updates can generally only be performed against the primary DNS server(s) for a DNS zone.

To ensure that DNS can always be updated (with any one of the DNS servers unavailable), you must configure the DNS zone as primary on all DNS servers.

This also means that you will have to keep the DNS servers synchronized manually by always making all zone/record updates on both servers.

Alternatively, you can use the option in Simple Failover to serve DNS requests directly - see [Options dialog / DNS serving section](gui_opt_dnsserving.md).
