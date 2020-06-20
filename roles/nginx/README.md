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

| name                 | default | description                                     |
|                      |         |                                                 |
|----------------------|---------|-------------------------------------------------|
| cloudflare_protected | no      | only serve through Cloudflare                   |
| nginx_latest_ppa     | no      | configure nginx ppa to get more recent versions |
