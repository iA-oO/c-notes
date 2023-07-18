*对应课程视频链接：*

*【【慕课】Python语言基础与应用-北京大学-陈斌-字幕校对】 https://www.bilibili.com/video/BV1V741147QH/?p=14&share_source=copy_web&vd_source=615eb03d223cf19a23232ca4a7b70c1e*



***



# 1. 基础概念

## 1，介绍python
![](http://l1q.one:8080/i/2023/07/18/fct593.png)
![](http://l1q.one:8080/i/2023/07/18/fhev4w.png)
![](http://l1q.one:8080/i/2023/07/18/fmnj8v.png)

## 2，数据类型：数值
![](http://l1q.one:8080/i/2023/07/18/gz552a.png)

### （1）int
#### ①int，运算，比较
![image](http://l1q.one:8080/i/2023/07/18/hdy66v.png)
![](http://l1q.one:8080/i/2023/07/18/hg8v8b.png)

#### ③进制
![image](http://l1q.one:8080/i/2023/07/18/i746js.png)
![image](http://l1q.one:8080/i/2023/07/18/i8vqhg.png)

### （2）float
#### ①特点
![image](http://l1q.one:8080/i/2023/07/18/ibsz53.png)

#### ②比较
不能用 a == b 判断，应该： a - b <= e-17（比如）→ a 和 b 是同一个数

### （3）复数
#### ①运算
![image](http://l1q.one:8080/i/2023/07/18/iee66t.png)

#### ②比较，应用
![image](http://l1q.one:8080/i/2023/07/18/ig69qo.png)
一个复数加abs()，表示它与原点间距离

### （4）数学函数
![image](http://l1q.one:8080/i/2023/07/18/iif5rp.png)
![image](http://l1q.one:8080/i/2023/07/18/ik3mkx.png)
从上方红字也可看出浮点数比较不能用 ==

## 3，数据类型：逻辑值
### （1）逻辑（bool）类型
![image](http://l1q.one:8080/i/2023/07/18/pfv9ev.png)

### （2）逻辑运算
![image](http://l1q.one:8080/i/2023/07/18/png5hr.png)
![image](http://l1q.one:8080/i/2023/07/18/qgnfjz.png)
![image](http://l1q.one:8080/i/2023/07/18/qh8voh.png)
![image](http://l1q.one:8080/i/2023/07/18/qj1s7t.png)

### （3）各种类型对应的真值
![image](http://l1q.one:8080/i/2023/07/18/qkbeak.png)

## 4，数据类型：字符串

### （1）文本的表示
![image](http://l1q.one:8080/i/2023/07/18/qm45kj.png)
![image](http://l1q.one:8080/i/2023/07/18/qsth91.png)
![image](http://l1q.one:8080/i/2023/07/18/qtdp4j.png)
![image](http://l1q.one:8080/i/2023/07/18/quws32.png)

### （2）字符串与名字的区别
![image](http://l1q.one:8080/i/2023/07/18/r3zfhh.png)
![image](http://l1q.one:8080/i/2023/07/18/r97hxh.png)

### （3）字符串操作
![image](http://l1q.one:8080/i/2023/07/18/rese1v.png)
注意，如果没有step，则左闭右开 [   )。如，[ 3 ,8 ]取到 3 4 5 6 7。
![image](http://l1q.one:8080/i/2023/07/18/s75eoc.png)
![image](http://l1q.one:8080/i/2023/07/18/s7q2lw.png)
![image](http://l1q.one:8080/i/2023/07/18/s92xl4.png)

### （4）字符串是一种序列
![image](http://l1q.one:8080/i/2023/07/18/saf04x.png)

## 5，变量和引用
### （1）命名数据
![image](http://l1q.one:8080/i/2023/07/18/seafbo.png)
![image](http://l1q.one:8080/i/2023/07/18/si1nhz.png)
![image](http://l1q.one:8080/i/2023/07/18/si3nd2.png)
（python是动态语言，与其他语言不一样）
![image](http://l1q.one:8080/i/2023/07/18/sjuxzo.png)
![image](http://l1q.one:8080/i/2023/07/18/skt7x5.png)
注意，+和=之间不能有空格！

## 6，容器类型：列表，元组
### （1）列表和元组的概念
![image](http://l1q.one:8080/i/2023/07/18/wdi51v.png)
![image](http://l1q.one:8080/i/2023/07/18/x2uzw5.png)

### （2）列表和元组的创建
![image](http://l1q.one:8080/i/2023/07/18/x5aurv.png)

### （3）列表的操作
#### ①增加/缩减
![image](http://l1q.one:8080/i/2023/07/18/xg3mdn.png)
append：加在末尾；insert：加在中间（序号，如3，就是第4个）;extend：把另一个列表接在原列表后
pop：指定序号，不带参数就是最后一个；remove：指定值，如hello；clear：清空列表

#### ②重新组织
![image](http://l1q.one:8080/i/2023/07/18/xlekr4.png)

#### ③列表的方法总结
![image](http://l1q.one:8080/i/2023/07/18/xly9t6.png)

### （4）列表和元组的操作
![image](http://l1q.one:8080/i/2023/07/18/xr9qic.png)
![image](http://l1q.one:8080/i/2023/07/18/xuysoh.png)
![image](http://l1q.one:8080/i/2023/07/18/z16z6g.png)
![image](http://l1q.one:8080/i/2023/07/18/z3017t.png)
![image](http://l1q.one:8080/i/2023/07/18/z6zzkj.png)

## 5，容器类型：字典
### （1）标签，数据值
![image](http://l1q.one:8080/i/2023/07/18/10y9udy.png)

### （2）创建字典
![image](http://l1q.one:8080/i/2023/07/18/1135k5u.png)
![image](http://l1q.one:8080/i/2023/07/18/116jpe3.png)

### （3）更新字典
![image](http://l1q.one:8080/i/2023/07/18/11am1sn.png)
![image](http://l1q.one:8080/i/2023/07/18/123e8ao.png)

### （4）访问字典的数据项
![image](http://l1q.one:8080/i/2023/07/18/124nus3.png)
![image](http://l1q.one:8080/i/2023/07/18/125m4hn.png)

### （5）查找
![image](http://l1q.one:8080/i/2023/07/18/126gici.png)

## 6，容器类型：集合

## 7，可变类型与不可变类型