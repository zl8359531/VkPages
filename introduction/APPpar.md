## APP settings item details

The setting functions include the configuration and the remote control setting of the UAV, plant protection setting, remote control channel inspection, motor inspection, flight calibration, and the reading of the flight log.

# Remote control settings

Figure of the Remote Control Settings page

<img src= " pictures / remote control connection.jpeg" width="50%">

 At present, the Bluetooth connection mode and the USB connection mode are supported.

 Click search remote control in Bluetooth connection mode, find the remote control code and connect successfully, the operation mode will appear, select Japanese hand / American hand above, select the remote control will send a "drop", indicating that the setting is successful, the upper right corner is the name of the remote control you are connected to.

In USB connection mode, directly connect the remote control with USB cable (the cable with the remote control).

# Channel detection

Figure channel check page

<img src="pictures/APPPAR2.png" width="50%">

Channel detection is used to test whether the remote control to the drone is connected properly, and to determine whether the remote control is working properly. When the user dials the switch and tick on the remote control, the user will see the corresponding channel change on the ground station.

The display of the channel corresponds to the following display data:

1. Channel 1234: the green line is at position 150; the maximum value is 1200, the minimum value is 100; channel 2 is the reverse channel;

2. Channel 5: If in manual stabilization mode (GPS mode), it should be 150; if in attitude mode, it should be 110; AB point mode, it should be 190, with three values of 110,150 and 190;

3. Channel 678:110 at standby default bit; three values are 110,150 and 190;

# Motor inspection

Figure the motor inspection page

<img src="pictures/APPPAR3.png" width="50%">

Motor inspection is used to check whether the motor of the UAV is working normally (the oil-moving direct drive does not have the motor inspection function). Click the check button for each motor, and the electric opportunity of the UAV will rotate, and the motor speed will be displayed on the progress bar to judge the working condition of the motor. Up to 8 motors can be inspected.

 The following points should be checked during the inspection:

1. Steering of motor, single motor is counterclockwise; double motor is clockwise.

2, the motor speed, observe whether the speed of the motor is consistent.

# Plant protection setting

Figure The Plant Protection Settings page

<img src="pictures/APPPAR4.jpeg" width="50%">

 In the plant protection setting, the user can adjust the ridge distance (AB route spacing), flight speed (maximum speed), and set the spraying flow in two ways (select the operating power percentage of the motor of the pump when fixed from 0-100; select the speed per mu according to the maximum speed of the aircraft).

Users can adjust the parameters by dragging and dropping the slider, or by clicking plus or minus. There are still many places on the ground station to adjust the parameters that can be set with these two operating modes.

# Flight Settings

<img src="pictures/APPPAR5.png" width="50%" height="50%">

In the flight settings, the user can set up:

* * Automatic take-off altitude * *: The altitude of the aircraft in automatic take-off mode

* * Return height * *: The lowest height of the aircraft in the automatic return mode and one-key return mode. If the current aircraft is below this altitude, it will rise first, and if it is above this altitude, it will directly return and then drop.

* * Voltage alarm threshold value and protection measures * *: Set a reasonable voltage alarm threshold value, and trigger the corresponding voltage protection action when the voltage is lower than this threshold value. The oil-moving / hybrid aircraft will have two-stage oil volume alarm setting and protection action at the same time.

* * Manual control direction * *: Head pointing can be manually changed in the route. The default open.

* * Manual control height * *: The height can be manually adjusted at any time in the route. Default controllable.

* * Anti-ground radar sensitivity * *: Using this sensitivity in ground protection cases, increase sensitivity The aircraft is more responsive to terrain fluctuations.

* * Maximum speed * *: Maximum speed of manual flight in GPS mode.

* * Barricavoidance action * *: When obstacle avoidance opens, you can choose to hover / bypass an obstacle.

* * Fencing radius / height * *: The aircraft can fly in the park with the takeoff point as the center and the radius of the fence radius. After exceeding the range, it will alarm and turn back. If the ground of the takeoff point is 0, the height of the fence can not be exceeded in the upward direction. After exceeding, the return flight will be triggered.

* * Drug off protection * *: triggers the drug off protection when the amount of Chinese medicine is low, and can hover / return

Remote control runaway protection: remote control runaway will trigger corresponding protection in manual flight, and protection will not be triggered during automatic route operation.

* * * *: In automatic operation mode, if the ground station link fails, the corresponding protection action will be triggered

* * * *: This action is triggered after the route operation and can hover / return

* * Distance of obstacle avoidance * *: encounter obstacles in flight, enter the obstacle avoidance distance will perform the corresponding obstacle avoidance action, hover / detour

* * Type * *: Right Angle turning takes the longest time and is smooth. The U-shaped turn takes the least time, turns fast, and has large turning angles. The regular turn is in between.

# daily record

Figure log page

