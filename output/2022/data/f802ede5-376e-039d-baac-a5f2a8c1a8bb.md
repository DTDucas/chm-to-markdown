# AssignedLossCoefficient Property (2022)

﻿
 Code: All Code: Multiple Code: C# Code: Visual Basic Code: Visual C++   
---  
C#Visual BasicVisual C++
Revit 2022 API  
---  
Connector..::..AssignedLossCoefficient Property   
[Connector Class](11e07082-b3f2-26a1-de79-16535f44716c.md "Connector Class") See Also  
---  
The assigned loss coefficient of the connector.
**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md "Autodesk.Revit.DB Namespace")**Assembly:** RevitAPI (in RevitAPI.dll) Version: 22.0.0.0 (22.1.0.0)
# Syntax
C#  
---  
```text
public double AssignedLossCoefficient { get; set; }
```
  
Visual Basic  
---  
```text
Public Property AssignedLossCoefficient As Double
	Get
	Set
```
  
Visual C++  
---  
```text
public:
property double AssignedLossCoefficient {
	double get ();
	void set (double value);
}
```
  
# Remarks
Assigned loss coefficient may be assigned for connectors of some family instances, for more information. In order to set this property, it must be mapped to a writable instance parameter in the family definition.
# Exceptions
| Exception | Condition |
| --- | --- |
| --- | --- |
| [Autodesk.Revit.Exceptions..::..InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md "InvalidOperationException Class") | Thrown when the connector's domain is not DomainHvac. Thrown when the connector is not in a family instance. |
| [Autodesk.Revit.Exceptions..::..ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md "ArgumentException Class") | Thrown when set an invalid value. |
| [Autodesk.Revit.Exceptions..::..InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md "InvalidOperationException Class") | Thrown on failure to get or set assigned loss coefficient. |

# See Also
[Connector Class](11e07082-b3f2-26a1-de79-16535f44716c.md "Connector Class")
[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md "Autodesk.Revit.DB Namespace")
Send comments on this topic to 