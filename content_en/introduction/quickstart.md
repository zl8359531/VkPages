

# Interface definition
<img src="pictures/接口说明.jpeg" width="100%"> 

| ** V9-FMU port * * | * * function description * * | * * V9-PMU port * * | * * Function description ** |
|------------------|----------------------------|----------------|-----------------------------|
| ** Digital transmission communication radio * * | Connect digital transmission link (receiver Link) | * * VIN * * | power supply (20 \ ~100v) |
| ** M1 \ ~M8 * * | 1 \ ~8 motor interface | * * FMU * * | Connect to FMU (XT30 2 + 2 line) |
| ** PMU interface * * | Connect to PMU (XT30 2 + 2 line) | * * P1 * * | Water pump 1 |
| ** SBUS + * * | SBUS-R + -Connection to the SBUS line | * * P1 * * | Water pump 2 |
| | RTCM-R connected Rtcm data | * * A1 * * * | Centrifugal nozzle 1 |
| ** Electric modulation can * * | Connect the electric modulation supporting CAN communication | * * A2 * * | Centrifuge nozzle 2 |
| ** GPS-CAN * * | Connect GNSS Master / From Module | * * F1 * * | Flow meter 1 |
| ** GPS-CAN * * | Ditto above, two GPS-CAN General | * * F2 * * | Flow meter 2 |
| ** RTK-COM * * | RTK equipment connected to D3-H | * * L1 * * | Drug break / material sensor 1 |
| ** Test-COM * * | spare serial port | * * L2 * * | drug / material sensor 2 |
| | | ** CAN 1 \ ~4 * * | CAN equipment for ground prevention / obstacle avoidance (12v output) |
| | | ** LED indicator light * * | LED module |
| | | ** COM * * | Spare serial port |

|** Interface / model * * | * * default * * |* * * double water pump * * | * * centrifugal head * * | * * seeding **|
|-------------------|-------------|------------------|----------------|------------|
|** P1 * * | Water pump | Water pump front | water pump | empty |
|** P2 * * | water pump | water pump | water pump | empty |
|** A1 * * | pump | centrifugal head | centrifugal head | VALVE servo |
|** A2 * * | pump | after centrifugal head | centrifugal head | SPEED motor |


# Master controller installation

 Installation considerations:
-Install it horizontally on the aircraft panel and in the positive center of the aircraft as far as possible to avoid instability of the aircraft during vibration.
-When installing the main controller, the side printed with the V9 logo must be mounted upward, and the installation direction can be divided into four directions: forward, left, back and right; the default forward orientation of the small triangle sign shall be consistent with the direction of the aircraft head. If the right direction installation is set, the small arrow should point to the right side of the aircraft

<img src="pictures/机头指向.jpeg" width="80%"> 

#GPS install

 Installation considerations:

-When installing the GPS module, the marked side must be oriented up with the same direction as the aircraft head.
-GPS module is magnetically sensitive equipment, the installation and use should be far away from other electronic equipment and strong magnetic substances, and the frame plane is above 10cm high.

# Dual-antenna RTK installation

-The two antennas of the RTK module must be installed in front and front (after 1, before 2) and right (1, left, 2, right), and should be set correctly on the APP. The module is antenna 1 with ANT 1 and antenna 2 with ANT 2.
-The distance between the two antennas is greater than 40cm

<img src="pictures/RTK安装.png" width="50%" height="350">

# Radar installation

-The ground radar is horizontally mounted at the bottom of the aircraft without any shielding from the lower part of the radar
-The obstacle avoidance radar is mounted on the front / rear of the aircraft, with the back bar heat sink facing up by 12 degrees


<img src="pictures/雷达安装.jpeg" width="70%">
