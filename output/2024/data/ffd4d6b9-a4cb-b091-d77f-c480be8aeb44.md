# TemperatureLossFactor Property (2024)

﻿
 Code: All Code: Multiple Code: C# Code: Visual Basic Code: Visual C++   
---  
C#Visual BasicVisual C++
Revit 2024 API  
---  
AdvancedLossFactor..::..TemperatureLossFactor Property   
[AdvancedLossFactor Class](30e62a9d-eb01-8830-f897-dc8f32b486da.md "AdvancedLossFactor Class") See Also  
---  
The temperature loss factor. 
**Namespace:** [Autodesk.Revit.DB.Lighting](a6a04f07-7fd2-0a4e-12e7-01842ee6daaf.md "Autodesk.Revit.DB.Lighting Namespace")**Assembly:** RevitAPI (in RevitAPI.dll) Version: 24.0.0.0 (24.0.0.0)**Since:** 2013 
# Syntax
C#  
---  
```text
public double TemperatureLossFactor { get; set; }
```
  
Visual Basic  
---  
```text
Public Property TemperatureLossFactor As Double
	Get
	Set
```
  
Visual C++  
---  
```text
public:
property double TemperatureLossFactor {
	double get ();
	void set (double value);
}
```
  
# ### Field Value
The loss factor as a numerical value between 0.0 and 2.0 
# Exceptions
| Exception | Condition |
| --- | --- |
| --- | --- |
| [Autodesk.Revit.Exceptions..::..ArgumentOutOfRangeException](60f148c9-ece0-a6bb-4e12-bb4a9c8c8a24.md "ArgumentOutOfRangeException Class") | When setting this property: The loss factor is not valid because it is not between 0.0 and 2.0. |

# See Also
[AdvancedLossFactor Class](30e62a9d-eb01-8830-f897-dc8f32b486da.md "AdvancedLossFactor Class")
[Autodesk.Revit.DB.Lighting Namespace](a6a04f07-7fd2-0a4e-12e7-01842ee6daaf.md "Autodesk.Revit.DB.Lighting Namespace")
Send comments on this topic to 