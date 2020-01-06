# Python项目：
| 撰写人  | 梁嘉颖  | 
|:-:|:-:|
| 学号  | 171013044  |
| 合作伙伴 | 谢文慧 181013100|
| 研究项目| 中国各省近十年财政教育支出与特殊教育发展情况的研究  |
|时间|2019.12-2020.01|

# 👍pythonanywhere URL：
### →请点击    [我的pythonanywhere作品](http://gawing.pythonanywhere.com)

# 👍代码Github URL： 
### → 点击可看详情代码文件   [我的代码文件](https://github.com/NFUNM044/Python/tree/master/code)

# ✏github文档（templates、static、app.py、数据文档）
详情看代码文件。

# Python档描述
- 首页HTML编辑<style>,增加<head>\<section>\<footer>
- 安装并导入pandas、pyecharts等第三方模块包
- pandas读取csv数据文件
- pyecharts的模块代码描绘散点、条形图、地图
- 安装Flask环境，导入flask和render_template函数。


# ✏数据传递描述：
- py文件执行 了@app.route('/') 下的 index()函数，响应对应路径的页面
1. 总共有6个路径，”/index” , “/local_expense”, “/detail”, “/data”, “/scatter”, “/effectScatter”，分别对应6个页面。
2. ”/”根路由重定向给”/index”，因为在HTML有option的标签，option的value属性无法直接实现”/”根路由的跳转
3.  “/index”跳转可以看到首页，也就是项目的介绍
4.  “/local_expense”跳转可以看“地方财政教育支出”
5.  “/detail” 跳转后是4个地图，有tab栏切换，可以切换不同地图。。
6.  “/data” 列表。存有所有数据的表单。而且有下拉内容菜单，可选择区域查看数据。
7. 在每个HTML的页面有select标签，每个select都有这六个路径，能够实现在不同的页面都可以跳转至另外一个页面。
#### ✨共有6个交互页面。
[首页](http://gawing.pythonanywhere.com/index) <br>
[地方财政教育支出](http://gawing.pythonanywhere.com/local_expense) <br>
[详情视图](http://gawing.pythonanywhere.com/detail) <br>
[四个不同省份对比](http://gawing.pythonanywhere.com/scatter) <br>
[四川特殊教育情况](http://gawing.pythonanywhere.com/effectScatter) <br>
[数据列表](http://gawing.pythonanywhere.com/data) <br>

# ✨基本交互功能的HTML5控件使用丰富性(加分项）：
- Select下拉框
- tab选项卡
- table表格布局
