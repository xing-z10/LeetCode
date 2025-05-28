## Day2 数组part02

[任务链接](https://docs.qq.com/doc/DUGRwWXNOVEpyaVpG?nlc=1)  

#### 209.Minimum Size Subarray Sum  
[LeetCode Link](https://leetcode.com/problems/minimum-size-subarray-sum/solutions/)  
[文章链接](https://programmercarl.com/0209.%E9%95%BF%E5%BA%A6%E6%9C%80%E5%B0%8F%E7%9A%84%E5%AD%90%E6%95%B0%E7%BB%84.html#%E5%85%B6%E4%BB%96%E8%AF%AD%E8%A8%80%E7%89%88%E6%9C%AC)

###### 题目思路  
运用双指针制造一个滑动窗口  

###### Code Solution
<img width="478" alt="image" src="https://github.com/user-attachments/assets/d9a10cb8-3564-428b-b271-47121b82fab6" />

Time Complexity: O(n)  
Space Complexity: O(1)  

#### 59. Spiral Matrix II
[LeetCode Link](https://leetcode.com/problems/spiral-matrix-ii/description/)  
[文章链接](https://programmercarl.com/0059.%E8%9E%BA%E6%97%8B%E7%9F%A9%E9%98%B5II.html#%E6%80%9D%E8%B7%AF)  

###### 题目思路
生成对应数量数组，模拟顺时针画圈过程  
**注意：四条边一定要保持一致的左闭右开原则**  

###### Code Solution
<img width="498" alt="image" src="https://github.com/user-attachments/assets/0011f8f2-c81f-4219-9829-b16b146da16a" />  

Time Complexity: O(n^2)  
Space Complexity: O(1)  

#### 58 区间和  
[Link](https://kamacoder.com/problempage.php?pid=1070)  
[文章链接](https://www.programmercarl.com/kamacoder/0058.%E5%8C%BA%E9%97%B4%E5%92%8C.html#%E6%80%9D%E8%B7%AF)  

###### 题目思路  
创建一个array储存从0到该下标的总和，然后通过减法找到对应数值  
例：创建sum_i 的array，sum_i[2]表示为从0加至下标2的总和，如果需要下标2至5的和，则为 sum_i[5]-sum_i[2-1]  

###### Code Solution  
<img width="662" alt="image" src="https://github.com/user-attachments/assets/e97b212a-c404-4b63-b4ed-478e2257bfbc" />  

Time Complexity: O(n+m)  
Space Complexity: O(n+m)  

#### 开发商购买土地  
[Link](https://kamacoder.com/problempage.php?pid=1044)  
[文章链接](https://www.programmercarl.com/kamacoder/0044.%E5%BC%80%E5%8F%91%E5%95%86%E8%B4%AD%E4%B9%B0%E5%9C%9F%E5%9C%B0.html)  

###### 题目思路。
和58思路相似  

###### Code Solution
<img width="580" alt="image" src="https://github.com/user-attachments/assets/b8d7e0c0-5ba9-4113-926c-3e4c10c636a9" />  

Time Complexity: O(n^2)
Space Complexity: O(n^2)



  
