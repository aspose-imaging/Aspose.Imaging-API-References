---
title: MagicWandSettings Class
type: docs
weight: 90
url: /python-net/aspose.imaging.magicwand/magicwandsettings/
---

**Summary:** A magic wand selection settings class.

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.MagicWandSettings

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MagicWandSettings(point)](#MagicWandSettings_point_1) | Initializes a new instance of the [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) class. |
| [MagicWandSettings(x, y)](#MagicWandSettings_x_y_2) | Initializes a new instance of the [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| area_of_interest | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Gets or sets the bounds of the area for algorithm work. |
| color_compare_mode | [ColorComparisonMode](/imaging/python-net/aspose.imaging.magicwand/colorcomparisonmode/) | r/w | Gets or sets the algorithm how colors are compared. |
| contiguous_mode | bool | r/w | Gets or sets a value indicating whether magic wand will define only contiguous pixels. |
| directional_mode | [FloodFillDirectionalMode](/imaging/python-net/aspose.imaging.magicwand/floodfilldirectionalmode/) | r/w | Gets or sets the mode of flood fill search algorithm: four of eight direction search. |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | r | Gets or sets the reference point for algorithm work. |
| threshold | int | r/w | Gets or sets the tolerance level for pixels color comparison. |


### Constructor: MagicWandSettings(point) {#MagicWandSettings_point_1}


```
 MagicWandSettings(point) 
```

Initializes a new instance of the [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| point | [Point](/imaging/python-net/aspose.imaging/point/) | The reference point. |

### Constructor: MagicWandSettings(x, y) {#MagicWandSettings_x_y_2}


```
 MagicWandSettings(x, y) 
```

Initializes a new instance of the [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the reference point. |
| y | int | The y-coordinate of the reference point. |

