# Hackintosh_ECS-H110s-2P_QNVH-I7-8850H_OC

---

2021-05-17 更新

- Update Opencore to 0.8.0  
- Update VirtualSMC to 1.2.9
- Update SMCProcessor to 1.2.9
- Update SMCSuperIO to 1.2.9
- Update WhateverGreen t0 1.5.8
- Update AppleALC to 1.7.1
- Update LiLu to 1.6.0    
- Update Whatevergreen to 1.5.8     
- Update AppleALC to 1.7.1  
- Fix some opencore config error
- Support to macOS Monterey 12.13.1

---

为数不多的STX小主板，上传了两个bios，```ECS-H110S-2P-6/7th.bin```为原版bios，支持6/7代u，```ECS-H110S-2P-8/9th.bin```为魔改版，支持8/9代u，当然也包括QNVH。

---

# Hardware/硬件

|                     | Specifications / 型号               | Note / 备注   |
| ------------------- |:---------------------------------:|:-----------:|
| Motherboard/主板:     | Ecs H110s-2p                      | (mini STX)  |
| CPU/处理器:            | QNVH                              | I7 8850h ES |
| CPU Cooler/散热器:     | NOCTUA NH-L9i                     |             |
| Hard Drive/硬盘:      | Hikvision C2000pro 512gb          |             |
| RAM/内存:             | JUHOR 16G DDR4 2666MHz X2         |             |
| Wireless Card/无线网卡: | BCM94350CS2                    	| 原厂拆机卡+转接    |
| Tower Case/机箱:      | SilverStone VT02                  |             |
| Power/电源:           | 55/25mm 19v 120w DC power adapter |             |

---

# Functions/功能

### Work：

- All HDMI ports (1080p)  
- DP port (1080p)  
- Audio output on HDMI  
- All USB ports  
- Wi-Fi & Bluetooth  
- Airdrop  
- AirPlay  
- Continuity  

### Not working:

- Sleep  

### Not tested yet:

- 4k display  
- 2.5mm Audio Output & Mic Input

---

# BIOS setting/BIOS设定：

### Disable：

- Fast Boot  
- CFG Lock   
- CSM   

### Enable：

- VT-x  
- Hyper Threading  

---

# Performance/展示

图源自[自制最小STX主板机箱 H110S-2P主板的完美归宿_台式机_什么值得买](https://post.smzdm.com/p/a3g7rlzn/)

https://npm.elemecdn.com/road-blog-figure-webp@1.1.0/Hackintosh_ECS-H110s-2P_QNVH-I7-8850H_OC/cb54ac540fbbf1e8819dd10e2f495eac.webp

![cb54ac540fbbf1e8819dd10e2f495eac.jpeg](https://npm.elemecdn.com/road-blog-figure-webp@1.1.0/Hackintosh_ECS-H110s-2P_QNVH-I7-8850H_OC/cb54ac540fbbf1e8819dd10e2f495eac.webp)

![223926.jpg](https://npm.elemecdn.com/road-blog-figure-webp@1.1.0/Hackintosh_ECS-H110s-2P_QNVH-I7-8850H_OC/223926.webp)

---

# Reference/参考

[精解OpenCore](https://blog.daliansky.net/OpenCore-BootLoader.html) - [黑果小兵的部落阁 ](https://blog.daliansky.net/)

[使用OpenCore引导黑苹果](https://blog.xjn819.com/?p=543) - [XJN](https://blog.xjn819.com/) 

[2066元的Macmini 2018，完美配置，内有clover](https://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1821138) - [果特尔](https://i.pcbeta.com/space-uid-2873645.html)

[自制最小STX主板机箱 H110S-2P主板的完美归宿_台式机_什么值得买](https://post.smzdm.com/p/a3g7rlzn/) - [qichezhijia](https://zhiyou.smzdm.com/member/3401236017/)
