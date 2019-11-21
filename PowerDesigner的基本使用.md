### PowerDesigner的基本使用

###### 1.如何建一个物理模型

Ctrl+N  新建模型

<img src="C:\Users\源\AppData\Roaming\Typora\typora-user-images\image-20191121144151793.png" alt="image-20191121144151793" style="zoom: 80%;" />

![image-20191121113657667](C:\Users\源\AppData\Roaming\Typora\typora-user-images\image-20191121113657667.png)

这个是工具，如果不小心x掉了 ：工具->自定义工具 勾选palette

![image-20191121113851631](C:\Users\源\AppData\Roaming\Typora\typora-user-images\image-20191121113851631.png)

点击空白后![image-20191121114048952](C:\Users\源\AppData\Roaming\Typora\typora-user-images\image-20191121114048952.png)

双击

![image-20191121114517485](C:\Users\源\AppData\Roaming\Typora\typora-user-images\image-20191121114517485.png)

<img src="C:\Users\源\AppData\Roaming\Typora\typora-user-images\image-20191121144913440.png" alt="image-20191121144913440" style="zoom:50%;" />

另外如果没有默认设置和注释那一栏可以，在这按ctrl+u,勾选comment和default value

###### 2.如何添加外键，主键等

上面双击要设置的那一列



<img src="C:\Users\源\AppData\Roaming\Typora\typora-user-images\image-20191121150413673.png" alt="image-20191121150413673"  />



如果要设置外键，先建立好两个表，点击

![image-20191121151639208](C:\Users\源\AppData\Roaming\Typora\typora-user-images\image-20191121151639208.png)

先选依赖的表拉向另外一张表

![image-20191121151803199](C:\Users\源\AppData\Roaming\Typora\typora-user-images\image-20191121151803199.png)

这里字段都是随意设置的

双击中间的箭头可以设置外键的属性

###### 3.如何表添加编码，注释等

最上面点 数据库->edit currentDBMS..如下图中value加入

ENGINE = %s : list = BDB | HEAP | ISAM | InnoDB | MERGE | MRG_MYISAM | MYISAM, default = InnoDB
DEFAULT CHARACTER SET = %s : list = utf8 | gbk, default = utf8

<img src="C:\Users\源\AppData\Roaming\Typora\typora-user-images\image-20191121151140027.png" alt="image-20191121151140027" style="zoom: 67%;" />

在点击表中如下图，出现在左边下面，双击添加到右边，点击确定。

<img src="C:\Users\源\AppData\Roaming\Typora\typora-user-images\image-20191121151328950.png" alt="image-20191121151328950" style="zoom:50%;" />

###### 4.如何设置唯一约束

![image-20191121152533951](C:\Users\源\AppData\Roaming\Typora\typora-user-images\image-20191121152533951.png)

###### 5.如何导出sql文件

Ctrl+G 

###### 

