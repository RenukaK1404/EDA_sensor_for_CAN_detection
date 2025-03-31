# EDA_sensor_for_CAN_detection
# Real-Time EDA Signal Processing System for Early Detection of Cardiovascular Autonomic Neuropathy
Measures and monitors the skin conductance of a person and plots an EDA signal graph, which can be interpreted for early detection of CAN in at-risk population

## Overview  
This project presents a real-time Electrodermal Activity (EDA) signal processing system for early detection of **Cardiovascular Autonomic Neuropathy (CAN)**. By measuring **skin conductance levels (SCL)**, the system assesses **autonomic nervous system (ANS) activity**, which is closely linked to cardiovascular health. The system is built using an **Arduino microcontroller**, an **operational amplifier (Op-Amp)**, and other basic electronic components, making it a **cost-effective** and **non-invasive** diagnostic tool.

## Features  
- **Real-time EDA measurement** using skin conductance sensors.  
- **Signal amplification** using an Op-Amp (LM358).  
- **Data visualization** through a real-time graph on a serial plotter.  
- **Automated classification** of normal and abnormal conductance levels.  
- **Low-cost, non-invasive, and easy-to-use design** for early cardiovascular disease detection.  

## System Architecture  
### Hardware Components  
- **Arduino Uno (ATMega328P)** – Microcontroller for signal processing.  
- **Operational Amplifier (LM358)** – Amplifies weak EDA signals.  
- **Resistors & Capacitors** – For signal conditioning and stability.  
- **Skin Electrodes** – To capture skin conductance levels.  
![prototype](https://github.com/user-attachments/assets/6b727e87-1623-4a6b-8041-40c8afbc63f5)

### Software Implementation  
- **Arduino IDE** – Used for coding and signal processing.  
- **Serial Plotter** – Visualizes the real-time EDA signal graph.  
- **Conductance Thresholding** – Values below **75 µS** indicate normal autonomic function.
- ![graph copy](https://github.com/user-attachments/assets/7fb55678-765c-461a-a85a-9c577eb2a4ef)


## Working Principle  
1. Electrodes measure **skin conductance** variations due to autonomic nervous system activity.  
2. A **small electrical current** is passed through the skin, and changes in conductivity are detected.  
3. The **Op-Amp amplifies** the signal, which is then **processed by Arduino**.  
4. The **processed data** is plotted in real-time for visual analysis.  
5. The system detects anomalies that could indicate **Cardiovascular Autonomic Neuropathy (CAN)**.  

## Performance Evaluation  
- The system effectively detects **autonomic nervous system activity**.  
- Normal skin conductance levels are below **75 µS**.
- ![image](https://github.com/user-attachments/assets/1ee0fc60-5ab7-4f6e-8c1d-5d29b69abd65)
 - Sudden spikes or drops in conductance may indicate **early signs of CAN or other cardiovascular issues**.  

## Future Enhancements  
- **Integration with wireless data transmission** for remote health monitoring.  
- **Machine learning models** for improved CAN risk prediction.  
- **Miniaturization of hardware** for wearable applications.  

## How to Use  
1. **Connect the circuit** as per the schematic.  
2. **Upload the provided code** to Arduino using **Arduino IDE**.  
3. **Run the serial plotter** to visualize real-time data.  
4. Observe **skin conductance trends** for potential abnormalities.  

