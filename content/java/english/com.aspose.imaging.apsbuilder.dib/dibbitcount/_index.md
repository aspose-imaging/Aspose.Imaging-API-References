---
title: DibBitCount
second_title: Aspose.Imaging for Java API Reference
description: The BitCount Enumeration specifies the number of bits that define each pixel and the maximum number of colors in a device-independent bitmap DIB.
type: docs
weight: 10
url: /com.aspose.imaging.apsbuilder.dib/dibbitcount/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DibBitCount extends System.Enum
```

The BitCount Enumeration specifies the number of bits that define each pixel and the maximum number of colors in a device-independent bitmap (DIB).
## Fields

| Field | Description |
| --- | --- |
| [BIT_COUNT_0](#BIT-COUNT-0) | The number of bits per pixel is undefined. |
| [BIT_COUNT_1](#BIT-COUNT-1) | The image is specified with two colors.Each pixel in the bitmap is represented by a single bit. |
| [BIT_COUNT_2](#BIT-COUNT-2) | The image is specified with a maximum of 16 colors. |
| [BIT_COUNT_3](#BIT-COUNT-3) | The image is specified with a maximum of 256 colors. |
| [BIT_COUNT_4](#BIT-COUNT-4) | The image is specified with a maximum of 2^16 colors. |
| [BIT_COUNT_5](#BIT-COUNT-5) | The bitmap has a maximum of 2^24 colors, and the Colors field of DIB is NULL. |
| [BIT_COUNT_6](#BIT-COUNT-6) | The bitmap has a maximum of 2^24 colors |
### BIT_COUNT_0 {#BIT-COUNT-0}
```
public static final short BIT_COUNT_0
```


The number of bits per pixel is undefined. The image SHOULD be in either JPEG or PNG format. Neither of these formats includes a color table, so this value specifies that no color table is present. See [JFIF] and [RFC2083] for more information concerning JPEG and PNG compression formats.

### BIT_COUNT_1 {#BIT-COUNT-1}
```
public static final short BIT_COUNT_1
```


The image is specified with two colors.Each pixel in the bitmap is represented by a single bit. If the bit is clear, the pixel is displayed with the color of the first entry in the color table; if the bit is set, the pixel has the color of the second entry in the table.

### BIT_COUNT_2 {#BIT-COUNT-2}
```
public static final short BIT_COUNT_2
```


The image is specified with a maximum of 16 colors. Each pixel in the bitmap is represented by a 4-bit index into the color table, and each byte contains 2 pixels.

### BIT_COUNT_3 {#BIT-COUNT-3}
```
public static final short BIT_COUNT_3
```


The image is specified with a maximum of 256 colors. Each pixel in the bitmap is represented by an 8-bit index into the color table, and each byte contains 1 pixel.

### BIT_COUNT_4 {#BIT-COUNT-4}
```
public static final short BIT_COUNT_4
```


The image is specified with a maximum of 2^16 colors. Each pixel in the bitmap is represented by a 16-bit value

### BIT_COUNT_5 {#BIT-COUNT-5}
```
public static final short BIT_COUNT_5
```


The bitmap has a maximum of 2^24 colors, and the Colors field of DIB is NULL. Each 3-byte triplet in the bitmap array represents the relative intensities of blue, green, and red, respectively, for a pixel. The Colors color table is used for optimizing colors used on palette-based devices, and MUST contain the number of entries specified by the ColorUsed field of the BitmapInfoHeader Object

### BIT_COUNT_6 {#BIT-COUNT-6}
```
public static final short BIT_COUNT_6
```


The bitmap has a maximum of 2^24 colors

