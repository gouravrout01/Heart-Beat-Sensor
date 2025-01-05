# Heart-Beat-Sensor
### `README.md`

# Heartbeat Sensor Using 8051 Microcontroller  

## **Project Overview**  
This project involves designing a real-time heartbeat monitoring system using the 8051 microcontroller. The system reads the heartbeat signal via a sensor, processes it, and displays the heart rate in beats per minute (BPM) on a 7-segment LED display.

---

## **Features**  
- Real-time heart rate measurement.  
- Compact and efficient design.  
- Heart rate displayed on a 7-segment LED for clear visualization.  

---

## **Components Used**  
1. **8051 Microcontroller**: Core controller for processing and logic.  
2. **Heartbeat Sensor**: Captures the heartbeat signal (e.g., IR-based or pulse sensor).  
3. **Analog-to-Digital Converter (ADC)**: Converts the analog signal into a digital format.  
4. **7-Segment LED Display**: Displays the heart rate in BPM.  
5. **Decoder IC**: Converts digital data into a format suitable for 7-segment LED display.  
6. **Resistors and Capacitors**: For signal conditioning and circuit stability.  
7. **Power Supply**: Provides 5V DC power to the circuit.  

---

## **System Workflow**  
1. **Signal Acquisition**: The heartbeat sensor detects pulses and generates an analog signal.  
2. **Signal Conditioning**: The signal is amplified, filtered, and prepared for ADC conversion.  
3. **ADC Conversion**: The analog signal is converted to a digital signal for processing.  
4. **Microcontroller Processing**:  
   - The 8051 microcontroller calculates BPM based on the input signal.  
   - It sends the result to the 7-segment display for real-time visualization.  
5. **Display Output**: The BPM is shown on the 7-segment LED in real time.  

---

## **Software Requirements**  
- **Keil µVision IDE**: For programming the 8051 microcontroller.  
- **Proteus**: For circuit simulation and testing.  
- **Embedded C**: Programming language for the microcontroller.  

---

## **Applications**  
- Personal heart rate monitoring devices.  
- Fitness tracking systems.  
- Healthcare systems for continuous monitoring.  

---

## **Advantages**  
- Real-time and accurate BPM monitoring.  
- Simple, clear display using a 7-segment LED.  
- Low-cost and portable system design.  

---

## **Future Enhancements**  
- Add wireless connectivity (e.g., Bluetooth or Wi-Fi) for remote monitoring.  
- Integrate additional health parameters, such as oxygen saturation.  
- Implement alert systems for abnormal heart rate detection.  

---

## **How to Use**  
1. Assemble the circuit as per the schematic.  
2. Connect the heartbeat sensor and place it on your fingertip or wrist.  
3. Power the system using a 5V DC power supply.  
4. Observe the BPM displayed on the 7-segment LED in real time.  

---


## **License**  
This project is open-source and free to use for educational and non-commercial purposes.  

---

**Enjoy building and using your Heartbeat Sensor System!** 😊
