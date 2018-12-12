菜单栏显示开发工具（Excel2010）
    文件-选项-自定义功能区-选择开发工具
进入函数编辑页面
    开发工具-Visual Basic-插入-模块

字符串替换
```
Function B(a)
B = Replace(a, "-", ""):
End Function

示例：2018-12-12  =>  20181212 
```

字符串分割与拼接
```
Function Z(a)
AA = Left(a, 4):
bb = Mid(a, 5, 2):
cc = Right(a, 2):
Z = AA & "-" & bb & "-" & cc:
End Function

示例：20181212  => 2018-12-12
```
