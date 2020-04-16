# http over socks
This is a demo that setup a shadowsocks client locally and make a request over the socks. 
I used it to detect remote server status.

 `go run httpget.go -s 192.168.0.11 -p 3340 -k password -m aes-256-cfb  -nc 2 -nr 10   https://www.google.com/`
 
 ## Todo
 - [ ] refactor
 - [ ] add build action 
 
 ## Reference
 - https://github.com/shadowsocks/shadowsocks-go/blob/master/cmd/shadowsocks-httpget/httpget.go