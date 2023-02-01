Project Title :

House price predicition 

——————————————————————————————————



Goal of the Project :

Predict the price of the house by its features.If you are a buyer or seller of the house but you don't know the exact price of the house, So Supervised Machine Learning Regression Algorithms can help you to predict the price of the house just providing features of the target house.

——————————————————————————————————




Roles and Responsibiliets :
1. Undestand, analyze and interpret large dataset.
2. To discover trends and patterns, combine various algorithms and modules.
3. Present data using various data visualization techniques and tools.
4. Develop advance programs to extract the data needed, prepare the data for further analysis.

——————————————————————————————————

Libraries Used :

NumPy

Pandas

Matplotlib 

Seaborn

Scikit-Learn

——————————————————————————————————

Performed EDA and Model Training

——————————————————————————————————

Results of the Model Being Trained(Before and after Feature Selection)

      1 .Before Hyperparameter Tuning
      
               LinearRegression               -2.533295309271931e+26
        
                SGDRegressor                  -23749.15367038007
       
                SVR                           -0.052342367631724826
        
                KNeighborsRegressor            0.36634102550065195
 
                GaussianProcessRegressor      -5.398031442917398
 
                DecisionTreeRegressor          0.6653952085060029
 
                GradientBoostingRegressor      0.8767904064560017
 
                RandomForestRegressor          0.845485886031432
 
                MLPRegressor                  -4.945191394314034

      2. After Hyperparameter Tuning(Perormed Hyperparameter Tuning on top 2 Algorithms which are given High Accuracy)
      
                 GradientBoostingRegressor     0.8932161373541663
                 
                 RandomForestRegressor         0.8391873347030853
                 

   Then implemented Feature Selection :

      3 .Before Hyperparameter Tuning
      
                LinearRegression               0.8480199009470512
                 
                SGDRegressor                  -1.2131825648614307e+20
            
                SVR                           0.8871361016846799
 
                KNeighborsRegressor           0.8123424294654289
 
                GaussianProcessRegressor      -804.6303188728976
 
                DecisionTreeRegressor         0.7143457474236532
 
                GradientBoostingRegressor     0.8956156432931586
 
                RandomForestRegressor         0.8683166475612271
 
                MLPRegressor                 -0.4145671681324671

      4. After Hyperparameter Tuning(Perormed Hyperparameter Tuning on top 2 Algorithms which are given High Accuracy)
      
                GradientBoostingRegressor     0.9067464819264395
                
                RandomForestRegressor         0.8638866349951642
      
   







