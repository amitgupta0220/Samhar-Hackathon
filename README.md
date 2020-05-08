# Samhar-Hackathon

#### Problem Faced

In order to ensure the safety of a region, it is necessary that troublemakers are monitored and each action must come into notice by the officers. Also, it is necessary to maintain social distancing and it is not possible for every store owners and police officers to continuously keep a track onto this. During this pandemic, it has been made compulsory to wear a mask whenever a person gets out of his/her house, but it has been seen that a lot of them do not obey this rule. Hence it is mandatory to keep a track of it for the safety of every citizen during the lockdown. To resolve this problem we are seeking to create a model which will detect and notify the concerned store owner or police officer of that locality and the necessary actions can be taken accordingly.

#### Proposed Idea

You can see a small video of our proposed idea [here](https://youtu.be/1urNc679zwY)

#### Proposed Solution

Looking into the problem statement, it comes into mind that there must be something done with the surveillance. So to monitor these activities, we have a smart solution in which we would deploy our model in the pre-existing CCTV cameras to keep a track of the different activities and to ensure that the lockdown rules are being followed like social distancing, wearing masks outside, keeping a track of the count of people in a place,  etc. 

Our model will be running on a server where the feed of all the CCTVs of a particular region is present. We have trained the model with the dataset to detect abnormal activities amongst individuals. It can also detect when a person sneezes or whether the mask is present on a person or not to alleviate the spread of Covid-19. The model will generate a confidence value depending on what it sees in the live CCTV feed. If the confidence value exceeds the set threshold, it will trigger an action in our model which will allow it to capture the frame along with the location and notify the nearby police officer via an application.



## Authors

* **Aashish Jethwa** - [PsychicA](https://github.com/PsychicA)
* **Amit Gupta** - [amitgupta0220](https://github.com/amitgupta0220)
* **Pawan Pujari** - [TeaViris](https://github.com/TeaViris)
