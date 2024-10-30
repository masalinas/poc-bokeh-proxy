# Description
PoC Bokeh Proxy using HAProxy

## Execute using a proxy
```
docker run -d --name poc-proxy -u root -p 80:80 --volume ${PWD}/haproxy.cfg:/usr/local/etc/haproxy/haproxy.cfg --network host haproxy:3.0-alpine
```