<img src="pictures/APPPAR7.jpeg" width="50%">

 The log page is used to read the flight log on the drone and to help drone developers better identify problems with the drone.* Note: The log must be read when the drone is parked on the ground and the propeller is locked to avoid danger.*

 The log list will show all the log files stored in the flight control. Look at the file name. The first part is the flight control number, the second part is the flight number, and the third part is the log file time.

 The first button behind each log is the download button, which can read the log from the flight control to the APP local. When the reading is completed, the log will have two more buttons. The upload button is: upload the log to the cloud server, and the manufacturer can obtain the log files from the cloud platform. Share button: It can be sent to others through social software such as wechat / QQ.

After selecting the log, you can press the Delete Log " button in the lower right corner to delete it.

# Version of the information

Figure version information page

<img src="pictures/APPPAR8.jpeg" width="50%">

 Version information is used to display the ground station version, flight control firmware version, serial number and other information. You can also check for other firmware versions such as updates, upgrade ground station software and flight control firmware here.

When the aircraft power supply is connected, open the APP and connect the remote control, it will independently indicate whether there is an update. If there is an update, the user can click to the version information page to check, download the latest version firmware and then directly upgrade and install it. After the installation, unplug the aircraft battery, then reconnect the aircraft, and then update other firmware after restart.

# shakedown test

Figure debugging page

<img src="pictures/APPPAR9.jpeg" width="50%">

The debugging page displays some flight control information in more detail.

# Kit device settings

Enter the mapping, select the dot, and then select the Bluetooth of the dot


# Intelligent battery

When the smart battery matching with the flight control is used, the smart battery related information will be displayed, as shown in the figure.

Figure the smart battery page

<img src="pictures/APPPAR10.jpeg" width="50%">

# Oil and electricity engine

The gas-electric engine is also hidden, only displayed when using the gas-electric drone, providing data status.

# Operation machine type

Can be configured with the current aircraft pressure nozzle or centrifugal nozzle, is a single water pump or double water pump.

Figure the machine type page

<img src="pictures/APPPAR11.jpeg" width="50%">

# Other settings

In other Settings, map setting and voice prompt can be selected according to user needs; video display is only available by users with optional camera.

Another: map type: domestic mapbox; for foreign users and mobile phone open Google map in foreign flight switch Google map, South Korea use Naver

Figure Other settings page

<img src="pictures/APPPAR12.jpeg" width="50%">

# advanced setup

* * Note: Advanced settings options for only the APP.**

* * 1) Model setup * *

Figure Advanced Settings-Model Settings

<img src="pictures/APPPAR13.jpeg" width="50%">

Set the type matching the aircraft, pay attention to the motor steering and motor serial number definition.

* * 2) Algorithm parameters * *

Figure advanced settings- -algorithm parameters

<img src="pictures/APPPAR14.png" width="25%" height="300">

* * Noise suppression * *: inhibit the vibration of the aircraft body, the greater the vibration of the aircraft, the higher the value needs to be set. This option needs to match the aircraft vibration situation. The selection basis is to try to change only this parameter under the basic flying parameter, and to select a suitable level based on the flying body.

* * Motor Idle * *: Set the minimum idle PWM value for the unlocked motor. This value allows the propeller to rotate normally but without pulling up the plane.

* * Take-off throttle * *: Invalid

* * Positioning enhancement * *: Default on

* * Front and after obstacle avoidance sensitivity * *: The sensitivity setting of obstacle avoidance radar is used to adjust the sensitivity of obstacle avoidance recognition. The stronger the sensitivity, the approximate sensitivity will also increase the probability of false alarm. Generally set up to about 40.

* * Brake coefficient * *: Adjust the sensitivity of the brake, the smaller the sensitivity, the softer the brake. Default 20

* * 3) Installation setup * *

Figure Advanced Settings-Installation Settings

<img src="pictures/APPPAR15.png" width="50%">

* * Flight control installation direction * *: Set the installation direction of flight control, subject to the flight control arrow

* * RTK installation direction * *: Set the installation direction of two RTK antennas according to the actual situation, front / left / right / lower left / lower right. Single-antenna RTK requires no setting.

* * Set the RTK / GPS / IMU installation error * *: Deviation from the center position of the aircraft, no Z-axis setting is required.(RTK: RTK antenna 1.)

* * 4) Sense setting * *

Refer to [2.3 sensitivity debugging] (# _2.3 sensitivity debugging)

* * 5) Flight calibrations * *

Figure Advanced Settings- -flight calibration

<img src="pictures/APPPAR17.png" width="25%" height="300">

* * Horizontal calibration * *: When the flight control level deviation, do a horizontal calibration, generally flight control factory calibration, the customer does not need to calibration.

* * GPSA / B setting * *: Change GPS master / secondary for dual GPS version.

* * Location type * *: Position the device type and select according to the actual device used

* * Battery type * *: Battery type, according to the actual use of the battery selection

* * Restore factory Settings * *: With 5 consecutive clicks, all parameters in the flight control will be restored to the default.