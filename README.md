java c
Assignment 5 (20 Marks)
MCEN90061 Mechatronics Systems Design
Due 8 Nov 2023 5pm
This assignment is made of three independent exercises.   Each  exercise  assesses  a different stage of the design process, each on a different real-world context. You are to attempt ALL of the 3 exercises.
README:
•  There are 5 pages to this final assignment document including this cover page.
•  This assignment serves as the final assessment for this subject, covering content of the entire subject.
•  Not all exercises in this assignment are of equal marks. Read the instructions carefully.
•  Ensure that your assignment is typed (using a word processor) and not hand-written, for the legibility of the content.
• You may ask question(s) only through the Ed Discussion Board during the period of the assessment. A Discus- sion Board channel for Assignment 5 has been created.  No question should be asked over emails.  This ensures that everyone gets access to any clarification and comments we may provide.  We will answer the question if it pertains to any lack of clarity of the assignment, but not to provide any assistance in the execution of the assignment.
•  There is no explicit page limit for this assignment. However, succinct and clear is always better (more is NOT better).
•  The quality of the report (presentation and quality of the explanations) are not explicitly accounted for with explicit marks but will be accounted for in the marking of each exercise.  As such, it is highly recommended that you keep enough time to proofread your assignment, edit it as necessary and improve your explanations and the presentation.
•  This is an INDIVIDUAL assessment.  It is open-book, hence you may consult any material, BUT you are not to communicate with any other person on this assessment. This includes your peers and anyone outside the class, including any “study help websites or services” that are manned to provide answers to specific questions asked. As per the University policy, while you can use ChatGPT or other LLMs to prepare your assignment this should be clearly and explicitly acknowledged in your assignment, as any other external resource you may use/refer to.
•  Students have been instructed to familiarise themselves with what constitutes academic integrity and academic misconduct, and there will be no excuse for ignorance in this Master level subject.
Objectives
1.  To evaluate ability of individual students to apply the concept of design thinking and the knowledge of mecha- tronics systems on the structured problems below.
2.  To assess the ability of the students to manage a complex design problem and to communicate clearly and professionally in written format.


