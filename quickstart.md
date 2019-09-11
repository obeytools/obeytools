# Quick start

Just place your .hda files into /Documents/houdiniXX.X/otls
where XX.X - is your current Houdini version.  

Or, place anywhere you want on drive (for example: "C:\obeyTools"), and define this path as variable in houdini.env  

```
oTools="C:\obeyTools"
```

and put this variable into $HOUDINI_PATH

```
HOUDINI_PATH = $HOUDINI_PATH;$oTools;&
```

All hail Hydra and Obey