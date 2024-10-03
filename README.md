# arkwall
generate nftables basic fw with IPv4 &amp; IPv6 GeoIP blocklists  

example:
```
./genft ru cn sg
```

# TODO
- [ ] Retrieve MX / A / AAAA dns entries to create a blocklist for one or more specific domains. ( e.g. block outgoing traffic to tiktok )
- [ ] Automatic copying of nftables.nft and the block lists to /etc/  
