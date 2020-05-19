# Machine Learning with PySpark - Distributed Computing Project ENSAE 2020

Apply Machine Learning methods with PySpark to PUBG finish placement prediction.  
Link to the associated project : https://github.com/YannickLy/Machine-Learning-Project-ENSAE-2020  

## Dataset
Data from https://www.kaggle.com/c/pubg-finish-placement-prediction/data  
Since our local machines are not powerful enough, we decided to limit the dataset at 5%.  

## Local Spark Setup
Driver memory option has to be changed in the **spark-defaults.conf** if executed in local environment.  
<code> spark.driver.memory = 8g </code>

## Authors
* Remi Lacoste
* Yannick Ly
