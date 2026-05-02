---
layout: project
title: Nutcracker Design
description: Advanced CAD project
image: /assets/images/NutCracker_Diagrams.jpg
---

Objective: Create a nutcracker for macadamia nuts that is easily usable by the majority of individuals.


Constraints and Input Parameters: It takes 222.18 kg of strength to crack a macadamia nut; average grip strength for a woman is 30kg. This design may also use an actuator instead of a hand.


Approach: The first step was to design a nutcracker for a person to use, and then update the design with an actuator if needed. 


For design (1), taking the moments about point A to calculate the ratio b:a (ratio of distance from A to applied force : distance from A to center of nut) yields a value of 7.4. For every inch the nut is from A, the applied force must be 7.4 inches away from A. This is not ideal, and so design (2) incorporates an actuator to make the nut cracking process easier and more accessible. The linear motor actuator is a great choice for the design of the nut cracker because it has a max force of 90kg. Recalculating the moment gives a b:a ratio of 2.4, which is more optimal than 7.4.



Discussion: This nutcracker would fulfill the purpose of its design: to crush a nutcracker. However, many people, in fact most people, do not crush macadamia nuts often. An actuator is very expensive (the one featured in this problem is $137.99), and the use of this item compared to its price does not justify its purchase. 

PART 2:

a)The nutcracker can be modeled as a beam with a pin at L=0, another one at L = nut and a force at L. To simplify this even more, we can look at the nut as a fixed wall and a beam coming out of it witha force at the end. 

Through logic, the maximum deflection should be at L, because this is the part that is moving the most. It is a free end with a force pushing down, so it will move the most. Max deflection will be -ML^2/2EI. 

b) If we choose the material to be stainless steel, a popular material for kitchen utensils, E = 190 GPa. The maximum deflection is 2% of the length of the arm. Assuming the length is 2.4 inches, the max deflection is 0.001218 meters. We plug this into the Max deflection equation, and we get that I can be a minimum of 1.68 * 10 ^ -4. This gives many options, as nearly every cross section beam there is in the textbook is greater than this. We can then pick W920 x 449 with a Ixx of 3250 m^4. 



