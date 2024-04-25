---
title: JpegLsInterleaveMode
second_title: Aspose.Imaging for Java API Reference
description: Defines the interleave mode for multi-component color pixel data.
type: docs
weight: 15
url: /com.aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class JpegLsInterleaveMode extends System.Enum
```

Defines the interleave mode for multi-component (color) pixel data.
## Fields

| Field | Description |
| --- | --- |
| [None](#None) | The data is encoded and stored as component for component: RRRGGGBBB. |
| [Line](#Line) | The interleave mode is by line. |
| [Sample](#Sample) | The data is encoded and stored by sample. |
### None {#None}
```
public static final int None
```


The data is encoded and stored as component for component: RRRGGGBBB.

### Line {#Line}
```
public static final int Line
```


The interleave mode is by line. A full line of each component is encoded before moving to the next line.

### Sample {#Sample}
```
public static final int Sample
```


The data is encoded and stored by sample. For color images this is the format like RGBRGBRGB.

