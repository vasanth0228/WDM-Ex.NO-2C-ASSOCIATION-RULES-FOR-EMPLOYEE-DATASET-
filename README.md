# WDM-Ex.NO-2C-ASSOCIATION-RULES-FOR-EMPLOYEE-DATASET
### Aim:
To Find the Association Rules for Employee data.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered in databases using different measures of interestingness. In market basket analysis association rules are used and they are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
##Creation of Banking Table:
### Procedure:
1)	Open Start  Programs  Accessories  Notepad
2)	Type the following training data set with the help of Notepad for Employee Table.
  ```
@relation employee-1
@attribute age {youth, middle, senior}
@attribute income {high, medium, low}
@attribute class {A, B, C}

@data
youth, high, A 
youth,medium,B 
youth, low, C 
middle, low, C 
middle, medium, C 
middle, high, A 
senior, low, C 
senior, medium, B 
senior, high, B 
middle, high, B
```

3)	After that the file is saved with .arff file format.
4)	Minimize the arff file and then open Start  Programs  weka-3-4.
5)	Click on weka-3-4, then Weka dialog box is displayed on the screen.
6)	In that dialog box there are four modes, click on explorer.
7)	Explorer shows many options. In that click on ‘open file’ and select the arff file
8)	Click on edit button which shows employee table on weka.
 
Training Data Set  Employee Table
<img width="731" height="788" alt="image" src="https://github.com/user-attachments/assets/4606bb39-2189-499b-93cd-de557254bf3f" />

### Procedure for Association Rules:
1)	Open Start  Programs  Weka-3-4  Weka-3-4
2)	Open explorer.
3)	Click on open file and select employee-1.arff
4)	Select Associate option on the top of the Menu bar.
5)	Select Choose button and then click on Apriori Algorithm.
6)	Click on Start button and output will be displayed on the right side of the window.
 <img width="1080" height="855" alt="image" src="https://github.com/user-attachments/assets/ed55ef14-ccfe-4eb0-9c8a-cd5740aab138" />

 
### Output:
<img width="941" height="568" alt="image" src="https://github.com/user-attachments/assets/553cab8b-b1a0-4116-ac90-37308e0b6273" />
<img width="941" height="636" alt="image" src="https://github.com/user-attachments/assets/6eda356b-a835-48c4-a32b-c708825289ac" />


 
 





























### Result:
Thus, this program has been successfully executed.
