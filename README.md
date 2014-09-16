# CoAP Testserver

This Dockerfile starts a CoAP plugtest testserver using Californium from
<a href="https://github.com/mkovatsc/Californium/">Matthias Kovatsch</a>.

# Usage

```
docker run -p 5683:5683/udp jdede/coap-testserver
```

starts the server. You can access the server: coap://127.0.0.1
