---
<<<<<<< HEAD
title: StartUpPosition Property
=======
title: StartUpPosition property
>>>>>>> master
keywords: vblr6.chm1100523
f1_keywords:
- vblr6.chm1100523
ms.prod: office
api_name:
- Office.StartUpPosition
ms.assetid: 0ceb1e6d-b45e-a1df-03df-fd73ce814a79
<<<<<<< HEAD
ms.date: 06/08/2017
---


# StartUpPosition Property



Returns or sets a value specifying the position of a  **UserForm** when it first appears.
You can use one of four settings for  **StartUpPosition**:
=======
ms.date: 08/24/2018
---


# StartUpPosition property

Returns or sets a value specifying the position of a **UserForm** when it first appears.
You can use one of four settings for **StartUpPosition**:
>>>>>>> master


|**Setting**|**Value**|**Description**|
|:-----|:-----|:-----|
|**Manual**|0|No initial setting specified.|
<<<<<<< HEAD
|**CenterOwner**|1|Center on the item to which the  **UserForm** belongs.|
|**CenterScreen**|2|Center on the whole screen.|
|**WindowsDefault**|3|Position in upper-left corner of screen.|

 **Remarks**
You can set the  **StartUpPosition** property programmatically or from the **Properties** window.

## Example

The following example uses the  **Load** statement and the **Show** method in UserForm1's Click event to load UserForm2 with the **StartUpPosition** property set to 3 (the Windows default position). The **Show** method then makes UserForm2 visible.
=======
|**CenterOwner**|1|Center on the item to which the **UserForm** belongs.|
|**CenterScreen**|2|Center on the whole screen.|
|**WindowsDefault**|3|Position in upper-left corner of screen.|

## Remarks

You can set the **StartUpPosition** property programmatically or from the **Properties** window.

## Example

The following example uses the **Load** statement and the **Show** method in UserForm1's Click event to load UserForm2 with the **StartUpPosition** property set to 3 (the Windows default position). The **Show** method then makes UserForm2 visible.
>>>>>>> master


```vb
Private Sub UserForm_Click()
    Load UserForm2
<<<<<<< HEAD
    UserForm2. StartUpPosition = 3
=======
    UserForm2.StartUpPosition = 3
>>>>>>> master
    UserForm2.Show
End Sub
```

