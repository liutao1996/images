# images

## 关于github上README.md图片显示不出来的问题解决办法

以win10为例，将C:\Windows\System32\drivers\etc\hosts文件拷贝到桌面（因为该文件是在C盘如果你不拷贝出来是无法进行修改的），打开该文件添加两行：
```
199.232.68.133 raw.githubusercontent.com
199.232.68.133 githubusercontent.com
```

打开命令行刷新DNS即可，输入：
```
ipconfig /flushdns
```
