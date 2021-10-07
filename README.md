# Improvements_in_automatic_ship_collision_avoidance_using_AI


**Collision prevention** is critical for navigation safety at sea. In the early days, researchers developed navigational assistance systems to help humans in ships tackle collision occurrence. Recently, autonomous vehicles have gained a remarkable amount of attention, focusing on solving collision problems by machines. In this project, we would like to improve state-of-art mechanisms for automatic ship collision avoidance(CA). 

CA's procedure is divided into three steps: 
i)   Motion prediction, 
ii)  Conflict detection, and
iii) Conflict resolution.

**Motion prediction** involves predicting trajectories of own ship and obstacles. Those trajectories will help to determine the collision risk for conflict detection. Motion prediction relies on the motion models of the ship(mathematical expressions). This can be done using Monte-Carlo simulation or Kalman filter.

**Conflict detection** involves expert-based and model-based detection. Expert-based detection uses Fuzzy logic. Model-based detection involves various methods, and one of them is Monte-Carlo simulation to assess the probability. The expert-based process can offer customized services for different navigators, which can meet users' preferences. On the other hand, the model-based approach usually addresses some relative objective fact, which shows the rigid boundary of safety and danger. These two methods are combined to offer a better service to human-crewed and uncrewed ships.

**Conflict resolution** is the crucial step in CA. There are several methods for conflict resolution. Here we would like to develop a novel approach of using constraint-based AI search mechanisms to find optimal trajectories. The constraints here are that the path found should be optimal and should not overlap the target ship's collision range.
