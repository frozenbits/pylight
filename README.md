# pylight
A home project to control my Yeelight lamp.

# How to use:
Modify the IP in the "if \_\_name__ == "\_\_main__"" block.<br />
After that, you can call it from the commandline. <br />
The default action will only turn it on or off.
```
python pylight.py
```

To use the more advanced options, use the -m parameter
```
python pylight.py -m
```

The available options are:

    1: "Turn on",
    2: "Turn off",
    3: "Toggle power",
    4: "Set brightness",
    5: "Set RGB value",
    6: "Set HSV value",
    7: "Set color temperature",
    8: "Select preset",
    9: "Change lamp",
    10: "Get lamp properties",
    0: "Exit",
