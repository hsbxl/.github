# Github is broken /o\

Hello everyone. Github is broken and has been for a while now ( [rfc2460](https://datatracker.ietf.org/doc/html/rfc2460) It only exists since 1998...).

````shell
dig -t AAAA github.com

;; OPT PSEUDOSECTION:
; EDNS: version: 0, flags:; udp: 1232
;; QUESTION SECTION:
;github.com.			IN	AAAA

;; AUTHORITY SECTION:
github.com.		444	IN	SOA	ns-1707.awsdns-21.co.uk. awsdns-hostmaster.amazon.com. 1 7200 900 1209600 86400
```


Based on that, we decided to migrate away from it. We will probably not maintain anything on this organisation. Anything up to date is a mirror of what you can find in our [gitlab](https://gitlab.com/hsbxl).

See you ;-)
