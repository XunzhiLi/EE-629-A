# This is Machine Learning project based on SVM model to detect fruits(Binary) for CPE 629A.
* student name: XUNZHI LI
* id: 10457500

## Running Instruction: 
*precondition: You need to install jupyter notebook to run the code file (can not run in python environment directly).*
1. open .ipynb file in jupyter notebook
2. run all codes following picture instruction：
<img src="https://github.com/XunzhiLi/EE-629-A/blob/f54a3bd8c086ab79833c5c370dbdf81e16a18f5e/step2%20screenshot.pic.jpg" width="500" />
3. Check results for three examples      
<img src="https://github.com/XunzhiLi/EE-629-A/blob/8d5e362a237d506ffea183602b327b0e949f4d15/step3%20srceenshot.pic.jpg" width="500" /> 
4. Result analysis: For 'Pineapple' and 'Mango' / Grape White' and 'Grape Pink', the SVM model can 100% detect/classify them. While the result for 'Potato Red' and 'Potato Sweet' is only 78.67%.


5. For more binary fruit detection, you can just add a cell and input like this:
   fruitlist=['fruit1','fruit']
   Fruit_Dectetion(fruitlist)
   fruit1 and fruit2 are two kinds of fruit that you wanna to detect/classify.
