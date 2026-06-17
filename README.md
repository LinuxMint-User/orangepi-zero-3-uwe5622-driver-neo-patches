# orangepi-zero-3-uwe5622-driver-neo-patches
目前（20260617UTC+8）主线外的修改，让uwe5622正常工作的必要修改。

drivers目录直接复制合并即可，里面是sunxi-addr文件夹，是正确设置芯片MAC地址的必要模块  
0001号patch旨在让蓝牙栈初始化流程稍微宽松，避免该芯片由于不支持某些指令导致初始化失败  
0002号patch旨在添加对h618的支持，否则会出现找不到正确的MAC值的问题（应该是） 

设备树文件请参考仓库：https://github.com/LinuxMint-User/orangepi-zero-3-dtb-neo

