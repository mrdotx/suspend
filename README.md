# suspend systemd service

service to lock the screen before sleep

## installation

- copy file suspend@.service to /etc/systemd/system

## enable service

- systemctl enable suspend@[username]

## check after reboot

- systemctl status suspend@[username]
