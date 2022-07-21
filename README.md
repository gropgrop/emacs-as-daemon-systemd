# emacs-as-daemon-systemd
Personal modification of emacs systemd user module

To use:
1. Download file
2. Copy emacs.service to:
   /usr/lib/systemd/emacs.service
   
```
systemctl enable --user emacs
systemctl start --user emacs
```
