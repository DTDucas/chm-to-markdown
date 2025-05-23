# GetCircuitNamingSchemeSettings Method (2023)

﻿
 Code: All Code: Multiple Code: C# Code: Visual Basic Code: Visual C++   
---  
C#Visual BasicVisual C++
Revit 2023 API  
---  
CircuitNamingSchemeSettings..::..GetCircuitNamingSchemeSettings Method   
[CircuitNamingSchemeSettings Class](60f49706-88f3-d2fb-0732-b1536c6e2e82.md "CircuitNamingSchemeSettings Class") See Also  
---  
Gets the circuit naming scheme settings of the project. 
**Namespace:** [Autodesk.Revit.DB.Electrical](212a1314-7843-2c6c-3322-363127e4059f.md "Autodesk.Revit.DB.Electrical Namespace")**Assembly:** RevitAPI (in RevitAPI.dll) Version: 23.0.0.0 (23.1.0.0)**Since:** 2021 
# Syntax
C#  
---  
```text
public static CircuitNamingSchemeSettings GetCircuitNamingSchemeSettings(
	Document cda
)
```
  
Visual Basic  
---  
```text
Public Shared Function GetCircuitNamingSchemeSettings ( _
	cda As Document _
) As CircuitNamingSchemeSettings
```
  
Visual C++  
---  
```text
public:
static CircuitNamingSchemeSettings^ GetCircuitNamingSchemeSettings(
	Document^ cda
)
```
  
# ### Parameters
cda
    Type: [Autodesk.Revit.DB..::..Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md "Document Class") The document. 
# ### Return Value
The circuit naming scheme settings of the project. 
# Exceptions
| Exception | Condition |
| --- | --- |
| --- | --- |
| [Autodesk.Revit.Exceptions..::..ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md "ArgumentNullException Class") | A non-optional argument was null |

# See Also
[CircuitNamingSchemeSettings Class](60f49706-88f3-d2fb-0732-b1536c6e2e82.md "CircuitNamingSchemeSettings Class")
[Autodesk.Revit.DB.Electrical Namespace](212a1314-7843-2c6c-3322-363127e4059f.md "Autodesk.Revit.DB.Electrical Namespace")
Send comments on this topic to 