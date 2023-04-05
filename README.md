### Preview: A demo of using DRLA-eTGM to solve a single-track rail scheduling problem instance
author: Feiyu Yang et al.  
feiyu@my.swjtu.edu.cn  


 In order to demonstrate a new method for solving single-track railway train schedules, DRLA-eTGM, proposed by our research team, we present part of this method here.
For the confidentiality of article review, we have only opened one demo on the Internet.  

The full open-source project: C, Python and .NetFramework-based eTGM emulators and PyTorch-based DRLA-eTGM learning algorithm implementations will be further released after the authorization of the research funding unit. 

 This preview will show the solution process (i.e. the training process) for the largest problem case Ins-III described in the paper using the method on MATLAB. So that you can quickly evaluate the method, we package the project as a MATLAB app. The specific steps are as follows:
1. download and install (using MATLAB to install) the app.  
2. download and put resource files in a dir.  
3. using MATLAB to open the dir.  
4. run the installed app in the Applications (installed apps in the MATLAB) window.  

 We recommend using a high-performance GPU that operates in TCC mode and making sure that the computer has enough memory.When expected, the app will solve the Ins-III case and output a graphical timetable with 104 trains. When the app is running, we will be able to observe the total reward received by the agent through the window of the app. When the reward exceeds 45,000, we believe that the app has found a conflict-free timetable. 
 
 Typically, the process will not take more than several hours.   

 It is worth mentioning that after authorization, we will release C, Python and C#-based eTGM emulators and PyTorch-based DRLA-eTGM learning algorithm implementations, which will accelerate our algorithms by orders of magnitude time advantage.  
  
Form more detailed info:
[![View Railway Scheduling With a Gridworld Model and DRL on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/126710-railway-scheduling-with-a-gridworld-model-and-drl)
