## 1. Problem Statement

### Background

	Growing concerns with environmental issues have led to the consideration of alternatives to urban mobility. Among available options, electric vehicles (EV) have been considered in advantage in terms of sustainability as well as emission of pollutants. This work using Gorubi optimizer and K-means to optimize the EV charging station allocation in NewYork City.

	At present, there are three levels of chargers in the EV market. The charging time, construction and labor costs are different according to the chargers’ level. Through investigating, there are 361 charging stations, each charging station averagely has 1-3 chargers of different levels, most of them has 2 chargers and the level 2 charger is the most general. In addition, New York City has 6551 registered EV on the road. 


### Data Resources

The following datasets are collected form the Electric Vehicle Station Locator Website (https://www.nyserda.ny.gov/All-Programs/Programs/Drive-Clean-Rebate). 
And NYC Open DataWebsite (https://data.cityofnewyork.us/widgets/i8iw-xf4u)

## 2. Optimization Model

* Assumption: 
	1. Each station can only install one specific level of charger, and each charger can only serve one user only. 
	2. The user can only go to the assigned station. 
	3. Each station would install 2 chargers.

* Python Packages
	
	Gorubi

	The Gurobi Optimizer is a commercial optimization solver for linear programming (LP), quadratic programming (QP), quadratically constrained programming (QCP), mixed integer linear programming (MILP), mixed-integer quadratic programming (MIQP), and mixed-integer quadratically constrained programming (MIQCP). Gurobi was founded in 2008 and isnamed for its founders: Zonghao Gu, Edward Rothberg and Robert Bixby. Bixby was also the founder of CPLEX, while Rothberg and Gu led the CPLEX development team for nearly a decade.
	See Jupyter notebook for detailed model and results
