Title:World Models of robotics 

Authors:David Ha, Jürgen Schmidhuber

Year:2018

Problem : Current reinforcement learning agents require a large number of real-world interactions to learn effective behaviors, making them inefficient and impractical for many robotic applications.

Main Idea : The authors propose learning a compact internal representation of the environment (a world model) that enables an agent to simulate future states and make decisions using imagined experiences.

Motivation : Training robots through repeated trial-and-error is costly, time-consuming, and potentially unsafe. A robot that can internally model and predict its environment could learn faster while reducing the need for physical interactions.

Results : The proposed architecture successfully learns to perform simulated control tasks while requiring significantly fewer real interactions than conventional reinforcement learning methods.

Limitations : 1) The framework does not include a mechanism for generating human-understandable explanations for its decisions.

              2) The robot is uncertain but acts anyway.
              
              3) Errors accumulate over time.

              
open research questions -1) Can we design a world model that generates human-understandable explanations before executing an action?

                         2) Can a robot estimate its own uncertainty before taking an action?
                         
                         3) Can robots continuously update their world model while operating in dynamic environments?   

                    
