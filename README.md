# Speech-Recognition-System
**Name: AMIT MISHRA** 
**Company: CODTECH IT SOLUTIONS**
**ID: CTO8DAQ**
**Domain: EMBEDDED SYSTEMS**
**Duration: 12TH DECEMBER 2024 TO 12TH JANUARY 2025**
**Mentor: N.SANTHOSH**



Building a basic speech recognition system for command-based control of devices using an embedded board such as an Arduino can be an exciting project that merges hardware and software to create a functional application. In this project, we aim to control a bulb through voice commands, using a Tinkercad simulation environment that includes components like a double pole double throw (DPDT) relay, a bulb, an Arduino board, and a resistor.

The main objective of this system is to provide a user-friendly interface to control a household appliance, such as a bulb, through voice commands. This approach enhances accessibility and convenience, making it easier for users to interact with their environment. The project relies on the fundamental principles of speech recognition, where the system interprets spoken commands and executes corresponding actions.

In our implementation, we opted for a simulation on Tinkercad due to the unavailability of a dedicated speech recognition module. Instead of incorporating a physical speech recognition system, we simulated the input through a power supply, allowing us to focus on the control mechanism and the relay operation. The Arduino board acts as the central control unit, interpreting the simulated signals and activating the relay that manages the bulb.

The circuit design consists of an Arduino connected to a DPDT relay and a bulb. The relay serves as a switch that controls the power supply to the bulb. By using a relay, we can safely manage higher voltage and current levels required by the bulb while keeping the Arduino circuit at a low voltage. The DPDT relay has two sets of contacts that allow for toggling between different states. In our case, it will control whether the bulb is on or off based on the command received.

To create the control logic, we utilize the Arduino programming environment to write a simple sketch that listens for specific commands. The basic structure of the code involves initializing the relay and setting up a loop that continuously checks for input signals. Although we simulated speech recognition, in a practical application, this would involve using a microphone and a speech recognition library or module to convert spoken words into digital signals that the Arduino can process.

Once the Arduino receives a simulated command signal, it determines the desired action based on predefined keywords or phrases. For instance, commands like "turn on the light" or "turn off the light" would trigger specific functions within the code. When a command is recognized, the Arduino activates the relay to either connect or disconnect the power to the bulb, effectively controlling its state.

In the absence of a real speech recognition system, we can simulate this functionality by using a switch or button that represents voice input. This approach allows us to test the control logic and verify that the relay responds appropriately to the commands. The bulb should light up when the "turn on" command is simulated and remain off when the "turn off" command is issued.

This project not only demonstrates the feasibility of controlling devices through voice commands but also highlights the importance of integrating hardware and software components in modern electronic systems. The Arduino serves as an excellent platform for prototyping such applications, as it provides an accessible environment for beginners and advanced users alike.

Additionally, implementing this speech recognition control system can lead to further enhancements. For example, one could integrate a microphone module to enable real-time voice recognition, allowing users to control the device with their voice directly. Furthermore, adding more commands or controlling multiple devices can enhance the functionality and complexity of the system, transforming it into a comprehensive home automation solution.

In conclusion, the basic speech recognition system for command-based control of devices using an embedded board demonstrates the integration of various electronic components to achieve a practical application. Through Tinkercad simulation, we successfully created a circuit that allows voice command simulation to control a bulb using a relay and an Arduino. This project serves as a foundation for exploring more advanced voice recognition systems and home automation technologies, showcasing the potential for innovation in the field of embedded systems and IoT (Internet of Things).
