# cloudflare_dns_proxy [![Build Status](https://drone.jonnrb.com/api/badges/jon/cloudflare_dns_proxy/status.svg?branch=master)](https://drone.jonnrb.com/jon/cloudflare_dns_proxy)

Uses `cloudflared` to open a DNS-over-HTTPS proxy to `1.1.1.1`.

Designed to be stupid simple by being stupid simple.

## Deets

OK, so you want some of this secure DNS everyone's talking about. There are
two big options if you want privacy:

 1. DNS-over-TLS, which has an [RFC](https://tools.ietf.org/html/rfc7858), and
 2. DNS-over-HTTPS.
