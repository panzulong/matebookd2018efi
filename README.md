# MateBook D 2018 OC EFI

OpenCore 0.7.8 EFI for Huawei Matebook D 2018

系统能升级，已更新到12.2.1

所有驱动都能正常使用，就是独立显卡屏蔽了，好像是无解吧。
可以通过HDMI连接外屏了。
遇到过的问题：
1:触控板，最初可以使用，后来通过configurator调整了kext顺序，结果就不行了，千万别调整啊。
2:外接HDMI时，内屏黑屏，开关一次就正常了。得慢点操作，反应有点慢。
3:蓝牙正常，暂时没断断续续的感觉。


基本完美了，

## __Laptop specs__

- CPU: i5 8250U //型号都可以，processtype为0即可
- iGPU: UHD 620
- RAM: 8GB DDR4
- 256GB SSD NVMe+1Tdisk
- Wi-Fi & Bluetooth: 笔记本内置的可以使用 



