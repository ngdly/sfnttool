# 在TTF字体中提取想要的文字，让字体文件变迷你

http://download.csdn.net/detail/ldpjay/8822587

【使用】
1. 确保你的电脑已经安装了Java环境（能运行Java命令），这是必须的。

2. 命令行进入到sfnttool所在目录下。（一个小技巧，在当前文件夹里按住Shift再右键，里面有个“在此处打开命令行”。）

3. 输入下面的命令即可：

```
java -jar sfnttool.jar  -s '这是一段测试文字' msyh.ttf msyh_simplify.ttf
```

sfnttool.jar说明如下：

```
java -jar sfnttool.jar -h
subset [-?|-h|-help] [-b] [-s string] fontfile outfile
prototype font subsetter
        -?,-help        print this help information
        -s,-string       string to subset
        -b,-bench        benchmark (run 10000 iterations)
        -h,-hints        strip hints
        -w,-woff         output woff format
        -e,-eot  output eot format
        -x,-mtx  enable microtype express compression for eot format
```

4. 输出字体在同目录下。

