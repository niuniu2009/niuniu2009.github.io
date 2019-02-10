# 有趣的linux

- 蒸汽小火车 sl 

```bash
[root@lsrlinux lsr]# yum install sl
[root@lsrlinux lsr]# sl
```

- 模拟打字  pv

  ```bash
  [root@lsrlinux lsr]# yum  install pv
  [root@lsrlinux lsr]# echo "welcome to linux world" |pv -qL 10
  
  ```

- 黑客帝国cmatrix

  ```bash
  [root@lsrlinux cmatrix-1.2a]# cmatrix -C red
  -C color
     green, red, blue, white, yellow, cyan, magenta and black.
  
  ```

- 字符版《星球大战》，很有创意，telnet

```bash
[lsr@lsrlinux ~]$ telnet towel.blinkenlights.nl
```

- Cowsay 小牛替你说话

  ```bash
  [root@lsrlinux lsr]# cowsay I love linux
  ```

- 看天气预报

  ```bash
  [root@lsrlinux tempfile]# curl wttr.in
  ```

- 终端上的世界地图

```bash
[root@lsrlinux tempfile]#  telnet mapscii.me
```

- linux内核地图

  [[Linux内核地图]](https://img-blog.csdn.net/20130827192302828?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQvZGV5YW5nbGl1/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/SouthEast)

- 录制Linux终端GIF动画
  ![录制样例](D:\download\render1549682344861.gif)

  centos7录制GIF动画步骤：

  * 首先安装terminalizer。具体安装方法见http://www.sohu.com/a/276236992_819009。

  * 然后开始录制：

    ```bash
    [root@lsrlinux lsr]# terminalizer record giffilename //输入ctrl+D结束录制
    会在当前目录下生成一个giffilename.yml的文件。
    然后使用下面命令把该YML格式文件转换为gif文件即可。
    [root@lsrlinux lsr]# terminalizer render 2g-session.yml
    //该转换命令必须在图形界面下使用
    ```

     