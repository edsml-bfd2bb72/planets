# Independent Research Project
## Temperature Stability of Bloch Point 
### BAI YANG, MSc student of Applied Computational Science and Engineering
### Departament of Earth Science and Engineering
### Imperial College London
|  Version  |    Date    |  Update content  |
|:---------:|:----------:| :---------------:|
|    1.0    | 27/8/2022  |      Relese      |

## Objective
![avatar](https://github.com/ese-msc-2021/irp-yb121/blob/main/figure/bloch%20point.png)
The existence of the bloch point provides ideas for the development of new types of memory, but we need to determine the temperature(β) range in which the bloch point exists to ensure that the principles the memory relies on are reliable within the operating temperature range. Based on this requirement, we propose a solution to find the temperature(β) range where the bloch point exists by numerical simulation. In this project, the mean field (MF) for simulation is first realized, and then it is combined with dichotomy to find the critical temperature parameter β.

## Package Requirement
Python 3.9.12

Numpy

Ubermag https://ubermag.github.io/

matplotlib

## Program Structure
This project mainly contains three files, namely:

basic_calculation.py, which is used to accept and process the magnetic moment data from Ubermag to calculate the effective field.

mean_field.py, which is used to implement MF algorithm.

simulation.py, which is or finding critical β and visualizing magnetic moment data. It's include part 1 and part 2, if you want to run any of it, please comment
out the other. 

## For Physics Scientist
If you need to use the MF method, the algorithm is in mean_field.py. If you need to find two bloch points of "Head to Head" or "Tail to Tail", the relevant examples and parameters have been marked in the simulation.py. You can run it directly after modifying the parameters.

## For Computational Scientist
To understand the principle behind this project, please read reports/yb121-final-report.pdf. If you want to continue to develop the whole project, the points that need attention in the project have been commented in the code, please read carefully.

## Acknowlegement
This project thanks Dr. Marijan Beg, Dr. Samuel Holt for their guidance and suggestions.

## Reference
Please see final report.

## Contact
If you have any questions to discuss, please email:

yb121@ic.ac.uk
