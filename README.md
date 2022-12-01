# Eurobot-2023-General

This repository contains the general information about the Eurobot 2023 competition.

## Rules

Rules can be found [here](https://www.coupederobotique.fr/wp-content/uploads/Eurobot2023_Rules_EN_FINALE.pdf).

## Strategy

1. Optimize the robot for cherry picking & dropping in the basket
2. If 1 works reliably, optimize for cake "pushing"
3. If 2 works reliably, optimize for cherry on cake.
4. If 3 works reliably, optimize for cake layer order.
5. If 4 works reliably, start working on a second robot optimized for cherry picking & dropping in the basket.

## Scoring points

Ways to score points :

* Cakes (max 10/cake) :
  * must be at least partially on a plate, max 3/plate
  * 1 point each cake layer (max 3)
  * 4 additional points if 3 layers in legendary order
  * 3 additional points if cherry on a cake (max 1/cake)
* Basket (max 60 if 10 internal + 40 external cherries are used) :
  * 5 points if it exists
  * 1 additional point per cherry in basket
  * 5 points if basket count is correct and not null
* Placement (max 15) :
  * 15 points if robot ends in its own dropping area
* Disguise (max 5) :
  * 5 points if robot is disguised at the end
* Bonus :
  * 20 points max if points estimation is correct (for example, you say you'll make 35 points but you only make 30, you will win 20-(35-30) (so 15) bonus points)

## Milestones

### Milestone 1

#### **Rolling basis**

* Go straight on
* Be able to go where we want given a position
* Empty the ball

#### **Basket prototype**

* Mechanical
* Electronic
* No so much into the programming thing

#### **Analyze**

* Analyze all the mechanical part
  * How pick up the cherries ?
  * Analyze the space to store the cakes
  * ...
* Analyze the software based on ROS, cur our software into severals works to analyze how we will do in the high level

#### **ROS**

* Draw a ROS architecture
  * Bloc diagram of the high level code including ROS

### Milestone 2

#### **Basket**

* The basket is able to count the number of cherry contained inside of it

#### **Robot**

* The robot is able to pick up the cherries
* Knowing how to find your way around the set
* Push the cakes inside the plates
* Install camera + color detector

### Milestone 3

* To dress up the robot
* Sort cakes in the right order and add cherry at the top
* Focus on the software intelligence
  * Include game strategy
* Display the score
  * At start, the score will be estimated so no communication with the basket

### Milestone 4

* Verification + integration
* Testing the features
* Calculate the final score
  * Implement communication between the robot and the basket using a solid radio communication
* Prepare speech for the victory

## Competences

### Quentin

* 3D mechanical design
* Team management
* Software high level

### Alex

* Software low + high level
* Electronic

### Fred

* Electronic
* Manufacturing
* 3D mechanical design
* Software low + high level

### Théo

* Software low + high level
* Electronic
* Regulation

## Acknowledgements

Proudly made by Alejandro Borbolla, Frédéric Druppel, Théo Engels, Quentin Jadoul

Made with ❤️, lots of ☕️, and lack of 🛌  
Published under CreativeCommons BY-NC-SA 4.0

[![Creative Commons License](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)  
This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).
