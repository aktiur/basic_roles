# Common

This role check Ubuntu release, install essential packages, basic settings, and import
nginx, letsencrypt and ssmtp roles.

## Summary

* upgrade system to latest packages versions
* install utils used by other roles like git, pip, build-essential...
* add github pubkey to ssh known hosts
* install fail2ban and add a conf for nginx
* ensure journald keeps
* install and enable ufw, with a special tweak to allow network block devices
* install various diagnostic commands so you have it in case of emergency (htop, nmap...)
* run nginx letsencrypt and ssmtp roles, unless `--skip-tags rolename`

## Variables

|name|default|description|
|---|---|---|
|cloudflare_protected|no|if yes, remove fail2ban instead of installing
