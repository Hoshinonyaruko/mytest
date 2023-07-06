# BetterQQNT-Adapter
red-protocol simple onebot adapter

# BetterQQNT-Adapter-epl
Red-Protcol的epl-adapter-demo,欢迎参考开发其他语言版本


请不要在官方群聊等内提及本教程。

请不要发送视频，帖子等来宣传此教程。

本教程请不要大规模传播，请不要在视频或论坛投稿。


# 操作【一】

一加入bant频道获取 dll (https://t.me/betterqqnt)

（不可以分发所以请自行在原项目仓库获取：https://github.com/BetterQQNT/BetterQQNT）

一将 better-qqnt-x64.dll 重命名为 version.dll 并放入 QQNT 安装文件夹。

一进入QQ在设置-插件 RedProtocol确认开启打勾

一关闭QQ窗口防止崩溃


# 操作【二】

获取适配器

https://wwcr.lanzoul.com/redpro


# 操作【三】

获取TOKEN

—在路径【C:\Users\你的用户名(默认是administrator)\AppData\Roaming\BetterUniverse\QQNT\】

下找到文件 【RED_PROTOCOL_TOKEN】，用记事本打开复制出token 内容，这在下一步有用


# 操作【四】

—在操作二获取的red.exe同一目录下，

创建1.txt文件，

复制模板内容并将举例中的机器人号码、机器人ws地址、red密钥、red的ws地址(如果你的red不在本地,否则保持不变)，

修改为对应您自己的参数

然后将1.txt改为1.bat并运行


title 标题，可自定义

red ws://zaomiao.com:机器人端口号 red密钥 机器人号码 ws://127.0.0.1:16530

举例：
```
title 2289766976
red ws://zaomiao.com:20036 c5387d04c649852314ff43d50de1f2ca3b6c9867236e7dd6a56361269a0dcdb0 2289766976 ws://127.0.0.1:16530
```
举例2:（koishi已经自带在bqnt中，但如果你依然想要连接到老koishi的onebot-adapter）请参考
```
title 3570577015
red ws://127.0.0.1:5140/onebot 7dcb37d1b0874368e0e21b3242e7d5084bd6851b84108f3b1bde61c0055fd322 3570577015 ws://192.168.0.134:16530
```
举例3:（nonebot2）
```
title 3570577015
red ws://127.0.0.1:8080/onebot/v11/ws 7dcb37d1b0874368e0e21b3242e7d5084bd6851b84108f3b1bde61c0055fd322 3570577015 ws://192.168.0.134:16530
```
```
小提示:

云上地址应为:ws://zaomiao.com:端口

----云上地址无需自己部署后端(并且免费)----
(建议有装插件需求的、用本地后端，或者创建多个bat运行多个，适配器可多开接入多个后端，但bqnt不行。）

端口20001~20050是早苗

端口20050~20070是灵梦

端口20071~20099是魔理沙

端口25369是公用云崽

端口25370是澪

端口25371是浅羽

端口25372是公用真寻

--------------本地地址--------------—

真寻和nb2的ws地址应为:ws://地址:端口/onebot/v11/ws

Trss云崽ws地址应为:ws://地址:2536/go-cqhttp

外置的Koishi的ws地址应为:ws://地址:5140/onebot

内置的Koishi的ws地址应为:ws://地址:11400/onebot
```
本地地址不出意外一般都是127.0.0.1

比如nonebot2的地址就是

ws://127.0.0.1:8080/onebot/v11/ws

端口号在您设置了的场景下可能不会是默认值，需要有一定了解并且自行设置正确的反向ws地址
# 操作【五】

运行刚刚修改的1.bat，如果遇到问题，请到交流群at作者询问

免费开源，禁止任何形式的倒卖盈利。

作者不承担因此产生的任何后果。

若您发现有人正在进行此类行为，请发邮件上报

或您有侵权和任何问题以及争议之处，

请发送邮件给我，通过邮件，友好沟通协商解决问题

applegm@me.com

# Addition License

Copyright (c) [2023] [Hoshinonyaruko]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, and distribute the Software, and to
permit persons to whom the Software is furnished to do so, subject to the
following conditions:

1. Redistributions in any form must retain the above copyright notice,
   this list of conditions and the following disclaimer.

2. Redistributions of the Software must not be sold or used for any
   commercial purpose without the express written consent of the copyright
   holder.

3. Modifications to the Software must include the original author's
   name as well as a clear indication of the changes made.

4. The Software is provided "as is", without warranty of any kind, express
   or implied, including but not limited to the warranties of
   merchantability, fitness for a particular purpose and noninfringement.
   In no event shall the authors or copyright holders be liable for any
   claim, damages or other liability, whether in an action of contract,
   tort or otherwise, arising from, out of or in connection with the
   Software or the use or other dealings in the Software.

   purpose without the express written consent of the copyright holder.

4. The author is not responsible for any consequences resulting from the use
   or redistribution of the Software.
