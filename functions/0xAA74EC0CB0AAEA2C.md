# PED::RESET_PED_MOVEMENT_CLIPSET

## Parameters
* **PED_INDEX** ped
* **FLOAT** blendDuration = 0.25

## Notes
<!-- AUTOGENERATED: Remove this line before editing -->
Resets the movement clipset to the default for the ped type.
The default movement clipset is defined in peds.meta under <MovementClipSet>
DON'T FORGET to unstream the clipset if no longer needed

If p1 is 0.0, I believe you are back to normal.
If p1 is 1.0, it looks like you can only rotate the ped, not walk.

Using the following code to reset back to normal
PED::RESET_PED_MOVEMENT_CLIPSET(PLAYER::PLAYER_PED_ID(), 0.0);

## Hashes
<!-- AUTOGENERATED: Do not change -->
|Version|Hash              |
|-------|------------------|
|2944   |0x4A46A67DB6AC487D|
|2845   |0x4A46A67DB6AC487D|
|2824   |0x4A46A67DB6AC487D|
|2802   |0xEF514FB2706C4C1B|
|2699   |0x03DD3DA99C7ED7D1|
|2612   |0x03DD3DA99C7ED7D1|
|2545   |0x03DD3DA99C7ED7D1|
|2372   |0x87FB9C4434EDF1A5|
|2189   |0xE18B77DC016551AA|
|2060   |0x76D5D8AF296F50CE|
|1868   |0x2AF3CF45011CC65F|
|1737   |0xEB5F94C785667633|
|1604   |0xE469AA5F14AFD92F|
|1493   |0x7FD552896FDFC9E4|
|1365   |0x75B1352F83860B74|
|1290   |0xE32626D0E44BC8F1|
|1180   |0x32A59EDAE32A8749|
|1103   |0x3851B6B87498EDBF|
|1011   |0xCFEAF108FE47852A|
|944    |0xF0C989F97C26A641|
|877    |0x046314D7B672BA6D|
|791    |0x72EBC579C3BEB645|
|757    |0x138F835BA3602081|
|678    |0x31D56B8BF9715256|
|617    |0x1903C6D8991C1CC2|
|573    |0xC456353A87F0538B|
|505    |0x2288F0F0680B6992|
|463    |0xBD489EEEE752CD58|
|393    |0x92C730EF01FAE94A|
|372    |0x4F94F6F61C24F87C|
|350    |0x708A5EFEB2660CE4|
|323    |0xAA74EC0CB0AAEA2C|
|joaat  |0xB83CEE93        |