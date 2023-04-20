<!-- This is the markdown template for the final project of the Building AI course project, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# SmartLights

Final project for the Building AI course project

## Summary

Smart traffic lights that use AI to analyze traffic and prioritize which lights should show red or green to maximize traffic flow and create fewer queues.

## Background

* Too much traffic
* Emergency services not getting through
* No priority
* Having to wait forever

## Deep Description

Two types of traffic signal control are used today. Time-fixed steering and vehicle-activated steering. With time-fixed control, the lights are controlled by a timer that determines when different lights should change to green or red respectively. When vehicle steering is activated, the traffic lights detect when vehicles are approaching and then change to green for that roadway if no other roadway has vehicles driving. The vehicle's activated steering, however, acts as time-fixed steering in case of large queues, etc. These controls lead to queues forming and cars sometimes having to wait longer than they actually had to. This is where intelligent control comes in.

With intelligent traffic signals, AI can learn which lanes should be prioritized in order to have the best traffic flow possible with as few queues as possible.

The traffic signals must be able to learn which roadways should be prioritized by analyzing the traffic and seeing which roadway needs to be prioritized. For example, there may be an intersection where there are 4 cars on one road but only 2 on the crossing. Then the one with 4 cars should be prioritized and thus get green. However, AI must learn to make exceptions under different conditions. For example, a roadway should not have to wait too long. This must be done by the AI seeing which lane has been waiting the longest and if it considers that one road lane has been waiting too long, then this must be prioritized.

AI must learn to recognize blue lights and then give green to blue light vehicles that have an emergency. It must then communicate over a network and give traffic signals further ahead a green light to speed up the traffic flow for emergency vehicles. At the same time, crossing roads must be red so as not to create any dangers for traffic.

Building AI course project
