# VEHICLE::SET_VEHICLE_MOD

## Summary
Sets a mod on the specified mod slot. Use GET_NUM_VEHICLE_MODS to find out the count available

## Parameters
* **VEHICLE_INDEX** vehicle
* **MOD_TYPE** modSlot
* **INT** mod
* **BOOL** variation = false

## Notes
<!-- AUTOGENERATED: Remove this line before editing -->
In b944, there are 50 (0 - 49) mod types.

Sets the vehicle mod.
The vehicle must have a mod kit first.

Any out of range ModIndex is stock.

#Mod Type
Spoilers - 0
Front Bumper - 1
Rear Bumper - 2
Side Skirt - 3
Exhaust - 4
Frame - 5
Grille - 6
Hood - 7
Fender - 8
Right Fender - 9
Roof - 10
Engine - 11
Brakes - 12
Transmission - 13
Horns - 14 (modIndex from 0 to 51)
Suspension - 15
Armor - 16
Front Wheels - 23
Back Wheels - 24 //only for motocycles
Plate holders - 25
Trim Design - 27
Ornaments - 28
Dial Design - 30
Steering Wheel - 33
Shifter Leavers - 34
Plaques - 35
Hydraulics - 38
Livery - 48

ENUMS: https://pastebin.com/QzEAn02v

## Hashes
<!-- AUTOGENERATED: Do not change -->
|Version|Hash              |
|-------|------------------|
|2944   |0x8450270DC5896D39|
|2845   |0x8450270DC5896D39|
|2824   |0x8450270DC5896D39|
|2802   |0x886F6B56E2966139|
|2699   |0x0061B7C9351B41ED|
|2612   |0x0061B7C9351B41ED|
|2545   |0x0061B7C9351B41ED|
|2372   |0x6895CB0D4F2E7CDC|
|2189   |0x8DFB45E7317A7ED7|
|2060   |0xEE6A1776A67F70C1|
|1868   |0xED4CA44675A55548|
|1737   |0xB4B3AEABE432069B|
|1604   |0x1EE56D43DA30ADC6|
|1493   |0x5C9F67BE33A5A3EE|
|1365   |0xA9EF3F93CBFFF6D0|
|1290   |0x6819ABF1BBD7D728|
|1180   |0x5A814851114E34FB|
|1103   |0x7940803ED711B46E|
|1011   |0xE8BE9EFA248A9414|
|944    |0x47EE94F716B70695|
|877    |0xF55EA971ECC0BCE5|
|791    |0x67867FC0711CB640|
|757    |0x406E9DA605D8FD2B|
|678    |0xA05B0407D11A92AD|
|617    |0x01A8ACBE7F8B45EF|
|573    |0x16580F6E093503C8|
|505    |0x323720FEE81B53C0|
|463    |0x85AB5576B5457AED|
|393    |0x3E9FFBB0E33D344F|
|372    |0x75F35BD9450C6115|
|350    |0x5D4B50E2007354F0|
|323    |0x6AF0636DDEDCB6DD|
|joaat  |0xB52E5ED5        |