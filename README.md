# Auto-Sort-Machine
The Auto Sort Machine is a system that automates sorting objects based on 
specific criteria. It typically uses various technologies such as sensors, motors, and 
microcontrollers to detect, sort, and move objects along a conveyor belt or other types of 
systems. The Auto Sort Machine can be customized to sort objects based on different criteria, 
such as size, weight, shape, and color. It is widely used in manufacturing plants and warehouses 
to increase efficiency, reduce errors, and improve productivity.
In addition to its practical applications, the Auto Sort Machine project aligns with the 
Sustainable Development Goal (SDG) 9: Industry, Innovation, and Infrastructure. This SDG 
emphasizes investing in infrastructure, innovation, and research to support 
sustainable industrialization and economic growth. The Auto Sort Machine project is a prime 
example of such innovation, as it aims to improve the efficiency and productivity of industrial 
processes using advanced technologies. By contributing to SDG 9, the Auto Sort 
Machine project also promotes sustainability and economic development

# Components used
1. Arduino Nano
2. Ultrasonic Sensors
3. IR Sensors
4. Servo Motor
5. DC Motor
6. External Power Supply

# Working
• Initially, the conveyor belt has an IR sensor that will detect the presence of the object 
on the conveyor belt. If the IR sensor gives a value of HIGH, then the DC motor will 
start rotating which will eventually rotate the conveyor belt and make the box move.
This mechanism can conserve energy.
• Now, we have two ultrasonic sensors each on both sides of the conveyor, which would 
detect the size of the box on the conveyor.
• As the size of the box is stored now, we have another IR sensor that will detect the 
object’s presence in the range of the servo, as the second IR sensor reads HIGH the 
servo motor will rotate and move the object with size more than 5 cm to the other side 
of the servo. Whereas for objects with a size less than 5 cm, the servo will not rotate.
• So, in this manner the objects will get sorted based on a threshold size of 5cm.
