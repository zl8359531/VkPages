## RTK use instructions

# The RTK onboard end

 At present, it has two RTK airborne terminals, both of which are 3-star multi-frequency differential board cards. Single antenna RTK has high precision positioning, without dual antenna direction finding function; dual antenna RTK has both high precision positioning and dual antenna orientation function, and has good diamagnetic interference capability.

The RTK airborne end and ordinary GNSS module provide dual redundant positioning function for the aircraft. When the RTK state is fixed, the system uses the positioning information of the RTK module; when the RTK state is not fixed, the system uses the positioning information of the GNSS module.

Installation considerations of the RTK module:

-The arrow shall be aligned with the nose direction when installing the single-antenna RTK module
-The two antennas of the dual antenna RTK must be right (ANT 1 behind) or right (ANT 1 at left), and the antenna distance is greater than 40cm
-RTK signal occlusion resistance is not as good as ordinary GNSS, and it is normal that some star search stability will deteriorate in the occlusion environment

# RTK Mobile base station

In the case of no mobile network or no Qianxun service, the mobile base station can provide high precision relative positioning, but there is a certain deviation in absolute positioning. The mobile base station purchased Qianxun service can provide high-precision dot mapping and flight operations. The process is as follows:

-Enter Settings- - \> RTK base station settings, search for RTK base station
-After Bluetooth connects to the RTK base station, click the spot mode, and the base station will automatically access the Chihiro location
-Base station location type display fixed solution for 30 seconds, click the current position to the base station coordinate button and keep the base station position still to provide high precision mobile base station service.

Figure: RTK base station information diagram

<img src="pictures/RTKP1.png" width="35%" height="300">

Notes for using mobile base stations:

-Ensure that the mobile base station battery is sufficient
-When a mobile base station provides a base station service, the position is unchanged
-After the mobile base station enters the check mode, it will no longer provide the base station service. It can re-power on or click the current position to set the base station coordinate button to make it work in the base station mode again.