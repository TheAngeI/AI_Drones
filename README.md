# Firefighting AI drones

Final project for the Building AI course

## Summary

The idea is to have AI powered drones assist firefighters during emergencies. By equipping the drones with thermal imaging, the drones should navigate fire zones, detect heat sources, spot potential hazards(gas leaks etc.), follow and predict fire spread. The goal is to help firefighters during crucial high stress situations.


## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

* I am currently studying to become a fire engineer and I am very interested in how AI can help in my field. I also want to examine how/if we can advance the current technology used.
* Providing the firefighters with real-time data is critical in dynamic fire situation where the conditions change rapidly.
* 

## How is it used?

The firefighters would use this when there is a big fire, or if the vision is limited, if there is a fire in a tall building, if its a wildfire that is quickly spreading. By getting additional information on the evolution of the fire the firefighters will be able to make a more informed decision. 




## Data sources and AI methods
* Thermal imaging data: being able to collect and analyze data through smoke.
* Using current weather data and applying it to how the current fire situation is developing.

* To have the drones fly in an effective and optimal path we would be using reinforcement learning to guide drones through the complex environments and avoid crashing.
* To have the drones be able to detect/recognize what is happening we would have the AI trained to recognize heat signatures of victims/fire sources/gas leaks/etc.
     * Additionally it would perhaps be possible to train the AI to recognize most likely hiding spots where victims are trying to survive.
* To have the drones be able to predict the fire development we would be using the wind speed/humidity/geography(is the fire in the woods/beach/hills/etc).
## Challenges

* One challenge could be battery life of the drone. The situations where the drones would be useful would also be situations where the fire responses lasts several hours and could provide a issue with the battery time of the drones. However if they could work with either the drone simply being a drone that collects data and all the calculations are done in homebase, this way you could swap two drones in and out without them starting from zero.
* Depending on weather conditions/environment it could be difficult to use a drone. If there is heavy winds/rain/etc. or if there is a situation in a dense urban area.
* However the biggest challenge would probably be training AI on fire detection/prediction.  

## What next?

Maybe you could develop some kind of AR glasses that the firefighters would wear that would provide real time mapping. However I havent thought about that one as much.


## Acknowledgments

