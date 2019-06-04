# ansible-routinator
Ansible role installing [Routinator](https://github.com/NLnetLabs/routinator) and keep track of the daemon via systemd.
Currently tested on Ubuntu 18.04 only!

## Variables
```
routinator_path: /opt/routinator
routinator_listener_tcp:
  - "127.0.0.1:3323"
  - "[::1]:3323"
routinator_listener_http:
  - "127.0.0.1:9556"
- "[::1]:9556"
```
