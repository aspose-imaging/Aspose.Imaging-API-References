---
title: CompressionMethod
second_title: Aspose.Imaging for Java API Reference
description: Defines the compression method used for image data.
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.psd/compressionmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CompressionMethod extends System.Enum
```

Defines the compression method used for image data.
## Fields

| Field | Description |
| --- | --- |
| [Raw](#Raw) | No compression. |
| [RLE](#RLE) | RLE compressed the image data starts with the byte counts for all the scan lines (rows \* channels), with each count stored as a two-byte value. |
| [ZipWithoutPrediction](#ZipWithoutPrediction) | ZIP without prediction. |
| [ZipWithPrediction](#ZipWithPrediction) | ZIP with prediction. |
### Raw {#Raw}
```
public static final short Raw
```


No compression. The image data stored as raw bytes in RGBA planar order. That means that first all R data is written, then all G is written, then all B and finally all A data is written.

### RLE {#RLE}
```
public static final short RLE
```


RLE compressed the image data starts with the byte counts for all the scan lines (rows \* channels), with each count stored as a two-byte value. The RLE compressed data follows, with each scan line compressed separately. The RLE compression is the same compression algorithm used by the Macintosh ROM routine PackBits and the TIFF standard.

### ZipWithoutPrediction {#ZipWithoutPrediction}
```
public static final short ZipWithoutPrediction
```


ZIP without prediction.

### ZipWithPrediction {#ZipWithPrediction}
```
public static final short ZipWithPrediction
```


ZIP with prediction.

