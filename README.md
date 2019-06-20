# ADAPTIVE2019
A repostiory for reproducing the submitted results for Journal of Adaptive Behavior.

> **Abstract:** Biological agents need to complete perception-action cycles to perform various cognitive and biological tasks such as maximizing their well-being and their chances of genetic continuation. However, the processes performed in these cycles come at a cost. Such cost forces the agent to evaluate a trade-off between the optimality of the decision making and the time and computational effort required to make it.  Several cognitive mechanisms that play critical roles in managing this trade-off have been identified. Among these mechanisms, there are: adaptation, learning, memory, attention, and planning.  One of the often overlooked outcomes of these cognitive mechanisms, in spite of the critical effect that it may have on the perception-action cycle of organisms, is 'emotion.' In this study, we hold that emotion can be considered as an emergent phenomenon of a plausible neuro-computational energy regulation mechanism, which generates an internal reward signal to minimize the neural energy consumption of a sequence of actions (decisions), where each action triggers a visual memory recall process. To realize an optimal action selection over a sequence of actions in a visual recalling task, we adopted a model-free reinforcement learning framework, in which the reward signal -- i.e., the cost-- was based on the iterations steps of the convergence state of an associative memory network.  The proposed mechanism has been implemented in simulation and on a robotic platform: the iCub humanoid robot. The results show that the computational energy regulation mechanism enables the agent to modulate its behavior to minimize the required neuro-computational energy in performing the visual recalling task.

## Repository folders and their brief descriptions  
+ **Assets:** This folder contains the visual assets that used for constructing associative memory, building scene and converged state patterns.  
+ **Figures:** This folder contains subfolder in which the iCub experiment snapshots, methods for flow description and the result figures that shared in the paper are located.  
+ **Source:** The source code for a simulated and robotic agent to perform the designed experiments.  
+ **DATA:** The final results and experiment file in *.mat* format. 
+ **Logs:** Various logs both for the experiment and intermediate steps to evaluate results.  
+ **iCubExperiment.mp4:** A video to show the robotic agent experiment. 
+ **report:** This folder contains the resultd for different learning rates in table format.   

