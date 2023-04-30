Setup Syncthing on Kindle Touch
==========================

1. You need jailbreak and [KUAL](http://www.mobileread.com/forums/showthread.php?t=203326) first.
1. Download this [repository](https://github.com/gutenye/syncthing-kindle/archive/master.zip)
1. Download [syncthing-linux-arm 1.19.2](https://github.com/syncthing/syncthing/releases/tag/v1.19.2) and copy `syncthing` binary to `syncthing/bin/`  
    - (Using 1.19.2 possibly due to https://github.com/syncthing/syncthing/issues/8325)
1. Connect Kindle Touch to Your PC
1. Copy `syncthing/` to `KINDLE-ROOT/extensions/syncthing/`
1. Select "Open ALL Firewall ports" from KUAL
1. Select "Start Syncthing INSECURE Admin" from KUAL
1. Find out your Kindle IP address by type `;711` in search, then open `http://IP-ADDRESS:8080` in your browser. <br>
1. Configure all peers and folders
1. Ignore kindle auto generated index files: `*.sdr`
1. Select "Close INSECURE Admin port" from KUAL (Optional, for security reason)
1. Select "Stop Syncthing" and then "Start Syncthing" from KUAL
1. Note: connect kindle to computer or restart kindle will terminate syncthing process and firewall.
