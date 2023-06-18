# squid-proxy
This script installs and configures the squid package, which is a widely-used HTTP proxy server for Linux. It configures squid to listen on port 3128 and allows connections from any host on the local network. It also blocks connections to non-safe ports and limits the maximum refresh rate for cached content.

You can then use the VPS's IP address and port 3128 as the proxy server in your client software. For example, you can set the http_proxy and https_proxy environment variables to http://[VPS IP]:3128 to use the proxy for HTTP and HTTPS traffic.

# installation
```
curl -Ls raw.githubusercontent.com/hosh3iyah/squid-proxy/main/app.sh | bash
```
