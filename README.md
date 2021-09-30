# BalanceDataProject
Task 1 - Build a decision Tree model

## BalanceDataDT
Decision Tree Model on balance data from UCI -> [Dataset](https://archive.ics.uci.edu/ml/datasets/Balance+Scale)

## Project Submission Guidlines:
1. First Fork the Repo.
2. Then go to issue section of my repo.
3. Search the Issue with your name.
4. Ask me in Comments to assign the issue to you.
5. After that you can clone the repo of yours in your local system ```git clone https://-------``` and
6. then make a dev branch using -> ``` git checkout -b dev``` 
7. upload the project in your folder according to name.
8. Update the the readme files of your project folder
9. then add ```git add .``` and commit ```git commit -m "add project files" ``` all your work 
10. to your origin/dev branch using -> ```git push -u origin dev```
11. And then finally make A Pull Request by going to your github forked repo.
12. Write a suitable title and comment in your Pull Request(PR).
13. If Everything will be fine It'll get merge.

## Dataset Description
1. Title: Balance Scale Weight & Distance Database

2. Source Information: 
    (a) Source: Generated to model psychological experiments reported
		by Siegler, R. S. (1976).  Three Aspects of Cognitive
		Development.  Cognitive Psychology, 8, 481-520.
    (b) Donor: Tim Hume (hume@ics.uci.edu)
    (c) Date: 22 April 1994

3. Past Usage: (possibly different formats of this data)
   - Publications
	1. Klahr, D., & Siegler, R.S. (1978).  The Representation of
	   Children's Knowledge.  In H. W. Reese & L. P. Lipsitt (Eds.),
	   Advances in Child Development and Behavior, pp. 61-116.  New
	   York: Academic Press 
	2. Langley,P. (1987).  A General Theory of Discrimination
	   Learning.  In D. Klahr, P. Langley, & R. Neches (Eds.),
	   Production System Models of Learning and Development, pp.
	   99-161. Cambridge, MA: MIT Press
	3. Newell, A. (1990).  Unified Theories of Cognition.
	   Cambridge, MA: Harvard University Press
	4. McClelland, J.L. (1988).  Parallel Distibuted Processing:
	   Implications for Cognition and Development.  Technical
	   Report AIP-47, Department of Psychology, Carnegie-Mellon
	   University 
	5. Shultz, T., Mareschal, D., & Schmidt, W. (1994).  Modeling
	   Cognitive Development on Balance Scale Phenomena. Machine
	   Learning, Vol. 16, pp. 59-88.

4. Relevant Information: 
	This data set was generated to model psychological
	experimental results.  Each example is classified as having the
	balance scale tip to the right, tip to the left, or be
	balanced.  The attributes are the left weight, the left
	distance, the right weight, and the right distance.  The
	correct way to find the class is the greater of 
	(left-distance * left-weight) and (right-distance *
	right-weight).  If they are equal, it is balanced.

5. Number of Instances: 625 (49 balanced, 288 left, 288 right)

6. Number of Attributes: 4 (numeric) + class name = 5

7. Attribute Information:
	1. Class Name: 3 (L, B, R)
	2. Left-Weight: 5 (1, 2, 3, 4, 5)
	3. Left-Distance: 5 (1, 2, 3, 4, 5)
	4. Right-Weight: 5 (1, 2, 3, 4, 5)
	5. Right-Distance: 5 (1, 2, 3, 4, 5)

8. Missing Attribute Values: 
	none

9. Class Distribution: 
   1. 46.08 percent are L
   2. 07.84 percent are B
   3. 46.08 percent are R
