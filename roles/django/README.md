# Django

Deploy Django projects. This role has many
configuration options by default.

## Summary

* clone projects repositories
* configure uwsgi services
* configure celery services if any
* configure Nginx server blocks
* use [virtualenv](../virtualenv/doc.md) role to install
dependencies and setup env variables
* install utility commands `{{ app_name }}-shell`
and `{{ app_name }}-manage` to launch scripts without
having to deal manually with virtualenv

## Variables

This roles have a few required variables.
See [default variables](defaults/main.yml).
