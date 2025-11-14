---
title: ColorantCmyk Class
type: docs
weight: 20
url: /python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/
---

**Summary:** Represents CMYK Colorant.

**Module:** [aspose.imaging.xmp.types.complex.colorant](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/)

**Full Name:** aspose.imaging.xmp.types.complex.colorant.ColorantCmyk

**Inheritance:** IXmpType, ColorantBase

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ColorantCmyk()](#ColorantCmyk__1) | Initializes a new instance of the [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/) class. |
| [ColorantCmyk(black, cyan, magenta, yellow)](#ColorantCmyk_black_cyan_magenta_yellow_2) | Initializes a new instance of the [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| COLOR_VALUE_MAX [static] | float | r | Color max value in CMYK colorant. |
| COLOR_VALUE_MIN [static] | float | r | Color min value in CMYK colorant. |
| black | float | r/w | Gets or sets the black component value. |
| color_type | [ColorType](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colortype/) | r/w | Gets or sets the type of the color. |
| cyan | float | r/w | Gets or sets the cyan component value. |
| magenta | float | r/w | Gets or sets the magenta component value. |
| mode | [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/) | r | Gets [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/). |
| namespace_uri | string | r | Gets the default namespace URI. |
| prefix | string | r | Gets the prefix. |
| swatch_name | string | r/w | Gets or sets the name of the swatch. |
| yellow | float | r/w | Gets or sets the yellow component value. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clones this instance. |
| [get_xmp_representation()](#get_xmp_representation__2) | Gets the string contained value in XMP format. |


### Constructor: ColorantCmyk() {#ColorantCmyk__1}


```
 ColorantCmyk() 
```

Initializes a new instance of the [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/) class.

### Constructor: ColorantCmyk(black, cyan, magenta, yellow) {#ColorantCmyk_black_cyan_magenta_yellow_2}


```
 ColorantCmyk(black, cyan, magenta, yellow) 
```

Initializes a new instance of the [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| black | float | The black component value. |
| cyan | float | The cyan color component value. |
| magenta | float | The magenta component value. |
| yellow | float | The yellow component value. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clones this instance.

**Returns**

| Type | Description |
| :- | :- |
| System.Object | A memberwise clone. |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

Gets the string contained value in XMP format.

**Returns**

| Type | Description |
| :- | :- |
| string | Returns the string contained value in XMP format. |


