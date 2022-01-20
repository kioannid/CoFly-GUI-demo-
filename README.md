# CoFly-GUI-demo

<p align="center">
<img src="https://user-images.githubusercontent.com/77329407/105342573-3040e900-5be9-11eb-92df-7c09392b1e0c.png" width="300" />

## Description
CoFly-GUI is a novel, low-cost, user-friendly Precision Agriculture platform that attempts to alleviate the drawbacks of limited battery life by carefully designing missions tailored to each field's specific, time-changing characteristics. The main objective of the CoFly is to insert pioneering functionalities in a MAV system aiming at reducing the operational cost as well as provide intelligent modules assisting non-expert users in proper manipulation. In specifoc, the proposed system is capable of:
  
* Designing coverage missions for any type of UAVs, integrating field characteristics inside the resulting trajectory ([Waypoint-Trajectory-Planning module](https://github.com/CoFly-Project/Waypoint-Trajectory-Planning))
* The collected images are automatically processed to create detailed orthomosaics of the field and extract the corresponding vegetation indices ([Vegetation-Indices]() module).
* Automatically extracts possible problematic areas of the field (([Problematic-Areas-Detection](https://github.com/CoFly-Project/Problematic-Areas-Detection) module)) and subsequently designs a follow-up UAV mission to acquire extra information on these regions
* The toolchain is completed by employing a specifically designed deep learning module ([Weed-Detection](https://github.com/CoFly-Project/Weed-Detection)) trained on the [CoFly-WeedDB](https://github.com/CoFly-Project/CoFly-WeedDB) dataset to detect weeds in the close-examination flight based on . 

All the above functionalities are enclosed into an open-source, end-to-end platform, named Cognitional Operations of micro Flying vehicles (CoFly). The effectiveness of the proposed system was tested and validated with extensive experimentation in agricultural fields with cotton in Larissa, Greece during two different crop sessions.
  
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

The developed platform has several operations in order to examine the field of interest. The below 
![alt text](https://github.com/CoFly-Project/cofly-gui/blob/master/readme_images/main_screen.gif?raw=true?raw=true)

Set your scanning 
