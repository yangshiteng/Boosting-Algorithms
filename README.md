# 1. CatBoost

- https://catboost.ai/en/docs/concepts/installation
- Based on gradient boosting on decision trees

## 1.1 What is CatBoost

![image](https://user-images.githubusercontent.com/60442877/157367429-1cae84d5-a4ff-48cb-b305-e618ecc3d7cf.png)

## 1.2 Advantages of CatBoost 

![image](https://user-images.githubusercontent.com/60442877/157368102-dbd1f527-6340-4e30-9630-f05889336a5d.png)

Note: In addition to this, CatBoost does not require conversion of data set to any specific format like XGBoost and LightGBM.

## 1.3 Decision Tree Introduction 

![image](https://user-images.githubusercontent.com/60442877/157383012-8e220867-f61c-4176-9fda-11d4daa60110.png)
![image](https://user-images.githubusercontent.com/60442877/157383031-5d120b4d-a5fe-4cc1-8179-a64a1bd70ee4.png)
![image](https://user-images.githubusercontent.com/60442877/157383310-9e6cbec1-81ff-4ef2-95b0-c6ff5a10627a.png)
![image](https://user-images.githubusercontent.com/60442877/157383365-50c8e69b-0cb7-4695-814b-928ec1845ac3.png)
![image](https://user-images.githubusercontent.com/60442877/157383411-dbb020ef-dc9e-4bb9-8bd7-13aa180cf0e8.png)
![image](https://user-images.githubusercontent.com/60442877/157383463-95004f2f-9d53-4e31-8f07-0ae36b164829.png)
![image](https://user-images.githubusercontent.com/60442877/157383474-52797169-ca13-4c6d-ac5f-069f6ee6b1d0.png)
![image](https://user-images.githubusercontent.com/60442877/157383597-680761fc-2c27-4308-9785-6db86d017cd2.png)

## 1.4 Ensembles

- bagging: averaging the prediction over a collection of classifiers
- boosting: weighted vote with a collection of classifiers
- stacking: combining a set of heterogeneous classifiers

![image](https://user-images.githubusercontent.com/60442877/157384357-dd1e8b01-1e28-4228-901c-3d87765d97a8.png)

## 1.5 Random forest algorithm (bagging)

![image](https://user-images.githubusercontent.com/60442877/157384678-8ee0a2b6-cebc-4fc0-a155-a156fccf0f62.png)

Method of random subspaces can help to reduce the correlation between trees and avoid overfitting.

![image](https://user-images.githubusercontent.com/60442877/157384977-f5877e29-f311-4fa2-aadb-2f6c21899b4a.png)

## 1.6 Boosting

![image](https://user-images.githubusercontent.com/60442877/157385122-6d720b22-b063-4c08-a7c0-4d8f51f1d930.png)
![image](https://user-images.githubusercontent.com/60442877/157385199-ad45daf7-c649-453c-aebd-7fc7708831e3.png)

### 1.61 Gradient Boosting

![image](https://user-images.githubusercontent.com/60442877/157385480-8abb1a7c-0878-4714-b841-1a75ebf034bf.png)
![image](https://user-images.githubusercontent.com/60442877/157385563-d2546664-f5ed-4873-83ea-4f804c13fe54.png)

### 1.62 Catboost

![image](https://user-images.githubusercontent.com/60442877/157390908-cf8678b7-6d37-4b55-b47e-b2eaf84ca123.png)
![image](https://user-images.githubusercontent.com/60442877/157390990-b54a4ecb-8ccb-492a-917e-ac3cda8e1e60.png)
![image](https://user-images.githubusercontent.com/60442877/157391056-3ef35fbe-838e-49bc-81ec-ef606fd8788e.png)
![image](https://user-images.githubusercontent.com/60442877/157391107-df1f296b-0c5c-4c52-8954-3ea79ddc561f.png)
![image](https://user-images.githubusercontent.com/60442877/157391129-477e3ba4-bbe0-45fb-b703-7eeacb802cb6.png)
![image](https://user-images.githubusercontent.com/60442877/157391177-e71554f8-9784-47d4-a194-0bc024c04340.png)
![image](https://user-images.githubusercontent.com/60442877/157391351-6c1d9162-f7c5-41f3-8919-08ced03911e1.png)




