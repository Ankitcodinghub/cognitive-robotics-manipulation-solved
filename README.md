# cognitive-robotics-manipulation-solved
**TO GET THIS SOLUTION VISIT:** [Cognitive Robotics Manipulation Solved](https://www.ankitcodinghub.com/product/cognitive-robotics-manipulation-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96778&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Cognitive Robotics Manipulation Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column"></div>
</div>
<div class="layoutArea">
<div class="column">
&nbsp;

Assignment Overview

Service robots typically use a perception system to per- ceive the world. In particular, perception systems provide valuable information that the robot has to consider for interacting with users and environments. To assist hu- mans in various daily tasks, a robot needs to know how to grasp and manipulate objects in different situations. For instance, consider a clear table task, where a robot needs to remove all objects from a table and put them into a basket. Such tasks consist of two phases: the first phase is dedicated to the perception of the object, and the second phase is about the planning and execution of the manipu- lation task. In this assignment, we mainly focus on deep visual object grasping and manipulation.

</div>
<div class="column">
Cognitive Robotics Course (2021-2021)

https://rugcognitiverobotics.github.io

</div>
</div>
<div class="layoutArea">
<div class="column">
The main goal of this assignment is to make a coupling

between perception and manipulation using eye-to-hand

camera coordination. Towards this goal, we have devel-

oped a simulation environment in PyBullet, where a Uni-

versal Robot (UR5e) with a two-fingered Robotiq 2F-140

gripper perceives the environment through an RGB-D cam-

era. The experimental setup for this assignment is shown

in Fig. 1. This setup is very useful to extensively evalu-

ate different object grasping approaches. After successful

completion of this assignment, students will be able to implement and experiment several methods for object grasping.

</div>
</div>
<div class="layoutArea">
<div class="column">
Traditional object grasping approaches explicitly model how to grasp different objects by considering prior knowledge about object shape, and pose. It has been proven that it is hard to obtain such prior information for never-seen-before objects in human-centric environments. More recent approaches try to tackle this limitation by formulating object grasping as an object-agnostic problem, in which grasp synthesis is detected based on learned visual features without considering prior object-specific information. In this vein, much attention has been given to object grasping approaches based on Convolutional Neural Network (CNN). Among deep visual grasping approaches, GR-ConvNet [1] showed the state-of-the-art results. In particular, GR-ConvNet receives an RGB and a Depth images and generate a pixel-wise grasp configuration. As an example of how to use CNN in visual grasping experiments, we have integrated the GR-ConvNet to our setup.

</div>
</div>
<div class="layoutArea">
<div class="column">
Figure 1: Our experimental setup consists of a table, a basket, a UR5e robotic arm, and objects from the YCB dataset. The green rectangle shows the robot’s workspace, and the camera indicates the pose of the camera in the environment. Syn- thesis RGB and depth images, together with a segmentation mask are shown on the left side of the figure.

</div>
</div>
<div class="layoutArea">
<div class="column">
In this assignment, we are pursuing three main goals: (i) learning about at least two deep visual grasping ap- proaches, (ii) evaluating and comparing their performances in three scenarios including, isolated, packed, and pile sce- narios (see Fig. 2); (iii) investigating the usefulness of formulating object grasping as an object-agnostic problem for general purpose tasks. You can also use this setup to develop your final project.

</div>
<div class="column">
Figure 2: Illustrative examples of three evaluation scenarios: (left) isolated; (center) packed and (right) pile of objects.

</div>
</div>
<div class="layoutArea">
<div class="column">
In this assignment, we use simulated YCB objects

dataset [2]. All objects were inspected to be sure that at least one side of the object fits within the gripper.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Ð Your tasks

</div>
</div>
<div class="layoutArea">
<div class="column">
This assignment comprises two parts, each worth 50% of your grade. For the first part, you need to understand and describe how this system works by reading GR-ConvNet paper, checking the provided code, and examining its performance in isolated, packed, and pile scenarios. We explain the evaluation scenarios and metrics below.

For the second part of this assignment, you need to select another deep visual grasping approach and integrate it into the system. Similar to the previous part, you need to evaluate the model in isolated, packed, and pile scenarios. Finally, you need to analyze and compare the obtained results with the GR-ConvNet model.

It should be noted that it is possible to select a 3D based deep learning approach (e.g., [3, 4, 5, 6]), or depth only based approaches (e.g., [7]), or even data-driven approach (e.g., [8]) instead of RGB-D based approaches. To convert the RGB-D image to point cloud you can use Open3D library. In the case of deep learning approaches, we strongly recommend using pre-trained models.

To evaluate a grasping approach, you need to performed 10 rounds of experiments per scenario and analysis the obtained results. In the case of pile and packed scenarios, for each experiment, we randomly generate a new scene consisting of five objects (see Fig. 3). For the isolated object scenario, we place a randomly selected object in an arbitrary pose inside the robot’s workspace. In all experiments, the robot knows in advance about the pose of the basket object as the placing area, while the robot needs to predict grasp synthesis for the given scene and select the best graspable pose to grasp the target object, pick it up, and put it in the basket. Note that, at the beginning of each experiment, we set the robot to a predefined setting, and randomly place objects on the table.

</div>
</div>
<div class="layoutArea">
<div class="column">
A particular grasp is recorded as a success if the object is

inside the basket at the end of the experiment. You need

to report the performance of an approach by measuring success_rate = numberof successful grasps .

number of attempts

In the case of pile and packed scenarios, to generate a sim- ulated scene containing five objects, we randomly spawn objects into a box placed on top of the table. We wait for a couple of seconds until all objects become stable, and then remove the box. To generate a packed scenario, we iteratively placed a set of objects next together in the workspace. These procedures are shown in Fig. 3.

For the pile and packed scenarios, in addition to the success_rate, you need to report the average percent- age of objects removed from the workspace. An exper- iment is continued until either all objects get removed from the workspace, or four failures occurred consecu- tively. Note that, the system automatically reports a sum- mary of the obtained results in the “results” folder, and the prediction of network is visualized and saved in the

“network_output” folder.

Ð What we offer for this assignment

</div>
<div class="column">
Figure 3: Generating random scenes to make: pile of objects (top-row); and packed objects (bottom-row).

</div>
</div>
<div class="layoutArea">
<div class="column">
• A detail instruction about how to install and run the experiments. Check the GitHub repository • Automatically report the obtained results after each round of experiments.

Policies

<ul>
<li>Feel free to collaborate on solving the problem but please write your code individually. In particular, do not
copy code/text from other students.
</li>
<li>You are not allowed to use this code in other projects (even if the code is partially used). If you want to publish your results as a scientific paper or use this framework in other projects, contact Hamidreza Kasaei (hamidreza.kasaei@rug.nl) directly and discuss the case explicitly.
Submission

At the end of the practical assignment, a report (i.e., up to four pages + one page appendix in IEEE conference format) has to be delivered. At the end of the report, you have to include an “Authors’ Contributions” section, and explain how did
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
you divide the work among the members, and what are the contributions of each author. We expect all authors contribute equally to the assignment. This assignment prepares students to do the final course project. Submit your assignment in as a pdf file named group_number_prj2.pdf

U Do not delete your results after submitting the report. We may ask you to send us your cognitive_robotics_manipulation packages and the obtained results.

References

<ol>
<li>[1] &nbsp;Sulabh Kumra, Shirin Joshi, and Ferat Sahin. Antipodal robotic grasping using generative residual convolutional neural network. In 2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), pages 9626–9633, 2020.</li>
<li>[2] &nbsp;Berk Calli, Aaron Walsman, Arjun Singh, Siddhartha Srinivasa, Pieter Abbeel, and Aaron M Dollar. Benchmarking in manipulation research: The YCB object and model set and benchmarking protocols. IEEE Robotics and Automation Magazine, 2015.</li>
<li>[3] &nbsp;Michel Breyer, Jen Jen Chung, Lionel Ott, Siegwart Roland, and Nieto Juan. Volumetric grasping network: Real-time 6DOF grasp detection in clutter. In Conference on Robot Learning, 2020.</li>
<li>[4] &nbsp;Adithyavairavan Murali, Arsalan Mousavian, Clemens Eppner, Chris Paxton, and Dieter Fox. 6DoF grasping for target-driven object manipulation in clutter. In 2020 IEEE International Conference on Robotics and Automation (ICRA), pages 6232–6238. IEEE, 2020.</li>
</ol>
[5] Peiyuan Ni, Wenguang Zhang, Xiaoxiao Zhu, and Qixin Cao. PointNet++ grasping: Learning an end-to-end spatial grasp generation algorithm from sparse point clouds. In 2020 IEEE International Conference on Robotics and Automation (ICRA), pages 3619–3625. IEEE, 2020.

<ol start="6">
<li>[6] &nbsp;Jeffrey Mahler, Jacky Liang, Sherdil Niyaz, Michael Laskey, Richard Doan, Xinyu Liu, Juan Aparicio Ojea, and Ken Goldberg. Dex-net 2.0: Deep learning to plan robust grasps with synthetic point clouds and analytic grasp metrics. arXiv preprint arXiv:1703.09312, 2017.</li>
<li>[7] &nbsp;Douglas Morrison, Peter Corke, and Jürgen Leitner. Closing the Loop for Robotic Grasping: A Real-time, Generative Grasp Synthesis Approach. In Proc. of Robotics: Science and Systems (RSS), 2018.</li>
<li>[8] &nbsp;Marcus Gualtieri, Andreas Ten Pas, Kate Saenko, and Robert Platt. High precision grasp pose detection in dense clutter. In 2016 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), pages 598–605. IEEE, 2016.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
