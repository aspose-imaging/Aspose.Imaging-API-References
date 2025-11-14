---
title: AutoMaskingArgs Class
type: docs
weight: 20
url: /python-net/aspose.imaging.masking.options/automaskingargs/
---

**Summary:** Represents the arguments that are specified for automated masking methods

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.AutoMaskingArgs

**Inheritance:** IMaskingArgs

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [AutoMaskingArgs()](#AutoMaskingArgs__1) | Initializes a new instance of the AutoMaskingArgs class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| max_iteration_number | int | r/w | Gets or sets the maximum number of iterations. |
| number_of_objects | int | r/w | Gets or sets the number of objects<br/>            to separate initial image to (optional), default value is 2 (object and background). |
| objects_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | Gets or sets the points that belong to separated objects (optional)<br/>            NumberOfObjects coordinates that belong to NumberOfObjects objects of initial image.<br/>            This parameter is used to increase segmentation method precision. |
| objects_rectangles | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Gets or sets the objects rectangles that belong to separated objects (optional).<br/>            This parameter is used to increase segmentation method precision. |
| orphaned_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Gets or sets the points that no longer belong to any object (optional).<br/>            This parameter is used only in case of re-segmentation. |
| precision | float | r/w | Gets or sets the precision of segmentation method (optional). |


### Constructor: AutoMaskingArgs() {#AutoMaskingArgs__1}


```
 AutoMaskingArgs() 
```

Initializes a new instance of the AutoMaskingArgs class

