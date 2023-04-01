## Autonomous route mode

* Plot planning and homework tutorial: * [* https: / / www.bilibili.com/video/BV1US4y1m77f?spm_id_from=333.999.0.0*](https://www.bilibili.com/video/BV1US4y1m77f?spm_id_from=333.999.0.0)

* Chihiro Connection tutorial: * [* https: / / www.bilibili.com/video/BV1dU4y1g7YN?spm_id_from=333.999.0.0*](https://www.bilibili.com/video/BV1dU4y1g7YN?spm_id_from=333.999.0.0)

# Plot surveying and mapping

Before automatic operation, it is necessary to map the boundary of the plot and the intermediate obstacle information. Click on the Mapping to enter the mapping page:

Map mapping plot type selection

<img src="pictures/AUTO1.jpeg" width="50%">

 Select the type of ground to map:

* * Polygon plot * *: For the whole piece of the large field block, map the boundary of the plot, and then plan the route to operate in the plot.

* * Free route * *: For the needs of irregular spraying, such as spraying irregular fruit trees, the need to stay on the tree for spraying, etc.

 The APP supports * mobile phone / remote control / aircraft / RTK base station / dot / map * There are 6 plot mapping methods, among which * aircraft / RTK base station / dot * can support RTK high precision dot (optional RTK version).

The following takes is used as an example to describe how to carry out high-precision RTK plot mapping.

1) First enter the remote control Settings page, and then connect to Qianxun service;

The Figure opens the Chihiro service

<img src="pictures/AUTO2.jpeg" width="50%">

2) into the surveying and mapping interface, select * polygon plot / free route *, then click on the lower right corner of the dot selection button, select the dot, select the corresponding dot device, click sure, APP will automatically connect the dot set bluetooth, connecting the dot location status and location will be displayed on the map.

Figure dot mode selection

<img src="pictures/AUTO4.jpeg" width="50%">

3) Point Select the ① dot type-boundary point in the yellow box.② records the point. Click ② at the boundary to click until all boundary point records are completed. When the location is wrong, you can click the cancel button to cancel the previous point and rearrange.

Figure the polygon plot dot

<img src="pictures/AUTO7.jpeg" width="50%">

4) After mapping the boundary of the polygon, if necessary, you can dot the obstacles inside the polygon. Click the dot type button to enter the obstacle point mapping mode. Also, click the click button to record the obstacle boundary. * * After recording the obstacle boundary, click the end obstacle button to complete the mapping of the area of the obstacle * *.

Figure Schematic diagram of obstacle dot switching

<img src="pictures/AUTO5.jpeg" width="50%">

1. If you need to surveying and mapping poles / trees, such as circular obstacles, can continue to click the dot type button to switch to the pole obstacle mapping mode, and then put the dot in the center of the obstacles, click the dot button, can automatically generate a polygon obstacle area, the lower right corner ruler icon can freely set the radius of the pole obstacle area.

Diagram of bar body obstacle mapping

<img src="pictures/AUTO6.jpeg" width="50%">

1. After completing all the mapping, switch the dot type to the boundary point, and click the upload button, the mapping plot information and obstacle information can be saved and synchronized to the plant protection network management platform for subsequent operations, as shown in the figure below.

Figure plot upload server

<img src="pictures/AUTO8.png" width="60%">

* * So far, the surveying and mapping work is completed.**

# Route planning

After the plot mapping is completed, the plot needs to be edited to generate the route. The route editing mainly has the following attributes:

* * 1) Route generation * *

-Entering the automatic operation interface, the current account plot near the location will be displayed. The APP obtains the plots from the plant protection management platform through the network. If the network is not smooth and not successful, it can refresh the list again after the plot list. Where there is no network at all, the plots will be kept locally.
-In the plot list, select the plot that you want to work on. Click the next button to enter the plot planning.

Figure plot selection

<img src="pictures/AUTO9.jpeg" width="50%">

-After entering the plot planning interface, you can set the route direction, edge distance, ridge width, and starting point position related to the plot planning.

Figure plot planning parameter setting

<img src="pictures/AUTO10.jpeg" width="50%">

-Select different edges (edge 1 / edge 2...), and the planned route will be parallel to the selected edges (orange label highlighted).
-Each edge can be set with a safe distance, and the safe distance can be set either by adding or subtracting buttons, or by entering numbers directly.
-Select the vertex of the plot as the starting point of the route. Touching the vertex of the plot, the ① navigation point is automatically planned near the vertex.
-If the route direction of the plot boundary is not meeting the operation, any Angle disk can be used to adjust the route Angle.
-Click the route type button, you can select the route type to be planned in the current plot, and you can plan the * bow route / winding route / fruit tree route / throwing route.*

* * Bow route: plan the bow route back and forth on the plot.**

* * Side route: a route around the edge of the plot for sweeping * *

* * Fruit tree route: For the whole row of fruit trees, you can make 1 / 2 / 3 / 4 at the end of one tree row, and 5 / 6 / 7 / 8 at the end of the other tree row. When planning the fruit tree route, you can automatically connect 1-8,2-7,3-6,4-5 into a line and plan the flight path.**

