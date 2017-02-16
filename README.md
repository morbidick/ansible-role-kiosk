# Kiosk mode with X.org and Midori

[![Build Status](https://travis-ci.org/morbidick/ansible-role-kiosk.svg?branch=master)](https://travis-ci.org/morbidick/ansible-role-kiosk)

Ansible Role to autologin, start X-Server and the Midori browser in kiosk mode.

## Role Variables

```` yaml
kiosk_user: kiosk
kiosk_url: "http://example.net"
````

For more options see [defaults/main.yml](defaults/main.yml)
