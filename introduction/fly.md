
# Flight debugging

# Unlock / add lock

* * Outside eight unlock: * * wait for star search good, APP no alarm display, the remote control outside the eight operation to unlock the plane, unlock the propeller will turn up. Before the plane will take off.

* * Inside eight plus lock: * * after the plane landing down the throttle will automatically lock, can also be manually inside eight plus lock, inside eight plus lock at any time, in the air can also be inside eight plus lock.

Figure Schemdiagram of remote control unlocking / locking

<img src="pictures/遥控器解锁.png" width="100%"> 


# Parameter setting (preliminary)

* * Parameter setting is very important, setting error will directly lead to the crash accident, be sure to be careful to confirm * *. Enter the advanced setting, (* * manufacturer account has the advanced setting option * *) Select the correct plant protection machine model, and confirm whether the motor serial number and steering are consistent with the diagram; enter the algorithm parameters, ensure the flight control installation method is consistent with the actual installation.

The default 3 can be selected for the first test flight noise suppression; the installation deviation of GPS is the distance from GPS installation position to the center of the aircraft, with positive right on X axis, positive in front of Y axis and positive on Z axis.


# Sensing debugging

For the first test flight, the default sensitivity parameters can be adopted. In the open room, wait for a good star search, unlock in GPS mode, take off to check the flight status in the air, and conduct further parameter tuning.


* * Description: * *

**① R / P base sensitivity: * * In attitude mode, the base sensitivity is first adjusted, and the default value is 120 (please set this parameter to 100 for aircraft above 30 inch paddle). In the attitude mode, try to not move the pole and observe the self-stability ability of the aircraft. The simple method is to hit the pole back in a small range to see whether the aircraft can quickly recover the level. If not, it will increase upward with the value of 5 each time. Increase this sensation until the aircraft has a slight jitter, and then reduce by 20% is the appropriate sensation. The base sensitivity should not exceed 180, otherwise there will be a greater risk of self-excitation oscillation.

**② Y base sense: * * heading base sensitivity adjustment method and roll / pitch base sense of similar, manual heading follow slow can increase this parameter, in general the default value of 260 can meet the requirements of the flight, if the feeling heading stability ability is not enough, performance in the case of wind, heading a little rotation, then at the same time with each plus 10 numerical increase this parameter.

**③ R / P / Y attitude sense: * * attitude sense is the parameter of adjusting the aircraft to follow the flight command, that is, the mobility performance of the aircraft during flight. In the case of good base sensitivity debugging, fast rod / full rudder rod, to see whether the aircraft can quickly perform Angle response (the maximum Angle is limited to 20 degrees in attitude mode). If the response of the aircraft is slow when hitting the rod, this parameter can be increased, and the attitude sense should not exceed 600.

**④ R / P damping: * * This coefficient is to increase the stability of the aircraft, and to prevent self-excitation oscillation to a certain extent. If the base / attitude sense cannot suppress the aircraft jitter, try to set this parameter to 0. Generally, the default 3 or 4 can meet the flight requirements. When the attitude mode hit the Angle back in the middle position slightly shaking can increase this value, add 1 each time, try not to exceed 10.

**⑤ Y damping: * * This coefficient is for increasing the stability of the heading channel. Default 3 or 4 can meet the flight requirements.

**⑥ Height coefficient: * * The default 20 can meet the requirements. If the vibration of the aircraft is large and the output of the motor is obviously not smooth enough, and the motor is quickly added and reduced, these two parameters can be reduced to 15 or 10.

**⑦ Vertical speed coefficient: * * Adjust the response speed of the throttle, the greater the sensitivity, the faster the throttle response, the smaller the sensitivity, the slower the response, the general aircraft 350 value can meet the requirements.

**⑧ Horizontal velocity damping: * * If the vehicle in the hovering air resistance is poor, and the position drift is large, this parameter can be appropriately increased (not large and 50).

**⑨ Horizontal velocity coefficient: * * default 120. In GPS position mode, if the speed follow response is not enough, this parameter can be appropriately increased (not more than 150); if the speed follows the overshoot, this parameter can be appropriately reduced (not less than 80). In GPS mode, too large braking angle can reduce this parameter, while too slow braking can increase this parameter.

**⑩ Brake coefficient: * * Default coefficient of 20. The larger the coefficient, the more sensitive the brake, and the opposite.

# Job task interface

<img src="pictures/手动页面.jpeg" width="70%"> 

The top status bar shows the current status of the drone.

Status display bits:

* * 1 * *: Battery level. Click the battery level icon to display the engine detail page

* * 2 * *: Height information, with the ground height above and the altitude below

* * 3 * *: Flight speed, horizontal speed size

* * 4 * *: Distance from home, distance from the HOME point

* * 5 * *: For GPS stars, click the GPS star icon to pop up box 14 to display satellite / radar information

* * 6 * *: Flight time, power failure is reset

* * 7 * *: Flow rate information, the flow rate of the liquid after pump opening, unit L/min

* * 8 * *: Number of mu, number of mu / total number of mu

* * 9 * *: Operating dosage, already sprayed dosage information, unit L

* * 10 * *: Signal quality, information quality of communication between remote control and aircraft

* * 11 * *: The alarm display bit, display the current alarm state of flight control, but no alarm information

* * 12 * *: Mode display bit showing the flight mode of the current aircraft

* * 13 * *: Notification information bits, some notification information will be displayed through this box

* * 14 * *: Equipment information bit, showing the connection and basic information of the current aircraft equipment

* * 15 * *: Command operation position, successively, return, fall, AB Angle (AB point set Angle to AB point)

* * 16 * *: Barrier avoidance and ground prevention switch button

* * 17 * *: Clear the AB point

* * 18 * *: Enter the Settings interface

* * 19 * *: One-click center
