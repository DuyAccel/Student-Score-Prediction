# This project has 2 stages:
## 1. Data exploration and preprocessing
I had to deal with *many categorical features* of this dataset.</br>
![image](https://github.com/DuyAccel/Into_Machine_Learning_SGU/assets/84909478/a9b1a0f4-e01a-42a5-81d3-e98633a1f3e8)</br>
![image](https://github.com/DuyAccel/Into_Machine_Learning_SGU/assets/84909478/71c1ed54-5c11-47e9-97be-e594ed373e6e)</br>
![image](https://github.com/DuyAccel/Into_Machine_Learning_SGU/assets/84909478/2eb6b21b-f8b2-4b66-8174-64bd12eaf8ba)</br>
![image](https://github.com/DuyAccel/Into_Machine_Learning_SGU/assets/84909478/c105dc0f-2954-46e8-8233-9610daed1333)</br>
The hardest part in project was **dimesionality reduction**. By using correlation matrix and domain knowledge, I selected features to use in models.
## 2. Model selection
I chose 3 algorithms for this regression problem. *GridSearchCV* was used to estimate **best hyperparameters** of each model.
Finally, **Random Forest** was chosen with mean square error: `4.78638`
# Model mean square error:
![image](https://github.com/DuyAccel/Into_Machine_Learning_SGU/assets/84909478/944a2b35-35ec-45eb-8433-667159842ff0)
