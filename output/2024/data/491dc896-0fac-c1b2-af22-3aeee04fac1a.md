# IsValidObject Property (2024)

﻿
 Code: All Code: Multiple Code: C# Code: Visual Basic Code: Visual C++   
---  
C#Visual BasicVisual C++
Revit 2024 API  
---  
RebarFreeFormAccessor..::..IsValidObject Property   
[RebarFreeFormAccessor Class](bf146aa3-f780-646e-c3cd-42e7a61d18e6.md "RebarFreeFormAccessor Class") See Also  
---  
Specifies whether the .NET object represents a valid Revit entity. 
**Namespace:** [Autodesk.Revit.DB.Structure](d586b341-f687-9d90-e96d-255806b7d4fc.md "Autodesk.Revit.DB.Structure Namespace")**Assembly:** RevitAPI (in RevitAPI.dll) Version: 24.0.0.0 (24.0.0.0)**Since:** 2014 
# Syntax
C#  
---  
```text
public bool IsValidObject { get; }
```
  
Visual Basic  
---  
```text
Public ReadOnly Property IsValidObject As Boolean
	Get
```
  
Visual C++  
---  
```text
public:
property bool IsValidObject {
	bool get ();
}
```
  
# ### Return Value
True if the API object holds a valid Revit native object, false otherwise. 
# Remarks
If the corresponding Revit native object is destroyed, or creation of the corresponding object is undone, a managed API object containing it is no longer valid. API methods cannot be called on invalidated wrapper objects. 
# See Also
[RebarFreeFormAccessor Class](bf146aa3-f780-646e-c3cd-42e7a61d18e6.md "RebarFreeFormAccessor Class")
[Autodesk.Revit.DB.Structure Namespace](d586b341-f687-9d90-e96d-255806b7d4fc.md "Autodesk.Revit.DB.Structure Namespace")
Send comments on this topic to 