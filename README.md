# Flipkart-Gridlock-Hackathon
The files present here would provide a simulation of traffic for Bengaluru's KR Puram junction using SUMO (Simulation of Urban Mobility) & OpenStreetMap.
To execute the simulation, you need to download the windows/linux version of SUMO open source software. Here I have used the windows version.
After unzipping the SUMO simulation tool, please go to the following path, sumo-win32-0.30.0\sumo-0.30.0\bin.
Run the executable, sumo-gui.exe.
There will be two .sumocfg files provided for simulation.
One is krpuram_existing_traffic.sumocfg & other is krpuram_solution_traffic.sumocfg. These two simulation files, show the simulation of current situation at the KR Puram signal and situation after optimizing some bottlenecks, like stopping the U-Turn and removing the traffic signal.
These two .sumocfg files internally refer to two .net.xml files, which are also uploaded.
These two files are krpuram_left.net.xml and krpuram_left_no_signal.net.xml.
So, to execute these two simulations, copy all these four mentioned files under a same folder/directory and execute the same using SUMO Windows 7 executable.
