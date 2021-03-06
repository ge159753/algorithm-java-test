
## 排序

排序是计算机程序设计中的常用技术，当进行数据处理时，经常需要进行查找操作，而为了查得快、找得准，通常需要将待处理的数据按照关键字的大小有序排列，
以便采用查找效率高的算法进行查找。
这里介绍几种排序算法：插入排序、选择排序、交换排序、归并排序和基数排序。

### 概念：

1. 关键字：记录（排序中经常将数据元素称为记录）中的某个可以用来标识一个元素的数据项，称为关键字项，该数据项的值为关键字。
1. 排序：*排序(Sorting)* 是把一组无序的数据或记录按照关键字值递增或递减重新排列的过程。假设含n个记录的序列为{R1,R2,...,Rn}，
其相应的关键字序列为{K1,K2,...,Kn}，相应的下标序列为1,2,...,n。通过排序，要求找出当前下标序列的一种排列p1,p2,...,pn，使得相应的关键字满足递增或递减关系：Kp1≤Kp2≤...≤Kpn。这样，就得到了一个按关键字的有序排列的记录序列：{Rp1,Rp2,...,Rpn}。

### 以下为几个经典排序算法的简单原理介绍及实现：

- [冒泡排序](https://github.com/lq920320/algorithm-java-test/blob/master/src/test/java/sort/bubble_sort/BubbleSort.md)
- [选择排序](https://github.com/lq920320/algorithm-java-test/blob/master/src/test/java/sort/select_sort/SelectSort.md)
- [快速排序](https://github.com/lq920320/algorithm-java-test/blob/master/src/test/java/sort/quick_sort/QuickShort.md)
- [希尔排序](https://github.com/lq920320/algorithm-java-test/blob/master/src/test/java/sort/shell_sort/ShellSort.md)
- [堆排序](https://github.com/lq920320/algorithm-java-test/blob/master/src/test/java/sort/heap_sort/HeapSort.md)


