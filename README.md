[![](https://badge.imagelayers.io/bbania/odoo-nginx:latest.svg)](https://imagelayers.io/?images=bbania/odoo-nginx:latest 'Get your own badge on imagelayers.io')

# Nginx proxy for Odoo

This image is built to serve as a proxy for [Odoo](https://hub.docker.com/r/bbania/odoo-centos/) and to be deployed as a Marketplace installation on [Layershift Jelastic PaaS](https://app.j.layershift.co.uk) platform.

## Nginx version

Governed by `NGINX_VERSION` environment variable:

```
NGINX_VERSION 1.8.1-1.el7.ngx
```

## Base Docker image

[bbania/nginx:latest](https://hub.docker.com/r/bbania/nginx/)

# Installation

Log into your Layershift Jelastic [Dashboard Panel](https://app.j.layershift.co.uk) and search for *Odoo* in Marketplace.