EXERCISE I - Winning is everything – Engineering requirements (7 marks)
Background informationThe famous road cycling team  is looking for an efficient way to  “boost the performance” of their team leader , currently ranked among the top 10 road cyclists.  The team is thus exploring the possibility to design a mechatronics system able to provide him with some “assistance” during one-day races (typically The ’Mon- ument’ Classics races as listed on https://en.wikipedia.org/wiki/List_of_men%27s_road_bicycle_races).  As part of this process, you have been tasked to define the Needs and Requirements of possible solutions to the following Problem Statement:How  might  we  design  a  “mechanical  assistance  system”  that  provides    with  the  best overall energy  benefit  over one-day  classic  races  without raising suspicion from  other cyclists  or the international cycling federation  (UCI)?

Figure 1: From The Varsity (Toronto, Canada) — thevarsity.ca
Your task
With the help of the above information, specifically address the following questions:
1.  Define the Needs of a system addressing the above Problem Statement  (as a guide, between 5 to  10 needs). Needs should ideally be self-explanatory but you may provide a short explanation (one sentence for each) if you believe additional information is required.  (2 marks)
2.  Derive the Engineering Requirements associated with five of these needs and justify each of them with a short paragraph and appropriate references.  (5 marks)While mechanical doping is possibly a more  ethical form. of doping  than the  more  common  chemical doping  (which can in addition cause serious health issues), it is clear that the client ethics is highly controversial and that mechanical doping is not to  be  encouraged.  Still  we  believe  this  is  an  interesting problem  to  be  investigated  and  a fun  exercise.




EXERCISE II - Wood pellet heater — Product architecture (6 marks)
Background informationWood pellet heaters are gaining popularity as heating systems due to their convenience and cost-efficiency. They are essentially a modern version of the good-old fireplace but they autonomously burning wood pellets instead of wood logs, as shown on Figure 2.
Figure   2:      A    typical    wood-pellet   heater    (left);     and   wood    pellets    sample    (right).        (Pictures    from
www.pelletexperts.com.au)More specifically, these systems are made of a combustion chamber in which a controlled quantity of wood pellets is burned continuously. Ignition (to start the burning process) is performed by an electrical heating element, and the feeding of pellets is regulated to provide the desired burning rate to regulate the room temperature.It is desired to design an autonomous wood pellet heater to heat a room to a set t代 写MCEN90061 Mechatronics Systems Design Assignment 5Matlab
代做程序编程语言emperature defined via a thermostat by the user.  The heater is to work autonomously (without human intervention) for a minimum of a full week and maintain the room at the set temperature.
Your task
You are to propose the product architecture of a household wood pellet heater.  To do so, specifically address the following questions:1.  List the functional elements of the wood pellet heater, briefly explaining them (with one or two sentence each).
(3 marks)
2.  Derive a functional diagram (including the interaction flows) of the system.  (1 mark)
3. We intend to produce a range of heaters of different sizes (and so heating capacity).  Propose a physical elements configuration for this range of products, briefly justifying your choices (1 or 2 paragraphs).  (2 marks)

EXERCISE III - Speed climbing — System design and components se-lection
(7 marks)
Background informationSport climbing has been introduced as part of the Summer Olympics in 2020.  One of the two climbing discipline is the speed climbing where two athletes compete side by side on two standard artificial 15-metre climbing walls (i.e. the wall is exactly the same, with the exact same route, the exact same holds, at the exact same place for every competition and for both athletes).  The fastest athlete to get to the top wins the race.  You can see an example during a world championship on Youtube: https://www.youtube.com/live/3OO4LPwRuOE?si=BEgLOkcfNZkeCHIit=40 .
Best athletes climb this standard wall in 4s to 8s, with the women’s world record set at 6.06s and the men’s world record at 4.74s.
For such competitions, the artificial wall is equipped with a mechatronic system which has two main roles:
• ensuring climbers safety at all time via a safety rope, automatically winding up as they climb the wall and bringing them down at the end;
•  accurately measuring the climbing time, to identify the winner and possible records.
The mechatronic system requirements, defined based on the user needs and the international federation rules and recommendations, are as follows (all are essential requirements):
Table 1: Essential Requirements of the speed climbing system
Name
Definition
Units
Min  Value
Max  Value
Etraction
Force provided by the rope at all time while climbing in normal opera- tions (no fall)
N
1
10
Efall
Do not let climber fall of more than a reasonable distance when fall is detected
m
/
0.5
Esafe
Sustain sufficient weight for a very short time when fall happen
kg
200
/
Edown
Return climber to the ground (down) at a reasonable speed
m.s −1
0.5
2
Eweight
Support operation with a climber of weight up to
kg
100
/
Etime
Measure climbing time with sufficient accuracy
ms
/
1
Efalsestart
Detect a false start if climber lift from ground before start beep: detec- tion time
ms
100
100
Epower
Can be powered by a standard socket
/
Yes
/
You have been tasked to design such system for athletes to train in similar conditions as during the competition and specifically using an active (motorised) auto-belaying system.
We assume that the system is made of two independent subsystems which only share a common power source and controller:
•  A - The auto belaying sub-system and,
•  B - The time measurement sub-system.In addition, given the difficult mechanical requirements of the auto belaying sub-system (sub-system A),we consider a sub-system made of one actuator (motor) and two different gearheads, one acting in one direction (up) and one acting in the other direction (down).  Each of these gearheads are connected to the actuator shaft (the input) and to the pulley (the output) only in one of the direction.  This is achieved by placing a sprag clutch  (each in reverse direction of the other) on the respective gearheads shafts as shown on Figure 3.
Your task
1.  Provide the necessary modelling of the system to link the system requirements and components specifications for sub-system A and find the mechatronics components required, briefly justifying your choice based on the above requirements and modelling.  (5 marks)
2.  Find the necessary components required for sub-system B, briefly justifying your choice and why they can be used to produce a functional system.  (1 mark)Figure 3: Mechanical diagram of sub-system A with a motor driving two parallel shafts, one engaging the pulley only in the up direction with sprag clutch Su and gearhead Gu and one engaging the pulley only in the downwards direction with sprag clutch Sd and gearheads Gd.
3.  Explain why the designer made the choice of designing sub-system A with two different gearheads and sprag clutches instead of a more simple mechanical design.  (1 mark)For question 1 and 2, you will pay attention to ensure the compatibility of the different components, ensuring they can be used to produce a functional system.  Expect for the gearheads, mechanical parts necessary for the final system  (e.g.   sprag clutches, pulleys, shaft, bearings...)   as well as the display/sound components  (e.g.   to display the time or warn of a false start as can be seen on the video) are out of the scope of this exercise.  For the selected components, explicitly provide links  (and datasheets/specifications screenshots).   You  can  source them from  (but are not limited to) RS Components (https://au.rs-online.com), Digikey (https://www.digikey.com.au) and/or (https://www.maxongroup.com).


         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
