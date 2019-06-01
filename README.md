# ansible-routinator
Ansible role installing [Routinator](https://github.com/NLnetLabs/routinator) and keep track of the daemon via systemd.

## Variables
```
routinator_path: /opt/routinator
routinator_listener_tcp:
  - "127.0.0.1:8282"
  - "[::1]:8282"
routinator_listener_http:
  - "127.0.0.1:8080"
  - "[::1]:8080"
```

