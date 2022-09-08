# TPA311x

基于TPA311x的立体声功放

# 简介

这是一个基于TPA311x系列芯片的数字功放项目，默认采用TPA3116D2作为放大器，LM4562作为前端放大器。同时为了保证运放放大不失真，采用了双电源供电。

还提供了外壳的设计文件，详见Shell文件夹。

# 实物图

![PCBA图](.\Picture\TPA3116 PCBA.jpg)
![内部装配图](.\Picture\TPA3116-ASM-Int.jpg)
![前面板](.\Picture\TPA3116-ASM-Front.jpg)
![后面板](.\Picture\TPA3116-ASM-Back.jpg)

# 存在的问题

需要注意的是，本功放板目前存在关机pop声，经测试是由于+5V电路掉电顺序与MUTE及PVCC不一致导致，本问题待解决
