---
title: AutoMaskingGraphCutOptions Class
type: docs
weight: 30
url: /python-net/aspose.imaging.masking.options/automaskinggraphcutoptions/
---

The GraphCut auto masking options.

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.AutoMaskingGraphCutOptions

**Inheritance:** GraphCutMaskingOptions

**Aspose.Imaging Version:** 23.6

The AutoMaskingGraphCutOptions type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions__0) | Initializes a new instance of the [AutoMaskingGraphCutOptions](/imaging/python-net/aspose.imaging.masking.options/automaskinggraphcutoptions/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| method | [SegmentationMethod](/imaging/python-net/aspose.imaging.masking.options/segmentationmethod) | r/w | Gets or sets the segmentation method. |
| args | [IMaskingArgs](/imaging/python-net/aspose.imaging.masking.options/imaskingargs) | r/w | Gets or sets the arguments for segmentation algorithm. |
| export_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | r/w | Gets or sets the image export options. |
| masking_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r/w | Gets or sets the masking area. |
| decompose | bool | r/w | Gets or sets a value indicating whether<br/>            needless to separate each Shape from mask as individual object or as united object from mask separated from background. |
| background_replacement_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets the background replacement color. |
| BACKGROUND_OBJECT_NUMBER [static] | int | r | The background object number |
| feathering_radius | int | r/w | Gets or sets the feathering radius. |
| default_foreground_strokes | [Point[]](/imaging/python-net/aspose.imaging/point) | r | Gets the pre-calculated default foreground strokes. |
| default_background_strokes | [Point[]](/imaging/python-net/aspose.imaging/point) | r | Gets the default background strokes. |
| default_objects_rectangles | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle) | r | Gets the default objects rectangles. |
| assumed_objects | System.Collections.Generic.List<AssumedObjectData> | r/w | Gets or sets the assumed objects. |
| calculate_default_strokes | bool | r/w | Gets or sets a value indicating whether default strokes should be calculated. |

### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions__0}


```
 AutoMaskingGraphCutOptions() 
```

Initializes a new instance of the [AutoMaskingGraphCutOptions](/imaging/python-net/aspose.imaging.masking.options/automaskinggraphcutoptions/) class.

