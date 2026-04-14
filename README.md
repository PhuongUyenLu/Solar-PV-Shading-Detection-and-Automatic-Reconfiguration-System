# Solar-PV-Shading-Detection-and-Automatic-Reconfiguration-System
This project develops a hardware-based system to detect partial and full shading in solar PV arrays using current sensors and a microcontroller. Relay-based bypass switching automatically reconfigures the system to reduce power loss and improve efficiency under varying shading conditions.

## System Architecture (Baseline Design - 5 MW solar farm)
<img src="images/solar_baseline_5MW.png" width="700">

*Figure: 5 MW solar PV baseline system developed in Visio based on industry references.*

The baseline solar PV system architecture was developed using Microsoft Visio based on component research and references from real-world solar farm designs. The diagram represents a multi-array photovoltaic system integrated with combiner boxes, a DC bus bar, and grid-connected inverters.

Each PV array consists of multiple series-connected panels forming strings. These strings are combined through combiner boxes, which provide protection and aggregate current from multiple inputs. The combined DC output is then delivered to a centralized DC bus bar.

The DC bus bar serves as the main distribution point, collecting power from multiple PV arrays and supplying it to the inverter stage. The inverter converts DC power into AC power suitable for grid connection or load usage.

This baseline design reflects standard industry practices in large-scale PV systems and was used as a reference for implementing the shading detection and reconfiguration system in this project.

This architecture also provides the foundation for implementing intelligent control strategies, such as shading detection and dynamic reconfiguration, at the string or module level.

This solar PV baseline design primarily focuses on the DC side of the system, including PV arrays, combiner boxes, and the DC bus bar. The inverter stage converts the DC power into AC power. After conversion, a transformer steps up the voltage to a higher level suitable for transmission, allowing the generated power to be integrated into the grid.
