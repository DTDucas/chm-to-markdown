# CreateNotEndsWithRule Method (ElementId, String) (2024)

﻿
 Code: All Code: Multiple Code: C# Code: Visual Basic Code: Visual C++   
---  
C#Visual BasicVisual C++
Revit 2024 API  
---  
ParameterFilterRuleFactory..::..CreateNotEndsWithRule Method (ElementId, String)  
[ParameterFilterRuleFactory Class](317755a4-24ba-9f36-7639-f6fb2aa5a1a7.md "ParameterFilterRuleFactory Class") See Also  
---  
Creates a filter rule that determines whether strings from the document do not end with a certain string value. 
**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md "Autodesk.Revit.DB Namespace")**Assembly:** RevitAPI (in RevitAPI.dll) Version: 24.0.0.0 (24.0.0.0)**Since:** 2023 
# Syntax
C#  
---  
```text
public static FilterRule CreateNotEndsWithRule(
	ElementId parameter,
	string value
)
```
  
Visual Basic  
---  
```text
Public Shared Function CreateNotEndsWithRule ( _
	parameter As ElementId, _
	value As String _
) As FilterRule
```
  
Visual C++  
---  
```text
public:
static FilterRule^ CreateNotEndsWithRule(
	ElementId^ parameter, 
	String^ value
)
```
  
# ### Parameters
parameter
    Type: [Autodesk.Revit.DB..::..ElementId](44f3f7b1-3229-3404-93c9-dc5e70337dd6.md "ElementId Class") A string-typed parameter used to get values from the document for a given element. 
value
    Type: System..::..String The user-supplied string value for which values from the document will be searched. 
# ### Return Value
Created filter rule object. 
# Exceptions
| Exception | Condition |
| --- | --- |
| --- | --- |
| [Autodesk.Revit.Exceptions..::..ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md "ArgumentNullException Class") | A non-optional argument was null |

# See Also
[ParameterFilterRuleFactory Class](317755a4-24ba-9f36-7639-f6fb2aa5a1a7.md "ParameterFilterRuleFactory Class")
[CreateNotEndsWithRule Overload](bf313835-139c-f9b2-457b-640a0e115813.md "CreateNotEndsWithRule Method")
[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md "Autodesk.Revit.DB Namespace")
Send comments on this topic to 