# JavaScript 数据结构与算法（十一）排序.md

## 大O表示法
  O(1)  常数的
  O(log(n))  对数的
  O(n)  线性的
  O(nlog(n))  线性和对数乘积
  o(n²) 平方
  O(2n次方) 指数的
  ![](https://github.com/greendayzz/Data-structure/blob/master/img/big%20O.png)
  推导大O表示法的方式：
    ①用常量1取代运行时间中所有的加法常量
    ②在修改后的运行次数函数中，只保留最高阶项
    ③如果最高项存在且不为1，则去除与这个项相乘的常数

## 冒泡排序
  相比较其他排序算法，效率较低
  思路：
  ![](https://github.com/greendayzz/Data-structure/blob/master/img/bubblesort/%E5%86%92%E6%B3%A1%E6%8E%92%E5%BA%8F%E6%8E%92%E9%AB%98%E5%BA%A6.png)
  ![](https://github.com/greendayzz/Data-structure/blob/master/img/bubblesort/%E5%86%92%E6%B3%A1%E6%8E%92%E5%BA%8F%E6%80%9D%E8%B7%AF.png)
  冒泡排序代码解析：
  ![](https://github.com/greendayzz/Data-structure/blob/master/img/bubblesort/%E5%86%92%E6%B3%A1%E6%8E%92%E5%BA%8F%E6%8E%92%E9%AB%98%E5%BA%A6.png)
  冒泡排序的效率：
  ![](https://github.com/greendayzz/Data-structure/blob/master/img/bubblesort/%E5%86%92%E6%B3%A1%E6%8E%92%E5%BA%8F%E7%9A%84%E6%95%88%E7%8E%87.png)