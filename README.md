# my\_first-project

我的第一个测试开发项目项目仓库

用于管理python自动化测试脚本、接口测试框架

from pyecharts.charts import Line

from pyecharts.options import TitleOpts

折线图开发：

\# 准备数据

x\_data = \["周一", "周二", "周三", "周四", "周五"]

y\_data = \[10, 20, 15, 25, 30]

\# 创建折线图

line = Line()

line.add\_xaxis(x\_data)

line.add\_yaxis("销量", y\_data)

line.set\_global\_opts(

&#x20;   title\_opts=TitleOpts(title="测试折线图"),

)

\# 生成HTML文件

line.render("test\_line.html")

print("图表生成成功！")

8行信息录入

class Student:

&#x20;   def \_\_init\_\_(self,name,age,dress):

&#x20;       self.name=name

&#x20;       self.age=age

&#x20;       self.dress=dress

for i in range(1,11):

&#x20; print(f'当前第{i}位，总共十位学生需要录入信息')

&#x20; stu=Student(input('请输入学生姓名'),int(input('请输入学生年龄')),input('请输入学生地址'))

