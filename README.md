# DWDM21
**Data Warehouse &amp; Data Mining 2021**

**นางสาวณิชากร ไชยสุวรรณ 623020521-8**

**Group name : Sandbox นะจ๊ะ**

**_1 นางสาวณิชากร ไชยสุวรรณ 623020521-8_**

**_2 นางสาวชนัญชิดา เมธีกุลมานิต 623020516-1_**

**_3 นางสาวกิตติมา อุปสุข 623021040-9_**

**_4 นางสาวนฤมล ไสยโสภณ 623021050-6_**

**_5 นางสาวภิญญาดา เพ็ญสุข 623021052-2_**


# สารบัญ 

## ภาคทฤษฎี

### Chapter 1 [Introduction](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Data%20Warehouse.pdf)
  
  * Data Warehouse
  * Data Mining
  
### Chapter 2 Getting to Know Your Data

  * [Getting to Know Your Data](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Chapter2.pdf)
    
    - ประเภทของข้อมูล
    - คุณลักษณะของข้อมูล
    - Attributes
    - Attributes Types
    - Numeric Attributes Types
    - Discrete Attributes
    - Continuous Attributes
  * [Measuring Data Similarity and Dissimilarity](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Measuring%20Data%20Similarity.pdf)
    - Similarity measure or similarity function (ความเหมือน)
    - Dissimilarity (or distance) measure (ความไม่เหมือน)
    - Proximity (ความต่าง ระยะห่างระหว่างข้อมูล)
    - ความหมายของ Distance matrix
    - ความหมายของ Dissimilarity matrix
    - การวัดระยะห่างด้วยวิธีของ Minkowski distance
  * [Symmetric Binary Variables](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Symmetric%20Binary%20Variables.pdf)
    - ความหมายของ Binary 
    - การวัดระยะห่างของข้อมูลประเภท Binary
    - Categorical Attributes
    - วิธีการวัดระยะห่างของแอตทริบิวที่เป็นประเภท
    - วิธีการวัดความห่างด้ววยมุม
    
### Chapter 3 [Data Preprocessing](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Chapter3%20Preprocessing.pdf)
  
  * Data Cleaning
  * Data INtegration
  * Data Reduction and Transformation
  * Dimensionality Reduction

### Chapter 6 [Mining Frequent Patterns, Association and Correlations](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Chapter6.pdf)

  * Pattern Discovery คืออะไร
  * K-Itemsets
  * Absolute Support
  * Relative Support 
  * Association Rules
  * Apriori
  
### Chapter 7 Classification
  * [Basic Concepts](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Chapter8%20Classification%20Basic%20concepts%20HW14.pdf)
    - Supervised Learning
    - Unsupervised Learning
    - Classification
    - Numeric prediction
    - Decision Tree Induction
    - HW14
  * [Bayes Classification Methods](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Naive%2CK-NN.pdf)
    - Bayesian Classification คืออะไร
    - Naive Bayes Classifier
    - Traning Dataset
    - Lazy Learner (K-nearest neighbor approach),(Locally weighted regression),(Case-based reasoning)
  * [Model Evaluation and Selection](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Chapter8%20Evaluation-and-Selection.pdf)
    - Confusion Matrix
    - Accuracy, Error Rate, Sensitivity, Specificity
    - Percision and Recall, and F-measures
  * [Neural Network for Classification](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Neural-Network.pdf)
    - ความหมายของ Neural Network 
    - เพอร์เซปตรอน
    - Algorithm Perceptron-Learning-Rule
    - ตัวอย่างการเรียนฟังก์ชัน AND และ XOR ด้วยกฏเรียนรู้เพอร์เซปตรอน

### Chapter 8 [Cluster Analysis](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Evaluation%20%26%20Kmeans.pdf)
  * Based Clustering Methods
  * K-means Clustering Method

## ภาคปฏิบัติ 

### Chapter 2 

  * [Basic Pythoon](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Data101(chapter2).ipynb)
    - Variables
    - Casting int() flat() str()
    - Data structture
    - Loop
    - ลักษณะของ input 
    - Quiz
  * [Data exploration](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Data102_(Chapter2).ipynb)
    - Box plot
    - Time Series plot
  * [Data Visualization](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Data_Visualization.ipynb)
    - Scatter plot
    - Bar chart
    - Histogram
  * [Distance Numpy](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Distance_Numpy.ipynb)
    - Numpy Array(Matrix) จาก list
      - สร้าง numpy array
      - สร้าง matrix เริ่มต้น (zeros,ones)
      - สร้าง matrix random
      - Indexing & Silcing
      - Useful function
    - วนลูป
    - Distance Matrix
      - Euclidean Distance (L2-norm)
      - Distance function
      - Manhattan Distance (L1-norm)
    - HW
     
### Chapter 3 

  * [Data Preprocessing](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Data_Preprocessing(Chapter_3).ipynb)
    - การชี้ข้อมูลในตาราง
    - Missing Values
    - สร้าง list ของ boolean
    - ต่อตารางแนวแกน Y [PD]
    - Outlier
    - Pandaslooping (.iterrows)
    - การรวมตาราง (ต่อตารางในแนวแกน X)
    - Group by (Pandas)
    - [PD] Save ตารางเอาไปใช้ที่อื่น
    - [PD] การสร้างตาราง
 
### Chapter 6 

  * [Association Rules](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Chapter6_Association_Rules.ipynb)
    - ลบ Records ที่ถูก Cancel ออกไป
    - เตรียม Data สำหรับ Fequence Pattern Association Rules
    - Apriori
   
### Chapter 7 

  * [Classification (Decision Tree)](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Chapter7_Classification_(Decision_Tree).ipynb)
    - Load data 
    - Train Model
    - Plot tree
    - Evaluation
    - Advancede Tree
    - ทดลอง
    - HW
  * [Classification (KNN-NN)](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Chapter7_Clssification_(KNN_NN).ipynb)
    - Load data 
    - Split data
    - Train model
    - Neural Neteork
  * [Classification (Evaluation)](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Chapter7_Classification(Evaluation).ipynb)
    - Load data
    - แบ่ง data
    - สร้าง model ทำนาย
      -  Import
      -  Define
      -  Train
      -  Evaluation

### Chapter 8
  * [Clustering](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Chapter8_Clustering.ipynb)
    - Generate data
    - Explore data
    - Clustering
    - Exampke Application (Color)
    - เพิ่มเติม
### MiniExam
  * [MiniExam](https://github.com/nichakornchaisuwan/DWDM21/blob/main/MiniExam.ipynb)

### Project 
  * [Project Mid](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Project1.ipynb)
  * [Project Final](https://github.com/nichakornchaisuwan/DWDM21/blob/main/ProjectFinal.ipynb)
  * [สไลด์นำเสนอ](https://github.com/nichakornchaisuwan/DWDM21/blob/main/Final%20Project%20DWDM2021.pdf)
