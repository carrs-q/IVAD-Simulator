
# CARRS-Q ADS Driving Simulator

![Main Menue](... "CARRSQ ADS Driving Simulator")

This Software is written at CARRS-Q to run research studies for autonomous driving vehicles, 
with focus on AES Level 3. 

---


### Questions regarding the research to:
**Dr. Ronald Schroeter | QUT**    
r.schroeter@qut.edu.au  
**Michael A. Gerber | QUT**  
michaelandreas.gerber@hdr.qut.edu.au  

### Technical questions to
gerberm@qut.edu.au  

---

### Publications
Gerber, M. A., Schroeter, R., & Vehns, J. (2019). A Video-Based Automated Driving Simulator for Automotive UI Prototyping, UX and Behaviour Research. _In Proceedings of the 11th International Conference on Automotive User Interfaces and Interactive Vehicular Applications_. Presented at the International Conference on Automotive User Interfaces and Interactive Vehicular Applications, Utrecht, Netherlands. https://doi.org/10.1145/3342197.3344533

Schroeter, R., & Gerber, M. A. (2018). A Low-Cost VR-Based Automated Driving Simulator for Rapid Automotive UI Prototyping. _Adjunct Proceedings of the 10th International Conference on Automotive User Interfaces and Interactive Vehicular Applications_, 248–251. https://doi.org/10.1145/3239092.3267418

---
### Requirements
* Nvidia GTX1080 or better
* SSD or NVMe (~ 10GB per scenario, if local 20GB )
* 8GB RAM
* Windows 10
* VR-Mode requires Oculus Rift
* HDMI Video Capture Card - (HDMI to USB3)

### Setup
1. Compile with Unity 2017
2. Install NPM and NodeJS
3. Run CDN (If not installed, install dependencies with ```npm install```)
4. Check config-file for Simulator in ```/ADS Simulator_Data/StreamingAssets/node-config.xml```
5. Run ADS Simulator
6. Choose Simulator-Type (top left)

### Config File (possible values)
If the config files contains  
node type: **master | slave** (Cluster Master, VR | Cluster Slave)  
node screen: **1 - 5** rendered Camera   
node debug: **0 | 1** (OFF|ON) for Cluster  
server ip: **IP.v4** (IP of Cluster Master)  
server port: **PORTNR** (Port of Cluster Master)  
cdn address: **HTTP ADDRESS of CDN** (with Port)  
hdmi video: **Name of Video Capture device** (Hardware name)  
hdmi audio: **Name of Audio Capture device** (Hardware name)  

---
### Licence
Apache 2.0
