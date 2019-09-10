# Here can paste usefull VEX code?

## Incremental Save
Create ShelfTool and insert:

curfile = hou.hipFile.basename()
hou.hipFile.saveAndIncrementFileName()
 
