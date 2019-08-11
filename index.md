# About Me
&ensp;&ensp;My name is Minzhao Zhu. I am a student at Beijing Institute of Technology, China, pursuing my M.S degree in Control Science and Engineering. My research interests are localization and perception of robots. ([CV](https://minzhao1995.github.io/figures/MinzhaoZhu_BIT.pdf))

# Research
### LiDAR-based Vehicle Localization based on Satellite Image Matching
<center>
<video id="video" controls="" preload="none" poster="https://minzhao1995.github.io/figures/paper.png"  width ="720"><source id="mp4" src="https://minzhao1995.github.io/figures/paper.mp4" type="video/mp4"  width="720"></video>
</center>
<center>Demonstration Video</center>
&ensp;&ensp;Proposed a localization method that uses satellite image as the prior information to achieve localization in GNSS-denied area. A neural network is proposed to compare the LiDAR grid-map with the satellite image patch in the Bird&apos;s Eye View (BEV). The network first extracts the spatial-discriminative feature maps of the grid-map and the satellite image respectively, then a classification network is used to compare the feature maps and outputs the probability of correspondence. Then based on the outputs, a particle filter is used to obtain the probability distribution of the vehicle&apos;s pose.
	

# Projects
### UAV-UGV Cooperative System
<center class="half">
<img src="https://minzhao1995.github.io/figures/uav.jpg" height="240"/><img src="https://minzhao1995.github.io/figures/air_ground.png" height ="240"/>
</center>
<center> The UAV in the system</center>

&ensp;&ensp;The UAV and UGV searches and tracks the moving target (a vehicle) in an unknown area collaboratively. The UAV searches the ground target in a wide area and send the position of the target to the UGV continuously after the target is found.

### Hongqi-H7 Self-driving Car
<center>
<img src="https://minzhao1995.github.io/figures/hongqi.png" width="480"/>
</center>
<center>Hongqi-H7 Self-driving Car</center>

&ensp;&ensp;We won the First Prize in 2017 China Smart Car Future Challenge Highway Competition. I designed a lane detection algorithm in which SegNet is used to segment the ground region and Hough transform is used to detect the lane in the Bird&apos;s Eye View (BEV). The feature maps of the image patches on the lane candidate regions are fed to a classification network to obtain the type of the lane. 

### Intelligent Mouse and Keyboard Switcher 
<center>
<img src="https://minzhao1995.github.io/figures/svm.gif"  width="480"/>
</center>
<center>Demonstration of Usage</center>

&ensp;&ensp;This project is designed to make it easy for users to operate multiple computers with a single mouse and keyboard. Face orientation recognition algorithm is used to find which computer the user desires to use. Then the device automatically switches the mouse & keyboard signals to that computer.

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

&ensp;&ensp;This mobile robot is designed for bank reception service. I designed a localization algorithm which can be used for docking with the auto-charge station. The algorithm uses 2D-laser SLAM and visual-based charge station detection to localize the robot. Up until now, the robot has been deployed into service at 35 banks for 2 years.



