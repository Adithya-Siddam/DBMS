# EX.NO.12: Simulating Classification using WEKA Data mining and Analysis Tool

Date:
## AIM:
To perform a classification technique using WEKA tool

## WEKA:
Weka is a comprehensive software that lets you to preprocess the big data, apply different machine learning algorithms on big data and compare various outputs. This software makes it easy to work with big data and train a machine using machine learning algorithms. This tutorial will guide you in the use of WEKA for achieving all the above requirements. WEKA - an open source software provides tools for data preprocessing, implementation of several Data mining and Machine Learning algorithms, and visualization tools so that you can develop machine learning techniques and apply them to real-world data mining problems. What WEKA offers is summarized in the following diagram
![image](https://github.com/soundariyan18/DBMS/assets/119393307/26d7f079-62c7-4581-b98f-99a4496058a2)

## CLASSIFICATION:
Classification in data mining is a common technique that separates data points into different classes. It allows you to organize data sets of all sorts, including complex and large datasets as well as small and simple ones. It primarily involves using algorithms that you can easily modify to improve the data quality. This is a big reason why supervised learning is particularly common with classification in techniques in data mining. The Classification algorithm is a Supervised Learning technique that is used to identify the category of new observations on the basis of training data. In Classification, a program learns from the given dataset or observations and then classifies new observation into a number of classes or groups. Such as, Yes or No, 0 or 1, Spam or Not Spam, cat or dog, etc. Classes can be called as targets/labels or categories.

## PROCEDURE:
1.Load the data file into the WEKA explorer. The data can be loaded from the following sources − Local file system Web Database

2.Click on the "Open file" button. A directory navigator window opens as shown in the following screen −

![image](https://github.com/soundariyan18/DBMS/assets/119393307/1af5aef9-0c92-4255-9a20-c01145a83733)

3.Click on the Classify tab, and you would see the following screen.

![image](https://github.com/soundariyan18/DBMS/assets/119393307/f90c8788-950e-4f0e-b824-43fedee5e285)

4.Now, keep the default play option for the output class −

![image](https://github.com/soundariyan18/DBMS/assets/119393307/383f8827-6e18-4318-a852-ab9168a00903)

5.Click on the Choose button and select the following classifier − weka→classifiers>trees>J48.

![image](https://github.com/soundariyan18/DBMS/assets/119393307/51c27692-0d50-4fb7-b318-c1cd875eb3ac)

6.Click on the Start button to start the classification process. After a while, the classification results would be presented on your screen as shown here −

![image](https://github.com/soundariyan18/DBMS/assets/119393307/3c80c14e-d938-455e-9a6b-4635a5a632c9)

7.To see the visual representation of the results, right click on the result in the Result list box. Several options would pop up on the screen as shown here −

![image](https://github.com/soundariyan18/DBMS/assets/119393307/c644d700-6f1e-4d40-9f83-4004d1854b86)

8.Select Visualize tree to get a visual representation of the traversal tree as seen in the screenshot below −

![image](https://github.com/soundariyan18/DBMS/assets/119393307/c993bd64-ad64-406f-b71f-322a11b0f059)

9.Selecting Visualize classifier errors would plot the results of classification as shown here −

![image](https://github.com/soundariyan18/DBMS/assets/119393307/0c549f6f-3bbb-4ef6-8ec0-7cee5a2f23fa)

10.A cross represents a correctly classified instance while squares represents incorrectly classified instances. At the lower left corner of the plot you see a cross that indicates if outlook is sunny then play the game. So this is a correctly classified instance.

## OUTPUT:

![image](https://github.com/soundariyan18/DBMS/assets/119393307/319f32f2-269e-4552-b7fa-483337a1c596)

![image](https://github.com/soundariyan18/DBMS/assets/119393307/4f05c1eb-c713-4633-9e19-c12999e2c571)

![image](https://github.com/soundariyan18/DBMS/assets/119393307/339cce92-f158-466c-988c-c0fd4731b723)

![image](https://github.com/soundariyan18/DBMS/assets/119393307/ffd8009d-6277-4f11-beae-74507258abf6)

![image](https://github.com/soundariyan18/DBMS/assets/119393307/2f815cf2-1594-457c-9ccb-cc4183fb0446)

## RESULT:
Thus the simulation of classification technique has been executed using WEKA tool successfully.
