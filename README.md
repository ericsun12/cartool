cartool
=======

Export images from OS X / iOS .car CoreUI archives. Very rough code, probably tons wrong with it, but still useful.

1. 从git下载工程文件，编译OK。 
2. 然后从如下目录查找生成的可执行文件。(小技巧：直接把cartool拖到终端上去，就会有全路径了) 然后直接执行
```
cd /Users/ericsun/Library/Developer/Xcode/DerivedData/cartool-aumovaqpmmfvpnazhlyslqilcvhg/Build/Products/Debug/
```

3. 接着按照上面的执行命令 ./cartool assert.car(把这个文件直接拖到终端上就可以得到全路径) 解压的路径(提前创建好) 
   具体命令如下：
```
./cartool /Users/ericsun/Desktop/APPname/Payload/XXX.app/Assets.car /Users/ericsun/Desktop/1
```
正常情况下,完成后就会打印所有解压出来图片的名称： 
4. 然后去 /Users/ericsun/Desktop/1 文件夹(上边写的解压路径)下就可以看到我们需要的图片了。 
