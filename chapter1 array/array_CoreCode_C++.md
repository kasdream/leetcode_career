# 基础说明：  
## 数组array
基础array数组介绍：https://www.runoob.com/cplusplus/cpp-arrays.html   
查看大小： 
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
推出数值： vec.pop_back()    
序号对应值： vec[i]   
迭代取值：   
   vector<int>::iterator v = vec.begin();   
   while( v != vec.end()) {   
      cout << "value of v = " << *v << endl;   
      v++;   
   }    
## 哈希表map 
基础map介绍：https://blog.csdn.net/sevenjoin/article/details/81943864           
哈希表查表内元素值为O(1)，可以直接输出该数在数组中的位置           
map与unordered_map相比：          
   map底层实现为红黑数，undered_map底层实现为哈希表，两者均不能有重复的建，均支持[]运算符           
   map与multimap相比：        
   两者底层实现均为红黑树，但是multimap支持重复的键，不支持[]运算符            
声明： unordered_map\<int, int\> m        
赋值： 特别注意，哈希表是将对应的数组值作为序列（链表），把数组中的序列作为值         
           for (int i = 0; i < nums.size(); ++i) {         
            m[nums[i]] = i;        
        }          
查哈希表中值为nums[i]个数： m.count[nums[i]]          
                          (用来做为数组中对应值是否存在的判断条件之一   if (m.count(t) && m[t] != i))         
返回值(序号) m[nums[i]]     
                                          
## 相关时间复杂度
https://blog.csdn.net/ted_cs/article/details/82881831
 

# 视频基础算法:

## 遍历
https://www.cnblogs.com/jpfss/p/10337163.html

