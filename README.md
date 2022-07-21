# emacs-as-daemon-systemd
Personal modification of emacs systemd user module: When emacs config gets huge, running it as a service works much better for me.

To use:
1. Download file
2. Copy emacs.service to:
   /usr/lib/systemd/emacs.service
   
```
systemctl enable --user emacs
systemctl start --user emacs
```

From here, run emacsclient. Emacs, by default, comes with this desktop entry. I've added the following line to my i3 config to launch via keybinds:

```
bindsym $mod+Shift+w exec emacsclient -c
```
