# HUD::GET_MENU_LAYOUT_CHANGED_EVENT_DETAILS

## Summary
Passes the details of the layout changed event - must only be called once, and only when HAS_MENU_LAYOUT_CHANGED_EVENT_OCCURRED returns true

## Parameters
* **FRONTEND_MENU_SCREEN\*** previousId
* **FRONTEND_MENU_SCREEN\*** nextId
* **INT\*** menu

## Notes
<!-- AUTOGENERATED: Remove this line before editing -->
lastItemMenuId: this is the menuID of the last selected item minus 1000 (lastItem.menuID - 1000)
selectedItemMenuId: same as lastItemMenuId except for the currently selected menu item
selectedItemUniqueId: this is uniqueID of the currently selected menu item

when the pausemenu is closed:
lastItemMenuId = -1
selectedItemMenuId = -1
selectedItemUniqueId = 0

when the header gains focus:
lastItemMenuId updates as normal or 0 if the pausemenu was just opened
selectedItemMenuId becomes a unique id for the pausemenu page that focus was taken from (?) or 0 if the pausemenu was just opened
selectedItemUniqueId = -1

when focus is moved from the header to a pausemenu page:
lastItemMenuId becomes a unique id for the pausemenu page that focus was moved to (?)
selectedItemMenuId = -1
selectedItemUniqueId updates as normal

## Hashes
<!-- AUTOGENERATED: Do not change -->
|Version|Hash              |
|-------|------------------|
|2944   |0xE869B507D3624306|
|2845   |0xE869B507D3624306|
|2824   |0xE869B507D3624306|
|2802   |0xE75795DF9BF99E2E|
|2699   |0xA981C26F706D5ECF|
|2612   |0xA981C26F706D5ECF|
|2545   |0xA981C26F706D5ECF|
|2372   |0x0AEF9B8AE42AA0CC|
|2189   |0x93B7A49D3402A3D8|
|2060   |0x3BD0DFBDFB3F80EC|
|1868   |0x9B722346D238F440|
|1737   |0xA883D79CD1311DFE|
|1604   |0x348C6A3C218D5AF0|
|1493   |0x59460F5419193EFE|
|1365   |0x40DB21BFB2DA4FA1|
|1290   |0x671BD1855CD3F2E2|
|1180   |0xEBD809CDD59CFED0|
|1103   |0x1E4A69055467EEBF|
|1011   |0xA6AE0FB06ABB77D8|
|944    |0xD024C05E8C94E046|
|877    |0xAABAF601DBFAD3B3|
|791    |0x44EC9A123D2A8DEA|
|757    |0x35BFD0A3F7CAD931|
|678    |0x19AF48D653E52196|
|617    |0xEBF8A1185831211E|
|573    |0x2A9654D331EC2E10|
|505    |0x9F73A284AA03E619|
|463    |0xD56EE95C189883AE|
|393    |0xD17C177380D8F252|
|372    |0x0733C871E158FFF3|
|350    |0x5F93BED9D86A6FD4|
|323    |0x7E17BE53E1AAABAF|
|joaat  |0x6025AA2F        |