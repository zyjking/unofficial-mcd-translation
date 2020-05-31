# unoffical-mcd-translate(en-US → zh-Hans)
这是Minecraft Dungeons非官方中文语言包的存档项目，仅用于存档，不接受任何issue或pull requests。  
本项目采用署名-非商业性使用-禁止演绎 4.0 国际许可协议（CC BY-NC-ND 4.0）进行许可。  

注意：此语言包基于英语制作，会覆盖语言选项内的英语，卸载语言包即可恢复！  

**启动器版使用方法：**  

1. 打开游戏安装目录（也就是启动器目录）  
2. 进入 \products\dungeons\dungeons\Dungeons\Content\Paks ，将Pak文件直接复制到此处即可  
  
  卸载：删除Pak文件即可  
  注意：请不要重命名文件  

  注意：如果启动器下方显示“修复”，请直接忽略，并直接从安装目录下的程序 Dungeons-Win64-Shipping.exe（直接搜索即可）启动游戏，不影响登录和成就解锁！！！  

**Win10版使用方法：**  
1. 找到设置-更新和安全-开发者选项-选择“开发人员模式”并等待安装完毕  
2. 下载UWPDumper-x64并解压：https://lanzous.com/id0xtyj  
3. 启动游戏，等待加载完毕到主界面  
4. 打开解压后的Injector.exe，寻找“Dungeons.exe”，然后输入左边的数字，等待DUMP完成  
如果遇到“缺少VCRUNTIME140_1.dll”，请自行百度解决  

5. DUMP完毕后会弹出一个目录窗口，将里面的文件复制到你想作为安装目录的地方（一定要复制到不同目录下！）  
如果没有弹出，请在 C:\Users\ {你的用户名} \AppData\Local\Packages\Microsoft.Lovika_8wekyb3d8bbwe\TempState\DUMP 目录下找到刚刚DUMP的文件  

6. 卸载原来的游戏，注意备份存档，存档位于 C:\Users\ {你的用户名} \AppData\Local\Dungeons\{一串数字}\Characters  
7. 打开刚刚DUMP并复制的目录，进入Dungeons\Content\Paks目录下，复制汉化文件到此处  
8. 返回到主目录（带有appxmanifest.xml文件），在空白处按住左Shift并右键，点击“在此处打开Powershell 窗口”，复制输入以下命令：  

“Add-AppxPackage -path .\appxmanifest.xml -register” （去掉引号）  

这会将资源文件与系统作关联，双击exe或者用开始菜单中的快捷方式即可启动带有汉化包的游戏了！  

注意：如果游戏更新了版本，你**必须**要重复以上步骤打补丁！  
注意：按照此方法操作后，游戏将**不会**接收到更新，要想接受更新，请不要执行第6步和第8步，并直接从exe文件Dungeons-Win64-Shipping.exe（直接搜索即可）启动游戏  

**下载地址：**  
蓝奏云：https://lanzous.com/b0bwh52qj   密码:327n  
备用：GitHub的release  

繁体中文请按此（不受ND影响）：https://forum.gamer.com.tw/Co.php?bsn=18673&sn=950359  

**遇到问题/漏翻/对文本质量不满意？**  
https://www.mcbbs.net/thread-1018057-1-1.html  
直接跟帖回复即可，我会视情况回应

文本提取 ：zyjking  
项目创建 ：zyjking，ff98sha，WDLJT  
翻译/校对：中文MCD Wiki Project（MCDWiki）全体成员  
打包/发布：zyjking  

关于其它的汉化包详细声明，请查看压缩包内的readme文件。

