# Semester project in "Basic control of robots"

**Technologies:** Python, Micropython

This project was developed as part of a competition at the University of Southern Denmark (SDU), where the objective was to design and build autonomous line-following robots.

![[img/bil.jpg]]

Two different versions of the robot were created, each with a specific purpose.

1. **Racing Version**  
    The first version was optimized for speed and agility. It utilized line sensors to detect and follow a pre-defined track with high precision. The control algorithm was tuned to minimize lap time while maintaining stability at high speeds. Lightweight construction and efficient motor control ensured optimal performance during the racing challenge.
    
2. **Nut Collector Version**  
    The second version was designed to navigate along the track while collecting metallic nuts placed along the route. This was achieved by integrating an electromagnet mounted on a mechanical arm. The robot followed the line using the same sensor-based navigation system as the racing version but included additional logic for detecting and activating the electromagnet at collection points. The collected nuts were securely stored until the end of the run.
    
Both versions were implemented using C++ for embedded programming and tested extensively to ensure reliability under competition conditions. The project demonstrated the ability to adapt a base robotic platform for multiple competitive tasks, combining precise navigation with specialized functionality.