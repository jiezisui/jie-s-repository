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


