Project Title:

This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. 
The first part, contains use Python visualization libraries to systematically explore a selected dataset, starting from plots of 
single variables and building up to plots of multiple variables. The second part contains producing a short presentation that illustrates 
interesting properties, trends, and relationships that is being discovered in the selected dataset. The primary method of conveying 
findings will be through transforming exploratory visualizations from the first part into polished, explanatory visualizations.



Prerequisites:

Data Set was chosen from the options given at the Udacity Project Details and it contained two files i.e.
Loan Data from Prosper (which contained the data) with Prosper Data Dictionary to Explain Dataset's Variables


Installations:

This project uses Python 3 and is completed through the Jupyter Notebooks IDE. 
The Anaconda distribution is used to install Python, since the 
distribution includes all necessary Python libraries as well as Jupyter Notebooks. 

The following libraries are installed and used in this project:
(i) NumPy
(ii) pandas
(iii) Matplotlib
(iv) Seaborn



Running the tests:

The zip file contains four documents/files.
(1) Ipynb - This Jupyter Notebook contains all the executable cells with codes used for exploration followed by explanation.
(2) html - This Jupyter Notebook contains all the executable cells with codes used for exploration followed by explanation.
(3) readme file - This text file contains the information about the Project. 
(4) slide deck - This Jupyter Notebook contains starter cells that contains final deliverables.


Documenting The Story:

Firstly bivariate and univariate plots were made to find some relation between the variables that can effect the Gross Principal Loss.
Then after gaining some insights that the variable can have an effect on Gross Principal Loss a third variable was added to see the pattern
and if it does show something interesting and valuable to know, it was polished there and then.

Some exploration Lead to dead end in finding answer and certain exploration lead to great interesting insights. 
Hence, Summary of the findings in a nutshell are as below. (Albiet, these are just insights and has its limitations.)


Summary:

(1) We got an idea that most of the borrowers fall under the category of C, D and B category of Credit Grade.

(2) Most many borrower fall under the category of Annual Income range of dollars 25,000 - 49,999 and dollars 50,000 - 74,999, both are 
nearly double than any other categories when compared individually.

(3) Different group of borrowers based upon Income Range showed different Gross Principal Losses. 

(4) There exists a relation between Original Loan Amount and Gross Principal Loss alongwith credit grade. As, Number of Loans with Gross 
Principal loss in smaller ticket size loans are more than Larger Loans and mostly Credit grade HR, C and D are occupying places less than 
10000 dollars amount. Whereas, for large loans(Amounting Greater than dollars 10000) mostly AA, B and A are occupying places in figure. 
Though, for larger amounting loan the density is less but severity of hitting a loss is also high. Hence, both the factors should be taken
 into consideration before strategising.

(5) Certain Professional Occupations can be less risky in terms of Gross Principal Loss and highly profitable. Hence, Prosper Financial 
Institution can focus upon these occupations and encourage certain categories to improve its profitability like for example 'student - 
College Freshman' are less dense and the severity of loss is also less, hence these category of loanees can be a good risk.

(6) It can be seen that Credit Grading Categories like HR, E, NC are showing the least Gross Pricipal Losses. Whereas, Credit Grading like 
B, A and C are showing highest Gross Principal Losses.

(7) Gross Principal Loss varies with the State.

(8) The ones with Prosper Rating A,B and C and having a mortgage on their credit profile or provide documentation confirming they are a 
homeowner are most likely to hit Gross Principal Loss on the balance sheet of Prosper Loans. In contrast to the group of Borrowers having 
Prosper Rating AA, A and HR and not having a mortgage on their credit profile or provided any documention confirming the same are least 
likely to show Gross Principal Losses and so they are least risky borrowers to whom loans can be disbersed. Although, its just an insight
 and needs further investigation.

(9) The ones with Zero Income and the ones with income 'Not Displayed' but having a mortgage on their credit profile or provided documentation
 confirming they are a homeowner are most likely to hit Gross Principal Loss on the balance sheet of Prosper Loans. In contrast, the group of 
loanees with income range dollars (100,000+) & dollars (75000 - 99,999) with no mortgage on their credit profile or have'nt provided 
documentation confirming being homeowner are best prospects which can boost in increasing the profitabilty for Prosper Loans as these group of 
Borrower are having least Gross Principal Losses.  Most many borrower fall under the category of Annual Income range of dollars 25,000 - 49,999
 and dollars 50,000 - 74,999 and so, the profitability of these income Groups is also not so bad in terms of Losses due to Gross Principal. 
Hence, these above mentioned income groups and not owning a home categories can be a good focus areas for the Proper Group.

(10) Very Short Term Loans with Loan Term of 12 Months with Higher Prosper Score can be the least risky loans to be given by the Financial Instution.
 vis. Prosper Score with 10, 9, 8 and 7 with Term 12 months can be the best possible option to reduce Gross Principal Losses. In contrast, group of 
Borrowers having Prosper Score with 1, 5 and 6 and having Term of the Loan as 36 Months or 60 Months are showing the highest Gross Principal Losses,
 amongst these group with Prosper Rating 1 being the leader in Gross Principal Losses Highest.


Versioning:

(1) Python 3

(2) Jupyter Notebooks IDE


Acknowledgments:

(1) Udacity Team for Tutorials and Contents

(2) Udacity Mentors

(3) Udacity Reviewers
