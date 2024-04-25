---
title: WmfCompression
second_title: Aspose.Imaging for Java API Reference
description: The Compression Enumeration specifies the type of compression for a bitmap image
type: docs
weight: 16
url: /com.aspose.imaging.fileformats.wmf.consts/wmfcompression/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfCompression extends System.Enum
```

The Compression Enumeration specifies the type of compression for a bitmap image
## Fields

| Field | Description |
| --- | --- |
| [BI_RGB](#BI-RGB) | The bitmap is in uncompressed red green blue (RGB) format that is not compressed and does not use color masks. |
| [BI_RLE8](#BI-RLE8) | An RGB format that uses run-length encoding (RLE) compression for bitmaps with 8 bits per pixel. |
| [BI_RLE4](#BI-RLE4) | An RGB format that uses RLE compression for bitmaps with 4 bits per pixel. |
| [BI_BITFIELDS](#BI-BITFIELDS) | The bitmap is not compressed and the color table consists of three DWORD color masks that specify the red, green, and blue components, respectively, of each pixel. |
| [BI_JPEG](#BI-JPEG) | The image is a JPEG image, as specified in [JFIF]. |
| [BI_PNG](#BI-PNG) | The image is a PNG image, as specified in [RFC2083]. |
| [BI_CMYK](#BI-CMYK) | The image is an uncompressed CMYK format. |
| [BI_CMYKRLE8](#BI-CMYKRLE8) | A CMYK format that uses RLE compression for bitmaps with 8 bits per pixel. |
| [BI_CMYKRLE4](#BI-CMYKRLE4) | A CMYK format that uses RLE compression for bitmaps with 4 bits per pixel. |
### BI_RGB {#BI-RGB}
```
public static final int BI_RGB
```


The bitmap is in uncompressed red green blue (RGB) format that is not compressed and does not use color masks.

### BI_RLE8 {#BI-RLE8}
```
public static final int BI_RLE8
```


An RGB format that uses run-length encoding (RLE) compression for bitmaps with 8 bits per pixel. The compression uses a 2-byte format consisting of a count byte followed by a byte containing a color index.

### BI_RLE4 {#BI-RLE4}
```
public static final int BI_RLE4
```


An RGB format that uses RLE compression for bitmaps with 4 bits per pixel. The compression uses a 2-byte format consisting of a count byte followed by two word-length color indexes

### BI_BITFIELDS {#BI-BITFIELDS}
```
public static final int BI_BITFIELDS
```


The bitmap is not compressed and the color table consists of three DWORD color masks that specify the red, green, and blue components, respectively, of each pixel. This is valid when used with 16 and 32-bits per pixel bitmaps.

### BI_JPEG {#BI-JPEG}
```
public static final int BI_JPEG
```


The image is a JPEG image, as specified in [JFIF]. This value SHOULD only be used in certain bitmap operations, such as JPEG pass-through. The application MUST query for the pass-through support, since not all devices support JPEG pass-through. Using non-RGB bitmaps MAY limit the portability of the metafile to other devices. For instance, display device contexts generally do not support this pass-through

### BI_PNG {#BI-PNG}
```
public static final int BI_PNG
```


The image is a PNG image, as specified in [RFC2083]. This value SHOULD only be used certain bitmap operations, such as JPEG/PNG pass-through. The application MUST query for the pass-through support, because not all devices support JPEG/PNG pass-through. Using non-RGB bitmaps MAY limit the portability of the metafile to other devices. For instance, display device contexts generally do not support this pass-through.

### BI_CMYK {#BI-CMYK}
```
public static final int BI_CMYK
```


The image is an uncompressed CMYK format.

### BI_CMYKRLE8 {#BI-CMYKRLE8}
```
public static final int BI_CMYKRLE8
```


A CMYK format that uses RLE compression for bitmaps with 8 bits per pixel. The compression uses a 2-byte format consisting of a count byte followed by a byte containing a color index.

### BI_CMYKRLE4 {#BI-CMYKRLE4}
```
public static final int BI_CMYKRLE4
```


A CMYK format that uses RLE compression for bitmaps with 4 bits per pixel. The compression uses a 2-byte format consisting of a count byte followed by two word-length color indexes.

