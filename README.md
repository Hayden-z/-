# -机器学习
1.单变量线性回归(Linear Regression with One Variable)
http://www.ai-start.com/ml2014/html/week1.html
![image](https://github.com/Hayden-z/ML/blob/master/images/10ba90df2ada721cf1850ab668204dc9.png)

![image](https://github.com/Hayden-z/ML/blob/master/images/13176da01bb25128c91aca5476c9d464.png)

![image](https://github.com/Hayden-z/ML/blob/master/images/QQ20181216-184922.png)
      
![image](https://github.com/Hayden-z/ML/blob/master/images/QQ20181216-184702.png)
      
![image](https://github.com/Hayden-z/ML/blob/master/images/QQ20181216-184831.png)
      
      

2.多变量线性回归(Linear Regression with Multiple Variables)
http://www.ai-start.com/ml2014/html/week2.html

![image](https://github.com/Hayden-z/ML/blob/master/images/QQ20181216-190429.png)        
      
      
      
1-特征缩放   在我们面对多维特征问题的时候，我们要保证这些特征都具有相近的尺度，这将帮助梯度下降算法更快地收敛
2-学习率    梯度下降算法的每次迭代受到学习率的影响，如果学习率过小，则达到收敛所需的迭代次数会非常高；如果学习率过大，每次迭代可能不会减小代价函数，可能            会越过局部最小值导致无法收敛。
           通常可以考虑尝试些学习率：0.01,0.03,0.1,0.3,1,3,10
3-特征和多项式回归





3.逻辑回归(Logistic Regression)
http://www.ai-start.com/ml2014/html/week3.html


![image](https://github.com/Hayden-z/ML/blob/master/images/6590923ac94130a979a8ca1d911b68a3.png)
 
![image](https://github.com/Hayden-z/ML/blob/master/images/eb69baa91c2fc6e7dd8ebdf6c79a6a6f.png)

![image](https://github.com/Hayden-z/ML/blob/master/images/QQ20181216-183134.png)
        
给代价函数增加一个正则化的表达式，得到代价函数：     
