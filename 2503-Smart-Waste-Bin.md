Smart Waste Bin 

Engineered an advanced robotic waste collection system integrating intelligent navigation, path planning, and real-time trash classification to enable next-generation smart recycling.

00:28, 00:48 - By integrating multiple sensors and Raspberry Pi controllers, the capacity, location and movement status of the trash cans can be monitored in real time, and historical data can be combined for predictive maintenance and scheduling optimization.
00:55 - Integrate global/local path algorithms (such as A*, Dijkstra and dynamic obstacle avoidance) and SLAM (simultaneous localization and mapping) technology to achieve spatial perception, autonomy, self-positioning and intelligent obstacle avoidance, and efficient mobile route planning.
03:10 - Using machine vision and deep learning models, it can automatically identify various types of garbage such as plastic, metal, paper, etc., achieve accurate classification, and greatly improve sorting accuracy.

---以下可省略---

In large workspaces, trash bins often need to be manually moved and checked, which is pretty inefficient.  
I took on the job of designing an autonomous smart bin that could navigate on its own and report its status in real time.  
I built the system with a TurtleBot3 robot using ROS and SLAM for navigation and path planning. Then, I added a Raspberry Pi 4 and various sensors for real-time trash level monitoring, plus a centralized visualization dashboard.  
The result: the bin now patrols itself and its status can be checked remotely—much smarter and easier for facility management.
