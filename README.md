# Lab-7

>　本节目标：
>
>　继续练习二维数组的使用
>  了解

## 填数字

自定义一个方法，输入为 int n，使得一个n*n的矩阵从初始位置（0,0）开始，按顺时针从外到内填充数字，并打印在控制台上。
*必须使用二维数组* 

例如：输入 n 为 4，则打印
```
1   2   3   4   
12  13  14  5   
11  16  15  6   
10  9   8   7   
```

## 方法的访问权限

作用域       当前类    同一package        其他package
 
 public        √         √                        √
 
 default       √          √                        ×
 
 private        √          ×                       ×
 
注：不写时默认为friendly

作业：设计一个实验，证明public，static，private的区别，需提交文档说明逻辑然后附上相应代码。

|Tables         | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
