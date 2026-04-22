> IoT platform for remote hardware control with a web-based backend, real-time communication, and a command transpiler.

##  Demo

Real demonstration of the system in operation. It shows the execution of commands sent from the web interface to the rover.

https://youtube.com/shorts/yoT20DtxeRs

---

##  Description

This project is an IoT platform that integrates a web application with physical hardware to enable real-time remote control of a rover.

The system allows commands to be sent from a web interface developed with Django. These commands are processed by the backend and transmitted via HTTP requests to an ESP8266 microcontroller, which is responsible for executing the rover’s movements.

The solution demonstrates a complete integration between backend development, networking, communication protocols, and embedded hardware, simulating a real-world IoT and remote control environment.

This project stands out for its practical approach to connecting software with physical devices, addressing real challenges such as communication, latency, and real-time control.

---

##  Project Screenshots

###  Main Control Panel
<p align="center">
  <img src="assets/panel.png" width="600"/>
</p>
<p align="center">
Main interface used to control the rover in real time.
</p>

---

###  HTTP Communication Testing
<p align="center">
  <img src="assets/test.png" width="600"/>
</p>
<p align="center">
Testing area used to validate communication between the web system and the hardware.
</p>

---

###  Movement Simulation
<p align="center">
  <img src="assets/simulacion.png" width="600"/>
</p>
<p align="center">
Simulation of the rover's behavior to verify command execution before real deployment.
</p>

---

##  Technologies Used

- Python / Django (Backend)
- HTML, CSS, JavaScript (Frontend)
- ESP8266 (Embedded hardware)
- ngrok (HTTP tunneling for remote access)
- MySQL / SQL Server (Databases)
- Real-time HTTP communication

---

##  Project Impact

- Real integration between software and hardware
- Automation of movements through programmable logic
- Simulation of IoT systems applicable to industry and robotics
- Solving challenges related to remote communication and real-time control
