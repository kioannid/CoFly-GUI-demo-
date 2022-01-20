# CoFly-GUI-demo

<p align="center">
<img src="https://user-images.githubusercontent.com/77329407/105342573-3040e900-5be9-11eb-92df-7c09392b1e0c.png" width="300" />

## Description
  
```CoFly-GUI``` is a novel, low-cost, user-friendly Precision Agriculture platform that attempts to alleviate the drawbacks of limited battery life by carefully designing missions tailored to each field's specific, time-changing characteristics. The proposed platform aims at providing the operator/farmer with a cost-effective and end-to-end integrated system that is able to accomplish autonomous tasks that were used to completed manually (e.g. crop growth monitoring). Besides, it will play a supportive role in decision-making objectives (e.g. possible weed infestations) enhancing crop yield management decisions by assisting non-expert users in proper manipulations. 
  
The main objective of the CoFly is to insert pioneering functionalities in a MAV system aiming at reducing the operational cost as well as provide intelligent modules assisting non-expert users in proper manipulation. In specific, the proposed system is capable of:
  
* UAV built-in flight planning for automated crop monitoring _([Waypoint-Trajectory-Planning](https://github.com/CoFly-Project/Waypoint-Trajectory-Planning) module)_
* Integrated image processing functionalities for orthomosaic extraction and vegetation health estimation _([Vegetation-Indices](https://github.com/CoFly-Project/Vegetation-Indices) module)_
* Automatically extracts possible problematic areas of the field _([Problematic-Areas-Detection](https://github.com/CoFly-Project/Problematic-Areas-Detection) module)_ and subsequently designs a follow-up UAV mission to acquire extra information on these regions
* UAV built-in site-specific mission based on the extracted knowledge and combined with incorporated deep learning model _([Weed-Detection](https://github.com/CoFly-Project/Weed-Detection) module)_ trained on the _[CoFly-WeedDB](https://github.com/CoFly-Project/CoFly-WeedDB)_ dataset for weed detection
* Timeline view for storing information according to the year's harvest

All the above functionalities are enclosed into an open-source, end-to-end platform, named Cognitional Operations of micro Flying vehicles (CoFly). The effectiveness of the proposed system was tested and validated with extensive experimentation in agricultural fields with cotton in Larissa, Greece during two different crop sessions. In Figure 1, we present the architecture of CoFly.
  
  <p align="center">
<img src="https://user-images.githubusercontent.com/80779522/150432702-1fdcdfb5-0525-491f-9708-4feec9532bfe.png" width="900" />
<figcaption align = "center"><p align="center">
  Figure 1. CoFly’s high-level architecture.</figcaption>
</figure>
  
## Installation
  
1. Clone this repo
2. Download & install [Node.js](https://nodejs.org/en/download/)
3. Open terminal on ~REPO_PATH
4. Install all necessary dependecies
```
npm install
```
5. Run CoFly-GUI
```
npm start
```

## Usage

The developed platform has several operations in order to examine the field of interest.  
![alt text](https://github.com/CoFly-Project/cofly-gui/blob/master/readme_images/main_screen.gif?raw=true?raw=true)

Set your scanning 
