# BodyConnectorId Property (2022)

﻿
 Code: All Code: Multiple Code: C# Code: Visual Basic Code: Visual C++   
---  
C#Visual BasicVisual C++
Revit 2022 API  
---  
FabricationConnectorInfo..::..BodyConnectorId Property   
[FabricationConnectorInfo Class](5da97d87-a3f6-f239-3c5c-102d2d82f942.md "FabricationConnectorInfo Class") See Also  
---  
Fabrication body connector Id. 
**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md "Autodesk.Revit.DB Namespace")**Assembly:** RevitAPI (in RevitAPI.dll) Version: 22.0.0.0 (22.1.0.0)**Since:** 2016 
# Syntax
C#  
---  
```text
public int BodyConnectorId { get; set; }
```
  
Visual Basic  
---  
```text
Public Property BodyConnectorId As Integer
	Get
	Set
```
  
Visual C++  
---  
```text
public:
property int BodyConnectorId {
	int get ();
	void set (int value);
}
```
  
# Remarks
A reference to the fabrication configuration connectors. Setting the connector value will also set the connector lock. A value of 0 indicates the connector is set to none. 
# Exceptions
| Exception | Condition |
| --- | --- |
| --- | --- |
| [Autodesk.Revit.Exceptions..::..ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md "ArgumentException Class") | When setting this property: bodyConnectorId is invalid based on the shape and domain. |
| [Autodesk.Revit.Exceptions..::..InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md "InvalidOperationException Class") | When setting this property: the connector cannot be modified on an owned fabrication part. -or- When setting this property: the connector is already connected. -or- When setting this property: the fabrication part is connected to more than one item. |

# See Also
[FabricationConnectorInfo Class](5da97d87-a3f6-f239-3c5c-102d2d82f942.md "FabricationConnectorInfo Class")
[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md "Autodesk.Revit.DB Namespace")
Send comments on this topic to 