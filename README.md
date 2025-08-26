## 一些网上找到的工具，备份一下（有些忘记哪里弄来的）

### 读取
- Word  查看 和 Excel 2003以下版本查看，高版本不支持。 读取 https://github.com/CreatNULL/backup/releases/download/1.0/WORD.EXCEL.rar
- Excel 查看 https://github.com/CreatNULL/backup/releases/download/1.0/BytescoutXLSViewer.zip
- Excel 查看（适合数据量很少） https://github.com/CreatNULL/backup/releases/download/1.0/Excel.7.1.exe
- Excel 查看 3.44MB安装包，需要安装 https://github.com/CreatNULL/backup/releases/download/1.0/freeexcelviewer.exe
- PPT 查看 https://github.com/CreatNULL/backup/releases/download/1.0/SmartPPT.-1.11.0.7-.rar
- 可将终端转义成 HTML 代码 （好像没用） https://github.com/CreatNULL/backup/releases/download/1.0/aha.exe
- cat https://github.com/CreatNULL/backup/releases/download/1.0/cat.exe
- less https://github.com/CreatNULL/backup/releases/download/1.0/less.exe
- tail https://github.com/CreatNULL/backup/releases/download/1.0/tail.exe
- tee https://github.com/CreatNULL/backup/releases/download/1.0/tee.exe
  
### 扫描
- arp 扫描 https://github.com/CreatNULL/backup/releases/download/1.0/arp-scan.exe
- 端口扫描 https://github.com/CreatNULL/backup/releases/download/1.0/masscan.exe，原项目地址：https://github.com/robertdavidgraham/masscan

### 编码解码
- base64编码解码 https://github.com/CreatNULL/backup/releases/download/1.0/base64.exe
- md5 https://github.com/CreatNULL/backup/releases/download/1.0/md5sum.exe
- sha1sum https://github.com/CreatNULL/backup/releases/download/1.0/sha1sum.exe
- sha3sum https://github.com/CreatNULL/backup/releases/download/1.0/sha3sum.exe
- https://github.com/cwansart/sha256sum.exe/
- 给定的标准输入或者文件做一次十六进制的输出，它也可以将十六进制输出转换为原来的二进制格式 https://github.com/CreatNULL/backup/releases/download/1.0/xxd.exe
- 十六进制查看、编辑 https://github.com/CreatNULL/backup/releases/download/1.0/hexed.exe，原项目地址：https://github.com/samizzo/hexed
- 十六进制查看 https://github.com/CreatNULL/backup/releases/download/1.0/hexyl.exe，原项目地址：https://github.com/sharkdp/hexyl

### 压缩解压缩
- bzip https://github.com/CreatNULL/backup/releases/download/1.0/bzip2.exe
- 7z https://github.com/CreatNULL/backup/releases/download/1.0/7z.zip
- gzip https://github.com/CreatNULL/backup/releases/download/1.0/gzip.exe
- tar https://github.com/CreatNULL/backup/releases/download/1.0/tar.exe
- unrar https://github.com/CreatNULL/backup/releases/download/1.0/unrar.exe
- unzip https://github.com/CreatNULL/backup/releases/download/1.0/unzip.zip
- xz https://github.com/CreatNULL/backup/releases/download/1.0/xz.exe  
- zip https://github.com/CreatNULL/backup/releases/download/1.0/zip.exe

### 文件目录操作
- chmod https://github.com/CreatNULL/backup/releases/download/1.0/chmod.exe
- cp https://github.com/CreatNULL/backup/releases/download/1.0/cp.exe
- 允许您在图像、音频和视频文件中读取和写入EXIF、GPS、IPTC、XMP、制造者标记等元数据信息 https://github.com/CreatNULL/backup/releases/download/1.0/exiftool.exe
- file 文件类型查看 https://github.com/CreatNULL/backup/releases/download/1.0/file.zip
- awk https://github.com/CreatNULL/backup/releases/download/1.0/gawk.zip
- grep https://github.com/CreatNULL/backup/releases/download/1.0/grep.zip
- ls https://github.com/CreatNULL/backup/releases/download/1.0/ls.exe
- mv https://github.com/CreatNULL/backup/releases/download/1.0/mv.exe
- rm https://github.com/CreatNULL/backup/releases/download/1.0/rm.exe
- rsync https://github.com/CreatNULL/backup/releases/download/1.0/rsync-win.zip
- sed https://github.com/CreatNULL/backup/releases/download/1.0/sed.zip
- touch https://github.com/CreatNULL/backup/releases/download/1.0/touch.exe
  
