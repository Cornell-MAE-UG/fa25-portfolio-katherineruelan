---
layout: project
title: Mechatronics Robot Competition
description: Mechatronics Robot Competition
technologies: [C Programming, Arduino UNO]
image: /assets/images/andre-open.jpeg
---


<h2>My Contributions:<h2>

For this project, I focused heavily on ciruit design and implementation. I was responsible for wiring the robot and assuring the safety and functionality of the electronic components. Additionally, I assisted with writing code that would enable our robot to move about the competition board--and do so without surpassing the borders. I also assisted with the mechanical construction of the robot from mounting sensors, to securing the battery packs, and contructing the expandable arms. 


<h3>Robot Demonstration</h3>

<video width="700" controls>
  <source src="{{ site.baseurl }}/assets/videos/andre-match-rivalry.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>



<h3>Full Report Below:<h3>

<h2>Robot Design and Strategy Overview<h2>

The robot is designed with two arms that lower at the start of the competition to create a basket-like alcove to catch the cubes. This was accomplished with two hinges mounted to the chassis of the robot that are able to drop down at the start using a makeshift hook and latch mechanism and a servo. The hinges expand the robot to the full width of the 12-inch circumference allowed for full robot expansion to maximize area to catch cubes as it moves around the board. During the competition, the robot uses two QTI sensors mounted on the forward end to sense the black borders of the playing field to navigate within the borders. 
The strategy is to have the robot perform loops around the middle of the playing field to collect cubes in the highest concentration area. We anticipate that many robots will start moving towards the center at the start of the competition, so we plan on starting from the sides of the field. 

<h2>Design Process Reflection<h2>

Our focus of design was mostly on the actual mechanism that would be collecting the cubes during competition. Because of this, we did not very intentionally think about where necessary things for robot functioning should be mounted. For the beginning milestones, we worked with the larger breadboard from the kit precariously placed on top of the smaller one mounted on the arduino board. At some point before all of the sensors were connected in the circuit, it seemed like maybe we could just use the smaller one, so we had switched all our wiring, and then ended up needing to switch it back again at some point and just decided to take the smaller breadboard off where it was mounted and put the larger one in its place. Similar things happened with battery placement, and in the end we just ended up using electrical tape to secure our 9V battery to the top of our robot. In hindsight, putting more intentional thought into where the necessary components for robot functioning would be placed would have been helpful. 
One problem we encountered was that one of our micro servos was not working properly, and we had to make a change to the physical design of the robot to accommodate the use of only one micro servo. This physical change did not affect the overall performance since we planned ahead with our laser cut piece to allow several possible positions of the servo to be mounted. It did change the way we used the servo to release our arms, which due to the makeshift nature of the hook and latch release, was inconsistent at many points. Luckily, we had gotten the hang of how to secure it just right by competition day. 

<h2>Competition Analysis<h2>

On competition day the robot had mixed results for several reasons. During a few of the matches our robot successfully retrieved a number of blocks that would have won the match, however our robot was either pushed off the board or had our blocks taken by the other robot. We did not anticipate that the other robot would have enough mass to push our robot across the board as we had deliberately added more weight to prevent this occurrence. Specifically, this mostly caused us to lose blocks in the situation of being pushed backward from a head-on position of the other robot. We had talked briefly about a plan to create some sort of gate mechanism during the build process to help keep the blocks in the alcove we had built to collect them, but because the other aspects of our build took longer than initially expected, this was not something we had time to complete. 
The other issues we had were around false starts that would cause our robot to not execute our code properly, and remain stationary. There were several reasons including a loose wire, and our battery dropping voltage faster than we anticipated. The competition presented a challenge of long term endurance for the battery that we had not encountered during lab testing. 

<h2>Conclusions<h2>

If keeping completely with our initial design idea, the number one improvement that we should have focused on was creating a way for the blocks to be retained by our robot, as this was the number one thing that voided all of our hard work come competition day. Another thing that could have improved our robot performance was spending more time adjusting the code. Specifically, the angles of turning. This was not refined completely just due to a time crunch in the end. Also, when testing our robot, we never let it run for the full length of the match, which we should have done, because our robot did stop after about 40 seconds and we still had more time where we could have been moving around collecting blocks or moving so we were not a sitting duck for other groups robots to hit us head on. One thing that would make the mechanical design of this project easier is if we did not utilize the lower mechanical arms design that we had planned. If we were to have focused on making a rigid laser cut design in the shape of an 8”x8” box, then we could cut down on the code, power, and moving parts complexity. 
Even considering this, we did have some aspects that were very successful, specifically our QTI sensors. There was a moment of worry after the first set of matches happened and many robots ran off the board. We never tested our robot under the lighting conditions in Duffield atrium, but we had ours mounted low enough that they held strong and guided our robot to remain on the board for all the matches (unless pushed off by another robot). 
Recommendations for future groups would definitely be to add a decent amount of weight to your robot to avoid it being pushed around. Additionally, prioritizing not just cube collection, but cube retention in your design, and to account for necessary components like the breadboard and batteries in your design.





