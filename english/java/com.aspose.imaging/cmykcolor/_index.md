---
title: CmykColor
second_title: Aspose.Imaging for Java API Reference
description: The CMYK color of pixel.
type: docs
weight: 18
url: /java/com.aspose.imaging/cmykcolor/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class CmykColor extends Struct<CmykColor>
```

The CMYK color of pixel.
## Constructors

| Constructor | Description |
| --- | --- |
| [CmykColor()](#CmykColor--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getEmpty()](#getEmpty--) | Gets the empty. |
| [getC()](#getC--) | Gets the cyan component value of this `com.com.aspose.imaging.Color` structure. |
| [getM()](#getM--) | Gets the magenta component value of this `com.com.aspose.imaging.Color` structure. |
| [getY()](#getY--) | Gets the yellow component value of this `com.com.aspose.imaging.Color` structure. |
| [getK()](#getK--) | Gets the black component value of this `com.com.aspose.imaging.Color` structure. |
| [isEmpty()](#isEmpty--) | Gets a value indicating whether this `com.com.aspose.imaging.Color` structure is uninitialized. |
| [fromParams(int cyan, int magenta, int yellow, int black)](#fromParams-int-int-int-int-) | Creates a `CmykColor` structure from a 32-bit cyan, magenta, yellow and black values. |
| [hashCode()](#hashCode--) | The get hash code. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | The conversion from 32-bit ARGB color to CMYKColor. |
| [toColor(CmykColor[] cmykPixels)](#toColor-com.aspose.imaging.CmykColor---) | The conversion from CMYKColor to Color using icc conversion with default profiles. |
| [toArgb32(CmykColor[] cmykPixels)](#toArgb32-com.aspose.imaging.CmykColor---) | The conversion from CMYKColor to 32-bit ARGB Color using icc conversion with default profiles. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | The conversion from 32-bit ARGB to CMYKColor. |
| [toColor(CmykColor cmykPixel)](#toColor-com.aspose.imaging.CmykColor-) | The conversion from CMYKColor to Color. |
| [toColorIcc(CmykColor[] cmykPixels)](#toColorIcc-com.aspose.imaging.CmykColor---) | The conversion from CMYKColor to Color using icc conversion with default profiles. |
| [toColorIcc(CmykColor cmykPixel)](#toColorIcc-com.aspose.imaging.CmykColor-) | The conversion from CMYKColor to Color using icc conversion with default profiles. |
| [toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-) | The conversion from CMYKColor to Color using icc conversion. |
| [toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-) | The conversion from CMYKColor to Color using icc conversion. |
| [toValue()](#toValue--) | The to value. |
| [CloneTo(CmykColor that)](#CloneTo-com.aspose.imaging.CmykColor-) |  |
| [Clone()](#Clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isEquals(CmykColor obj1, CmykColor obj2)](#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-) |  |
### CmykColor() {#CmykColor--}
```
public CmykColor()
```


### getEmpty() {#getEmpty--}
```
public static CmykColor getEmpty()
```


Gets the empty.

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor)
### getC() {#getC--}
```
public byte getC()
```


Gets the cyan component value of this `com.com.aspose.imaging.Color` structure.

**Returns:**
byte - The cyan component value of this `com.com.aspose.imaging.Color`.
### getM() {#getM--}
```
public byte getM()
```


Gets the magenta component value of this `com.com.aspose.imaging.Color` structure.

**Returns:**
byte - The magenta component value of this `com.com.aspose.imaging.Color`.
### getY() {#getY--}
```
public byte getY()
```


Gets the yellow component value of this `com.com.aspose.imaging.Color` structure.

**Returns:**
byte - The yellow component value of this `com.com.aspose.imaging.Color`.
### getK() {#getK--}
```
public byte getK()
```


Gets the black component value of this `com.com.aspose.imaging.Color` structure.

Value: The black component value of this `com.com.aspose.imaging.Color`.

**Returns:**
byte
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Gets a value indicating whether this `com.com.aspose.imaging.Color` structure is uninitialized.

**Returns:**
boolean - This property returns true if this color is uninitialized; otherwise, false.
### fromParams(int cyan, int magenta, int yellow, int black) {#fromParams-int-int-int-int-}
```
public static CmykColor fromParams(int cyan, int magenta, int yellow, int black)
```


Creates a `CmykColor` structure from a 32-bit cyan, magenta, yellow and black values. This method is deprecated. Please use more effective CmykColorHelper\#fromComponents(int, int, int, int).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cyan | int | The cyan component. Valid values are 0 through 255. |
| magenta | int | The magenta component. Valid values are 0 through 255. |
| yellow | int | The yellow component. Valid values are 0 through 255. |
| black | int | The black component. Valid values are 0 through 255. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The `CmykColor`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


The get hash code.

**Returns:**
int - The `int`.
### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static CmykColor[] toCmyk(int[] argbPixels)
```


