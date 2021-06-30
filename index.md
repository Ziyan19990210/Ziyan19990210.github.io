## Ziyan Liao

You can use the [editor on GitHub](https://github.com/Ziyan19990210/Ziyan19990210.github.io/edit/main/index.md) to maintain and preview the content for your website in Markdown files.

### About me

Name: Ziyan Liao 

Date of birth: 10/02/1999

Nationality: China

![image](https://user-images.githubusercontent.com/86719547/124009765-e64d0200-d9d5-11eb-836c-c182b9686388.png)

### Education background           
1. MPhil in Electrical Engineering, 2020.11-2021.11
   University of Manchester, UK
   Supervisor: Dr Alessandra Parisio

2. Exchange student in Electrical Engineering, 2019.07-2020.07
   University of Birmingham, UK
   Supervisor: Dr Dilan Jayaweera
   GPA: 3.5/4.0, Weighted Average Mark:65.667/100 

3. B.E. in Electrical Engineering, 2016.09-2019.06
   Beijing jiaotong University (BJTU), China
   Supervisor: Prof Xiaojun Wang
   GPA: 3.37/4.0, Weighted Average Mark:83.5/100

### Research experience
### 1. Reliability assessment and optimization of multi-energy system, 2020.11-2021.11

This is the main project that I have investigated in my research during my MPhil study in University of Manchester this year. This project mainly includes five parts:

(1) Modeling of multi-energy system;

(2) Reliability assessment in multi-energy system considering load uncertainties;

(3) Reliability optimization of multi-energy system considering energy storage devices effects;

(4) Sensitive analysis of proposed research;

(5) Optimal dispathing problem in multi-energy system.

At present, all the main parts of this project have been finished, and my first paper is going to be published. I still make an effort to get another chance to have my second publication.

(1) Modeling of multi-energy system

The multi-energy system contains IEEE 24 bus system, 13-node heat network, and 9-node natural gas system. The multi-energy schematic diagram is shown as below:
![image](https://user-images.githubusercontent.com/86719547/124008374-43e04f00-d9d4-11eb-8d46-a67016e834fb.png)

(2) Reliability assessment in multi-energy system considering load uncertainties

The Weibull distribution and Beta distribution have been used to model wind and PV uncertainties. 
![image](https://user-images.githubusercontent.com/86719547/123991001-36ba6480-d9c2-11eb-8e54-5b941b495eff.png)

The power load curve of MES after considering uncertainties is shown below:
![image](https://user-images.githubusercontent.com/86719547/123982278-cbb95f80-d9ba-11eb-8acd-0a6ac31f848a.png)

BP neural network also has been adopted to forecast different types of load, the load forecasting results for heat and natural gas network user is presented below:
![image](https://user-images.githubusercontent.com/86719547/123990733-f0fd9c00-d9c1-11eb-8956-01624afe8ea1.png)


The implementation of sequential Monte Carlo simulation in multi-energy system reliability evaluation with different energy storage devices considering time varying cost models and load uncertainties can be presented in the following flow chart:
![image](https://user-images.githubusercontent.com/86719547/124008639-8bff7180-d9d4-11eb-8dde-c2d06c5e6ad4.png)

(3) Reliability optimization of multi-energy system considering energy storage devices effects

Determine the optimal location number of storage device in power grid, heat network and gas network at the lowest possible cost and highest reliability under load uncertainty are the main objective of the research. The reliability optimization problem has been formulated as a multi-objective optimization problem (using NSGA-II algorithm) to minimize reliability index SAIDI (system average interruption duration index) and reliability cost. The cost functions are modeled as the interruption cost of different types of customer and installation cost of energy storage devices. A comparative analysis with other modern multi-objective algorithms such as MOPSO and SPEA2 is presented to validate the effectiveness of the proposed approach. 
The Pareto Front results of the multi-objective optimization is presented as below:
![image](https://user-images.githubusercontent.com/86719547/123983667-f5bf5180-d9bb-11eb-86e9-a00dfb9b6f76.png)

(4) Sensitive analysis of proposed research

Reliability sensitivity analysis is to obtain the partial differential of each reliability index against component parameters. The sensitivity index reflects the change degree and trend of system reliability caused by the small change of component parameters. this paper analyzes the influence of line failure rate and repair time, transformer failure rate and repair time, coupling components such as CHP, P2G, GB failure rate and repair time on the important system reliability index. Taking the 2 MESs as an example, the sensitivity of each index after the reliability parameter of each component is reduced by 10% is calculated respectively. The results of reliability sensitivity analysis are shown in the following figures:
![image](https://user-images.githubusercontent.com/86719547/123984852-e55ba680-d9bc-11eb-843b-11d57905788d.png)



(5) Optimal dispathing problem in multi-energy system
When we consider the minimum cost as the obective function, using YALMIP+CPEX solver, we can get the optimal dispatching of each unit shown as the following figures:
![image](https://user-images.githubusercontent.com/86719547/124009475-966e3b00-d9d5-11eb-8f66-75ca1ee97ccd.png)
![image](https://user-images.githubusercontent.com/86719547/124008931-e4367380-d9d4-11eb-8633-257cc92c1653.png)
![image](https://user-images.githubusercontent.com/86719547/124009014-fe705180-d9d4-11eb-8cb8-3b27bcd82718.png)

### 2. Reliability assessment in a smart power system with smart reconfiguration of lines, 2019.09-2020.06

This is the project when I was an exchange student in University of Birmingham last year. Using DIGSILENT power factory to model smart power system based on IEEE 24 bus system. The aim of this project is to model reconfiguration of lines in a smart grid and then assessing the performance with the introduced new environment. The project involves modelling of smart reconfiguration of lines by applying smart switching and network congestion issues. 

The following figures are the IEEE 24 bus system and RBTS bus 5 system that I built in Digsilent software.
![image](https://user-images.githubusercontent.com/86719547/123986713-75e6b680-d9be-11eb-889c-73c894b76832.png)
![image](https://user-images.githubusercontent.com/86719547/123986731-797a3d80-d9be-11eb-9bad-1e71fde94dcb.png)

Different reconfiguration scheme are used to compare the reliability performance. Among the 4 cases, case 4 is the optimal one, which obtained from simulated annealing algorithm.

![image](https://user-images.githubusercontent.com/86719547/123987274-f4435880-d9be-11eb-8b09-08bc186fc615.png)
After applying the optimal reconfiguration scheme to the power distribution system RBTS bus 5, the system diagram is shown below:
![image](https://user-images.githubusercontent.com/86719547/123987515-2bb20500-d9bf-11eb-8342-ad3bb33f8cbc.png)
Load points 12 and 13 have transferred to feeder 1, and load points 25 and 26 have transferred to feeder 3. 

### 3. Geometric parameter imaging monitoring of railway contact wire (overhead line) based on laser radar, 2018.06-2019.04

This is the project when I was a sophomore in Beijing jiaotong University beween 2018-2019. This project used MATLAB to process the data collected from the laser radar to reconstruct the image and calculate the guide height, pull out value and accuracy of the laser radar. The following video is I obtained from laser radar.
![image](https://user-images.githubusercontent.com/86719547/123988805-3a4cec00-d9c0-11eb-880f-84df890a5790.png)

Due to the limitation of the test condition, we have used a stick to simulate the railway contact wire. The length of the stick is the height of conductor, and the distance between stick and laser radar is the stagger value. The right side video is an actual experimental situation. The left side is what we got from MATLAB, and at the bottom right corner, this programme will indicate the data of the height of conductor and stagger value automatically with the movement of my classmate. Here, I need to point out that, in the real situation, the laser radar needs to be installed on the train, and with the movement of train, it can automatically show different overhead lines’ stagger value and its height. However, due to the limitations of the experimental place, we cannot let the laser radar move as it needs electricity to activate. Inversely, we let the person move to simulate the dynamic situation. 

![image](https://user-images.githubusercontent.com/86719547/123988942-58b2e780-d9c0-11eb-9d5c-1675ada6d05d.png)



### Contact

Phone: +44-7579861784

Email: ziyan.liao@postgrad.manchester.ac.uk
