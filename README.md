# systemd templates

## Installation

Step 1: Add `name.service` to `/etc/systemd/system/`

Step 2: Start this service by typing:
```
    systemctl daemon-reload
    systemctl enable name.service
    systemctl start name.service
```
