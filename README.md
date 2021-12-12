# This is Machine Learning project based on SVM and DecisionTree models to detect/classify fruit for CPE 629A.
* student name: XUNZHI LI
* id: 10457500

## Running Instruction: 
*Precondition: We need to install jupyter notebook to run the code file (can not run in python environment directly).*
*We need to download dataset from 'https://github.com/Horea94/Fruit-Images-Dataset' and store the file in the same route of the ipynb file.*
1. open .ipynb file in jupyter notebook
2. run all codes following picture instruction：
<img src="https://github.com/XunzhiLi/EE-629-A/blob/f54a3bd8c086ab79833c5c370dbdf81e16a18f5e/step2%20screenshot.pic.jpg" width="500" />
3. Check results for three examples      
<img src="https://github.com/XunzhiLi/EE-629-A/blob/8d5e362a237d506ffea183602b327b0e949f4d15/step3%20srceenshot.pic.jpg" width="500" /> 

4. Result analysis: For 'Pineapple' and 'Mango' / Grape White' and 'Grape Pink', the SVM model can 100% detect/classify them. While the result for 'Potato Red' and 'Potato Sweet' is only 78.67%.

5. For more binary fruit detection, we can just add a cell and input like this:
* fruitlist=['fruit1','fruit']
* Fruit_Dectetion(fruitlist)
* (fruit1 and fruit2 are two kinds of fruit that we wanna to detect/classify.)
6. To start multiple fruit detection/classification, a package called 'DecisionTreeClassifier' is very important. We use 'from sklearn.tree import DecisionTreeClassifier' to import it.
7. We define a the new function by using DecisionTree model, train the model with train_dataset and evaluate the model on test_dataset.
<img src="https://github.com/XunzhiLi/EE-629-A/blob/924f0d05f7e3a4cfb5087ac86080119676c48f02/step7_1.pic.jpg" width="500" />
<img src="https://github.com/XunzhiLi/EE-629-A/blob/bd5290e8e5a3b8c0d1b8f61f30b584aea1f34ac4/step7_2.pic.jpg" width="500" />

8. For more binary fruit detection, we can just add a cell and input like this:
* It's clear to see we can detect/classify 'Peach','Potato Red','Mango','Pineapple with a very high accuracy (97.68%), which means almost makes no mistake. 
* While the accuracy for 'Kiwi', 'Potato Red', 'Potato Sweet', 'Pineapple' is relative lower(77.81%).Because kiwi looks similar to Pineapple and 'Potato Red', 'Potato Sweet' look very semblable. 
* In addition, the model works very well on peppers in different colors(88.74%).

9. For more mulitple fruit detection, we can just add a cell with two lines and input like this:
* multi_fruitlist = ['fruit1','fruit2','fruit3'..........]
* multiple_Fruit_Detect(multi_fruitlist)
