# SEQUENCE LEARNING 
# Motorcyclist Safety System with AI 

This project has been developed to put an approach to avoid deadly motorcycle accidents. Everyday, due to the motor accidents, thousands of people die or get disabled. 
These accidents are happening both from the carelessness of the bikers and the carelessness of the drivers. 

Although, We all know that motorcyclists are much more open to getting an impact from an accident, companies still dont put the enough afford to decrease the numbers.   
# We hope to give companies a good starting point

# My Setup:
* Nvidia Gtx1070ti
* 4x8gb 3000Mhz memory
* Sata ssd
* i7 8700k

# Collecting Training DATA
* Carla(0.9.9.4) has been used to get training and test scenarios. Generated model wiil be tested on real life records.
  - To increase the randomness of scenarios, vehicles(except motorcycle) and weather were changed randomly. Of course dark and foggy sky scenarios haven't used.  
  - Image size has determined as 240x240 and field of view as 90 degree. The reason of the image size is obviously to increase the amount of scenarios that can be computed on ram at once. Optimization will always enhance your model from a couple of aspects(e.g faster array computation that would have been restricted by virtual ram). 
  - Of course this is a project of sequnce learning, so the length of the scenarios is chosen 8 which is also the batch size.
  
