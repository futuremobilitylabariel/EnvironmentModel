# EnvironmentModel
In this repository we order all the Aimsun Scripts for environment Analysis

Car Version Folder:

1.Env_Load_Outputs - Load from old CSV file that countain results of env model.

this script run from aimsun , and need the republucation be active (blue)

the script need path to result folder.

2. Env_Model_Cars - this script run new counculation of env model and save csv file of the results

this script run from aimsun , and need the republucation be active after run (blue)

this script need path to 

A. folder that countaions the founction.py file. (founction_car_linux)
B. folder that save the results.
C. tp parameter : number of intervals in the republication results.

3. Founction_car_linux.py - list of all methods that mesure the emmisions for all road sections.

this file need path to :

A. CO2 Emmison Factor
B. NOX Emmison Factor
C. FC Emmison Factor
D. PM2.5 Emmison Factor
E. NMVOC Emmison Factor
F. NMVOC -Ediu Emmison Factor
G. PM2.5 -Shhika Emmison Factor
H. tp parameter : number of intervals in the republication results.
I. havy parameter : the density that above that the road is in havy mode
J. stop_and_go parameter : the density that above that the road is in "pkak"









