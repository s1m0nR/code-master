# 第一个开源小项目：统计代码量

## 1.项目功能

- **实现代码统计**

- [x] 代码来源文件
- [x] 总代码量
- [x] 总注释量
- [x] 总空行量
- [x] 实际代码量
- [x] 实际代码比率
- [x] 总注释比率
- [x] 总空行比率

- **csv数据存储**

- [x] csv模块进行数据存储

- **美化输出结果**

- [x] prettytable模块美化输出
- [x] colorama模块颜色配置

- **csv数据统计分析**

- [x] pandas模块读取csv
- [x] pandas模块统计与描述

## 2.你会学到

- [x] python基础
- [x] 面向对象方法
- [x] os模块
- [x] pandas模块
- [x] csv模块
- [x] prettytable模块
- [x] colorama模块

## 3.如何使用

- **下载**

```python
git clone git@github.com:s1m0nR/code-master.git
```

- **使用**

将代码文件与文件夹放到code_dir，或者修改`statistic.py`文件里的

```python
dir = './code_dir' # 你的代码文件夹或者代码文件
```

- **运行**

运行`statistic.py`文件，然后会打印输出下面结果，并得到原统计数据data.csv以及排序结果数据sort_data.csv。

- **定制**

```python
def codeSort(self,c_name='实际代码量') # 默认为实际代码量排序
```

使用codeSort函数的时候，可以根据自己的需求来排序，比如可以按照以下参数配置：

codeSort('总代码量')。

可填入：(下面字符串中选择即可)

```
'文件', '总代码量', '总注释量', '总空行量', '实际代码量', '实际代码比率', '总注释比率', '总空行比率'
```

## 4.结果展示
- 美化输出结果

![](./show_res/py_output.jpeg)

- 数据存储结果

![](./show_res/data_csv.jpg)

- 排序存储结果

实际代码量排序结果

![](./show_res/sort_data_csv.JPG)

- 简单统计结果输出

![](show_res/py_static.jpeg)
