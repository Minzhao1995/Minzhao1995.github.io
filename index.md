## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Minzhao1995/Minzhao1995.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

#paper
<video id="video" controls="" preload="none" poster="https://minzhao1995.github.io/figures/paper.png"><source id="mp4" src="https://minzhao1995.github.io/figures/paper.mp4" type="video/mp4"  height="480"></video>



## Hongqi-H7 Self-driving Car
<img src="https://minzhao1995.github.io/figures/hongqi.png" title="bankbot" height ="480" />
<center>Hongqi-H7 Self-driving Car</center>

###### Designed a lane detection algorithm. SegNet is used to segment the ground region. Then the image with the ground mask is transformed into bird's-eye view by Inverse Perspective Mapping (IPM). Hough transform is used to detect the lane. Then the feature maps of the image patches on the lane candidate regions are fed to a classification network to obtain the type of the lane. The algorithm can run at a frequency of 5Hz on the computer with NVIDIA GTX 1070.


## BankBot
<div style="float:left;border:solid 1px 000;margin:2px;"><img src="https://minzhao1995.github.io/figures/mapping.gif" alt="screenshot" title="screenshot777" height="480" ></div>

<div style="float:left;border:solid 1px 000;margin:2px;"><img src="https://minzhao1995.github.io/figures/navigation.gif" alt="screens2hot" title="screen22shot" height="480" ></div>

<div style="float:left;border:solid 1px 000;margin:2px;"><img src="https://minzhao1995.github.io/figures/charging.gif" alt="screens2hot" title="screen22shot" height="480" ></div>

<div style="clear:both;"> </div>

Designed a localization algorithm which can be used for docking with the auto-charge station. The algorithm uses 2D-laser SLAM and visual-based charge station detection to localize the robot. Up until now, the robot has been deployed into service at 35 banks for 2 years.






