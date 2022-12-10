# 这是我的第一篇文章
## 二级标题

这是正文

这是正文
1. 插入图片：复制图片，然后CTRL+ALT+V
![](2022-12-10-10-15-34.png)
2. 插入图片，在左边栏添加图片，然后输入![](会自动弹出下栏显示添加到目录中的图片)
![](29bbad4b720b24af46f9d00d7883702.jpg)
*这是图片描述*  

## 插入公式：
$$
CTRL+M会自动添加两个美元符号，连按两下会是四个美元符号
$$
$\lim_{x \to \infin}f(x)$

## 表格
ALT+SHIFT+F 格式化表格

| Alice |  Amy  | Flora |
| ----: | :---: | :---- |
|   1.5 |  1.2  | 1.3   |

## 插入链接 
这是一个链接：复制链接，选中文字然后 CTRL+V 
这是一个[链接](https://www.google.com/search?q=%E7%8C%AB%E5%92%AA&source=lnms&tbm=isch&sa=X&ved=2ahUKEwj02ODe1O37AhXS-TgGHSdJBWQQ_AUoAXoECAEQAw&biw=1358&bih=722&dpr=2#imgrc=MdtRFHSGhQyQRM)

## code 
可以添加代码块，渲染之后可以用高亮表现出来
```c
import pandas as pd
import matplotlib.pyplot as plt
import numpy as np

xls=[i for i in range(1,1000000)]
yls=[10**5*x**2+10**8*x for x in xls]
zls=[10**5*x**2 for x in xls]
data=pd.DataFrame(
    {'x':xls,
     'y':yls   
    })
xlog=np.log(data.x)
ylog=np.log(data.y)
plt.scatter(xlog,ylog)
zlog=np.log(zls)
plt.scatter(xlog,zlog)
```
## 文件导出
1. 右上导航点开Preview enhanced
**ctrl+s 保存文档**
右键Chrome (Puppeteer)选 PDF导出
2. 发表到limfx 点右上角$f_X$图标 然后会让我们在上方搜索栏输入账号-会自动打开自动编辑器
3. 在本地修改文章之后再点$f_X$图标，就可以实现更新

## OPEN Zenmode: focus on writing:
CTRL+K->release both ->press Z  
ESC 退出 
