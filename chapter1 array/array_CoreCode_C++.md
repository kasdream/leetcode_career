# 基础说明：  
## 数组array
基础array数组介绍：https://www.runoob.com/cplusplus/cpp-arrays.html   
## 向量vector   
基础vector介绍：https://www.runoob.com/w3cnote/cpp-vector-container-analysis.html
leetcode常用vector 与 array的区别和用法： https://www.cnblogs.com/Kernel001/p/7853441.html   
1：array 定义的时候必须定义数组的元素个数;而vector 不需要   
2：array 定义后的空间是固定的了，不能改变；而vector 要灵活得多，可再加或减.     
3：数组不提供 push——back或者其他的操作在数组中添加新元素，数组一经定义就不允许添加新元素；    
4.一个数组不能用另一个数组初始化，也不能将一个数组赋值给另一个数组；    
声明：    vector\<int\> vec   
查看大小： vec.size()   
添加数值： vec.push_back(i)   
推出数值： vec.pop()    
序号对应值： vec[i]   
迭代取值：   
   vector<int>::iterator v = vec.begin();   
   while( v != vec.end()) {   
      cout << "value of v = " << *v << endl;   
      v++;   
   }    
## 哈希表map 


# 视频基础算法:

## 遍历
https://www.cnblogs.com/jpfss/p/10337163.html

