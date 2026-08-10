# Semester project in "Basic control of robots"

**Technologies:** Python, Micropython

**Demo video:** https://bit.ly/47UPwd7

This project was developed as part of a competition at the University of Southern Denmark (SDU), where the objective was to design and build autonomous line-following robots.

![[img/bil.jpg]]

In my first-semester project on robot technology, our team was tasked with developing two autonomous mobile robots to compete in a series of predefined challenges. The project focused on integrating theory, electrical design, and software development to create two functional robots, each optimized for a specific task. I was responsible for a significant part of the software development and played a key role in the design and programming of the logistics robot.

The competition included three main disciplines: "Racing," "Logistics," and "Pimp my ride". We developed two robots, codenamed "NASCAR" and "Wall-E," to tackle these challenges. The "NASCAR" robot was engineered for speed and code optimization, while "Wall-E," the logistics robot, was designed for precision and accurate movement, which required more advanced calculations and programming.

A core part of our solution was the software, which was built using a Raspberry Pi Pico microcontroller with MicroPython. This project allowed me to gain extensive experience in low-level hardware programming and optimization. A key challenge was the slower execution speed of MicroPython compared to other languages like C, which we overcame by implementing asynchronous programming (uasyncio) to handle multiple tasks efficiently. For the logistics robot, precision was paramount. The robot was equipped with an electromagnet and an extra sensor box, allowing it to detect pickup spots and lift magnetic objects with great accuracy. I focused on creating the algorithms for precise line-following to ensure the robot could navigate its environment and complete its tasks flawlessly.

The project was a success, with "Wall-E" securing a 1st place in its discipline and the team achieving a 2nd place overall. This experience honed my skills in system integration, problem-solving, and developing robust, efficient software for autonomous robotic systems.