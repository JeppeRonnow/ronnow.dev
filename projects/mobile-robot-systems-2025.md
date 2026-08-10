# Semester project in "Mobile Robot Systems"

**Technologies:** TurtleBot3, ROS, Python, Whisper, openWakeWord, MQTT, CustomTkinter, DSP

**Demo video:** https://youtu.be/K6KTOIJV2LA

Designed and programmed a voice-controlled TurtleBot capable of hands-free
navigation, using wake-word detection, Whisper speech-to-text, and MQTT
communication.

![[img/turtlebot.png]]

In my third-semester project at the University of Southern Denmark, my team and I built a
voice-controlled mobile robot system on the TurtleBot3 platform, designed for hands-free
operation in situations like construction surveying.

My role centered on the voice control pipeline and command interpretation, together with the
graphical user interface. I worked on the flow from wake-word detection through Whisper-based
transcription to parsing the recognized text into movement commands, before handing it off to
MQTT for transmission to the robot. I also built the CustomTkinter GUI, showing the robot's live
position, command history, latest transcription, and audio waveforms. Alongside this I
contributed more broadly across the system, including the MQTT communication layer and the
robot-side safety logic using time-of-flight sensors for obstacle and ledge detection.
