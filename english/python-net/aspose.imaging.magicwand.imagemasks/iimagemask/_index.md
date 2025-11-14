---
title: IImageMask Class
type: docs
weight: 40
url: /python-net/aspose.imaging.magicwand.imagemasks/iimagemask/
---

**Summary:** Describes a mask.

**Module:** [aspose.imaging.magicwand.imagemasks](/imaging/python-net/aspose.imaging.magicwand.imagemasks/)

**Full Name:** aspose.imaging.magicwand.imagemasks.IImageMask

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Gets the bounds, in pixels, of this mask. |
| height | int | r | Gets the height, in pixels, of this mask. |
| selection_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Gets the bounds of the selected part of the mask, in pixels. |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | r | Gets the source image used to create this mask, if exists. |
| width | int | r | Gets the width, in pixels, of this mask. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Creates a new object that is a copy of the current instance. |
| [get_byte_opacity(x, y)](#get_byte_opacity_x_y_2) | Gets the opacity of the specified pixel with byte precision. |
| [is_opaque(x, y)](#is_opaque_x_y_3) | Checks if the specified pixel is opaque. |
| [is_transparent(x, y)](#is_transparent_x_y_4) | Checks if the specified pixel is transparent. |


### Method: clone() {#clone__1}


```
 clone() 
```

Creates a new object that is a copy of the current instance.

**Returns**

| Type | Description |
| :- | :- |
| System.Object |  |


### Method: get_byte_opacity(x, y) {#get_byte_opacity_x_y_2}


```
 get_byte_opacity(x, y) 
```

Gets the opacity of the specified pixel with byte precision.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | Byte value, representing the opacity of the specified pixel. |


### Method: is_opaque(x, y) {#is_opaque_x_y_3}


```
 is_opaque(x, y) 
```

Checks if the specified pixel is opaque.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true if the specified pixel is opaque; otherwise, false. |


### Method: is_transparent(x, y) {#is_transparent_x_y_4}


```
 is_transparent(x, y) 
```

Checks if the specified pixel is transparent.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| x | int | The x-coordinate of the pixel. |
| y | int | The y-coordinate of the pixel. |

**Returns**

| Type | Description |
| :- | :- |
| bool | true if the specified pixel is transparent; otherwise, false. |


