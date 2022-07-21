# emacs-as-daemon-systemd
Quick and dirty emacs server systemd module

To use:
1. Clone Repository
2. Copy emacs.service to ~/.config/systemd/emacs.service
```
systemctl enable --user emacs
systemctl start --user emacs
```
Untested beyond user scope.
