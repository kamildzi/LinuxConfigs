# About
This repository contains GNU/Linux configuration files that I use in my systems.

# Contents and features
1. [Bashrc](etc/bash.bashrc) - Bash configuration
- Auto-complete enabled
- Output coloring enabled if supported (Long time ago I copied it from one of my Gentoo systems. I cannot spot the original author at this point but thank you!)
- Pre-set history settings (`HISTSIZE`, `HISTTIMEFORMAT`)
- `EDITOR` preset to nano
##### Quick install cmd
```bash
cd /etc/
mv bash.bashrc bash.bashrc.old && wget https://raw.githubusercontent.com/kamildzi/LinuxConfigs/master/etc/bash.bashrc
```
