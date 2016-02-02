# lv_LV
Latvian locale for Mac OS X

# Installation

1. Open up terminal
2. Go to downloaded lv_LV directory
3. Run:

```
sudo ./install.sh
```

or just

```
sudo cp -R lv_LV.UTF-8 /usr/share/locale/
```

# System Integrity Protection

Some newer systems like El Capitan (10.11) have this protection model that forbids even a root user to make chahnges in OS file-system directories. This also relates to /usr/share/locale/ directory and you can have "Operation not permitted" errors while copying files.

To overcome this issue, disable [System Integrity Protection](https://developer.apple.com/library/mac/documentation/Security/Conceptual/System_Integrity_Protection_Guide/ConfiguringSystemIntegrityProtection/ConfiguringSystemIntegrityProtection.html)
