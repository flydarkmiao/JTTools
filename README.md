﻿# JTTools

JT808、JT809、JT1078、JTNE解析工具

[在线解析工具](http://jttools.smallchi.cn)

使用nodejs的PM2托管应用程序

``` 1
pm2 start "dotnet JTTools.dll ASPNETCORE_ENVIRONMENT=Production" -n "JTTools.18888" -o "/home/Logs/JTTools/out.log" -e "/home/Logs/JTTools/error.log"
```
