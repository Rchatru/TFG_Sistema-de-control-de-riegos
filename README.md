# TFG - Sistema de Control de Riegos Gestionado Telemáticamente

This repository contains the code and other information used in the development of the Undergraduate Thesis Project in Industrial Electronics and Automation Engineering, called: [*Telematically Managed Irrigation Control System*](http://riull.ull.es/xmlui/handle/915/2928).

The objective of the project has focused on the design and implementation of a telematically managed irrigation system.

A central station, which we will call Master, allows wireless control of several sub-stations, which we will call Slaves, distributed throughout the terrain. The user enters, via a screen and keyboard included in the hardware, the characteristics of the field: type of plant, crop surface and irrigation flow rate.

The Slaves have their own power supply system. In addition, thanks to the sensors that each Slave terminal has, it will be possible to obtain information on environmental variables and transmit them to the Master, which will be able to adapt the programming to the changing conditions of the environment. In addition, a parameter called evapotranspiration will be calculated, from which a good approximation of the real water needs of the crop can be obtained.

All the data received by the Master will be sent to an external server so that it will be possible to access and control the system remotely.

![](https://github.com/Rchatru/TFG_Sistema-de-control-de-riegos/blob/main/Master-Slave.png "Schematic of the system")
