# AMDwithPermission-ML
Andoird Malware Detection with different numbers of permissions using machine learning  
Try to detect Android Malware with permissions only  
With Machine Learning  

### 3 folders with different numbers of permissions  

1. 88 permissions  
2. dangerous pid for 34 permissions  
3. sigpid for 22 permissions  

### packages needed:

1. androguard
2. numpy
3. pandas
4. scikit-learn

### usage:

1. all.py for training with train.csv and test.csv
2. apkPredict.py for predict apks in dir using model file generated by all.py
3. other py for merge permissions

### others:

models and dataset too big so they get compressed  
of course u can train ur own model  
dataset need to be merged by .py  

---------------------------

## 中文版

### 三个文件夹

1. 采用88个权限的代码
2. 采用34个权限的代码
3. 采用22个权限的代码

### 需要的库文件

1. androguard
2. numpy
3. pandas
4. scikit-learn

### 用法

1. all.py用于训练，需要提供train.csv和test.csv
2. apkPredict.py用于预测，读取现有的model文件中的模型  
3. 其他文件用于格式化找到的数据集，可能要根据不同的数据集进行调整

### 其他

1. 数据集和model文件太大，单独打包上传
2. 不同权限个数的代码应采用不同的model