The conversion from 32-bit ARGB color to CMYKColor. This method is deprecated. Please use more effective `CmykColorHelper.toCmyk(int[])`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argbPixels | int[] | The pixels of 32-bit ARGB format. |

**Returns:**
com.aspose.imaging.CmykColor[] - The `Aspose:Imaging:CmykColor[]`.
### toColor(CmykColor[] cmykPixels) {#toColor-com.aspose.imaging.CmykColor---}
```
public static Color[] toColor(CmykColor[] cmykPixels)
```


The conversion from CMYKColor to Color using icc conversion with default profiles. This method is deprecated. Please use more effective `CmykColorHelper.toArgb(int[])`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | The pixels of CMYKColor type in CMYK format. |

**Returns:**
com.aspose.imaging.Color[] - The array of the ARGB colors.
### toArgb32(CmykColor[] cmykPixels) {#toArgb32-com.aspose.imaging.CmykColor---}
```
public static int[] toArgb32(CmykColor[] cmykPixels)
```


The conversion from CMYKColor to 32-bit ARGB Color using icc conversion with default profiles. This method is deprecated. Please use more effective `CmykColorHelper.toArgb32(int[])`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | The pixels of CMYKColor type in CMYK format. |

**Returns:**
int[] - The array of the 32-bit ARGB color.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static CmykColor toCmyk(int argbPixel)
```


The conversion from 32-bit ARGB to CMYKColor. This method is deprecated. Please use more effective `CmykColorHelper.toCmyk(int)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argbPixel | int | The pixel of 32-bit ARGB format. |

**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor) - The `Aspose:Imaging:CmykColor`.
### toColor(CmykColor cmykPixel) {#toColor-com.aspose.imaging.CmykColor-}
```
public static Color toColor(CmykColor cmykPixel)
```


The conversion from CMYKColor to Color. This method is deprecated. Please use more effective `CmykColorHelper.toArgb(int)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | The pixels of CMYKColor type in CMYK format. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor[] cmykPixels) {#toColorIcc-com.aspose.imaging.CmykColor---}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels)
```


The conversion from CMYKColor to Color using icc conversion with default profiles. This method is deprecated. Please use more effective CmykColorHelper\#toArgbIcc(int[]).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | The pixels of CMYKColor type in CMYK format. |

**Returns:**
com.aspose.imaging.Color[] - The `com.com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel) {#toColorIcc-com.aspose.imaging.CmykColor-}
```
public static Color toColorIcc(CmykColor cmykPixel)
```


The conversion from CMYKColor to Color using icc conversion with default profiles. This method is deprecated. Please use more effective `CmykColorHelper.toArgbIcc(int)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | The pixel of CMYKColor type in CMYK format. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toColorIcc(CmykColor[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


The conversion from CMYKColor to Color using icc conversion. This method is deprecated. Please use more effective `CmykColorHelper.toArgbIcc(int[], InputStream, InputStream)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | [CmykColor\[\]](../../com.aspose.imaging/cmykcolor) | The pixels of CMYKColor type in CMYK format. |
| cmykIccStream | java.io.InputStream | The stream containing icc cmyk profile. |
| rgbIccStream | java.io.InputStream | The stream containing icc rgb profile. |

**Returns:**
com.aspose.imaging.Color[] - The `com.aspose.imaging.Color[]`.
### toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toColorIcc-com.aspose.imaging.CmykColor-java.io.InputStream-java.io.InputStream-}
```
public static Color toColorIcc(CmykColor cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


The conversion from CMYKColor to Color using icc conversion. This method is deprecated. Please use more effective `CmykColorHelper.toArgbIcc(int, Stream, Stream)`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | [CmykColor](../../com.aspose.imaging/cmykcolor) | The pixel of CMYKColor type in CMYK format. |
| cmykIccStream | java.io.InputStream | The stream containing icc cmyk profile. |
| rgbIccStream | java.io.InputStream | The stream containing icc rgb profile. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The `Color`.
### toValue() {#toValue--}
```
public long toValue()
```


The to value.

**Returns:**
long - The `long`.
### CloneTo(CmykColor that) {#CloneTo-com.aspose.imaging.CmykColor-}
```
public void CloneTo(CmykColor that)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| that | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |

### Clone() {#Clone--}
```
public CmykColor Clone()
```




**Returns:**
[CmykColor](../../com.aspose.imaging/cmykcolor)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### isEquals(CmykColor obj1, CmykColor obj2) {#isEquals-com.aspose.imaging.CmykColor-com.aspose.imaging.CmykColor-}
```
public static boolean isEquals(CmykColor obj1, CmykColor obj2)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj1 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |
| obj2 | [CmykColor](../../com.aspose.imaging/cmykcolor) |  |

**Returns:**
boolean
