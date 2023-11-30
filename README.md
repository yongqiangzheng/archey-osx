# Archey for OS X
An archey script for OS X.

## Usage
```
sudo cp archey /usr/local/bin/archey
alias mba="archey" # optional
```

这个项目，你可以学到：
1. shell编程
2. 了解Unix的基本命令
3. 字符过滤和提取，grep和awk
4. alias别名

设置了以下参数：
- 用户名
- 设备
- 系统
- 显示器
- 芯片
- 架构
- 内存
- 磁盘空间
- 电池健康度 循环次数
- 命令行数量
- 日期
- 时间

可以按个人喜好修改

效果如下：

```shell
                 ###               User: zyq
               ####                Device: MacBook Air
               ###                 System: macOS 14.1.1
       #######    #######          Display: 2560 x 1600
     ######################        Chip: Apple M1
    #####################          Arch: arm64
    ####################           Memory: Hynix LPDDR4 8 GB
    ####################           Disk: Avali: 21G Total: 245G
    #####################          Battery: Heal:97% Cycle: 142
     ######################        Command: 4270
      ####################         Uptime: 19小时24分钟
        ################           Date: 2023-11-30 星期四
         ####     #####            Time: 15:56:24
```