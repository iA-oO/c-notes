# 1.基础概念

## 1， 主函数（main函数）
![](https://pad.degrowth.net/uploads/upload_b6c58c4bb00b22024645a9fea92f90fc.png)
![](https://pad.degrowth.net/uploads/upload_63c954e49ce70662fc4e16ef131a1295.png)
![](https://pad.degrowth.net/uploads/upload_c86651c3189e327b17ac1fd043a64495.png)

## 2，引用头文件,printf
![](https://pad.degrowth.net/uploads/upload_20690ab8b79ce15cc301a0dcc2fe49ad.png)

## 3，数据类型
![](https://pad.degrowth.net/uploads/upload_64748d5cfd7f6edf9ca931965d03c096.png)
![](https://pad.degrowth.net/uploads/upload_0956bfb81c594578c9fc4cb0d1e715b9.png)

## 4，printf,double,float，打印字符串与数学属性
printf:直接输入是打印字符串,输入%d是数学属性的100,可以进行运算
("%d",100)也可以a=100 ("%d",a)
![](https://pad.degrowth.net/uploads/upload_a4bd73f5295a40f3d239f97f974d0277.png)
float用的是%f，double用的是%lf

注：printf的返回值是打印在屏幕上的字符个数！见11.3.2

## 5，sizeof与类型大小
![](https://pad.degrowth.net/uploads/upload_63342289e905b571c5eeea3ee4330212.png)
![](https://pad.degrowth.net/uploads/upload_036d89a182959febc0d7630b3c776bee.png)

### （1）sizeof计算类型、变量大小
![](https://pad.degrowth.net/uploads/upload_45142b609a9da59014950c83e3e34f8a.png)

注：计算变量大小时括号通常也不省略

### （2）sizeof计算数组大小,计算数组元素个数公式
![](https://pad.degrowth.net/uploads/upload_a503270eaa468a6248089b57771305c7.png)

## 6，计算机中的单位
![](https://pad.degrowth.net/uploads/upload_e71cd2e51cc04eac08068d1d05f83eb5.png)![](https://pad.degrowth.net/uploads/upload_a1f9d0e2cf2f38101a6dea7ba38cc5a8.png)
## 7，变量、常量
### (1)变量
局部变量：{}内的。局部变量被定义时，系统不会对其初始化
全局变量：{}外的
![](https://pad.degrowth.net/uploads/upload_fce240e3273ccce68342a7161ad9aa4b.png)
### (2)常量
![](https://pad.degrowth.net/uploads/upload_383351081cf9e20908fad780a406bd37.png)
![](https://pad.degrowth.net/uploads/upload_d878a5b96c82347d8d70e121be88f512.png)
![](https://pad.degrowth.net/uploads/upload_31ff49b482be53ffb31c3df1f5eda9d2.png)
![](https://pad.degrowth.net/uploads/upload_e1763d4830e4b13091500de2757cac7a.png)
![](https://pad.degrowth.net/uploads/upload_fc5bacb84ada5534666a3a3cdc031215.png)
![](https://pad.degrowth.net/uploads/upload_d0b0763cd403f84b7d86b1341446d353.png)
## 8，求和,scanf
### sanf
![](https://pad.degrowth.net/uploads/upload_389485181caf4a556939be1218bfc9a8.png)
&a,&b是指数据存放
### 求和
![](https://pad.degrowth.net/uploads/upload_03bceef81ff46230b345b8c7ea6bb3b8.png)
## 9，作用域,生命周期
![](https://pad.degrowth.net/uploads/upload_2bf6467c26493c5c00ef86c6e9697b32.png)
## 10，字符串
![](https://pad.degrowth.net/uploads/upload_b092a3b3b0af592a43c1d97fd4b79d3e.png)
![](https://pad.degrowth.net/uploads/upload_fae27bfea06204c1a2f1ca7a2c3be9a6.png)
![](https://pad.degrowth.net/uploads/upload_8b4d4f1dac11a1df96494eb4cfdf8407.png)
注意：\0作为字符串结束标志存在，但求长度时不算在内
![](https://pad.degrowth.net/uploads/upload_027603f6d46a4bd8d95495496fc63e75.png)
## 11，转义字符,%
### （1）转义字符\
![](https://pad.degrowth.net/uploads/upload_ac8989d2735d3fd32bd1d95757a382e4.png)
\ccc这种是8进制
![](https://pad.degrowth.net/uploads/upload_99def359773f1dcc2ad58bb9d31e4a30.png)
### （2）%
%d,用来输出十进制整数。 %f,用来输出实数（包括单，双精度），以小数形式输出，默认情况下保留小数点6位。 %c,用来输出一个字符。 %s,用来输出一个字符串。
%p专门用来打印地址
一个左对齐的小tip：-2%d


## 12，8进制&10进制→10进制
![](https://pad.degrowth.net/uploads/upload_4c69c70a0787304d90117be5d55e635c.png)

# 2.选择语句
![](https://pad.degrowth.net/uploads/upload_babd4951f644223d466bd70515d9ca3b.png)
![](https://pad.degrowth.net/uploads/upload_32c28048f3fa500a8c9f2174cf9741b4.png)

# 3.循环语句
![](https://pad.degrowth.net/uploads/upload_0c8cb4aaf5e28c1706db75a1fba11825.png)
注意：=是赋值，==是数

# 4.函数，数组
## 1，函数
![](https://pad.degrowth.net/uploads/upload_ca5e492302e78333514e8b9b2b3f59a7.png)

## 2，数组
![](https://pad.degrowth.net/uploads/upload_00c0508e938884683d7ccfc92a881348.png)
![](https://pad.degrowth.net/uploads/upload_3afe370de5a2a562cd8270982cf432a0.png)

# 5.操作符
![](https://pad.degrowth.net/uploads/upload_1ee8229e777813d5708d3f263bfb1921.png)

## 1，/,&,%
![](https://pad.degrowth.net/uploads/upload_ad8dbb7437e8018e8c921ca237be3e87.png)
（上图得到的是1）

## 2，左移<<、右移>>
![](https://pad.degrowth.net/uploads/upload_97661f5b4bbcfb04820a27119ef57823.png)

## 3，其他操作符
### （1）位操作符&赋值操作符
![](https://pad.degrowth.net/uploads/upload_40192b9a6a536b85a0fec174013386da.png)
![](https://pad.degrowth.net/uploads/upload_68e8ddee6bc0d7e39e877c2ff4372eaa.png)
这里的+=可以理解为先+再=

位运算（Bitwise Operation） - 知乎 (zhihu.com)

### （2）单目操作符、双目操作符
![](https://pad.degrowth.net/uploads/upload_d5bb343aaa672c7dcb44545e0206f2ae.png)
![](https://pad.degrowth.net/uploads/upload_7a5e2fdea7fba6b001799088138924e6.png)
#### ①！
把假变真，真变假
![](https://pad.degrowth.net/uploads/upload_5fdd107be6de6b4bdbafe4c2244c0513.png)
用法：
![](https://pad.degrowth.net/uploads/upload_361a6bd4ed0f737f664d0a1edc196c78.png)
注：!=可以用来表示不等于的比较符，见4.3.3
#### ②按位取反~
![](https://pad.degrowth.net/uploads/upload_4faabc7c35a64f81a4d3bcd9e9466d5a.png)
![](https://pad.degrowth.net/uploads/upload_c94f55142e6684a01fb221522a9c7228.png)
（注：按位取反符号位照常变）
这里的原码表示可以理解为，最左边的位（符号位），是0就说明这个数是正数，是1就说明这个数是负数

int类型在内存中的存储方式 | C语言研究中心 - C语言网 (dotcpp.com)

#### ③++
##### 前置++
++在使用前
![](https://pad.degrowth.net/uploads/upload_214ef14f72d24453c9af4bc2048f4f3c.png)

##### 后置++
++在使用后
![](https://pad.degrowth.net/uploads/upload_69cbe27fd7df0d7175d3600af852ac11.png)

#### ④强制类型转换()
不推荐使用
![](https://pad.degrowth.net/uploads/upload_6051f95905bc10d52400153c9075f434.png)
![](https://pad.degrowth.net/uploads/upload_9990cf3580c452cf37d1b18c8a761bcc.png)

#### ⑤sizeof：见1.8
注意：它是操作符，不是函数

### （3）关系操作符
![](https://pad.degrowth.net/uploads/upload_647b123dcd9b9c168717b46992f69fd8.png)

### （4）逻辑操作符
![](https://pad.degrowth.net/uploads/upload_c5ad3d3b8d8f007e90f28e43aa994919.png)
e.g.:
![](https://pad.degrowth.net/uploads/upload_2e77c0c6a66d80521acfd8f5cd0989d1.png)
![](https://pad.degrowth.net/uploads/upload_94b2ee2e3d9102672318101480d8480e.png)

### （5）条件操作符（三目操作符）?:
(exp：表达式）
![](https://pad.degrowth.net/uploads/upload_48207566406f856ddc5d5a723d05a2b3.png)
![](https://pad.degrowth.net/uploads/upload_3ab7c24024998752b1303bc48f2ffc95.png)
e.g.:
![](https://pad.degrowth.net/uploads/upload_91147afeefc7d5f4af47e5d7eb1073f0.png)
![](https://pad.degrowth.net/uploads/upload_2981761b1a7ff89b38f0948eba9f175a.png)

### （6）逗号表达式
![](https://pad.degrowth.net/uploads/upload_c8667702452291086ea8ede130300236.png)
![](https://pad.degrowth.net/uploads/upload_bb8a4f1f9818997c9229885b1228ef5d.png)

### （7）下标引用、函数调用和结构成员
![](https://pad.degrowth.net/uploads/upload_c37e93be32c0d23401b39f960125c102.png)
![](https://pad.degrowth.net/uploads/upload_dc9765260b98117b759b39adcd43472e.png)
     ->见8
     []见12.4.2
![](https://pad.degrowth.net/uploads/upload_5dc7532b2a1e96e916097febab4ff921.png)
![](https://pad.degrowth.net/uploads/upload_3eb999cd90f5b13cfddd29371bb546e1.png)

# 6.关键字
![](https://pad.degrowth.net/uploads/upload_69b5cc5bcec32fd5e01aa8769bc5509a.png)
![](https://pad.degrowth.net/uploads/upload_ea4a21f92d58d9ac7ec8e7c6e4165bab.png)
## 1，auto
![](https://pad.degrowth.net/uploads/upload_70ca22ed86df365360d5d6e5408e8903.png)
![](https://pad.degrowth.net/uploads/upload_d619771748c3ee9ae8962f0ad849d2e5.png)

## 2，extern
用来申明外部符号

## 3，register
寄存器关键字

![](https://pad.degrowth.net/uploads/upload_54c714fe13646019f5d30800b12f8207.png)

![](https://pad.degrowth.net/uploads/upload_202dbc5c2200c0c6f524f3f7da8c97d4.png)
编译器已经非常聪明了，一般不用自己加

## 3，signed、unsigned&static，union&void，volatile
![](https://pad.degrowth.net/uploads/upload_880f3610c5ba502119027f496c9dcd53.png)

## 4，typedef
![](https://pad.degrowth.net/uploads/upload_8e13c72ad96ee4f601663e6ae16633cb.png)
即重命名类型，给类型编一个更简单的名字
![](https://pad.degrowth.net/uploads/upload_68d91d6dec02fe1163dc200a80c374cd.png)
![](https://pad.degrowth.net/uploads/upload_eb5b62af1779b43e9091a3d804a8b6a3.png)

## 5，static
![](https://pad.degrowth.net/uploads/upload_0b6b443bc447216d8f4f3c7668c59b1c.png)
### （1）修饰局部变量
![](https://pad.degrowth.net/uploads/upload_6e410c665e844f5544d82b8dc4e12537.png)
![](https://pad.degrowth.net/uploads/upload_adb15fc8d213ce99cf6ca72b55738a17.png)
加上static后：
![](https://pad.degrowth.net/uploads/upload_edd51f0c11c653f66c1b5303ebcdd053.png)
![](https://pad.degrowth.net/uploads/upload_3dda087ff8f891ad263ec602e3ab4e34.png)
![](https://pad.degrowth.net/uploads/upload_552457866afd1abe06c8a8e86916531e.png)
### （2）修饰全局变量
![](https://pad.degrowth.net/uploads/upload_d36d99714f4804f5308e14499029a21c.png)
![](https://pad.degrowth.net/uploads/upload_cb6a1fcd0232a7a6b09e97cb380d1ed8.png)
![](https://pad.degrowth.net/uploads/upload_65a9493b1e8f4d07b7de2d0c351f0863.png)
### （3）修饰函数
![](https://pad.degrowth.net/uploads/upload_d0df7f5e973136debe2c849956442ef6.png)
![](https://pad.degrowth.net/uploads/upload_63dd350e2ef497cbd64f6736b1fad1f8.png)

# 7.常量和宏
## 1，define定义常量
![](https://pad.degrowth.net/uploads/upload_da6f32c586a1f693aa5a2251fc69ccee.png)

## 2，define定义宏
![](https://pad.degrowth.net/uploads/upload_85eff3c4629445a32d97c45437dd523e.png)
![](https://pad.degrowth.net/uploads/upload_b5a93f12e3051cfaac8d653f890b4a43.png)
要加括号！！
![](https://pad.degrowth.net/uploads/upload_ca7ca631b27c65560e3495dc212544f0.png)

# 8.指针（12）
## 1，内存
![](https://pad.degrowth.net/uploads/upload_d827b9ea0cf3c719dff14049fad9416f.png)
![](https://pad.degrowth.net/uploads/upload_92eaf3aa3d32aeaa13b3248b2935558d.png)
![](https://pad.degrowth.net/uploads/upload_ab291135d4d482b86918ddebf64f88be.png)

## 2，指针变量pa/pc
### （1）
传递、拷贝指针而不是对象是要快的多的，保存指针的副本而不是对象的副本是可以节省大量内存的
![](https://pad.degrowth.net/uploads/upload_48ff65dbce32da0eb66f70a81d9d9294.png)
![](https://pad.degrowth.net/uploads/upload_9a772a9b215bf0f6a15207ea331d8174.png)
指针就是地址

### （2）指针变量的大小
![](https://pad.degrowth.net/uploads/upload_8c6f626ac86de015c282d832ef892ece.png)
![](https://pad.degrowth.net/uploads/upload_5f27b703602bb611b07c2f7175fdb023.png)
### （3）解引用
（带*的）
![](https://pad.degrowth.net/uploads/upload_430a9d9f1ea600f0e3f7dce7f35697d1.png)

# 9.结构体
![](https://pad.degrowth.net/uploads/upload_ba51059e992129ef34e6ee840167ede8.png)
![](https://pad.degrowth.net/uploads/upload_5ebf962bf1ce715f59d452c09e7cf16c.png)
![](https://pad.degrowth.net/uploads/upload_e4d63ee901b9d3c28f943170d9618bda.png)
![](https://pad.degrowth.net/uploads/upload_28b85eaa0f883318587e476ee972d577.png)

# 10.分支
## 1，语句
![](https://pad.degrowth.net/uploads/upload_885fad0396abc6b3f806b0fb3b460235.png)
![](https://pad.degrowth.net/uploads/upload_2d8faa9931f468d6ee536b365e3f8214.png)

## 2，分支语句if else
### （1）if语句
![](https://pad.degrowth.net/uploads/upload_dc4226cf071579d3839490e143ca2414.png)
![](https://pad.degrowth.net/uploads/upload_afbeffeee73e6eece27dbb7ecf757557.png)
![](https://pad.degrowth.net/uploads/upload_cc23ca212c39cf42c307436caa8c51db.png)
![](https://pad.degrowth.net/uploads/upload_a7f316075ef616bda3227280bd46de6d.png)
注意：有多条语句时要带大括号！

两个条件的时候：
![](https://pad.degrowth.net/uploads/upload_ad726a4479455e230fd5eaba81091489.png)
![](https://pad.degrowth.net/uploads/upload_68dea8ec167539ce51edfcc5210a2027.png)
正确的写法：
![](https://pad.degrowth.net/uploads/upload_961eb772e11f493c843598b8348dded0.png)
&&前的可以不写，但写了可读性更高一些
![](https://pad.degrowth.net/uploads/upload_e837b67307b5a6ddea7bf0117caf3d26.png)
![](https://pad.degrowth.net/uploads/upload_1380c870168273a6f0cd8fe43ad8ff74.png)
![](https://pad.degrowth.net/uploads/upload_f788df0a45bee52971e82870c38f2be0.png)

### （2）代码风格
![](https://pad.degrowth.net/uploads/upload_3e1b54374f1ca1f8514c0b8b22d9662b.png)
![](https://pad.degrowth.net/uploads/upload_bc5a9ed2059ac19b2f5612eaba2d0018.png)
![](https://pad.degrowth.net/uploads/upload_d69c02f6781168f92bdf595492235338.png)
![](https://pad.degrowth.net/uploads/upload_b67a0551b4583401bd82dc84fcfe3e1a.png)
![](https://pad.degrowth.net/uploads/upload_93ecd09e1ce474ecc62850e3febfb82a.png)
（数字指常数）
### （3）练习
![](https://pad.degrowth.net/uploads/upload_25b0d248bc82c0d39b7e423459f1efd9.png)
1.
![](https://pad.degrowth.net/uploads/upload_1c119f138e1d0a3da84e5d685b0f3c32.png)

# 11.数组（3.2）
## 1，数组概念
![](https://pad.degrowth.net/uploads/upload_9f72311fdcf7b512fea70c482cf173ae.png)
![](https://pad.degrowth.net/uploads/upload_200ac3c474d970d7a5017839489565f5.png)

## 2，初始化
![](https://pad.degrowth.net/uploads/upload_d4e9939f1b4f1cd0617843b8d8ad86cc.png)
![](https://pad.degrowth.net/uploads/upload_0c571eaa59206c3998fa232709db9505.png)
![](https://pad.degrowth.net/uploads/upload_3f3f99adce42c79ae0aeeb0a87a66502.png)
![](https://pad.degrowth.net/uploads/upload_3129cfedf6e9dae60ca406b567142d97.png)
![](https://pad.degrowth.net/uploads/upload_6a34fc17b6c9a18710d8316ea4eafc81.png)
![](https://pad.degrowth.net/uploads/upload_48b4806e913b42db5dae1a196bacf618.png)
![](https://pad.degrowth.net/uploads/upload_cd7d06ab11a67408d5cb56584403124e.png)
注意：这里的strlen得到3，不是4。长度不算\0
![](https://pad.degrowth.net/uploads/upload_c7de669c0a10efb1ff9b5b539d6e4774.png)

## 3，下标
![](https://pad.degrowth.net/uploads/upload_4831798dcf0c1a1c1714c20a8346e2cd.png)
![](https://pad.degrowth.net/uploads/upload_20bbb02533d1eaf1e9b59db232c3a966.png)
![](https://pad.degrowth.net/uploads/upload_ec63e812cc160b88c0887d9fa01aa8db.png)

## 4，打印
![](https://pad.degrowth.net/uploads/upload_bdbd37edf9c6841e30c458a0a62cca69.png)
![](https://pad.degrowth.net/uploads/upload_3241e46fb1c5a8d836c3797ecd47011b.png)
![](https://pad.degrowth.net/uploads/upload_77e2e2f650037c119c645f07962cf334.png)
![](https://pad.degrowth.net/uploads/upload_3c6e4b76113cab230d3980df8fa8d607.png)
![](https://pad.degrowth.net/uploads/upload_54985357ef713547a4348179d176b9d3.png)
![](https://pad.degrowth.net/uploads/upload_77d557ead933514493af4fd586d7ebcb.png)
![](https://pad.degrowth.net/uploads/upload_90357e6d36e6368435eef3f5b9c910da.png)

## 5，二维数组
![](https://pad.degrowth.net/uploads/upload_81468b0a106fd889e152283e02e704b3.png)
![](https://pad.degrowth.net/uploads/upload_70f07b6a2d85e33eb28a5d5708e1696b.png)
![](https://pad.degrowth.net/uploads/upload_7f46e5ff639c5f2a2a04e064c17eadba.png)
![](https://pad.degrowth.net/uploads/upload_f9e7fca1d75626608fb2053bd6097547.png)
![](https://pad.degrowth.net/uploads/upload_ec8bafa4015cce6111e2e17681a38b82.png)
![](https://pad.degrowth.net/uploads/upload_7876a2fa0b4dca29777ce0e28f2b0dec.png)
### （1）二维数组的使用
![](https://pad.degrowth.net/uploads/upload_f69b3a1622876e92d5c8c4ebf3ff72b0.png)

（2）二维数组在内存中的储存
![](https://pad.degrowth.net/uploads/upload_d4200c365cf4feac4bfecf8b26dc1f0d.png)
![](https://pad.degrowth.net/uploads/upload_35c6a6a19f03e7eeb67f09992dd427f3.png)
![](https://pad.degrowth.net/uploads/upload_85eea1160abe10a7a3eb6ddaca1c76f4.png)
所以行不能省略
## 6，数组作为函数参数
### （1）冒泡排序
![](https://pad.degrowth.net/uploads/upload_3ef8b8b258bd208c766d9da64440d710.png)
![](https://pad.degrowth.net/uploads/upload_cfdeced35e8fb8d8058f4f4272f01e2c.png)
注意：当数组以形参传到函数内部时，是无法计算元素个数的
![](https://pad.degrowth.net/uploads/upload_4e5ecea98450eeeae3e26f0714b923ef.png)
注意：当数组以形参传到函数内部时，是无法计算元素个数的

### （2）数组名
![](https://pad.degrowth.net/uploads/upload_641e6ec228f02bd3173e4ae597130632.png)
![](https://pad.degrowth.net/uploads/upload_2ae448dff83903be2323968958e4d9a1.png)
![](https://pad.degrowth.net/uploads/upload_8b4adbef019f7d9cb767404409e269da.png)
![](https://pad.degrowth.net/uploads/upload_3e0e95ec8d939c0ced5b8b0c7a78dd23.png)
# 12.函数（3.1）
## 1，分类
![](https://pad.degrowth.net/uploads/upload_3ba8accb422446cc9df7cdb739b7c676.png)

### （1）库函数
![](https://pad.degrowth.net/uploads/upload_1a824cbf1aa7786ac7c1782f9fca530e.png)

#### ①strcpy
![](https://pad.degrowth.net/uploads/upload_b5a5f67b561a43c63c29e38456442179.png)
![](https://pad.degrowth.net/uploads/upload_cbe255a49842f21b7a58ce75b017bf70.png)

#### ②memset
![](https://pad.degrowth.net/uploads/upload_05960e1a978f5a11263c070bef94a018.png)
![](https://pad.degrowth.net/uploads/upload_a1abaf652e90eea7296c0dde075cbd7c.png)
![](https://pad.degrowth.net/uploads/upload_519d4f1135c2e6bd4151ae755872cd85.png)
#### ③10的次方
![](https://pad.degrowth.net/uploads/upload_bd3bce19dacb6fea3c033d0d087b68b9.png)
![](https://pad.degrowth.net/uploads/upload_f813a6f1df8149fde67ff668e41051e7.png)
#### ④保留n位小数，四舍五入
![](https://pad.degrowth.net/uploads/upload_a6c09b6bf55b0cea339c552ef6cc6e3d.png)
round函数是一个数学函数，用于将一个浮点数四舍五入为最接近的整数。
![](https://pad.degrowth.net/uploads/upload_169768cb30756ee9fa9c7b11506d4d8b.png)

### （2）自定义函数
![](https://pad.degrowth.net/uploads/upload_d9d394caa344da8195c6d1c645428db7.png)
#### ①int get_max( , )
![](https://pad.degrowth.net/uploads/upload_a3195deecd6decdfd0f1886783ff15f8.png)
![](https://pad.degrowth.net/uploads/upload_39901ecd046c5580152e73178fb36bc3.png)
#### ②void swap(  ,  )
![](https://pad.degrowth.net/uploads/upload_b360358bc489b427c64249fba66900be.png)
![](https://pad.degrowth.net/uploads/upload_eac69fd98207b9f710e479521dd5c6b0.png)
![](https://pad.degrowth.net/uploads/upload_3511f92438d381361de63693b46f8973.png)
（如果是要改变主函数里面的变量就得传地址，用指针）

## 2，函数的调用
### （1）形参、实参
![](https://pad.degrowth.net/uploads/upload_23f312dce9740a14f0acae9a0e1aeaec.png)
![](https://pad.degrowth.net/uploads/upload_62711543afe6ccb74b32d295fc65e126.png)
![](https://pad.degrowth.net/uploads/upload_fe33cdd4654d60990f9b99ad08e9087d.png)
![Uploading file..._xp1w43owr]()

### （2）概念
![](https://pad.degrowth.net/uploads/upload_52e2c18b0009ef134b8c25b93669a56f.png)
![](https://pad.degrowth.net/uploads/upload_515b045144b64af23383e405797b71f7.png)

### （3）练习
#### ①判断素数（质数）
![](https://pad.degrowth.net/uploads/upload_a170bf7c46ba80b25f722b1df8597cc9.png)
![](https://pad.degrowth.net/uploads/upload_67cc9acbb64ef6552cfe5f422f8e7f42.png)
![](https://pad.degrowth.net/uploads/upload_50ed0d54d31d94c6d9b5bd715918c672.png)
![](https://pad.degrowth.net/uploads/upload_43be55fe842b1ae513e7ee0f342ed27b.png)
不是素数的数a可以拆成非1非自身的两个乘数，必定一个小于根号下a,一个大于根号下a，只判断小的那个是否存在就能判断a是否为素数

#### ②判断闰年
注：公历年份是4的倍数且不是100的倍数为普通闰年
1、公历闰年计算原则（按一回归年365天5小时48分45.5秒）
1)普通年能整除4且不能整除100的为闰年。（如2004年就是闰年,1900年不是闰年）
2)世纪年能整除400的是闰年。(如2000年是闰年...

#### ③写一个函数，实现整形有序数组的二分查找

#### ④写一个函数，每调用一次这个函数，就会将num的值加1
![](https://pad.degrowth.net/uploads/upload_8c073d63aa6830dd59ff76d93ef37a69.png)

## 3，函数的嵌套调用和链式访问
### （1）函数的嵌套调用
![](https://pad.degrowth.net/uploads/upload_0c3c02c30adfb077b6bb5b30c2ec9088.png)
![](https://pad.degrowth.net/uploads/upload_42e5653e1d3f67c6a89af2286ab2aba2.png)
### （2）链式访问
![](https://pad.degrowth.net/uploads/upload_9fde4a4dd80fb59b31f6bb21a67432a9.png)
![](https://pad.degrowth.net/uploads/upload_28dcc6f34d2849fe78461e26d3f41959.png)
（VS2019    strlen没引头文件也能用）
![](https://pad.degrowth.net/uploads/upload_cc29922dcf4744c4569f24267651d25d.png)
![](https://pad.degrowth.net/uploads/upload_8d3f359848ef486f84dd60e87bff3e6b.png)
![](https://pad.degrowth.net/uploads/upload_be82dc728f022a146b94eb8eafd77040.png)
![](https://pad.degrowth.net/uploads/upload_50718a666b7baaffb794fe0647b31c54.png)

## 4，函数的声明和定义
### （1）函数声明
![](https://pad.degrowth.net/uploads/upload_5f735fee055e3bebfe7a96bf60a527a9.png)
![](https://pad.degrowth.net/uploads/upload_290603e2c3f32800ce6065e3723cf992.png)
（↑这种使用方法较少用，一般的使用方法见↓）
函数声明放在头文件（.h）中
![](https://pad.degrowth.net/uploads/upload_1ac3efd6352f2335888931d394ecdd20.png)
![](https://pad.degrowth.net/uploads/upload_abe36c5e32e35c7edd3b41664a5b2657.png)
头文件的包含相当于替换：
![](https://pad.degrowth.net/uploads/upload_072106317acfe7aef43230e497b280a7.png)
![](https://pad.degrowth.net/uploads/upload_6b7566c33234a812f5302fe7c7d1b9c7.png)

用静态库lib加密文件变乱码的使用方法：
![](https://pad.degrowth.net/uploads/upload_e00c3fda5206fe515efdbf5d374ea3be.png)
### （2）函数定义
![](https://pad.degrowth.net/uploads/upload_93cc7e57903960de6ae6563c4b5814b8.png)

## 5，函数递归
### （1）概念
![](https://pad.degrowth.net/uploads/upload_2d45b4551db4b9591dfe5a619a50caac.png)

### （2）例子
#### ①（栈溢出）
![](https://pad.degrowth.net/uploads/upload_3b5ae21a11d6980abce1234a7d20d938.png)

#### ②练习1
![](https://pad.degrowth.net/uploads/upload_74eff3dcb9d147e1602eb697dbc5a6b1.png)
![](https://pad.degrowth.net/uploads/upload_2c48392be08424c2786bcacadf761ad5.png)
![](https://pad.degrowth.net/uploads/upload_b5d3396d05470946862fa45979a51991.png)
详解：
![](https://pad.degrowth.net/uploads/upload_c24903991cced69a78b78e490de22a2c.png)
![](https://pad.degrowth.net/uploads/upload_16591368dd362d850ebf16c09682e886.png)
![](https://pad.degrowth.net/uploads/upload_3e5b5fa2e9cc25b743bd81d078a0d9bc.png)
![](https://pad.degrowth.net/uploads/upload_1f2f2298ae0c544917ffd553d80fe8b4.png)
![](https://pad.degrowth.net/uploads/upload_2a1eda1cbc5b8c54af259d628a43a085.png)
![](https://pad.degrowth.net/uploads/upload_8545a6ad26399efa297f116309579235.png)

#### ③(栈溢出)
![](https://pad.degrowth.net/uploads/upload_a8220bd636b03e394b3135759a9dcca6.png)
（见5.3）

#### ④练习2
![](https://pad.degrowth.net/uploads/upload_41dd88e057f484f6120bd5763c08cd85.png)

求字符串长度方法（10.2）：
![](https://pad.degrowth.net/uploads/upload_7d7dbf0b3f71b8039b4b2a47d311fda3.png)
我们要做的：
![](https://pad.degrowth.net/uploads/upload_bf3e207b6e1a7d30738f6d1c55ace8e7.png)
（注意：以下为err）
![](https://pad.degrowth.net/uploads/upload_db393a23ef26db13e9f904df6a1ff79c.png)
![](https://pad.degrowth.net/uploads/upload_c13477c6e5985ce96b2024af72b0448f.png)

##### 正确的做法：
递归
![](https://pad.degrowth.net/uploads/upload_6250bbc7d8049077319a95827e953b34.png)
![](https://pad.degrowth.net/uploads/upload_04f6ed71f16fafc69d754b3291a91ff0.png)

![](https://pad.degrowth.net/uploads/upload_0c51a3b718da666bdc9aabd916d03248.png)

### （3）栈溢出
![](https://pad.degrowth.net/uploads/upload_c6452703515ecc4832aeeb1198610b64.png)
![](https://pad.degrowth.net/uploads/upload_e1e58301a8005b06256bba2a1094929b.png)
![](https://pad.degrowth.net/uploads/upload_19dc02d1b29d9f3947952b1c87564a7c.png)

### （4）递归与迭代
迭代：重复地做一件事情
#### ①练习1
![](https://pad.degrowth.net/uploads/upload_f73ea7447bc83c026d57db9e582707bf.png)
![](https://pad.degrowth.net/uploads/upload_1f820f5b6051f90b827bc38163e06fc2.png)
![](https://pad.degrowth.net/uploads/upload_230e747a31ce61d096dfe5d5d154ce05.png)
![](https://pad.degrowth.net/uploads/upload_8703e95ae61562f2739af37286f3bb89.png)

#### ②练习2（效率低下）
![](https://pad.degrowth.net/uploads/upload_2fe5150e2b1b5602d0de96c4774fdc33.png)
![](https://pad.degrowth.net/uploads/upload_9f74439f3b0e7aaa77c58f74d0b0c909.png)
![](https://pad.degrowth.net/uploads/upload_93f545436d5859786003784b8dfc5469.png)
![](https://pad.degrowth.net/uploads/upload_be2e6505325c2eb0a6978809e2437e54.png)
![](https://pad.degrowth.net/uploads/upload_370de165ccf3a007367e297e1b234300.png)
![](https://pad.degrowth.net/uploads/upload_78ed126924ef00261c5cc260e27f56a2.png)
![](https://pad.degrowth.net/uploads/upload_b35eeb8126fdae6f0179534ada1e9ad9.png)

#### ③汉诺塔
![](https://pad.degrowth.net/uploads/upload_bd396c8218362322eb88ff8399183a54.png)

#### ④青蛙跳台阶
青蛙可跳1/2阶台阶，问：n个台阶有几种跳法？
（这就是个斐波那契数列问题）

# 13.指针（7）

指针 - OI Wiki (oi-wiki.org)
理解C语言的传值与传指针 - 知乎 (zhihu.com)

## 1，概念（见7）
![](https://pad.degrowth.net/uploads/upload_45621b416df75bc79f5b1951d2d424c5.png)
![](https://pad.degrowth.net/uploads/upload_68945191fc71076269b7efa576770b6f.png)

## 2，指针和指针类型
### （1）指针类型的ee
![](https://pad.degrowth.net/uploads/upload_c54f35d414928b33cfe82d7b9713adfa.png)
![](https://pad.degrowth.net/uploads/upload_619c41bdd84667f057fe23cd99048a46.png)
![](https://pad.degrowth.net/uploads/upload_fd0ca8067b9e378712c71b5a6255d35e.png)
![](https://pad.degrowth.net/uploads/upload_f0d3d9a8dab9dcc1250e77c22437e0c7.png)
![](https://pad.degrowth.net/uploads/upload_15d2ab329f55559d227e271871feda99.png)
![](https://pad.degrowth.net/uploads/upload_36d508aa9964ff5f251cfe9727ee9cec.png)
![](https://pad.degrowth.net/uploads/upload_0b963058828c997ac652e4ddbfef3dfb.png)
![](https://pad.degrowth.net/uploads/upload_81af1119f0cab0503063be531eec8039.png)
![](https://pad.degrowth.net/uploads/upload_d54bb6a595297d7c801659cdea103938.png)
![](https://pad.degrowth.net/uploads/upload_6a88c577ef89d276a4772a1e16f982c9.png)

## 2，野指针
![](https://pad.degrowth.net/uploads/upload_b6370c3d8258e9e98df139a41a89facf.png)

### （1）野指针成因
![](https://pad.degrowth.net/uploads/upload_61bff0ea0891b8cea65b456bf5a084b6.png)
![](https://pad.degrowth.net/uploads/upload_db744ed04142e681ce13e30fb9f1a067.png)
![](https://pad.degrowth.net/uploads/upload_b2042c6801662891a9714403b5e0ca35.png)
![](https://pad.degrowth.net/uploads/upload_78aa8c4139aef41c08ffb07f9ca4e77a.png)
![](https://pad.degrowth.net/uploads/upload_c44dfa1d7da19f72252d3ace8aa54b1d.png)
![](https://pad.degrowth.net/uploads/upload_42765f0945e48d22d3a8e3a5bb02fc97.png)
![](https://pad.degrowth.net/uploads/upload_4f5aea8ccf3ae7bc7575f58c8eb540f0.png)

### （2）如何规避野指针
![](https://pad.degrowth.net/uploads/upload_47e20b5dab2c53a6337bbe039ae56b0b.png)
#### 习惯初始化
变量也是
![](https://pad.degrowth.net/uploads/upload_a20c6540b32edfa7f54023b9c8b5950e.png)
初始化指针
![](https://pad.degrowth.net/uploads/upload_4f706419dddeb5d26df47fbe23920461.png)

#### 使用前检查有效性
![](https://pad.degrowth.net/uploads/upload_b5eaa824abf09af536cd52bd883487f3.png)
0没有分配给用户，不能放
![](https://pad.degrowth.net/uploads/upload_99f4770480c43f32a68fbdc669272241.png)

#### 总结
一个指针变量，当不知道它指向什么地方时，把它置为空指针；当它指向的空间被释放时，也把它置为空指针；当它指向有效空间时，给它地址。使用前先判断是否为空指针

## 3，指针运算
### （1）指针+-整数
![](https://pad.degrowth.net/uploads/upload_046353ba473d6ff9c774f725e4f65aa9.png)
![](https://pad.degrowth.net/uploads/upload_dba2df46b343086251f30a636365c57e.png)

（2）指针-指针
![](https://pad.degrowth.net/uploads/upload_2b23e188769a0c555599c41a47451a16.png)
![](https://pad.degrowth.net/uploads/upload_9a38998eca5d69102849dea24170f393.png)
![](https://pad.degrowth.net/uploads/upload_40372ae7d3c9355ce594198144bb1063.png)

e.g.:
![](https://pad.degrowth.net/uploads/upload_aff225726a20d8e8390c988bcc1fbae8.png)
![](https://pad.degrowth.net/uploads/upload_a0fbd876bc561703a58bd4e3f8edf7f4.png)
![](https://pad.degrowth.net/uploads/upload_6e8e5aa85893693c8365c9d52f441532.png)
![](https://pad.degrowth.net/uploads/upload_abb768a99b218286b8ede693a2ed8f1a.png)

### （3）指针的关系运算
![](https://pad.degrowth.net/uploads/upload_9b6c0cc2da69e1ee9617ead0d970dfb8.png)
![](https://pad.degrowth.net/uploads/upload_54ee5dd962fb0f7bce491d2443cc39c1.png)
![](https://pad.degrowth.net/uploads/upload_29177a5046668e24c848d2312de6df07.png)
![](https://pad.degrowth.net/uploads/upload_4a13af239171508ebb8870e33178bf7e.png)

## 4，指针和数组
### （1）数组名（10.6.2）

![](https://pad.degrowth.net/uploads/upload_94e23afee03017985ff67563f0a67217.png)

### （2）[]
![](https://pad.degrowth.net/uploads/upload_19eb7e1b927c5b585bd250fe8d9ad3b5.png)
![](https://pad.degrowth.net/uploads/upload_15bc4dd04d3aaf1b681ebc299f245901.png)

理解深层，代码爱怎么写怎么写

### （3）指针数组
![](https://pad.degrowth.net/uploads/upload_71947ac7d0c5d0748be0c765003ecdf2.png)
![](https://pad.degrowth.net/uploads/upload_d2eaa36006ad929423214a46c6f61e67.png)
![](https://pad.degrowth.net/uploads/upload_fa822c951ffe25f19aae9da3c04b75fc.png)
![](https://pad.degrowth.net/uploads/upload_fa37a1ade58ad96623b68a2cced35aeb.png)
![](https://pad.degrowth.net/uploads/upload_6b764e2319700f78506953c8f52eb195.png)

## 5，二级指针
![](https://pad.degrowth.net/uploads/upload_e17bcbdd7da48b3cc628716c7b7d91a6.png)
![](https://pad.degrowth.net/uploads/upload_9d3faa2e2379bd0ad046468939090ac1.png)
![](https://pad.degrowth.net/uploads/upload_e96cff727cf3bd84108b7b4f0ba37ed9.png)

## 6，字符指针
### （1）存储一个字符
![](https://pad.degrowth.net/uploads/upload_cbdf4782b44c5194ee44c4c1fe05aae6.png)

### （2）存储字符串
![](https://pad.degrowth.net/uploads/upload_7ec9d5c1b56cacdcb90c980468d47fae.png)
![](https://pad.degrowth.net/uploads/upload_be2d21544b592a5e5a2ae0f5c1660178.png)
![](https://pad.degrowth.net/uploads/upload_df83b22c3abbeece9fa6627e42b47308.png)
![截图 (3)](https://github.com/iA-oO/notes/assets/138574037/bab1f104-86bb-49ef-9ccd-4861c5dea0c9)
![](https://pad.degrowth.net/uploads/upload_6501e50d12b29b89fc2f36339c40b406.png)
![](https://pad.degrowth.net/uploads/upload_360ba5eb0da18ade3c15a49ee987116d.png)

## 7，数组指针
### （1）概念
![](https://pad.degrowth.net/uploads/upload_745da7b8101d3aa2e5a9b9de26f5e171.png)
![](https://pad.degrowth.net/uploads/upload_c85d153e1484d843b4a9ec30bd94085b.png)
![](https://pad.degrowth.net/uploads/upload_8f97e321232c1222b2ac49403cdb8467.png)

### （2）数组、数组名
![](https://pad.degrowth.net/uploads/upload_da327bfc740a697a3c88a9515008c749.png)
（见10.4）
![](https://pad.degrowth.net/uploads/upload_607e71cc9befd3a763a8d1776c3cc8d2.png)
![](https://pad.degrowth.net/uploads/upload_ae473d58a29cd7a7f7231ba60b4b4698.png)
![](https://pad.degrowth.net/uploads/upload_630f7aaf674ee3f1b16054005d449c08.png)
![](https://pad.degrowth.net/uploads/upload_cb0053307c7c6fba6ae4bfd85bde82ea.png)

#### 使用
##### ①
![](https://pad.degrowth.net/uploads/upload_cc8b94b1a0b9601bfe08b274bf3deb5a.png)

##### ②
写法1：
![](https://pad.degrowth.net/uploads/upload_00cbc241c6bfb3915a7aa98e06a5d01d.png)
写法2：
![](https://pad.degrowth.net/uploads/upload_a0d02358939817f5ecdde9ca24557fd7.png)
![](https://pad.degrowth.net/uploads/upload_bb6108efddb20609b76de26dafa322df.png)

##### ③分析代码意思
![](https://pad.degrowth.net/uploads/upload_87076dbbe14f1c3b8426cee9ca946e6a.png)
![](https://pad.degrowth.net/uploads/upload_677672522b6f57b19039141350142625.png)

### （3）数组参数、指针参数
#### ①一维数组传参
![](https://pad.degrowth.net/uploads/upload_bb2b7b13355ca9e9e123f508b368aa79.png)
#### ②二维数组传参
![](https://pad.degrowth.net/uploads/upload_db93b7f0010723fe954a804f6a8ce9a5.png)
![](https://pad.degrowth.net/uploads/upload_3e167206fa34060a1601f66e9b7eb909.png)

#### ③一级指针传参
![](https://pad.degrowth.net/uploads/upload_257d5a012d3fdcc2fd499a33c3e1f424.png)
![](https://pad.degrowth.net/uploads/upload_ff69cf00640d32142c7626d6e7d624df.png)
![](https://pad.degrowth.net/uploads/upload_83a02731b01152e15ccd265a0f025bb4.png)

#### ④二级级指针传参
![](https://pad.degrowth.net/uploads/upload_e8058f9cd9b0b067933311111f7dd7d7.png)
![](https://pad.degrowth.net/uploads/upload_aca17498c43e1a24a917ea28b22d5014.png)

### （4）梳理
![](https://pad.degrowth.net/uploads/upload_9fbae9f9f1c72df280ded754d32bd314.png)

## 8，函数指针
### （1）概念
![](https://pad.degrowth.net/uploads/upload_f78a999ec047c6acd289b3d5e5581837.png)
![](https://pad.degrowth.net/uploads/upload_3665fcd40d019a72e656dfb559cdee0e.png)

### （2）数组、数组名
![](https://pad.degrowth.net/uploads/upload_659a426fb04ba7ab1f128b85046a3257.png)
![](https://pad.degrowth.net/uploads/upload_41e7d2a72f21199472c2f85575d132b7.png)

### （3）练习，写法
#### ①
![](https://pad.degrowth.net/uploads/upload_ab08c73cfa4cec84ef315a7409ae9b5e.png)
![](https://pad.degrowth.net/uploads/upload_47187e4c715278d457edd6ba3609a099.png)
![](https://pad.degrowth.net/uploads/upload_6e81d30ba80a30c660e89772ba9428dd.png)
![](https://pad.degrowth.net/uploads/upload_1e859f411cf0777d3dd326f90927b8e9.png)
![](https://pad.degrowth.net/uploads/upload_aeeb12e3dd009d6f967dc6d01565ab5d.png)
![](https://pad.degrowth.net/uploads/upload_9975d1c620999d5be57186b296c4d044.png)
总结：
![](https://pad.degrowth.net/uploads/upload_0df59c013ab1d467aa4ad9c0dadeaa08.png)

#### ②
![](https://pad.degrowth.net/uploads/upload_e917735e83db39add26890177b3a8703.png)
![](https://pad.degrowth.net/uploads/upload_739335fd16641a7268120b4c7583e339.png)
![](https://pad.degrowth.net/uploads/upload_05a1ab34d5dfd58ed39bf9839f50715b.png)

## 9，函数指针数组
### （1）概念
![](https://pad.degrowth.net/uploads/upload_f7285df562ce3c1140cdf148a2623410.png)
![](https://pad.degrowth.net/uploads/upload_d5d115cd786401cdc126f18840d9a272.png)

### （2）实例
![](https://pad.degrowth.net/uploads/upload_4cce1f4ebdedebf78ad686be32d7936b.png)
![](https://pad.degrowth.net/uploads/upload_8ca28b02e01f56f8bfc8ecd42f6e5010.png)
![](https://pad.degrowth.net/uploads/upload_ff466feb9f911f699d4b64a9f9965a67.png)
![](https://pad.degrowth.net/uploads/upload_abf43f1a02e7257d6fa97adce24180f8.png)
![](https://pad.degrowth.net/uploads/upload_9a4fb2d3bf5ead2795920d4825554024.png)

## 10，指向函数指针数组的指针，概念梳理
![](https://pad.degrowth.net/uploads/upload_e59d2ad694d8db7b5dbf8d285e0650d7.png)
![](https://pad.degrowth.net/uploads/upload_9b9e5180e226d617593c63ed1260ee01.png)

## 11，回调函数
### （1）概念
![](https://pad.degrowth.net/uploads/upload_1deaf81b5e87e61636f3b3e1fc96dc2f.png)
![](https://pad.degrowth.net/uploads/upload_d715883e0a27248aaf30893a8aa2bc09.png)

### （2）实例
（前同9.2实例）
![](https://pad.degrowth.net/uploads/upload_bf6dbebbdf308f91a3f488f2be4a590d.png)
![](https://pad.degrowth.net/uploads/upload_9abf418f537b3dc5cf7b2afc2af0bcbf.png)
![](https://pad.degrowth.net/uploads/upload_f406dc50da898e4e87225b33a5a8defa.png)
![](https://pad.degrowth.net/uploads/upload_bf28e1b1733a64cf674cbe3912b96a4b.png)

### （3）qsort函数

# 13.结构体
## 1，结构体（8）
### （1）结构体类型的声明
#### ①概念
![](https://pad.degrowth.net/uploads/upload_bf636c21a90d2b36e6fd2dccefc0dbf6.png)
![](https://pad.degrowth.net/uploads/upload_17513c1a4a2bf7c6ac507ea3798fdda9.png)
![](https://pad.degrowth.net/uploads/upload_f0de7c158b9fb055b6f9f7320f0d202b.png)
![](https://pad.degrowth.net/uploads/upload_3566d882456619ef0875eefca4f1358d.png)

#### ②变量定义和初始化
![](https://pad.degrowth.net/uploads/upload_ceb37036dab68ddb53e52748464abfba.png)
![](https://pad.degrowth.net/uploads/upload_f039d5c5439bc513cf5910d292701494.png)

### （2）结构体成员的访问
![](https://pad.degrowth.net/uploads/upload_ed1ee26402c8deba9a06c5f2092fb8a0.png)
![](https://pad.degrowth.net/uploads/upload_61988ae606dfa03a2338e9f93308a56d.png)
![](https://pad.degrowth.net/uploads/upload_ddf02827e7f76d043dd465e1b214d480.png)

### （3）结构体传参
#### ①方法
![](https://pad.degrowth.net/uploads/upload_a1ab72b620de9dee12b5770ef7b96aa8.png)
![](https://pad.degrowth.net/uploads/upload_2fd68a97ee2dba13eecfb30d1d72f02c.png)
![](https://pad.degrowth.net/uploads/upload_a15708f97b8dcce7d54a893aacd0b669.png)
![](https://pad.degrowth.net/uploads/upload_197fcf639f4fdf0b07134cd7689d8523.png)
![](https://pad.degrowth.net/uploads/upload_32f2b504d914a2c6a4b3d27c643c0d26.png)

#### ②参数压栈
![](https://pad.degrowth.net/uploads/upload_059ff11f88cc1bc45c2deeb38da99043.png)
![](https://pad.degrowth.net/uploads/upload_e1b93235b0f9ca3d0b733b2d88851d74.png)
走完之后main函数占用的空间也会还给它
传结构体到时候压栈空间可能比较大，效率比较低，用传指针的方式只传4个字节，效率更高一些
具体可了解：
![](https://pad.degrowth.net/uploads/upload_9b2a83804be44f58dbe626a89fe9c6ce.png)

## 2，链表
### （1）概念
![](https://pad.degrowth.net/uploads/upload_9f8d7e6292d40c2ac11b053817fa4df5.png)

### （2）链表结点的结构
![](https://pad.degrowth.net/uploads/upload_77d9ef48ba40525c7efb770e7764a7d3.png)
![](https://pad.degrowth.net/uploads/upload_6d8b888879ccc4498b84b802dfb4cd5a.png)

### （3）双链表
![](https://pad.degrowth.net/uploads/upload_3ecc2ccbf352688e2d0e2332610702e5.png)
![](https://pad.degrowth.net/uploads/upload_8a8272b2bf075cceae0fd817a467099d.png)
![](https://pad.degrowth.net/uploads/upload_08996042e91f6b4d70275d4469e18402.png)
![](https://pad.degrowth.net/uploads/upload_cf32b3e6138d2dfb7fbec65f1c158ba4.png)

### （4）搜查
#### ①概念
![](https://pad.degrowth.net/uploads/upload_e2dade72188e30115e9084f1a5267dd1.png)
![](https://pad.degrowth.net/uploads/upload_35ea4feb67f314339feabd7d14608be6.png)

#### ②e.g.1
![](https://pad.degrowth.net/uploads/upload_b582c511db32b2198852875e6b295827.png)
![](https://pad.degrowth.net/uploads/upload_c3c1833b8c5f7a7e4877ed4115f0f2e2.png)
![](https://pad.degrowth.net/uploads/upload_7027554b736e9275556abbf59470a321.png)

#### ③e.g.2
![](https://pad.degrowth.net/uploads/upload_efe7262176b97272754c64512b3f0b10.png)
![](https://pad.degrowth.net/uploads/upload_8846b085efb90945e11dece581a21405.png)

### （5）插入
#### ①概念
![](https://pad.degrowth.net/uploads/upload_45503ca0f366ddcd66c6b3b0b324d9c6.png)
![](https://pad.degrowth.net/uploads/upload_48bf629fc16e57faef9c4d3d29082b2d.png)
![](https://pad.degrowth.net/uploads/upload_9dd2b030fbb9b3326a946b085cadb5d8.png)

#### ②e.g.
![](https://pad.degrowth.net/uploads/upload_78376fb97a8b1bf4c834ab5b269e0012.png)
![](https://pad.degrowth.net/uploads/upload_807ac32a43a981376c0d16f15c452985.png)
![](https://pad.degrowth.net/uploads/upload_02ebae43fe3e7176dd922f6471010111.png)
![](https://pad.degrowth.net/uploads/upload_85a3b17b66c41193bc156cfccf996d76.png)

### （6）删除
#### ①概念
![](https://pad.degrowth.net/uploads/upload_b4a1799427b44b7ddac622db6f53de77.png)
![](https://pad.degrowth.net/uploads/upload_0b9a727f23e91460079c19966fc7806a.png)

#### ②e.g.
![](https://pad.degrowth.net/uploads/upload_98d2ed4f90179d41937cc2566a7af119.png)
![](https://pad.degrowth.net/uploads/upload_cde25571921ec26cc5db269afff9261f.png)
![](https://pad.degrowth.net/uploads/upload_d01c700ad31faa0e46195304803b1ada.png)

### （7）单链表
#### ①单链表的基本结构
![](https://pad.degrowth.net/uploads/upload_1c75f7f4b407bd625351eafda0e14d94.png)
![](https://pad.degrowth.net/uploads/upload_76b0b2354ba3fb0d2785fddb344fc125.png)

#### ②单链表元素的添加、删除
![](https://pad.degrowth.net/uploads/upload_e1c39d6faad179c546621408022e0de9.png)

### （8）哨兵
#### ①概念
![](https://pad.degrowth.net/uploads/upload_d61b58ff49b6c5a724162797cb4ff9b7.png)

#### ②删除的e.g.
![](https://pad.degrowth.net/uploads/upload_2104f63e80a894e8bcc3a609db22a1b9.png)
![](https://pad.degrowth.net/uploads/upload_5589b600ac99f54c5577d8708160a5ba.png)
![](https://pad.degrowth.net/uploads/upload_e9590ed43d5893cd2578809871647491.png)
![](https://pad.degrowth.net/uploads/upload_f28c9a545f403424f6eecbe7ee02bdf8.png)

#### ③搜查
![](https://pad.degrowth.net/uploads/upload_15e038144fe6ca2fc058093a8348f2bb.png)

#### ④插入
![](https://pad.degrowth.net/uploads/upload_8f2e4976238704b17db8f9f847d86e96.png)

#### ⑤意义
![](https://pad.degrowth.net/uploads/upload_6111a4bbdd27ceffc45659600470813f.png)







