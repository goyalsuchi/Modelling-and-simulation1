# Modelling-and-simulation1
Modelling and simulation of one day cricket in accordance with research paper
This project is concerned with the simulation of one-day cricket matches. Given that only a finite number of outcomes can occur on each ball that is bowled, a discrete generator on a finite set is developed where the outcome probabilities are estimated from historical data involving one-day international cricket matches. The probabilities depend on the batsman, the bowler, the number of wickets lost, the number of balls bowled and the innings. The proposed simulator appears to do a reasonable job at producing realistic results. The simulator allows investigators to address complex questions involving one-day cricket matches.

The data Taken here is of one day cricket from 2006 to 2017 of 21 teams in cricket. For the caluculation purpose later we use only 10 teams (teams who have played more than 50 matches).

The objective of the project is to predict the outcome of each ball based of diiferent factors such as batsman, bowler, innings, runs scored till now, wickets etc. Also we have to predict the batting order in the international cricket.

For ease purpose I have defined the runsperball as the target variable where outcome is the classification number 0=0 runs scored/wicket 1=1 runs scored 2=2 runs scored 3=3 runs scored 4=4 runs scored 6=6 runs scored

I have first fitted the data into a random forest classifier and later with SVC, Random Forest and PyMC

Data has been taken from cricsheet.org which gives ball by ball data of the match as required.

Requirement:
Python 3.8 Jupter notebook
