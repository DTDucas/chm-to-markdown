# Contains Method (2022)

﻿
 Code: All Code: Multiple Code: C# Code: Visual Basic Code: Visual C++   
---  
C#Visual BasicVisual C++
Revit 2022 API  
---  
TemperatureRatingTypeSet..::..Contains Method   
[TemperatureRatingTypeSet Class](572d809d-fc08-6038-5279-b43903e9a6b8.md "TemperatureRatingTypeSet Class") See Also  
---  
Tests for the existence of a TemperatureRating type within the set.
**Namespace:** [Autodesk.Revit.DB.Electrical](212a1314-7843-2c6c-3322-363127e4059f.md "Autodesk.Revit.DB.Electrical Namespace")**Assembly:** RevitAPI (in RevitAPI.dll) Version: 22.0.0.0 (22.1.0.0)
# Syntax
C#  
---  
```text
public virtual bool Contains(
	TemperatureRatingType item
)
```
  
Visual Basic  
---  
```text
Public Overridable Function Contains ( _
	item As TemperatureRatingType _
) As Boolean
```
  
Visual C++  
---  
```text
public:
virtual bool Contains(
	TemperatureRatingType^ item
)
```
  
# ### Parameters
item
    Type: [Autodesk.Revit.DB.Electrical..::..TemperatureRatingType](fe7e15d7-c31f-b24c-992f-332e54e9a5ba.md "TemperatureRatingType Class")The TemperatureRating type to be searched for.
# ### Return Value
The Contains method returns True if the TemperatureRating type is within the set, otherwise False.
# See Also
[TemperatureRatingTypeSet Class](572d809d-fc08-6038-5279-b43903e9a6b8.md "TemperatureRatingTypeSet Class")
[Autodesk.Revit.DB.Electrical Namespace](212a1314-7843-2c6c-3322-363127e4059f.md "Autodesk.Revit.DB.Electrical Namespace")
Send comments on this topic to 