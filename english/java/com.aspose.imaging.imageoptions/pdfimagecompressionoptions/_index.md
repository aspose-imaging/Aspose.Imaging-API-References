---
title: PdfImageCompressionOptions
second_title: Aspose.Imaging for Java API Reference
description: Pdf image compression options
type: docs
weight: 34
url: /java/com.aspose.imaging.imageoptions/pdfimagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfImageCompressionOptions extends System.Enum
```

Pdf image compression options
## Fields

| Field | Description |
| --- | --- |
| [Auto](#Auto) | Automatically selects the most appropriate compression for each image. |
| [None](#None) | Saves raw image bytes resulting in bigger pdf file sizes. |
| [Rle](#Rle) | Run Length compression. |
| [Flate](#Flate) | Flate compression. |
| [LzwBaselinePredictor](#LzwBaselinePredictor) | Predictor selection is restricted to PNG Paeth predictor to speed-up the process. |
| [LzwOptimizedPredictor](#LzwOptimizedPredictor) | Predictor selection is more complicated and should result in smaller image sizes but taking more time. |
| [Jpeg](#Jpeg) | Jpeg compression. |
| [Ccitt3](#Ccitt3) | /CCITTFaxDecode/DecodeParms/K 0/Columns 173 Does not support transparency. |
| [Ccitt4](#Ccitt4) | /CCITTFaxDecode/DecodeParms/K -1/Columns 173 Does not support transparency. |
### Auto {#Auto}
```
public static final int Auto
```


Automatically selects the most appropriate compression for each image.

### None {#None}
```
public static final int None
```


Saves raw image bytes resulting in bigger pdf file sizes.

### Rle {#Rle}
```
public static final int Rle
```


Run Length compression.

### Flate {#Flate}
```
public static final int Flate
```


Flate compression.

### LzwBaselinePredictor {#LzwBaselinePredictor}
```
public static final int LzwBaselinePredictor
```


Predictor selection is restricted to PNG Paeth predictor to speed-up the process. In practice performs surprisingly good. Better than [LzwOptimizedPredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwOptimizedPredictor).

### LzwOptimizedPredictor {#LzwOptimizedPredictor}
```
public static final int LzwOptimizedPredictor
```


Predictor selection is more complicated and should result in smaller image sizes but taking more time. RFC 2083 says it is the best way to go. But on the test data baseline predictor [LzwBaselinePredictor](../../com.aspose.imaging.imageoptions/pdfimagecompressionoptions\#LzwBaselinePredictor) kicks ass leaving optimized predictor behind by 25-40% compression rate gains.

### Jpeg {#Jpeg}
```
public static final int Jpeg
```


Jpeg compression. Does not support transparency.

### Ccitt3 {#Ccitt3}
```
public static final int Ccitt3
```


/CCITTFaxDecode/DecodeParms/K 0/Columns 173 Does not support transparency.

### Ccitt4 {#Ccitt4}
```
public static final int Ccitt4
```


/CCITTFaxDecode/DecodeParms/K -1/Columns 173 Does not support transparency.

