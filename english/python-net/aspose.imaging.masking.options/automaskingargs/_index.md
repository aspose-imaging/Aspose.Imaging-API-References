---
title: AutoMaskingArgs Class
type: docs
weight: 20
url: /python-net/aspose.imaging.masking.options/automaskingargs/
---

Represents the arguments that are specified for automated masking methods

**Namespace:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Class Name:** aspose.imaging.masking.options.AutoMaskingArgs

**Assembly:**  Aspose.Imaging Version: 23.5.6

The AutoMaskingArgs type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|AutoMaskingArgs()|Initializes a new instance of the AutoMaskingArgs class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|number_of_objects|Gets or sets the number of objects<br/>            to separate initial image to (optional), default value is 2 (object and background).|
|objects_rectangles|Gets or sets the objects rectangles that belong to separated objects (optional).<br/>            This parameter is used to increase segmentation method precision.|
|objects_points|Gets or sets the points that belong to separated objects (optional)<br/>            NumberOfObjects coordinates that belong to NumberOfObjects objects of initial image.<br/>            This parameter is used to increase segmentation method precision.|
|orphaned_points|Gets or sets the points that no longer belong to any object (optional).<br/>            This parameter is used only in case of re-segmentation.|
|precision|Gets or sets the precision of segmentation method (optional).|
|max_iteration_number|Gets or sets the maximum number of iterations.|
