# svn

####xcode和CornerStone初始化新建工程初始化步骤:
```
1. 在svn中创建好代码仓库,并设置好对应的Group和user权限
2. 在CornerStone添加HTTP Server类型的代码仓库
3. 选中代码仓库,点击右上角的check out同步working copies
   设置中的版本号一定选择1.7

```
####在working copies目录中创建xcode工程
```
1. xcode创建工程,路径放在working copies目录中
2. 在CornerStone中把xcshareddata xcuserdata开头的文件夹
   中显示?号的右键ignore,显示A的直接右键delete
3. 在xcode中设置取消断点等与上述文件夹有关的操作,回到
   CornerStone看到生成的xcshareddata xcuserdata相关的
   文件夹显示?的右键ignore.
4. commit其余的目录文件
```

####在工程路径下创建相关目录结构
```
1. 把创建好的目录拖入xcode
2. 在CornerStone中右键delete显示!号的文件
3. 回到xcode删除显示红色的文件,在xcode或者CornerStone
   中commit目录
```

####在工程中添加静态库目录(包括.a文件)
```
1. 把静态库目录拖拽到工程中,xcode中应显示A或者?,若无在
   finder确认文件是否添加
2. 用命令行进入到.a文件当前路径,手动添加svn add xx.a
3. 在CornerStone中查看文件为A状态后,commit
```


# Git

