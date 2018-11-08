# CART回归树


#### 文件说明
 
 + 数据文件

     + 北京市Pm2.5数据集：[数据下载以及说明](http://archive.ics.uci.edu/ml/datasets/Beijing+PM2.5+Data#)
     
     + 数据文件：[PRSA_data_2010.1.1-2014.12.31.csv](https://github.com/Anfany/Machine-Learning-for-Beginner-by-Python3/blob/master/Decision%20Tree/DT_Regression/PRSA_data_2010.1.1-2014.12.31.csv)
   
 
+ 基于不同库的代码文件
 
     - **AnFany**：[AnFany_DT_Classify.py](https://github.com/Anfany/Machine-Learning-for-Beginner-by-Python3/blob/master/Decision%20Tree/DT_Classify/AnFany_DT_Classify.py)
     
 
     - **Sklearn**：[Sklearn_DT_Classify.py](https://github.com/Anfany/Machine-Learning-for-Beginner-by-Python3/blob/master/Decision%20Tree/DT_Classify/Sklearn_DT_Classify.py)

    
 + 辅助代码文件

      - 数据读取与预处理程序：[DT_Classify_Data.py](https://github.com/Anfany/Machine-Learning-for-Beginner-by-Python3/blob/master/Decision%20Tree/DT_Classify/DT_Classify_Data.py)
      
 + 绘制树的程序
 
      - 绘制树程序：[AnFany_Show_Tree.py](https://github.com/Anfany/Machine-Learning-for-Beginner-by-Python3/blob/master/Decision%20Tree/DT_Classify/AnFany_Show_Tree.py)
   
      - 成人收入数据集(初始深度设为5)的树的示例：
      
      ![image](https://github.com/Anfany/Machine-Learning-for-Beginner-by-Python3/blob/master/Decision%20Tree/DT_Classify/adult_tree.png)
      
 
 + 成人收入数据集结果对比
  
      - **AnFany**
       
      ![image](https://github.com/Anfany/Machine-Learning-for-Beginner-by-Python3/blob/master/Decision%20Tree/DT_Classify/adult_anfany.png)
       
      - **Sklearn**
       
      ![image](https://github.com/Anfany/Machine-Learning-for-Beginner-by-Python3/blob/master/Decision%20Tree/DT_Classify/adult_sklearn.png)
       
 +  示例 
 
     - **y=sin(x1) + cos(x2)**
 
    - **AnFany**
    
       - 决策树程序：[AnFany_Example_DT.py](https://github.com/Anfany/Machine-Learning-for-Beginner-by-Python3/blob/master/Decision%20Tree/DT_Regression/AnFany_Example_DT.py)
    
       
       - 结果：
       
         + **不同初始深度**
         
          ![image](https://github.com/Anfany/Machine-Learning-for-Beginner-by-Python3/blob/master/Decision%20Tree/DT_Regression/shili_mse.png)
       
         + **拟合对比**
         
          ![image](https://github.com/Anfany/Machine-Learning-for-Beginner-by-Python3/blob/master/Decision%20Tree/DT_Regression/cure_shili.png)