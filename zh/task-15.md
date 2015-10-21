这个问题引入了“线性搜索”，这是一个应该透彻学习的流行算法，因为它经常用在更加复杂的编程任务中（排序等）。  

一个在一序列数或者数组上很常见的操作是寻找它们的极值 —— 最大值或最小值。为了完成这个任务，需要一个单独的变量来存储
**当前最大值**（或最小值），然后遍历数组，用其中的每一个元素与这个变量做比较。每当下一个值比这个临时变量大的时候，这
个值应该复制给临时变量（作为新的最大值）。  

当遍历结束后，这个临时的变量将会保存有极值。  

**输入数据** 将会在一行中给你确切的`300`个数字。     
**答案** 应该包括这些数值的最大值和最小值，并用空格分隔。        

示例：  

	输入数据：
	1 3 5 7 9 11 ... 295 297 299 300 298 296 ... 12 10 8 6 4 2
	
	答案：
	300 1