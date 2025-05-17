---
title: "Plotting Reaction Wheel Envelopes"
date: 2025-05-17T20:28:19+05:30
# bookComments: false
# bookSearchExclude: false
---

Reaction wheels are momentum-storage actuators that make spacecraft [spin around](https://youtu.be/PGNiXGX2nLU?si=aB0SFMN8PToa35LQ). They're highly precise motor-driven wheels that deliver torque along one axis. To achieve 
3-axis control, you'd typically need atleast 3 of them placed orthogonally.

However, reaction wheels are also one of the most failure-prone ADCS components in a spacecraft due to the fact that they
have moving parts. This is why they add a fourth wheel and reconfigure all the 4 wheels in a tetrahedral arrangement. This
gives extra reliability through redundancy (if one wheel fails, the other three can still deliver 3-axis control), and when
all 4 wheels function normally, the extent of control improves.

I came across this [paper](https://ntrs.nasa.gov/api/citations/20110015369/downloads/20110015369.pdf) by F. L. Markley et. al. (2009) that describes the **torque/momentum envelope** of a reaction wheel array. I set out to write the code for it to 
visualize the envelopes myself and understand them better.





