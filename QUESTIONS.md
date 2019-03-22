# 把想問的問題集中在這邊吧！
> i386™ 是什麼？
> 32bit 、64bit 是指位元，但是他的影響到底是什麼？

把幾個問題集中在這邊一起回答

以下為同義詞:
32 bit = i386 = x86
64 bit = amd64 = x86_64

簡單來說, 32 or 64 bit 指的是 CPU 內的暫存器 (register) 大小
可以想成 CPU 裡面有一格一格的暫存器 (記憶體空間), 每一格是 32 bits 大或者 64 bits 大這樣
差別有很多, 像是 64 bit 通常跑的比 32 bit 快之類的
不過最常拿來講的是支援的 RAM (記憶體) 大小
32 bit => 2^32 bit = 4,294,967,295 bit, 大約在 4 GB 左右
基本上如果你用 32 bit 版的 Windows (對, windows 也有分 32 bit 跟 64 bit 版)
你的電腦最多可用的記憶體大概就在 4 GB (通常大概顯示 3.5 或 3.8 吧好像), 就算你插了 16 GB 在上面也一樣

順帶一提, i386(Intel 386) 或者 amd64 雖然是廠牌名字沒錯 (Intel & AMD)
不過是紀念性質 (第一個 32 bit 是 Intel 做的, 第一個 64 bit 是 AMD 做的這種感覺)
不代表 Intel CPU 一定要用 i386 或者 AMD CPU 一定要用 amd64
基本上都是通用的

現在的 CPU 都是 64 bit 的, 所以大家就直接裝 amd64 版就好囉

> PAE 是什麼?

PAE 指的是實體位址擴充
前面提到 32 bit 記憶體位址只能用到 4 GB
這個就是用來突破這件事情的

PAE: https://en.wikipedia.org/wiki/Physical_Address_Extension

> ARM, MIPS是啥？

這些都是處理器內的指令集 (instruction set) 的名稱, 簡單說就是 CPU 內怎麼執行東西的
主要分成兩種: CISC 跟 RISC
CISC 的話最主要就是 x86 系列
RISC 的話 ARM 跟 MIPS 都算是
ARM 的話現在算是佔有率最高的, 幾乎所有手機都是 ARM 晶片
MIPS 的話我想不到 XD 大型工作站吧

剩下自己看 wiki 囉 XD
ARM: https://en.wikipedia.org/wiki/ARM_architecture
MIPS: https://en.wikipedia.org/wiki/MIPS_architecture

> PCI 是什麼？

PCI 是電腦裡面的匯流排, 你拆開電腦就會看到了, 長這樣
PCI: https://en.wikipedia.org/wiki/Conventional_PCI

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

> sysutils, devcpu-data 是啥？

sysutils 是 FreeBSD ports 裡面的一個分類, 主要放一些跟系統功能有關的 ports
devcpu-data 就是裡面的一個 ports

sysutils/devcpu-data: https://www.freshports.org/sysutils/devcpu-data/



fried system 、 following non-sleepable locks held 、 lock order reversal是甚麼?
