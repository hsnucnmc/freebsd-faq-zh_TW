# 把想問的問題集中在這邊吧！
> i386™ , PCI, PAE 是什麼？

(待補)

> 32bit 、64bit 是指位元，但是他的影響到底是什麼？

(待補)

> beadm 是什麼？ bectl 是什麼？

beadm 跟 bectl 是用來管理 ZFS 開機環境的指令。
beadm man page: https://www.freebsd.org/cgi/man.cgi?query=beadm
bectl man page: https://www.freebsd.org/cgi/man.cgi?query=bectl

不知道 ZFS 是什麼的話, 在 handbook 的 Ch.19 The Z File System (ZFS) 有
https://www.freebsd.org/doc/handbook/zfs.html

順帶一提, backup 用的就是 ZFS, 可以花時間看看 :)

> GEOM 是什麼? geli 是什麼？

GEOM 是在 FreeBSD 5 之後提供的一種儲存裝置框架, 簡單說就是可以拿來做軟體 RAID 
handbook 的 Chapter 18. GEOM: Modular Disk Transformation Framework 介紹了怎麼用 GEOM 做軟體 RAID
https://www.freebsd.org/doc/handbook/geom.html

如果不知道 RAID 是什麼, 可以查一下 google, 大致上搞清楚 RAID 0,1,5,6,10 的差別就行 :)

geli 是幫 GEOM 做加密的工具
geli man page: https://www.freebsd.org/cgi/man.cgi?query=geli

handbook 的 Chapter 17.12 Encrypting Disk Partitions 中用了 gdbe 跟 geli 當範例, 可以參考一下
https://www.freebsd.org/doc/handbook/disks-encrypting.html

> UEFI 是什麼？

UEFI 算是比較新的 BIOS, 可以把它想成韌體 (Firmware) 的擴充

> ARM, MIPS是啥？

> sysutils, devcpu-data 是啥？
