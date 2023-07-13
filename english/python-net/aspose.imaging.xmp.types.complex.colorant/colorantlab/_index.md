---
title: ColorantLab Class
type: docs
weight: 30
url: /python-net/aspose.imaging.xmp.types.complex.colorant/colorantlab/
---

Represents LAB Colorant.

**Module:** [aspose.imaging.xmp.types.complex.colorant](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/)

**Full Name:** aspose.imaging.xmp.types.complex.colorant.ColorantLab

**Inheritance:** IXmpType, ColorantBase

**Aspose.Imaging Version:** 23.6

The ColorantLab type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [ColorantLab()](#ColorantLab__0) | Initializes a new instance of the [ColorantLab](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantlab/) class. |
| [ColorantLab(a, b, l)](#ColorantLab_a_b_l_1) | Initializes a new instance of the [ColorantLab](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantlab/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| prefix | string | r | Gets the prefix. |
| namespace_uri | string | r | Gets the default namespace URI. |
| mode | [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode) | r | Gets [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/). |
| swatch_name | string | r/w | Gets or sets the name of the swatch. |
| color_type | [ColorType](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colortype) | r/w | Gets or sets the type of the color. |
| a | int | r/w | Gets or sets the A component. |
| b | int | r/w | Gets or sets the B component. |
| l | float | r/w | Gets or sets the L component. |
| MIN_A [static] | int | r | The minimum A component value |
| MAX_A [static] | int | r | The maximum A component value |
| MIN_B [static] | int | r | The minimum B component value |
| MAX_B [static] | int | r | The maximum A component value |
| MIN_L [static] | float | r | The minimum L component value |
| MAX_L [static] | float | r | The maximum A component value |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_xmp_representation()](#get_xmp_representation__2) | Gets the string contained value in XMP format. |

### ColorantLab() {#ColorantLab__0}


```
 ColorantLab() 
```

Initializes a new instance of the [ColorantLab](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantlab/) class.

### ColorantLab(a, b, l) {#ColorantLab_a_b_l_1}


```
 ColorantLab(a, b, l) 
```

Initializes a new instance of the [ColorantLab](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantlab/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| a | int | A component. |
| b | int | B component. |
| l | float | L component. |

### get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

Gets the string contained value in XMP format.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the string contained value in XMP format. |


