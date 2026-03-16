DIY 5000mAh Powerbank – Technical Write-up
Project Overview

This project demonstrates the design and assembly of a DIY 5000mAh powerbank using widely available electronic modules. The main objectives were:

To understand lithium battery charging

To practice soldering and circuit assembly

To implement a DC-DC voltage boost for USB output

The device converts the 3.7V output of a Li-Po battery to 5V USB output suitable for charging mobile devices.

Components

TP4056 charging module – manages Li-Po battery charging safely

MT3608 boost converter – boosts 3.7V to 5V

5000mAh Li-Po battery

USB-A female port

Wires

Electrical insulation tape

System Design

The powerbank system is divided into three main stages:

1. Battery Charging

The TP4056 module controls battery charging through a micro USB or Type-C port. It ensures:

Constant current / constant voltage charging

Overcharge protection

2. Voltage Boosting

The MT3608 module increases the 3.7V battery output to 5V, making it compatible with standard USB devices.

3. Output Delivery

The boosted 5V is delivered to the USB output port for device charging. The system was tested with a smartphone and provided stable voltage.

Measurements and Testing
Parameter	Value
Battery voltage	~3.7V
Output voltage (idle)	~5.02V
Output voltage (charging)	5.09V

The device successfully charged a smartphone for multiple test cycles without overheating the modules or battery.

Challenges

Stiff wires made soldering difficult

Some solder joints broke during initial assembly

One module was damaged due to overheating during soldering

Initial attempts required multiple retries

These challenges helped improve practical soldering skills and problem-solving abilities in electronics.

Lessons Learned

Fundamentals of lithium battery charging circuits

Understanding DC-DC voltage boosting

Hardware debugging and troubleshooting

Hands-on soldering practice

Future Improvements

Design and 3D-print a custom enclosure

Integrate a battery protection circuit

Add a charging efficiency measurement system

Include a battery level indicator

Conclusion

The DIY 5000mAh powerbank project successfully combines theory with practical application, demonstrating basic electronics design, assembly, and testing skills. It serves as a strong portfolio project for hardware and electronics-related applications.
