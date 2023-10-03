#**个人信息**
<img src="https://github.com/jiezisui/jie-s-repository/assets/146320061/86d87339-61a8-45fc-9bcd-769ccacc1034" width="150" align="right" />
---
-姓名：武彤

-学校：北京印刷学院

-学院：新媒体学院

-班级：数字媒体技术1班

-联系方式：15301336156

---


#**希望能够在414学习到的**

1.将专业学学习中学到的知识，落实到实践中

2.熟悉数字媒体处理工具，包括图像处理软件、音频处理软件、视频编辑软件等

3.了解该专业在各领域的应用

4.关注数字媒体技术的发展趋势

5.培养团队协作能力![9ad31e86gy1h3ypgme718j21hc11pakv](https://github.com/jiezisui/jie-s-repository/assets/146320061/657ac6e5-c775-4110-9709-2a9ec508da97)

---





#算法描述

利用冒泡排序对数组进行排序，依次比较相邻的两个数，将小数放在前面，大数放在后面。

用二重循环实现，外循环变量设为i，内循环变量设为j。假如有n个数需要进行排序，则外循环重复n-1次，内循环依次重复。

代码实现。

#优化代码

每经过一次冒泡，内层循环就可以减少一次。

如果某一轮冒泡没有发生交换，则表示所有数据有序，可以结束外层循环。

#伪代码

假设数组array[0…n-1]表示待排序数组`

For I = 0 to n-2 then

   For j = 0 to n-i-2 then
   
      If array[j] > array[j+1] then
      
         swap(array[j], array[j+1])

![0d7677d0-117b-425e-8e84-1c46763d0fa01](https://github.com/jiezisui/jie-s-repository/assets/146320061/0d89745b-5dfc-43fb-9b53-65498f9025d4)


