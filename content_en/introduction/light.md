# Flight control LED light language

| | LED Status | Status Description |
|--------------------|------------|-------------------------------|
| Red (combined flashing) | constant light | system initialization / magnetic compass calibration failure |
| | 1 Flash | Poor Positioning |
| | 2 Flash | Poor poor |
| | 3 Flash | low voltage alarm |
| | 4 Flash | background locking |
| Green (combination flashing) | always bright | magnetic compass level calibration |
| | 1 Flash | Attitude Mode |
| | 2 Flash | GPS fixed-point mode |
| | 3 Flash | Auto Mode |
| | 4 flash | positioning ready to take off |
| Blue (separate flashing) | often bright | magnetic compass vertical calibration |
| | 1 Flash | Transport Warning |
| | 2 Flash | IMU no data |
| | 3 Flash | GPS Star Loss Warning |
| | 4 Flash | Speed Warning |
| | 5 Flash | Remote Control Location Warning |
| Yellow (separate flashing) | 2 flash | | additional alarm
| | 3 Flash | Gyro alarm |
| | 4 Flash | Magnetometer alarm |
| | 5 flash | temperature over 65° alarm |
| Purple (combined flicker) | 1 Flash | AB point Record A point |
| | 2 Flash | AB point Record B point |
| | 3 Flash | Remote Control Calibration |
| | 4 flash | electric adjustment and calibration |
| Cyan (combination flash) | 1 flash | RTK not into fixed solution / GPS search star mass quality |
| | 2 Flash | motor balance difference |
| White (combined flashing) | 1 flash | imitation radar connected |
| | 4 Flash | IMU Part Upgrade |

Long bright flashing

# Mobile base station LED light language

<img src="pictures/LIGHT1.png" width="50%" height="350">

BT: Bluetooth indicator light, flash indicates that Bluetooth is not connected; long light indicates that the base station Bluetooth and APP link are normal.

RX: The base station sends the indicator light once representing a package of CORS data to the base station. When the base station works normally, the LED should flash 1 HZ

TX: Base station receiving indicator light, flashing once represents the receipt of data from a package of onboard RTK

FIX: Base station operating status indicator, flashing significance as follows:

Continuous flash: the base station coordinates successfully, and the base station works in fixed coordinate mode

4 Flash: no positioning

3. Flash: single-point positioning

2 Flash: RTK position floating point solution, positioning accuracy submeter level

1 Flash: RTK position fixed solution, positioning accuracy cm level

P_L: Bluetooth and RTK initialization indicator flashing as follows:

Continuous flash mob: enter the spot-checking mode

2 Flash: Bluetooth initialization failed

Long bright: normal

GPS: The Sparker representative is searching for stars

RTK: not have

# Dual-antenna direction-finding RTK module light language

<img src="pictures/LIGHT2.png" width="60%">

 RX-1: serial port 1 receive data light, is often out.

 RX-2: Serial port 2 receives the data light and has a normal 1s flash when connecting the Qianxun data.

 ANT-1:1 antenna abnormal light, is often out, often bright red means ANT 1 open circuit, often bright green means ANT 1 short circuit.

ANT-2:2 antenna abnormal lamp, is often out, often bright red means ANT 2 open circuit, often bright green means ANT 2 short circuit.


