HTTPS SSL
In this project, I've gained an understanding of the significance of HTTPS and its operation. I've successfully configured my HolbertonBnB web servers with certbot certificates and implemented HAproxy SSL termination.

Tasks 📃
0. World wide web

1-world_wide_web: A Bash script to display information about subdomains on my configured servers.
Usage: ./1-world_wide_web <domain> <subdomain>
Output: The subdomain [SUB_DOMAIN] is a [RECORD_TYPE] record and points to [DESTINATION]
If no subdomain parameter is passed, it will display information about the subdomains www, lb-01, web-01, and web-02 in that order.
2. HAproxy SSL termination

2-haproxy_ssl_termination: HAproxy configuration file configured to accept encrypted SSL traffic for the subdomain www. on TCP port 443.
3. No loophole in your website traffic

100-redirect_http_to_https: HAproxy configuration file designed to automatically redirect HTTP traffic to HTTPS.





