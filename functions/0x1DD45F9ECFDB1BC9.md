# TASK::TASK_GO_TO_COORD_ANY_MEANS_EXTRA_PARAMS

## Summary
Tells a ped to go to a coord by any means

## Parameters
* **PED_INDEX** ped
* **FLOAT** coorsX
* **FLOAT** coorsY
* **FLOAT** coorsZ
* **FLOAT** moveBlendRatio
* **VEHICLE_INDEX** vehicle
* **BOOL** useLongRangeVehiclePathing = false
* **DRIVINGMODE** drivingFlags = 786603
* **FLOAT** maxRangeToShootTargets = -1
* **FLOAT** extraVehToTargetDistToPreferVeh = 0
* **FLOAT** driveStraightLineDistance = 20: Allow script to define the distance at which vehicles switch to straight-line pathfinding; default to same value as in code (20m)
* **TASK_GO_TO_COORD_ANY_MEANS_FLAGS** extraFlags = 0:
Bitset of values from the TASK_GO_TO_COORD_ANY_MEANS_FLAGS enumeration fWarpTimeMS - Warps ped to target position if ped gets stuck for this amount of time (in milliseconds) (only if fWarpTimeMS != -1.0).
Only works for peds on foot or in a car/bike (not aircraft/boats).
Ped will be removed from vehicle on warp.
* **FLOAT** warpTimerMS = -1

## Hashes
<!-- AUTOGENERATED: Do not change -->
|Version|Hash              |
|-------|------------------|
|2944   |0xE4250AD3565B478E|
|2845   |0xE4250AD3565B478E|
|2824   |0xE4250AD3565B478E|
|2802   |0xE6193F5A8322049E|
|2699   |0x110DEDD855267AD4|
|2612   |0x110DEDD855267AD4|
|2545   |0x110DEDD855267AD4|
|2372   |0xDE70FC61C90EDC40|
|2189   |0x276888A388F25ACF|
|2060   |0xF9886237FC8D1C2C|
|1868   |0xE95B392528CF2F01|
|1737   |0x57FC8A645C1810FD|
|1604   |0x0602A4EE9C2B4D29|
|1493   |0x51BE2881D092263A|
|1365   |0x60123AB17F724A9F|
|1290   |0x8611737460597C42|
|1180   |0x537FFCA44F4F4A66|
|1103   |0x89E1616E11D67247|
|1011   |0x7E08FEC6DCA38B0D|
|944    |0x8E2AF2F500EDF8AD|
|877    |0xAB4B9B2BE318B4D4|
|791    |0x2D8109CDBA7494B2|
|757    |0x9F1CEAA058D36400|
|678    |0x2A833152645BB346|
|617    |0x089A1A0CBB6AB138|
|573    |0x451004AE6A7C7F2F|
|505    |0x4890BB26A29019B8|
|463    |0xDAF376FE973046EE|
|393    |0x0253D6FC8B22BFED|
|372    |0x4E707B14B7137CD6|
|350    |0x2A6FEBABC0830CA9|
|323    |0x1DD45F9ECFDB1BC9|
|joaat  |0x094B75EF        |