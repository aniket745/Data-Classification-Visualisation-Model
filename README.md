# Data-Classification-Visualisation-Model
## Abstract:  
Using the dataset provided, we built data visualization model and found the best data segmentation model using Python. Our classifier model has accuracy is 95.46% and f1-score is 94.19%. We have designed pdf file of graphs based on problem statement which will help to visualize relation between various parameter of dataset. 

## Keywords: 
Decision Tree, Random Forest Tree, F1-score, visualization 

## Introduction:  
Classification is the process of predicting the class of given data points. Classification predictive modeling is the task of approximating a mapping function (f) from input variables (X) to discrete output variables (y). Classification belongs to the category of supervised learning where the targets also provided with the input data. There are many applications in classification in many domains such as in credit approval, medical diagnosis, target marketing etc. There is a lot of classification algorithms available now, but it is not possible to conclude which one is superior to other. It depends on the application and nature of available data set. In this project for classification we have used Random Forest Classifier. It is an ensemble tree-based learning algorithm. The Random Forest Classifier is a set of decision trees from randomly selected subset of training set. It aggregates the votes from different decision trees to decide the final class of the test object. Data visualization is the discipline of trying to understand data by placing it in a visual context so that patterns, trends, and correlations that might not otherwise be detected can be exposed. Python offers multiple great graphing libraries that come packed with lots of different features. 
 
## Project Objective:  
The goal of this project is to build a data visualization model and find the best data segmentation model using the student’s dataset. Visualize various patterns in dataset. 
 
## Classification Model:  
   Our dataset has dimension 10000*34. Out of 34 column 25 column are categorical variable which will decide eligibility of student. So remaining column got dropped out. Then we renamed the column to short name. For better prediction we converted categorical variable into dummy variable. After that we split that data into training & testing set.  
   The main work starts here to identify best classifier which has better accuracy and precision to make our model more accurate. We have SVM classifier in which we get accuracy as 0.7993 and F1 score as 0.7378. In decision tree classifier we got accuracy and F1 score as 1.0 which is case of overfitting. Now in random forest classifier we got accuracy 0.9546 and F1 score 0.9419. So, we choose random classifier as best classifier for the given dataset.   

## Visualization Model:  
   In visualization, based on problem statement we plotted some meaningful graphs. We will interesting information by plotting each graph.  
   First problem is to find relation between number of students applied for different technologies. From this plot we got to know that maximum students are applied for “DevOps” followed by “Machine learning”. Less number of students are interested in “IOT”. 
   Second problem statement is to find number of students who applied for data science technology knows python. 535 students applied for data science do not know the python language while 66 students know it. 
   Third problem statement number of students learned about this program in different ways. We got to know that maximum students heard it from “Intern” followed by “News Paper” and “Twitter”. 
   Fourth statement is about fourth year students who have CGPA above 8. Answer to this is maximum students have CGPA in range 9 to 9.5. 
   Fifth problem statement is about digital marketing student who have written and verbal score above 8. From plot we got 220 student who satisfy this condition. 
   Sixth problem statement is number of students from different year having different branch. From this we got to know maximum students from all years are from computer science. 
   Seventh problem statement is classification of student based on city and college wise. Number of students from different cities are nearly same whereas maximum students are from “Rajarambapu Institute of Technology” college.  
   Eight problem is relation between CGPA and eligibility of students. From this we got to know that number of eligible students having CPGA between 8 to 9 and 9 to 10 are same. Most number of students having CGPA between 7 to 8 are ineligible. 
   Nineth problem is about relation between different technology and eligibility of students. Maximum eligible students are from “DevOps” technology followed by “Block Chain” and “Cyber Security”. Maximum ineligible students are from “IOT” followed by “RPA” technology. 
   Tenth problem is about relation between year of study, major and eligibility. From graph we can say, maximum number of ineligible students are from first year computer science followed by first year electronics and telecommunication. Maximum eligible students are from second, third and last year of computer science department.  
 
## Conclusion:  
   We have presented a simple data classification based on good F1 score. Different models could be used such as logistic regression, decision tree, SVM etc. It would be a good idea to try these different approaches to see if the results are comparable to the Random Forest Classifier. With random forest we got good accuracy and F1 score. Based on various plots we got some interesting points about dataset. 
