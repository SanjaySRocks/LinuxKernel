# Linux Kernel

[![GitHub release](https://img.shields.io/badge/release-5.14.3-blue)](https://GitHub.com/SanjaySRocks/LinuxKernel/releases/)

#### A Low latency kernel for linux servers highly tweaked ( 1000HZ Boosted )

Simply install the kernel and reboot your server

#### Installation:-

```
$ dpkg -i linux-*.deb
$ update-grub
$ apt-get install tuned -y && tuned-adm profile latency-performance
```

```
$ reboot
```


#### For GameServers:-

Set Game Server Nice value to -19 or -20 for extra smoothness

Currently Supported OS
| linux        | version           | supported  |
| ------------- |:-------------:| -----:|
| Debian      | 10 | yes |
| Ubuntu      | 20.04      |   yes |
| Centos | any      |    no |


