# Domain names and protocols

* We use domains without `www.` only.
* www subdomain will be redirected to the root domain, even for websites with wilcard subdomains.
* In production we use HTTPS only.
* Any HTTP URL will be redirected to it's HTTPS version, preserving the path and query string.

### Examples:

:x: `http://www.example.com/page?id=5` will be redirected to:  
:heavy_check_mark: `https://example.com/page?id=5`
