# InstallDriverTL722N


## Update Repository
```
$ sudo apt update
```

##  Upgrade
```
$ sudo apt upgrade
```

## Install dependecies

```
$ sudo apt install dkms bc make libglvnd-dev
```

```
$ sudo apt install linux-headers-$(uname -r)
```

## Git Clone
[GIT rtl8188eus](https://github.com/drygdryg/rtl8188eus.git)
```
$ git clone https://github.com/drygdryg/rtl8188eus.git
```
## Acesse o Git
```
$ cd rtl8188eus.git
```
## Acess root
```
$ sudo -i
```

## 
```
# echo "blacklist r8188eu" > "/etc/modprobe.d/realtek.conf"
# exit
```

```
$ sudo ./dkms-install.sh
```

```
$ reboot
```