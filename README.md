# GDP

Download the files (`startsitl.sh` and `takeoff-and-land.py`) in your home folder, you can either download them directly or using the following commands:  
`cd ~`  
`wget https://raw.githubusercontent.com/natpuch/gdp/main/startsitl.sh`  
`wget https://raw.githubusercontent.com/natpuch/gdp/main/takeoff-and-land.py`  

To take-off and land, launch the following commands in four different terminals:  

1. Launch the runway simulation in Gazebo  
`roslaunch iq_sim runway.launch`

2. Launch ArduCopter  
`~/startsitl.sh`

3. Launch mavros  
`roslaunch iq_sim apm.launch`

4. Launch the Python script  
`python takeoff-and-land.py`
