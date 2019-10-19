Asterisk with Blacklist
=======================

Installs and configures Asterisk to block unwanted calls from Swiss call centers.

Requirements
------------

A netvoid SIP account is required

Role Variables
--------------

vars/main.yml:
```yaml
---
sip_connections:
  - number: [first number]
    username: [first un]
    secret: [first secret]
  - number: [second number]
    username: [second un]
    secret: [second secret]
```
Further Info
------------
[blacklist provider and author of the script to update asterisk blacklist](https://github.com/trick77/callcenter-blacklist-switzerland)
