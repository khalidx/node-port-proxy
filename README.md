# node-port-proxy
A quick, simple node script that proxies from one port to another.

Useful for local development or on platforms like [Cloud9](https://c9.io) where the only ports that are open are 8080, 8081, and 8082.

All credit for this script goes to this awesome [StackOverflow answer](http://stackoverflow.com/a/19637388).

Usage:

`node proxy.js <port> <target-port>`

Example (proxy from port 8000 -> 8080 on localhost):

`node proxy.js 8000 8080`

Example (proxy from port 9000 -> 80 on another host):

`node proxy.js 9000 otherhost:80`
