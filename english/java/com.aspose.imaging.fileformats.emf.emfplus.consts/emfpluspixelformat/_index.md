---
title: EmfPlusPixelFormat
second_title: Aspose.Imaging for Java API Reference
description: The PixelFormat enumeration defines pixel formats that are supported in EMF bitmaps.
type: docs
weight: 43
url: /java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspixelformat/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPixelFormat extends System.Enum
```

The PixelFormat enumeration defines pixel formats that are supported in EMF+ bitmaps.
## Fields

| Field | Description |
| --- | --- |
| [PixelFormatUndefined](#PixelFormatUndefined) | The format is not specified. |
| [PixelFormat1bppIndexed](#PixelFormat1bppIndexed) | The format is monochrome, and a color palette lookup table is used. |
| [PixelFormat4bppIndexed](#PixelFormat4bppIndexed) | The format is 16-color, and a color palette lookup table is used. |
| [PixelFormat8bppIndexed](#PixelFormat8bppIndexed) | The format is 256-color, and a color palette lookup table is used. |
| [PixelFormat16bppGrayScale](#PixelFormat16bppGrayScale) | The format is 16 bits per pixel, grayscale. |
| [PixelFormat16bppRGB555](#PixelFormat16bppRGB555) | The format is 16 bits per pixel; 5 bits each are used for the red, green, and blue components. |
| [PixelFormat16bppRGB565](#PixelFormat16bppRGB565) | The format is 16 bits per pixel; 5 bits are used for the red component, 6 bits for the green component, and 5 bits for the blue component. |
| [PixelFormat16bppARGB1555](#PixelFormat16bppARGB1555) | The format is 16 bits per pixel; 1 bit is used for the alpha component, and 5 bits each are used for the red, green, and blue components. |
| [PixelFormat24bppRGB](#PixelFormat24bppRGB) | The format is 24 bits per pixel; 8 bits each are used for the red, green, and blue components. |
| [PixelFormat32bppRGB](#PixelFormat32bppRGB) | The format is 32 bits per pixel; 8 bits each are used for the red, green, and blue components. |
| [PixelFormat32bppARGB](#PixelFormat32bppARGB) | The format is 32 bits per pixel; 8 bits each are used for the alpha, red, green, and blue components. |
| [PixelFormat32bppPARGB](#PixelFormat32bppPARGB) | The format is 32 bits per pixel; 8 bits each are used for the alpha, red, green, and blue components. |
| [PixelFormat48bppRGB](#PixelFormat48bppRGB) | The format is 48 bits per pixel; 16 bits each are used for the red, green, and blue components. |
| [PixelFormat64bppARGB](#PixelFormat64bppARGB) | The format is 64 bits per pixel; 16 bits each are used for the alpha, red, green, and blue components. |
| [PixelFormat64bppPARGB](#PixelFormat64bppPARGB) | The format is 64 bits per pixel; 16 bits each are used for the alpha, red, green, and blue components. |
### PixelFormatUndefined {#PixelFormatUndefined}
```
public static final int PixelFormatUndefined
```


The format is not specified.

--------------------

Pixel formats are specified by [EmfPlusBitmap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbitmap) objects. They are encoded as follows: - Bits 0-7: Enumeration of the pixel format constants, starting at zero. - Bits 8-15: The total number of bits per pixel. - Bit 16: If set, the color value is indexed into a palette. - Bit 17: If set, the color value is in a GDI-supported format. - Bit 18: If set, the color value has an alpha component. - Bit 19: If set, the color value has a premultiplied alpha component. - Bit 20: If set, extended colors, 16-bits per channel, are supported. - Bits 21-31: Reserved.

### PixelFormat1bppIndexed {#PixelFormat1bppIndexed}
```
public static final int PixelFormat1bppIndexed
```


The format is monochrome, and a color palette lookup table is used.

### PixelFormat4bppIndexed {#PixelFormat4bppIndexed}
```
public static final int PixelFormat4bppIndexed
```


The format is 16-color, and a color palette lookup table is used.

### PixelFormat8bppIndexed {#PixelFormat8bppIndexed}
```
public static final int PixelFormat8bppIndexed
```


The format is 256-color, and a color palette lookup table is used.

### PixelFormat16bppGrayScale {#PixelFormat16bppGrayScale}
```
public static final int PixelFormat16bppGrayScale
```


The format is 16 bits per pixel, grayscale.

### PixelFormat16bppRGB555 {#PixelFormat16bppRGB555}
```
public static final int PixelFormat16bppRGB555
```


The format is 16 bits per pixel; 5 bits each are used for the red, green, and blue components. The remaining bit is not used.

### PixelFormat16bppRGB565 {#PixelFormat16bppRGB565}
```
public static final int PixelFormat16bppRGB565
```


The format is 16 bits per pixel; 5 bits are used for the red component, 6 bits for the green component, and 5 bits for the blue component.

### PixelFormat16bppARGB1555 {#PixelFormat16bppARGB1555}
```
public static final int PixelFormat16bppARGB1555
```


The format is 16 bits per pixel; 1 bit is used for the alpha component, and 5 bits each are used for the red, green, and blue components.

### PixelFormat24bppRGB {#PixelFormat24bppRGB}
```
public static final int PixelFormat24bppRGB
```


The format is 24 bits per pixel; 8 bits each are used for the red, green, and blue components.

### PixelFormat32bppRGB {#PixelFormat32bppRGB}
```
public static final int PixelFormat32bppRGB
```


The format is 32 bits per pixel; 8 bits each are used for the red, green, and blue components. The remaining 8 bits are not used.

### PixelFormat32bppARGB {#PixelFormat32bppARGB}
```
public static final int PixelFormat32bppARGB
```


The format is 32 bits per pixel; 8 bits each are used for the alpha, red, green, and blue components.

### PixelFormat32bppPARGB {#PixelFormat32bppPARGB}
```
public static final int PixelFormat32bppPARGB
```


The format is 32 bits per pixel; 8 bits each are used for the alpha, red, green, and blue components. The red, green, and blue components are premultiplied according to the alpha component.

### PixelFormat48bppRGB {#PixelFormat48bppRGB}
```
public static final int PixelFormat48bppRGB
```


The format is 48 bits per pixel; 16 bits each are used for the red, green, and blue components.

### PixelFormat64bppARGB {#PixelFormat64bppARGB}
```
public static final int PixelFormat64bppARGB
```


The format is 64 bits per pixel; 16 bits each are used for the alpha, red, green, and blue components.

### PixelFormat64bppPARGB {#PixelFormat64bppPARGB}
```
public static final int PixelFormat64bppPARGB
```


The format is 64 bits per pixel; 16 bits each are used for the alpha, red, green, and blue components. The red, green, and blue components are premultiplied according to the alpha component.

