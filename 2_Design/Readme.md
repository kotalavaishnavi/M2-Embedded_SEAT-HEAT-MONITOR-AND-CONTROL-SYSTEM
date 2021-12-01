# Design

![Capture 5](https://user-images.githubusercontent.com/94236183/143873770-7d49f3c0-d496-4835-8af3-ac6e97da731c.PNG)
# Structural Diagrams
![image](https://user-images.githubusercontent.com/89759853/133655306-ab257b88-8b8b-44ab-97f3-55b3f39e0ba9.png)
# Behavioural Diagrams
![Screenshot (47)](https://user-images.githubusercontent.com/94221735/144057736-a52d6e47-3ca3-482c-a830-b3e1014fcd2f.png)
# Block Diagrams

![Screenshot (45)](https://user-images.githubusercontent.com/94221735/144052026-a2a471fd-1edf-4e68-9775-a8bd643d3230.png)
# Simulations
The functionality of the heat control system is coded in embedded c and the working is demonstrated using simuation in a software called SimulIDE. Below shows two images where in the 1st image shows the status of the simulation when the system is ON and the second image shows the status of the system when it is OFF
## ON
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/94221735/144048994-df05f206-2faf-4938-8f25-c9408d269504.gif)
## OFF
![Screenshot (45)](https://user-images.githubusercontent.com/94221735/144052026-a2a471fd-1edf-4e68-9775-a8bd643d3230.png)
# Bill of Materils

## Functionality
- When the two switches are closed, the first LED glows indicating the actuation of the system and the heater.
- Next the analog input from the temperature sensor is received and digitized.
- The digitized temperature input is visualized using Pulse Width Modulation.
- The corresponding temperature values based on the digitized temperature input is transmitted by the UART protocol. Here the data is displayed on the serial monitor.

