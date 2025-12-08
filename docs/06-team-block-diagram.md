---
title: Team Block Diagram
---

# Water Detection System — Team Subsystem Overview

This page showcases the team's subsystems designed and built by each team member, which together form a complete, coordinated water detection system. Each teammate has developed a standalone subsystem using a **Microchip PIC18F57Q43 Curiosity Nano** as the microcontroller, and each subsystem is designed to perform a distinct sensing or actuation function.

The subsystems are now connected in a **hub-and-spoke configuration**, where each board interfaces directly with a central hub. This design simplifies communication and improves modularity.

Below is a diagram of the **hub-and-spoke setup**, visualizing the **connections and data flow** between the individual subsystems:

![Team Subsystem Hub-and-Spoke Diagram](images/Hub%20and%20Spoke%20TBD_update%20.drawio%20(1).png)

For the entire system, Khalid, as the hub, provides the device with the alarm system. Turning on the lights whenever it is informed that something has been detected. In turn, the three spokes all have different sensors that send data to the hub. Julian's spoke is a pressure system built into a water pipeline to check that the water is at the right level. Cristopher measures the humidity and temperature of the area where the device is placed. Lastly, Elisabeth's detector detects the presence of water. If any sensor gives a value that is too high, the signal is then sent to Khalid, and the alarm goes off.

> **Note:** You can [download the Hub-and-Spoke diagram as a PNG](images/Hub%20and%20Spoke%20TBD_update%20.drawio%20(1).png)

> **Reminder:** Every subsystem has a different function, and all team contributions come together to form the complete system.




