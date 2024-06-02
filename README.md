# solar-panel-system
Solar panel that orients towards the sun.

In this project, we aim to design a control system that automatically adjusts the position of a solar panel according to the sun's position. The system charges a battery with the energy harvested from sunlight, thereby conserving electricity. This creates an efficient battery management system.

A simple web interface for battery management control is implemented using the STM32. The ESP32 module is used for this purpose. Battery percentages can be viewed via the IP address displayed through the serial port, using the specified username and WiFi password.


<h3> Used materials </h3>
<img src="https://github.com/dilarabukerr/solar-panel-project/blob/main/kullan%C4%B1lan_malzemeler.png" alt="Kullanılan malzemeler" width="600" height="400">

<h3> Circuit Diagram Drawing </h3>
<img src="https://github.com/dilarabukerr/solar-panel-project/blob/main/devre_semas%C4%B1.png" alt="devre şeması çizimi" width="900" height="500">

<h3> Result </h3>
<img src="https://github.com/dilarabukerr/solar-panel-project/blob/main/devre2.png">

In this system, two LDR sensors on the solar panel measure light levels. The servo motor turns the panel towards the side with higher light intensity. The solar panel harnesses energy from sunlight and charges a battery through a BMS circuit. The ESP32 module measures the remaining battery energy and displays it to the user via a specified IP address.


<img src="https://github.com/dilarabukerr/solar-panel-project/blob/main/server.png" alt="server">


