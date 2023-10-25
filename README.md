# Plymouth Cat

![cat](cat/progress-0.png)

## Install theme

```shell
git clone https://github.com/axolotl13/cat.git /tmp/cat
cd /tmp
mv cat /usr/share/plymouth/themes
``` 

## Changing the theme

The theme can be changed editing the configuration file:

```shell
/etc/plymouth/plymouthd.conf
[Daemon]
Theme=cat
```

or by this command:

```shell
plymouth-set-default-theme -R cat
```
