### Control of DC motor
**Prepared by İdil Aygün**
#1.Rating Characteristics of Motor
**Voltage rating:**

**Current rating:**

**Power rating:**

#2.Information about Power Source and Control System

**a)Power Source:** Voltage value of the source should be greater than the emf of the motor to run it in motoring mode.

**b)Control System:**
Control system contains two control loops as inner one is current-control loop and outer one is speed control loop.

![](http://m.eet.com/media/1059850/dc_motor_drives_fig4.11.jpg)

*Figure 2.Schematic of Control loops*
**Outer loop:** This loop is responsible for speed control. It compares the measured speed value of motor with the desired(reference) speed of the motor. The difference between these values gives an error which contributes as a current reference value for inner loop system. The result of speed control loop should be steady state value to be used for reference current.Therefore, an used PI controller for speed controller can provide zero steady-state error.
**Inner loop:** This loop provides that the measured current value becomes very close to reference current value.

As a working principle of contro system, when load increases, the speed of motor decreases. Then, the speed error between reference speed and actual(measured) speed of motor increases. This leads to more current to inner loop as reference current. When the current error increases, the torque increases by providing acceleration and reducing the speed error to achieve balance in the system to make torque of the motor equal to torque of the load.

#3.Acceleration Curve from Stationary to Rated Speed

#4.Start-up Current Graphs

#5.Produced Torque During Start-up
