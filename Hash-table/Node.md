## 136.single-number.py

* 思路：使用异或运算的特点，两个相同元素异或为0，0与任何元素异或不改变元素值。即从第一个元素与所有元素异或，最终剩余的值为只出现一次的元素.
* 时间复杂度=O(n)


## 202.happy-number.py

* 思路：利用Python str函数将整型变为可循环的字符串，同时使用一个dict保存已经出现过的元素。如果陷入循环则退出
* 时间复杂度=O(k)，空间复杂度=O(k)
