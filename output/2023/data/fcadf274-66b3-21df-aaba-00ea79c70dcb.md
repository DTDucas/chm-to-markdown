# CreateParts Method (Document, ICollection(LinkElementId)) (2023)

﻿
 Code: All Code: Multiple Code: C# Code: Visual Basic Code: Visual C++   
---  
C#Visual BasicVisual C++
Revit 2023 API  
---  
PartUtils..::..CreateParts Method (Document, ICollection<(Of <(<'LinkElementId>)>)>)  
[PartUtils Class](a7384ccf-cd2b-9080-38d3-58b1253cd8e4.md "PartUtils Class") See Also  
---  
Creates a new set of parts out of the original elements. 
**Namespace:** [Autodesk.Revit.DB](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md "Autodesk.Revit.DB Namespace")**Assembly:** RevitAPI (in RevitAPI.dll) Version: 23.0.0.0 (23.1.0.0)**Since:** 2013 
# Syntax
C#  
---  
```text
public static void CreateParts(
	Document document,
	ICollection<LinkElementId> hostOrLinkElementIds
)
```
  
Visual Basic  
---  
```text
Public Shared Sub CreateParts ( _
	document As Document, _
	hostOrLinkElementIds As ICollection(Of LinkElementId) _
)
```
  
Visual C++  
---  
```text
public:
static void CreateParts(
	Document^ document, 
	ICollection<LinkElementId^>^ hostOrLinkElementIds
)
```
  
# ### Parameters
document
    Type: [Autodesk.Revit.DB..::..Document](db03274b-a107-aa32-9034-f3e0df4bb1ec.md "Document Class") The document containing the elements. 
hostOrLinkElementIds
    Type: System.Collections.Generic..::..ICollection<(Of <(<'[LinkElementId](6e18abde-8787-9906-8576-ab0c9c5432c6.md "LinkElementId Class")>)>)> The elements that parts will be created from. 
# Remarks
Parts will be added to the model after regeneration. To get the ids of the parts created by this method use PartUtils.GetAssociatedParts() with the contents of hostOrLinkElementIds. 
# Exceptions
| Exception | Condition |
| --- | --- |
| --- | --- |
| [Autodesk.Revit.Exceptions..::..ArgumentException](2e6e4206-97a8-dd4b-df5d-4269f4bb6088.md "ArgumentException Class") | One or more element ids was not permitted for creating parts. HostOrLinkElements should be of a valid category and the ids should be valid and should not already be divided into parts. |
| [Autodesk.Revit.Exceptions..::..ArgumentNullException](631e1424-60f4-929b-4e52-dda9dcd26316.md "ArgumentNullException Class") | A non-optional argument was null |
| [Autodesk.Revit.Exceptions..::..InvalidOperationException](9e715f03-3884-e539-4dd6-8d7545733adc.md "InvalidOperationException Class") | The document is in failure mode: an operation has failed, and Revit requires the user to either cancel the operation or fix the problem (usually by deleting certain elements). |
| [Autodesk.Revit.Exceptions..::..ModificationForbiddenException](53205486-5917-7c33-8e67-e362106ddc97.md "ModificationForbiddenException Class") | The document is in failure mode: an operation has failed, and Revit requires the user to either cancel the operation or fix the problem (usually by deleting certain elements). -or- The document is being loaded, or is in the midst of another sensitive process. |
| [Autodesk.Revit.Exceptions..::..ModificationOutsideTransactionException](8f025460-c283-ea99-aa8a-5a36e11528f4.md "ModificationOutsideTransactionException Class") | The document has no open transaction. |

# See Also
[PartUtils Class](a7384ccf-cd2b-9080-38d3-58b1253cd8e4.md "PartUtils Class")
[CreateParts Overload](7d85355b-ef4a-6c00-a2fe-01e6f5a7c4cb.md "CreateParts Method")
[Autodesk.Revit.DB Namespace](87546ba7-461b-c646-cbb1-2cb8f5bff8b2.md "Autodesk.Revit.DB Namespace")
Send comments on this topic to 