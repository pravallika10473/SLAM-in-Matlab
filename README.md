# SLAM-in-Matlab
* Implementing the pose graph optimization in matlab to build the map of the environment.
* This in particular can be used in case of robotic vacuum cleaners. Basic robotic vacuum cleaners moved more or less randomly using sensors to change direction whenever faced with an obstacle or the top of a set of steps .This is a heuristic approach which doesn't need any kind of map of its environment,this gets the job done, but it’s hardly very efficient or intelligent. 
* So we take lidar data set and use Simultaneous Localization and Mapping(SLAM) to simulate a room with walls and obstacles (various things in a room) in MATLAB and robot can predict the efficient path for the robot to follow between two points without any collisions in the map generated
# Build Map of the environment 
![First Loop closure](https://user-images.githubusercontent.com/68220390/176094505-8a690d08-6cdb-42fc-bb87-5fa5928cd3c5.png)
![final build](https://user-images.githubusercontent.com/68220390/176094579-a19405da-6354-4e6e-8092-cca92df8f635.png)


