# Root-Android

How to root android phones? This repo is all about how do I do it on my phone _(Oneplus 5)_.

Some important sites which are important for ROM Flashers:

1. Twrp.me
2. xda-developers.com


## Awesome commands which works on rooted device
```
pm uninstall -k --user 0 <package name>		//Will uninstall any app

getenforce					//To know Selinux policy

pm hide <package name>				//To hide app from launcher
```

### Reflash ROM original kernel
```
- Extract boot.imp from ROM zip
- Flash it on boot partition.
```
