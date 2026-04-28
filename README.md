#A 2D FGV (Functional Global Variable) 

This can be used as signalling or changing the states of booleans or state of a device
You can add any states (up to 31) in the TypeDef and an array of strings will be created at initialization.
To use instead of Globals in Labview (typically, I use it for LED indicators to see the state of some processes, and read the init or error state of devices).
