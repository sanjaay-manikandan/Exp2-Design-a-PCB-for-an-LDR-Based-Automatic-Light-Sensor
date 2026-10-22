# Exp2-Design-a-PCB-for-an-LDR-Based-Automatic-Light-Sensor
Aim

To design the schematic and PCB layout of an LDR-based light sensing circuit using KiCad, perform electrical and design rule checks, and generate Gerber files for PCB fabrication.

Apparatus Required

Software

KiCad (Version 10.0 )

Components

<img width="556" height="505" alt="image" src="https://github.com/user-attachments/assets/0a2c3c52-2694-481d-862d-5bfffbf72d94" />

Circuit Diagram




Procedure
```
1.Open KiCad and create a new project.
2.Draw the schematic by placing the LDR, transistor, resistors, preset, LED, and power connector.
3.Connect the components according to the circuit diagram.
4.Annotate the schematic and assign footprints to all components.
5.Perform the Electrical Rule Check (ERC) and resolve any reported errors.
6.Open the PCB Editor and import the schematic.
7.Arrange the components logically, placing the LDR near the board edge for maximum light exposure.
8.Route all tracks while maintaining proper spacing and track width.
9.Add a copper fill connected to the GND net.
10.Perform the Design Rule Check (DRC) and correct any violations.
Add silkscreen labels, reference designators, and board information.
Generate the Gerber and drill files required for PCB fabrication.
Verify the PCB layout using a Gerber viewer.
```

Schematic Output:

<img width="713" height="627" alt="image" src="https://github.com/user-attachments/assets/4109492c-19c6-4839-bb55-07c5662720b7" />

Design Rule :

<img width="1438" height="753" alt="image" src="https://github.com/user-attachments/assets/4e77273f-d681-461e-9413-8ab9697b3c02" />

3D Output :
<img width="1675" height="1012" alt="automatic_street_light_controller" src="https://github.com/user-attachments/assets/abcab593-2b9e-4dd8-8091-6b042a7644c6" />


Result

The PCB layout for the LDR-based light sensing circuit was successfully designed using KiCad. The schematic passed the Electrical Rule Check (ERC), the PCB layout passed the Design Rule Check (DRC), and the Gerber files required for PCB fabrication were successfully generated.


