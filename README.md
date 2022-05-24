# PumpNSuck
A programmatic, app driven vacuum pump with solenoids and pressure sensors to provide great oral sim and precise pump control. Slowly ramp to pressure to reduce bruising, maintain pressure for times. I'm working on a data collection engine so you can see progress over time. 


<img src="https://github.com/MikesMachines/PumpNSuck/blob/main/media/PumpOnWoodTopTextRotate.jpg" alt="Pump on Wood" height="400">
<p>

# Interface
  
The contol box for all my machines has the same basic design. It leverages Blync, which allows anyone to create an app interface with no code, just drag and drop widgets and select what to hook them to. The code runs on a local ESP32 that has 4 channels, each 400w / 15A for regular loads like brushed motors / pumps. The first channel can be either brushed DC motor or stepper, selectable in the interface. 
  
  <p>
<img src="https://github.com/MikesMachines/PumpNSuck/blob/main/media/Pumpscreen.jpg" alt="Pump App screen shot" height="600">
