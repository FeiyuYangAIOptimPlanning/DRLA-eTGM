### Preview: A demo of using DRLA-eTGM to solve a single-track rail scheduling problem instance
author: Feiyu Yang et al.  
feiyu@my.swjtu.edu.cn  


 In order to demonstrate a new method for solving single-track railway train schedules, DRLA-eTGM, proposed by our research team, we present part of this method here.
For the confidentiality of article review, we have only opened one demo here.  

The full open-source project: C, Python and .NetFramework-based eTGM emulators and PyTorch-based DRLA-eTGM learning algorithm implementations will be further released after the authorization of related parties. 

 This preview will show the solution process (i.e. the training process) for the largest problem case Ins-III described in the paper using the method on MATLAB. So that you can quickly evaluate the method. The specific steps are as follows:
1. download these .p and .mat files.  
2. put these files in a single directory.  
3. using MATLAB to open the directory. (Only supports MATLAB 2022 and later versions)  
4. Enter the code "runTrain" in the command window of MATLAB and press "Enter".    

As shown in the following figures:   

![1](https://user-images.githubusercontent.com/128687099/230165391-ac7b6a08-0eee-4c94-8359-1261b70b3566.PNG)  

![2](https://user-images.githubusercontent.com/128687099/230165414-c6c22de4-bd82-4d66-8c2f-ee55c3ea7b86.PNG)

 We recommend using a high-performance GPU that operates in TCC mode and making sure that the computer has enough memory.When expected, the app will solve the Ins-III case and output a graphical timetable with 104 trains. When the program is running, we will be able to observe the total reward received by the agent through the window. When the reward exceeds 45,000, we believe that the program has found a conflict-free timetable. 
 
 Typically, the process will not take more than several hours.   

 It is worth mentioning that after authorization, we will release C, Python and C#-based eTGM emulators and PyTorch-based DRLA-eTGM learning algorithm implementations, which will accelerate our algorithms by orders of magnitude time advantage.  
