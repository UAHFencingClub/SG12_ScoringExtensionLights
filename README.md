# SG12_ScoringExtensionLights

A module for the [SG12 fencing scoring machine](https://www.blue-gauntlet.com/SG12-ST-MACHINE-w-score-and-time-and-remote_p_3799.html) that allows for 12V LED strips to be used as extension lights.

You can view the mirror on [CADLAB.io](https://cadlab.io/project/27194/main/files) if you want to see the schematic. < Needs to be updated, not sure why mirroring is not working.

![Image of 3D PCB Rendering](pcb_3d_view.png)

# Wiring Diagram

Annocations and a wiring diagram can be found [here](Wiring.md)

# Parts (Haphazard)

Most things I got off amazon. I have not gotten all the connectors since not all are actually required. It depends on what you need. Look at the schematic to find out.

- IRF4905 MOSFET (Though probably most P Channel MOSFETs will do)
- Some sort of RJ45 (Ethernet) Connector (Don't get the ones with built in magnetics, those are usually a bit larger and are only for actual ethernet applications.
- Whatever 10k resistors you can find, the value really does not matter I would suggest something between 1k and 100k
- Some sort of barrel jack connector (Inner pin diameter of 2.1mm is more common than ones with 2.5mm inner pin diameter)
- PhoenixContact MSTBA 2,5 2-G-5,08 1x02 P5.08mm Horizontal
- Molex Mini-Fit Jr 5569 2x04 P4.20mm Horizontal
- Standard 2.54mm pin header

# Get PCBs

**Disclaimer: If ordering through their site, PCBWay will "donate 10% PCB and PCB assembly cost to" [me](https://github.com/QuantumEF)**

<a href="https://www.pcbway.com/project/shareproject/SG12_ScoringExtensionLights_36ba9fa8.html"><img src="https://www.pcbway.com/project/img/images/frompcbway-1220.png" alt="PCB from PCBWay" /></a>