### 磁盘
- df https://github.com/CreatNULL/backup/releases/download/1.0/df.exe
- du https://github.com/CreatNULL/backup/releases/download/1.0/du.exe

### 连接
- mysql命令行连接   https://github.com/CreatNULL/backup/releases/download/1.0/mysql.zip
- redis https://github.com/CreatNULL/backup/releases/download/1.0/redis-cli.exe
- 数据库连接工具（MySQL、SQLserver、PosterSQL、Firebird 等，https://github.com/CreatNULL/backup/releases/download/1.0/HeidiSQL_12.5_64_Portable-.-.SQL.Server-My.SQL-PostgreSQL-SQLite-Firebird-Interbase.zip
- wesocket测试 https://github.com/CreatNULL/backup/releases/download/1.0/websocat.exe
```
sshpass 是 Linux 上的一个免输入密码通过 ssh 登录的方案，可以通过在命令行中指定密码，无需交互的方式完成一些自动化的动作
```
- sshpass java版本，sshpass 可以指定账号密码 https://github.com/CreatNULL/backup/releases/download/1.0/sshpass.jar 原项目地址 ： https://github.com/luckyxp/sshpass
```
ssh -c
java -jar sshpass.jar -h %remote_host% -u %remote_host_user% -p %remote_host_passwd% -c "ls -l"

scp
java -jar sshpass.jar -h %remote_host% -u %remote_host_user% -p %remote_host_passwd% --scp local_file remote_file
```
- sshpass windows版本, https://github.com/CreatNULL/backup/releases/download/1.0/sshpass.exe 原项目地址：https://github.com/xhcoding/sshpass-win32
```
刚开始，先ssh连接一下然后保存密钥，下次就可以正常使用了
sshpass -p 12345 ssh xhcoding@192.168.139.128 ls
sshpass -p 12345 rsync -avz -e 'c:/Users/xhcoding/scoop/apps/cwrsync/current/bin/ssh.exe' README.md xhcoding@192.168.139.128:/home/xhcoding/
```

### 网络
- 抓包 https://github.com/CreatNULL/backup/releases/download/1.0/tcpdump.exe
- 网络测速度 https://github.com/CreatNULL/backup/releases/download/1.0/speedtest.exe
- 通过web共享本地终端 https://github.com/CreatNULL/backup/releases/download/1.0/ttyd.exe，原项目地址：https://github.com/tsl0922/ttyd
- 下载 https://github.com/CreatNULL/backup/releases/download/1.0/wget.exe
- IP地址修改器，https://github.com/CreatNULL/backup/releases/download/1.0/IP.Address.ModifierV5.0.5.8.exe，来源:https://www.ahhhhfs.com/47888/
- 防火墙修改器，https://github.com/CreatNULL/backup/releases/download/1.0/Fab_x64_windows.exe，来源：https://www.52pojie.cn/thread-1757548-1-1.html


### 开发
- java 环境管理切换工具, https://github.com/CreatNULL/backup/releases/download/1.0/JavaEnvSwitcher.dist.zip， 来源： https://bbs.huaweicloud.com/blogs/392288
- 通过鼠标定位查看窗口PID, https://github.com/CreatNULL/backup/releases/download/1.0/Locate.the.window.PID.with.the.mouse.7z, 忘记哪下的了，应该是来源：https://blog.csdn.net/weixin_46625757/article/details/122522741
- 一个简易的FTP服务器、Syslog服务器搭建，300kb -https://github.com/CreatNULL/backup/releases/download/1.0/3CDaemon.FTP.server.Syslog.server.-.very.small.300kb.7z，来源： https://www.updatestar.com/directdownload/3cdaemon/2005987
- host修改，管理员身份运行，https://github.com/CreatNULL/backup/releases/download/1.0/SwitchHosts_windows_installer_x64_4.2.0.6119.exe，原项目地址：https://github.com/oldj/SwitchHosts
- 注册表值有效性查看工具, https://github.com/CreatNULL/backup/releases/download/1.0/RapidEE_setup.exe,来源：https://www.rapidee.com/en/download

### 其他
- make https://github.com/CreatNULL/backup/releases/download/1.0/make.exe
- whois查询 https://github.com/CreatNULL/backup/releases/download/1.0/whois.exe
- 右键菜单管理, https://github.com/CreatNULL/backup/releases/download/1.0/ContextMenuManager.exe, 原项目地址：https://github.com/BluePointLilac/ContextMenuManager
