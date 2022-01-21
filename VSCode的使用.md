# VSCode的使用
1.双击打开软件
2.新建文件(Ctrl+N)
3.保存(Ctrl+S)，注意移动要保存为.html文件
4.Ctrl+加号键，Ctrl+减号键可以放大缩小视图
5.生成页面骨架结构
   输入！按下Tab键
6.利用插件在浏览器中预览页面：单击鼠标右键，在弹出出口中点击“Open In Default Browser”
# VSCode工具生成骨架标签新增代码
1.<!DOCTYPE>标签
2.lang语言
3.charset字符集
##  文档类型声明标签
<!DOCTYPE>文档类型声明，作用就是告诉浏览器使用哪种HTML版本来显示网页。

![image-20220121170443665](C:\Users\云轍\AppData\Roaming\Typora\typora-user-images\image-20220121170443665.png)
### 注意
1.<!DOCTYPE>声明位于文档中的最前面的位置，处于<html>标签之前。
2.<!DOCTYPE>不是一个HTML标签，它就是文档类型声明标签。

## lang语言种类
用来定于当前文档显示的语言
1.en定义语言为英语
2.zh-CN定义语言为中文
简单来说，定义为en就是英文网页，定义为zh-CN就是中文网页
这个属性对浏览器和搜索引擎(百度，谷歌等)还是有作用的

## 字符集
字符集是多个字符的集合。以便计算机能够识别和存储各种文字。
在<head>标签内，可以通过==<meta>==标签的==charset==属性来规定HTML文档应该使用哪种字符编码。
  <meta charset="UTF-8"/>
charset常用的值有：GB2312、BIG5、GBK和==UTF-8==也称为==万国码==，基本包含了全世界所有国家需要用到的字符。

