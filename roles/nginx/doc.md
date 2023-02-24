# Nginx

This role install and configure Nginx.

## Summary

* install nginx and nginx-extras
* setup secure defaults for SSL
* ensure fastcgi_params, proxy_params and uwsgi_params are present (they should
already be there on standard Ubuntu)
* install goaccess log analysis tool
* creates log formats used by other roles
* open port 80 and 443 on UFW

## Variables

|name|default|description|
|---|---|---|
|cloudflare_protected|no|if yes : open firewall to Cloudflare only, and configure Nginx to use client IP provided by Cloudflare headers
|nginx_latest_ppa|no|if yes, use Nginx official PPA rather than distribution version (use with caution)
