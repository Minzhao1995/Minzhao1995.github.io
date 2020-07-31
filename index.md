# About Me
&ensp;&ensp;My name is Minzhao Zhu. I am an algorithm engineer at Bytedance AI Lab. Before that, I received my M.S degree in Control Science and Engineering at Beijing Institute of Technology. My research interests include localization and perception of robots.  ([CV](https://minzhao1995.github.io/figures/MinzhaoZhu_BIT.pdf))

# Publications
LiDAR-based vehicle localization on the satellite image via a neural network  ([PDF](https://minzhao1995.github.io/figures/RAS.pdf))  
&ensp;&ensp;Mengyin Fu, **Minzhao Zhu**, Yi Yang, Wenjie Song, Meiling Wang  
&ensp;&ensp;Robotics and Autonomous Systems, 2020

<center>
<video id="video" controls="" preload="none" poster="https://minzhao1995.github.io/figures/paper.png"  width ="720"><source id="mp4" src="https://minzhao1995.github.io/figures/paper.mp4" type="video/mp4"  width="720"></video>
</center>



# Research
### Air-Ground Cross-View based LiDAR Odometry and Mapping  
<center>
<video id="video" controls="" preload="none" poster="https://minzhao1995.github.io/figures/ccdc.png" width ="720"><source id="mp4" src="https://minzhao1995.github.io/figures/ccdc.mp4" type="video/mp4"  width="720"></video>
</center>

To reduce the accumulated error of the LiDAR odometry, the satellite image patch, which is cropped on the pose given by the odometry, is compared with the LiDAR grid-map via a neural network. The network directly outputs the pose correction offset, which is added to the factor graph.

### Air-ground Cross-view Semantic SLAM

To improve the precision of semantic segmentation, based on a LiDAR projection image, the semantic information from aerial view is fused with multiple ground views via Bayesian update.


# Projects
### UAV-UGV Cooperative System
<center class="half">
<img src="https://minzhao1995.github.io/figures/uav.jpg" height="240"/><img src="https://minzhao1995.github.io/figures/air_ground.png" height ="240"/>
</center>
<center> The UAV in the system</center>

&ensp;&ensp; The UAV and UGV search and track the moving target (a vehicle) in an unknown area (3 km x 3 km) collaboratively. I led our team to build this system and we won the **first place** in the 2018 China Unmanned System Challenge (Air-Ground Collaboration Contest).

### Hongqi-H7 Self-driving Car
<center>
<img src="https://minzhao1995.github.io/figures/hongqi.jpg" width="480"/>
</center>
<center>Hongqi-H7 Self-driving Car</center>

&ensp;&ensp;We won the **first place** in the 2017 China Smart Car Future Challenge Highway Contest. As a team member, I designed a lane detection algorithm and a LiDAR-based accessible region detection algorithm.

### Intelligent Mouse and Keyboard Switcher 
<center>
<img src="https://minzhao1995.github.io/figures/kvm.gif"  width="480"/>
</center>
<center>Demonstration of Usage</center>

&ensp;&ensp;This project is designed to make it easy for users to operate multiple computers with a single mouse and keyboard. A face orientation recognition algorithm is designed to find which computer the user desires to use. Then the device automatically switches the mouse & keyboard signals to that computer.

## BankBot
<center>
<img src="https://minzhao1995.github.io/figures/mapping.gif" alt="mapping" title="mapping" width="720"/>
</center>
<center>Mapping</center>  

<center>
<img src="https://minzhao1995.github.io/figures/navigation.gif" alt="navigation" title="navigation" width="720"/>
</center>
<center>Navigation</center>  

<center>
<img src="https://minzhao1995.github.io/figures/charging.gif" alt="auto charging" title="auto charging" width="540"/>
</center>
<center>Auto Charging</center>

&ensp;&ensp;This mobile robot is designed for bank reception service. I designed a 2D-SLAM algorithm in which the weight of points with high roughness is enhanced so that scan matching in the longitudinal direction can be more accurate. Up until now, the robot has been deployed into service at 35 banks for 2 years.


