# PED::APPLY_PED_BLOOD_SPECIFIC

## Parameters
* **PED_INDEX** ped: Index - the index of the ped to apply the blood damage to
* **INT** component
* **FLOAT** u: & v - the UV texture coords for the placement of the decal within the specified zone.
* **FLOAT** v
* **FLOAT** rotation: The angle (in degrees) for the rotation
* **FLOAT** scale: The scale factor applied to the damage (range is 0.0 to 1.0, based on the MinSize/MaxSize tuning paramters in peddamage.xml) forceFrame - Allows a spefic frame of damage to be chosen (or use -1 for the usual random frame selection)
* **INT** forcedFrame
* **FLOAT** preAge: The number of seconds to preAge the damage, this allows you for generate an "old wound", using 0.0 will be a usual freash wound.
* **STRING** bloodName:
The name of the blood type.
this should match an entry in build\dev\common\data\effects\peddamage.xml

## Notes
<!-- AUTOGENERATED: Remove this line before editing -->
Applies  ped blood damage on a ped by specifying a specific zone, direct UV offsets, rotation, scale, and initial Age (for animation effects).
You can also force a specified frame to be used instead of a randomly chosen one.
you can use the widgets in  "Peds/Ped Damage/Test Blood by UV (Script Params)" to test u,v values for different zones, rotations, scales, etc

## Hashes
<!-- AUTOGENERATED: Do not change -->
|Version|Hash              |
|-------|------------------|
|2944   |0xD1D8E1BF0769890C|
|2845   |0xD1D8E1BF0769890C|
|2824   |0xD1D8E1BF0769890C|
|2802   |0x6842A202FD26C033|
|2699   |0x2D0C965C5964FC7A|
|2612   |0x2D0C965C5964FC7A|
|2545   |0x2D0C965C5964FC7A|
|2372   |0x6C8A8DADCB013067|
|2189   |0xC40573784954F2AD|
|2060   |0xBC92C4B04B43E102|
|1868   |0x7FDF24E50451EDE5|
|1737   |0x05CD36A082654514|
|1604   |0x130C1C99206E5D84|
|1493   |0x17F107392C2BF056|
|1365   |0x8B8D1CEBA80E6B77|
|1290   |0x6E84AEA23E75B751|
|1180   |0x50660034C16697DC|
|1103   |0x215F9EDB753B40D5|
|1011   |0xF444169F4A47AD24|
|944    |0xF88F16FD02391556|
|877    |0x1BECB532D62605C2|
|791    |0xFDB11437FF79A678|
|757    |0xD728E42852AE3D6E|
|678    |0x0E4DFA1A11FD6E27|
|617    |0xF3225131A596FA4E|
|573    |0x8A0F244B7BEAC4AC|
|505    |0xC1BE22F30A1CE5EB|
|463    |0xCDDC46B5A3EA0110|
|393    |0x898EE3A09E62E169|
|372    |0x26D5FEF1E670ED45|
|350    |0xC228A449B4DE49C8|
|323    |0xEF0D582CBF2D9B0F|
|joaat  |0xFC13CE80        |