* * Drop route: For the cast model, a drop point can be planned every other distance.**

-Click the intelligent mileage button to set the maximum flight mileage of a single flight. After the setting, the route will be divided by planning the route, and the route will be completed at the starting point close to the starting point within the maximum flight mileage. The drone will perform hover / return operations, and the next flight will start the next route from near. This function is set reasonably to ensure that the route is close near the starting point, and the next flight will fly to the distance without a load. If the smart mileage is set to 0, turn off the smart planning function, as shown below:

Figure intelligent mileage opening diagram

<img src="pictures/AUTO15.jpeg" width="50%">

-Click the safe distance button to set the safety boundary distance and the obstacle boundary safety distance. The boundary safe distance represents the shrinking distance within the route, and the obstacle boundary safe distance represents the extended distance outside the route near the obstacle.

* * 2) Delete some shipping points * *

In the process of actual operation, a plot may have several routes is not homework, can by deleting the point will not delete homework routes, specific operation is: click delete the route serial number icon, in the pop-up prompt box input delete the end of the route serial number, and then confirm, in the figure below:

Figure A schematic diagram of the deleted navigation point

<img src="pictures/AUTO12.png" width="50%">

* * 3) Set up the auxiliary take-off point landing point * *

If there is an obstacle between the take-off point and the flight point 1, or between the take-off point and the return point, the take-off / return flight can be set on the map. Operation: long press on the map, and a red triangle will be displayed on the map after 1 second, indicating that the setting of the auxiliary point has been successful. The auxiliary points need to be set up in advance, before the flight to the point and before the return flight. Re-upload the route or click the Clear secondary point button to clear the secondary point.

The Figure sets up the auxiliary points

<img src="pictures/AUTO14.png" width="50%">

# Autonomous flight

After the route planning is completed, click Next![](media/47b52b9eac87f78862ba41067816e0fb. The png) button to end the planning and enter the route operation interface as shown in the figure below.

Figure the automatic job interface

<img src="pictures/AUTO11.jpeg" width="50%">

After checking the route is normal, click the parameter setting to set the * height / speed / mu dosage of the route *, then upload the route (* * Remember must upload the route * * before starting the operation), and then take off and wait for the UAV to take off automatically. After taking off, click the operation UAV to start operating according to the scheduled route.

Route rearrangement: For operations with a distant breakpoint, you can use the route rearrangement function. After clicking the route rearrangement, you will replan the starting point at the position close to the UAV, and then start the operation.* * Remember to upload the route again after the route rearrangement.**

Figure route rearrangement

<img src="pictures/AUTO16.png" width="60%">

 Mobile route: make the overall movement of the route. If there is an overall deviation for the land parcel, the route movement can be used to adjust the route deviation.

 Emergency stop: you can click on the emergency stop to suspend the route.

 Switch lights: For drones equipped with lights, this button can switch the night lights.

 Take photos: For a drone equipped with a camera, this button can control the camera to take a camera view.

Switch shortcut key: can quickly switch ground prevention / obstacle avoidance radar, and height control mode.

-The route is not completed. After the UAV returns for change and dosing, the operation is no need to upload the route. After the UAV takes off, click operation again, then the aircraft will fly to the breakpoint of the last route;
-Even if the obstacle avoidance radar is installed, the radar obstacle avoidance is automatically closed during the process of navigation point 1;
-Ridge changing mode can choose right Angle turn or U-bend;
-Support real-time throttle / heading adjustment during the route process, and support remote control operation and obstacle avoidance, refer to section 3.1.4 for specific operation;
-Spray capacity can be set to fixed pump output or mu dosage automatic speed mode.
-When the job is completed, you need to continue the next day, just select the current job next time. When planning, the APP will prompt * to continue the last job / read the last plan / replan *, and select * * to continue the last job * *. You can retrieve the last job from the background and continue the last unfinished task.

Figure continues the last assignment diagram

<img src="pictures/AUTO18.jpeg" width="50%">

# Autonomous flight- -fruit tree mode

 Fruit tree mode is to measure the longitude, latitude, and altitude (relative height, altitude and altitude) of each tree by surveying the aircraft (or using the aircraft to dot), and plan it as a flight route. It can set whether the route is sprayed, and the hovering spraying time. Plot can also be surveyed in advance to generate usable routes and save them.cvs perhaps. Import the kml file into the APP for use.

1. Enter the mapping interface, select the free route to start clicking or select the import button in the upper right corner to import the generated navigation point file.

Figure free route test selection

<img src="pictures/AUTO19.jpeg" width="50%">

1. Take the path to fly. Free-route drones will follow the mapping path.
2. Enter the automatic operation interface, select the free route completed by mapping, set the free route spraying switch, hover time and other parameters. After the setting, upload the route and perform the operation.

Figure Schematic diagram of the free-way route mapping

<img src="pictures/AUTO20.jpeg" width="50%">

* Video tutorial: * [* https: / / www.bilibili.com/video/BV1M44y1V7A2?spm_id_from=333.999.0.0*](https://www.bilibili.com/video/BV1M44y1V7A2?spm_id_from=333.999.0.0)