---
title: CmykColorHelper
second_title: Aspose.Imaging for Java API Reference
description: Helper methods to work with CMYK color presented as a signed 32-bit integer value.
type: docs
weight: 19
url: /java/com.aspose.imaging/cmykcolorhelper/
---
**Inheritance:**
java.lang.Object
```
public final class CmykColorHelper
```

Helper methods to work with CMYK color presented as a signed 32-bit integer value. Provides the similar API as the [CmykColor](../../com.aspose.imaging/cmykcolor) struct. It's more lightweight because CMYK color is presented just as Int32 rather than structure with internal fields. Please prefer to use static methods of this class when possible instead of the deprecated [CmykColor](../../com.aspose.imaging/cmykcolor) struct.
## Methods

| Method | Description |
| --- | --- |
| [getC(int cmyk)](#getC-int-) | Gets the cyan component value. |
| [getM(int cmyk)](#getM-int-) | Gets the magenta component value. |
| [getY(int cmyk)](#getY-int-) | Gets the yellow component value. |
| [getK(int cmyk)](#getK-int-) | Gets the black component value. |
| [fromComponents(int cyan, int magenta, int yellow, int black)](#fromComponents-int-int-int-int-) | Creates CMYK from a 32-bit cyan, magenta, yellow and black values. |
| [toCmyk(int[] argbPixels)](#toCmyk-int---) | The conversion from ARGB colors to CMYK colors. |
| [toCmykBytes(int[] argbPixels, int startIndex, int length)](#toCmykBytes-int---int-int-) | Converts RGB to CMYK. |
| [toCmyk(int argbPixel)](#toCmyk-int-) | The conversion from ARGB color to CMYK color. |
| [toCmyk(Color pixel)](#toCmyk-com.aspose.imaging.Color-) | The conversion from ARGB color to CMYK color. |
| [toCmyk(Color[] pixels)](#toCmyk-com.aspose.imaging.Color---) | The conversion from ARGB colors to CMYK colors. |
| [toArgb(int[] cmykPixels)](#toArgb-int---) | The conversion from CMYK colors to ARGB colors. |
| [toArgb(int cmykPixel)](#toArgb-int-) | The conversion from CMYK color to ARGB color. |
| [toArgb32(int[] cmykPixels)](#toArgb32-int---) | The conversion from CMYK colors to ARGB colors. |
| [toArgbIcc(int[] cmykPixels)](#toArgbIcc-int---) | The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles. |
| [toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int---java.io.InputStream-java.io.InputStream-) | The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles. |
| [toArgbIcc(int cmykPixel)](#toArgbIcc-int-) | The conversion from CMYK color to ARGB Color using Icc conversion with default profiles. |
| [toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)](#toArgbIcc-int-java.io.InputStream-java.io.InputStream-) | The conversion from CMYK color to ARGB color using Icc conversion with custom profile. |
| [toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. |
| [toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int---java.io.InputStream-java.io.InputStream-) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. |
| [toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-) | The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. |
| [toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-) | Converts RGB to CMYK using custom ICC profiles. |
| [toCmykIcc(Color[] pixels)](#toCmykIcc-com.aspose.imaging.Color---) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. |
| [toCmykIcc(int[] pixels)](#toCmykIcc-int---) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. |
| [toPsdCmykIcc(int[] pixels)](#toPsdCmykIcc-int---) | The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. |
| [toCmykIcc(Color pixel)](#toCmykIcc-com.aspose.imaging.Color-) | The conversion from ARGB color to CMYK color using Icc conversion with default profiles. |
| [toCmykIcc(int argb)](#toCmykIcc-int-) | The conversion from ARGB color to CMYK color using Icc conversion with default profiles. |
| [toPsdCmykIcc(int argb)](#toPsdCmykIcc-int-) | The conversion from ARGB color to CMYK color using Icc conversion with default profiles. |
| [toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-) | The conversion from ARGB color to CMYK color using Icc conversion with custom profiles. |
| [toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)](#toCmykIcc-int-java.io.InputStream-java.io.InputStream-) | The conversion from ARGB color to CMYK color using Icc conversion with custom profiles. |
| [toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)](#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-) | The conversion from ARGB color to CMYK color using Icc conversion with custom profiles. |
### getC(int cmyk) {#getC-int-}
```
public static int getC(int cmyk)
```


Gets the cyan component value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmyk | int | The CMYK color presented as a 32-bit integer value. |

**Returns:**
int - The cyan component value.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//The output looks like this:
//Convert RGB to CMYK without using ICC profiles.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getM(int cmyk) {#getM-int-}
```
public static int getM(int cmyk)
```


Gets the magenta component value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmyk | int | The CMYK color presented as a 32-bit integer value. |

**Returns:**
int - The magenta component value.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//The output looks like this:
//Convert RGB to CMYK without using ICC profiles.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getY(int cmyk) {#getY-int-}
```
public static int getY(int cmyk)
```


Gets the yellow component value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmyk | int | The CMYK color presented as a 32-bit integer value. |

**Returns:**
int - The yellow component value.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//The output looks like this:
//Convert RGB to CMYK without using ICC profiles.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### getK(int cmyk) {#getK-int-}
```
public static int getK(int cmyk)
```


Gets the black component value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmyk | int | The CMYK color presented as a 32-bit integer value. |

**Returns:**
int - The black component value.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//The output looks like this:
//Convert RGB to CMYK without using ICC profiles.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### fromComponents(int cyan, int magenta, int yellow, int black) {#fromComponents-int-int-int-int-}
```
public static int fromComponents(int cyan, int magenta, int yellow, int black)
```


Creates CMYK from a 32-bit cyan, magenta, yellow and black values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cyan | int | The cyan component. Valid values are 0 through 255. |
| magenta | int | The magenta component. Valid values are 0 through 255. |
| yellow | int | The yellow component. Valid values are 0 through 255. |
| black | int | The black component. Valid values are 0 through 255. |

**Returns:**
int - The CMYK color presented as a 32-bit integer value.

**Example: The following example shows how to convert CMYK colors to their RGB counterparts in a fast manner following straightforward formulas without using ICC profiles.**

``` java
int[] cmykColors = new int[]
        {
                com.aspose.imaging.CmykColorHelper.fromComponents(255, 0, 0, 0),   // Cyan
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 255, 0, 0),   // Magenta
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 255, 0),   // Yellow
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 0, 255),   // Black
        };

System.out.println("Convert CMYK to RGB without using ICC profiles.");
for (int cmykColor : cmykColors) {
    com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgb(cmykColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

    System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, (int) rgbColor.getB() & 0xff);
}

//The output looks like this:
//Convert CMYK to RGB without using ICC profiles.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toCmyk(int[] argbPixels) {#toCmyk-int---}
```
public static int[] toCmyk(int[] argbPixels)
```


The conversion from ARGB colors to CMYK colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argbPixels | int[] | The ARGB colors presented as 32-bit integer values. |

**Returns:**
int[] - The CMYK colors presented as 32-bit integer values.
### toCmykBytes(int[] argbPixels, int startIndex, int length) {#toCmykBytes-int---int-int-}
```
public static byte[] toCmykBytes(int[] argbPixels, int startIndex, int length)
```


Converts RGB to CMYK.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argbPixels | int[] | The RGB colors presented as 32-bit integer values. |
| startIndex | int | The start index of RGB color. |
| length | int | The number of RGB pixels to convert. |

**Returns:**
byte[] - The CMYK colors presented as a byte array.
### toCmyk(int argbPixel) {#toCmyk-int-}
```
public static int toCmyk(int argbPixel)
```


The conversion from ARGB color to CMYK color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argbPixel | int | The ARGB color presented as a 32-bit integer value. |

**Returns:**
int - The CMYK color presented as a 32-bit integer value.
### toCmyk(Color pixel) {#toCmyk-com.aspose.imaging.Color-}
```
public static int toCmyk(Color pixel)
```


The conversion from ARGB color to CMYK color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | The ARGB color. |

**Returns:**
int - The CMYK color presented as a 32-bit integer value.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts without applying ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK without using ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmyk(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(@%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

//The output looks like this:
//Convert RGB to CMYK without using ICC profiles.
//RGB(255,0,0)        => CMYK(0,255,255,0)
//RGB(0,128,0)        => CMYK(255,0,255,127)
//RGB(0,0,255)        => CMYK(255,255,0,0)
```

### toCmyk(Color[] pixels) {#toCmyk-com.aspose.imaging.Color---}
```
public static int[] toCmyk(Color[] pixels)
```


The conversion from ARGB colors to CMYK colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | The ARGB colors. |

**Returns:**
int[] - The CMYK colors presented as 32-bit integer values.
### toArgb(int[] cmykPixels) {#toArgb-int---}
```
public static Color[] toArgb(int[] cmykPixels)
```


The conversion from CMYK colors to ARGB colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | The CMYK colors presented as 32-bit integer values. |

**Returns:**
com.aspose.imaging.Color[] - The ARGB colors.
### toArgb(int cmykPixel) {#toArgb-int-}
```
public static Color toArgb(int cmykPixel)
```


The conversion from CMYK color to ARGB color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | int | The CMYK color presented as a 32-bit integer value. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The ARGB color.

**Example: The following example shows how to convert CMYK colors to their RGB counterparts in a fast manner following straightforward formulas without using ICC profiles.**

``` java
int[] cmykColors = new int[]
        {
                com.aspose.imaging.CmykColorHelper.fromComponents(255, 0, 0, 0),   // Cyan
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 255, 0, 0),   // Magenta
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 255, 0),   // Yellow
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 0, 255),   // Black
        };

System.out.println("Convert CMYK to RGB without using ICC profiles.");
for (int cmykColor : cmykColors) {
    com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgb(cmykColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

    System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, (int) rgbColor.getB() & 0xff);
}

//The output looks like this:
//Convert CMYK to RGB without using ICC profiles.
//CMYK(255,0,0,0)        => RGB(0,255,255)
//CMYK(0,255,0,0)        => RGB(255,0,255)
//CMYK(0,0,255,0)        => RGB(255,255,0)
//CMYK(0,0,0,255)        => RGB(0,0,0)
```

### toArgb32(int[] cmykPixels) {#toArgb32-int---}
```
public static int[] toArgb32(int[] cmykPixels)
```


The conversion from CMYK colors to ARGB colors.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | The CMYK colors presented as 32-bit integer values. |

**Returns:**
int[] - The ARGB colors presented as 32-bit integer values.
### toArgbIcc(int[] cmykPixels) {#toArgbIcc-int---}
```
public static Color[] toArgbIcc(int[] cmykPixels)
```


The conversion from CMYK colors to ARGB colors using Icc conversion with default profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | The CMYK pixels presented as 32-bit integer values. |

**Returns:**
com.aspose.imaging.Color[] - The ARGB colors.
### toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static Color[] toArgbIcc(int[] cmykPixels, InputStream cmykIccStream, InputStream rgbIccStream)
```


The conversion from CMYK colors to ARGB colors using Icc conversion with custom profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixels | int[] | The CMYK colors presented as 32-bit integer values. |
| cmykIccStream | java.io.InputStream | The stream containing CMYK Icc profile. |
| rgbIccStream | java.io.InputStream | The stream containing RGB Icc profile. |

**Returns:**
com.aspose.imaging.Color[] - The ARGB colors.
### toArgbIcc(int cmykPixel) {#toArgbIcc-int-}
```
public static Color toArgbIcc(int cmykPixel)
```


The conversion from CMYK color to ARGB Color using Icc conversion with default profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | int | The CMYK color presented as a 32-bit integer value. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The ARGB color.

**Example: The following example shows how to convert CMYK colors to their RGB counterparts using ICC profiles.**

``` java
int[] cmykColors = new int[]
        {
                com.aspose.imaging.CmykColorHelper.fromComponents(255, 0, 0, 0),   // Cyan
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 255, 0, 0),   // Magenta
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 255, 0),   // Yellow
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 0, 255),   // Black
        };

System.out.println("Convert CMYK to RGB using default ICC profiles.");
for (int cmykColor : cmykColors) {
    com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgbIcc(cmykColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

    System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff);
}

// Specify your path to custom RGB and CMYK ICC profiles.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// Read all bytes from ICC files to memory to have a possibility to reset input profile stream before calling toCmykIcc
byte[] rgbProfileBytes;
java.io.RandomAccessFile rgbProfile = new java.io.RandomAccessFile(dir + "eciRGB_v2.icc", "r");
try {
    rgbProfileBytes = new byte[(int) rgbProfile.length()];
    rgbProfile.readFully(rgbProfileBytes);
} finally {
    rgbProfile.close();
}

byte[] cmykProfileBytes;
java.io.RandomAccessFile cmykProfile = new java.io.RandomAccessFile(dir + "ISOcoated_v2_FullGamut4.icc", "r");
try {
    cmykProfileBytes = new byte[(int) cmykProfile.length()];
    cmykProfile.readFully(cmykProfileBytes);
} finally {
    cmykProfile.close();
}

java.io.InputStream rgbProfileStream = new java.io.ByteArrayInputStream(rgbProfileBytes);
java.io.InputStream cmykProfileStream = new java.io.ByteArrayInputStream(cmykProfileBytes);
try {
    for (int cmykColor : cmykColors) {
        com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgbIcc(cmykColor);
        int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
        int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
        int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
        int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

        System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff);
    }
} finally {
    cmykProfileStream.close();
    rgbProfileStream.close();
}

//The output looks like this:
//Convert CMYK to RGB using default ICC profiles.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Convert CMYK to RGB using custom ICC profiles.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream) {#toArgbIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static Color toArgbIcc(int cmykPixel, InputStream cmykIccStream, InputStream rgbIccStream)
```


The conversion from CMYK color to ARGB color using Icc conversion with custom profile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cmykPixel | int | The CMYK color presented as a 32-bit integer value. |
| cmykIccStream | java.io.InputStream | The stream containing CMYK Icc profile. |
| rgbIccStream | java.io.InputStream | The stream containing RGB Icc profile. |

**Returns:**
[Color](../../com.aspose.imaging/color) - The ARGB color.

**Example: The following example shows how to convert CMYK colors to their RGB counterparts using ICC profiles.**

``` java
int[] cmykColors = new int[]
        {
                com.aspose.imaging.CmykColorHelper.fromComponents(255, 0, 0, 0),   // Cyan
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 255, 0, 0),   // Magenta
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 255, 0),   // Yellow
                com.aspose.imaging.CmykColorHelper.fromComponents(0, 0, 0, 255),   // Black
        };

System.out.println("Convert CMYK to RGB using default ICC profiles.");
for (int cmykColor : cmykColors) {
    com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgbIcc(cmykColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

    System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff);
}

// Specify your path to custom RGB and CMYK ICC profiles.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert CMYK to RGB using custom ICC profiles.");
// Read all bytes from ICC files to memory to have a possibility to reset input profile stream before calling toCmykIcc
byte[] rgbProfileBytes;
java.io.RandomAccessFile rgbProfile = new java.io.RandomAccessFile(dir + "eciRGB_v2.icc", "r");
try {
    rgbProfileBytes = new byte[(int) rgbProfile.length()];
    rgbProfile.readFully(rgbProfileBytes);
} finally {
    rgbProfile.close();
}

byte[] cmykProfileBytes;
java.io.RandomAccessFile cmykProfile = new java.io.RandomAccessFile(dir + "ISOcoated_v2_FullGamut4.icc", "r");
try {
    cmykProfileBytes = new byte[(int) cmykProfile.length()];
    cmykProfile.readFully(cmykProfileBytes);
} finally {
    cmykProfile.close();
}

java.io.InputStream rgbProfileStream = new java.io.ByteArrayInputStream(rgbProfileBytes);
java.io.InputStream cmykProfileStream = new java.io.ByteArrayInputStream(cmykProfileBytes);
try {
    for (int cmykColor : cmykColors) {
        com.aspose.imaging.Color rgbColor = com.aspose.imaging.CmykColorHelper.toArgbIcc(cmykColor);
        int c = com.aspose.imaging.CmykColorHelper.getC(cmykColor);
        int m = com.aspose.imaging.CmykColorHelper.getM(cmykColor);
        int y = com.aspose.imaging.CmykColorHelper.getY(cmykColor);
        int k = com.aspose.imaging.CmykColorHelper.getK(cmykColor);

        System.out.printf("CMYK(%s,%s,%s,%s)\t\t=> RGB(%s,%s,%s)\r\n", c, m, y, k, rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff);
    }
} finally {
    cmykProfileStream.close();
    rgbProfileStream.close();
}

//The output looks like this:
//Convert CMYK to RGB using default ICC profiles.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//CMYK(0,0,255,0)        => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
//Convert CMYK to RGB using custom ICC profiles.
//CMYK(255,0,0,0)        => RGB(46,188,220)
//CMYK(0,255,0,0)        => RGB(231,52,142)
//(0,0,255,0)            => RGB(244,253,63)
//CMYK(0,0,0,255)        => RGB(21,21,21)
```

### toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(Color[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | The ARGB colors. |
| rgbIccStream | java.io.InputStream | The stream containing RGB Icc profile. |
| cmykIccStream | java.io.InputStream | The stream containing CMYK Icc profile. |

**Returns:**
int[] - The CMYK colors presented as 32-bit integer values.
### toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixels | int[] | The ARGB colors. |
| rgbIccStream | java.io.InputStream | The stream containing RGB Icc profile. |
| cmykIccStream | java.io.InputStream | The stream containing CMYK Icc profile. |

**Returns:**
int[] - The CMYK colors presented as 32-bit integer values.
### toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int---java.io.InputStream-java.io.InputStream-}
```
public static int[] toPsdCmykIcc(int[] pixels, InputStream rgbIccStream, InputStream cmykIccStream)
```


The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. Uses PSD CMYK format KCMY byte order with inverted channel values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixels | int[] | The ARGB colors. |
| rgbIccStream | java.io.InputStream | The stream containing RGB Icc profile. |
| cmykIccStream | java.io.InputStream | The stream containing CMYK Icc profile. |

**Returns:**
int[] - The CMYK colors presented as 32-bit integer values in KCMY byte order with inverted channel values.
### toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIccBytes-int---int-int-java.io.InputStream-java.io.InputStream-}
```
public static byte[] toCmykIccBytes(int[] pixels, int startIndex, int length, InputStream rgbIccStream, InputStream cmykIccStream)
```


Converts RGB to CMYK using custom ICC profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixels | int[] | The RGB colors presented as 32-bit integer values. |
| startIndex | int | The start index of RGB color. |
| length | int | The number of RGB pixels to convert. |
| rgbIccStream | java.io.InputStream | The RGB profile stream. |
| cmykIccStream | java.io.InputStream | The CMYK profile stream. |

**Returns:**
byte[] - The CMYK colors presented as a byte array.
### toCmykIcc(Color[] pixels) {#toCmykIcc-com.aspose.imaging.Color---}
```
public static int[] toCmykIcc(Color[] pixels)
```


The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixels | [Color\[\]](../../com.aspose.imaging/color) | The ARGB colors. |

**Returns:**
int[] - The CMYK colors presented as 32-bit integer values.
### toCmykIcc(int[] pixels) {#toCmykIcc-int---}
```
public static int[] toCmykIcc(int[] pixels)
```


The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixels | int[] | The ARGB colors. |

**Returns:**
int[] - The CMYK colors presented as 32-bit integer values.
### toPsdCmykIcc(int[] pixels) {#toPsdCmykIcc-int---}
```
public static int[] toPsdCmykIcc(int[] pixels)
```


The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. Uses PSD CMYK format KCMY byte order with inverted channel values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixels | int[] | The ARGB colors. |

**Returns:**
int[] - The CMYK colors presented as 32-bit integer values in KCMY byte order with inverted channel values.
### toCmykIcc(Color pixel) {#toCmykIcc-com.aspose.imaging.Color-}
```
public static int toCmykIcc(Color pixel)
```


The conversion from ARGB color to CMYK color using Icc conversion with default profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | The ARGB color. |

**Returns:**
int - The CMYK color presented as a 32-bit integer value.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts using ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK using default ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmykIcc(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

// Specify your path to the RGB and CMYK ICC profiles.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// Read all bytes from ICC files to memory to have a possibility to reset input profile stream before calling toCmykIcc
byte[] rgbProfileBytes;
java.io.RandomAccessFile rgbProfile = new java.io.RandomAccessFile(dir + "eciRGB_v2.icc", "r");
try {
    rgbProfileBytes = new byte[(int) rgbProfile.length()];
    rgbProfile.readFully(rgbProfileBytes);
} finally {
    rgbProfile.close();
}

byte[] cmykProfileBytes;
java.io.RandomAccessFile cmykProfile = new java.io.RandomAccessFile(dir + "ISOcoated_v2_FullGamut4.icc", "r");
try {
    cmykProfileBytes = new byte[(int) cmykProfile.length()];
    cmykProfile.readFully(cmykProfileBytes);
} finally {
    cmykProfile.close();
}

java.io.InputStream rgbProfileStream = new java.io.ByteArrayInputStream(rgbProfileBytes);
java.io.InputStream cmykProfileStream = new java.io.ByteArrayInputStream(cmykProfileBytes);
try {
    for (com.aspose.imaging.Color rgbColor : rgbColors) {

        int cmyk = com.aspose.imaging.CmykColorHelper.toCmykIcc(rgbColor, rgbProfileStream, cmykProfileStream);
        int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
        int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
        int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
        int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

        System.out.printf("RGB(%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
    }
} finally {
    cmykProfileStream.close();
    rgbProfileStream.close();
}

//The output looks like this:
//Convert RGB to CMYK using default ICC profiles.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Convert RGB to CMYK using custom ICC profiles.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb) {#toCmykIcc-int-}
```
public static int toCmykIcc(int argb)
```


The conversion from ARGB color to CMYK color using Icc conversion with default profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argb | int | The ARGB color. |

**Returns:**
int - The CMYK color presented as a 32-bit integer value.
### toPsdCmykIcc(int argb) {#toPsdCmykIcc-int-}
```
public static int toPsdCmykIcc(int argb)
```


The conversion from ARGB color to CMYK color using Icc conversion with default profiles. Uses PSD CMYK format KCMY byte order with inverted channel values.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argb | int | The ARGB color. |

**Returns:**
int - The CMYK color presented as a 32-bit integer value in KCMY byte order with inverted channel values.
### toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-com.aspose.imaging.Color-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(Color pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


The conversion from ARGB color to CMYK color using Icc conversion with custom profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixel | [Color](../../com.aspose.imaging/color) | The ARGB color. |
| rgbIccStream | java.io.InputStream | The stream containing RGB Icc profile. |
| cmykIccStream | java.io.InputStream | The stream containing CMYK Icc profile. |

**Returns:**
int - The CMYK color presented as a 32-bit integer value.

**Example: The following example shows how to convert RGB colors to their CMYK counterparts using ICC profiles.**

``` java
com.aspose.imaging.Color[] rgbColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
                com.aspose.imaging.Color.getBlue(),
        };

System.out.println("Convert RGB to CMYK using default ICC profiles.");
for (com.aspose.imaging.Color rgbColor : rgbColors) {
    int cmyk = com.aspose.imaging.CmykColorHelper.toCmykIcc(rgbColor);
    int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
    int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
    int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
    int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

    System.out.printf("RGB(%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
}

// Specify your path to the RGB and CMYK ICC profiles.
String dir = "c:\\temp\\iccprofiles\\";

System.out.println("Convert RGB to CMYK using custom ICC profiles.");

// Read all bytes from ICC files to memory to have a possibility to reset input profile stream before calling toCmykIcc
byte[] rgbProfileBytes;
java.io.RandomAccessFile rgbProfile = new java.io.RandomAccessFile(dir + "eciRGB_v2.icc", "r");
try {
    rgbProfileBytes = new byte[(int) rgbProfile.length()];
    rgbProfile.readFully(rgbProfileBytes);
} finally {
    rgbProfile.close();
}

byte[] cmykProfileBytes;
java.io.RandomAccessFile cmykProfile = new java.io.RandomAccessFile(dir + "ISOcoated_v2_FullGamut4.icc", "r");
try {
    cmykProfileBytes = new byte[(int) cmykProfile.length()];
    cmykProfile.readFully(cmykProfileBytes);
} finally {
    cmykProfile.close();
}

java.io.InputStream rgbProfileStream = new java.io.ByteArrayInputStream(rgbProfileBytes);
java.io.InputStream cmykProfileStream = new java.io.ByteArrayInputStream(cmykProfileBytes);
try {
    for (com.aspose.imaging.Color rgbColor : rgbColors) {

        int cmyk = com.aspose.imaging.CmykColorHelper.toCmykIcc(rgbColor, rgbProfileStream, cmykProfileStream);
        int c = com.aspose.imaging.CmykColorHelper.getC(cmyk);
        int m = com.aspose.imaging.CmykColorHelper.getM(cmyk);
        int y = com.aspose.imaging.CmykColorHelper.getY(cmyk);
        int k = com.aspose.imaging.CmykColorHelper.getK(cmyk);

        System.out.printf("RGB(%s,%s,%s)\t\t=> CMYK(%s,%s,%s,%s)\r\n", rgbColor.getR() & 0xff, rgbColor.getG() & 0xff, rgbColor.getB() & 0xff, c, m, y, k);
    }
} finally {
    cmykProfileStream.close();
    rgbProfileStream.close();
}

//The output looks like this:
//Convert RGB to CMYK using default ICC profiles.
//RGB(255,0,0)        => CMYK(0,254,249,15)
//RGB(0,128,0)        => CMYK(247,21,254,85)
//RGB(0,0,255)        => CMYK(254,195,0,134)
//Convert RGB to CMYK using custom ICC profiles.
//RGB(255,0,0)        => CMYK(0,207,219,0)
//RGB(0,128,0)        => CMYK(238,16,254,80)
//RGB(0,0,255)        => CMYK(242,182,0,0)
```

### toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream) {#toCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toCmykIcc(int argb, InputStream rgbIccStream, InputStream cmykIccStream)
```


The conversion from ARGB color to CMYK color using Icc conversion with custom profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| argb | int | The ARGB color. |
| rgbIccStream | java.io.InputStream | The stream containing RGB Icc profile. |
| cmykIccStream | java.io.InputStream | The stream containing CMYK Icc profile. |

**Returns:**
int - The CMYK color presented as a 32-bit integer value.
### toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream) {#toPsdCmykIcc-int-java.io.InputStream-java.io.InputStream-}
```
public static int toPsdCmykIcc(int pixel, InputStream rgbIccStream, InputStream cmykIccStream)
```


The conversion from ARGB color to CMYK color using Icc conversion with custom profiles.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pixel | int | The ARGB color. |
| rgbIccStream | java.io.InputStream | The stream containing RGB Icc profile. |
| cmykIccStream | java.io.InputStream | The stream containing CMYK Icc profile. |

**Returns:**
int - The CMYK colors presented as 32-bit integer values in KCMY byte order with inverted channel values.
