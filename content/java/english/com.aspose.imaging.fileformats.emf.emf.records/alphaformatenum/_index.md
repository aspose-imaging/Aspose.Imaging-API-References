---
title: EmfBlendFunction.AlphaFormatEnum
second_title: Aspose.Imaging for Java API Reference
description: A structure that specifies how source and destination pixels are interpreted with respect to alpha transparency.
type: docs
weight: 10
url: /com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class EmfBlendFunction.AlphaFormatEnum extends System.Enum
```

A structure that specifies how source and destination pixels are interpreted with respect to alpha transparency.
## Fields

| Field | Description |
| --- | --- |
| [NotTransparency](#NotTransparency) | The pixels in the source bitmap do not specify alpha transparency. |
| [AC_SRC_ALPHA](#AC-SRC-ALPHA) | Indicates that the source bitmap is 32 bits-per-pixel and specifies an alpha transparency value for each pixel. |
### NotTransparency {#NotTransparency}
```
public static final byte NotTransparency
```


The pixels in the source bitmap do not specify alpha transparency. In this case, the SrcConstantAlpha value determines the blend of the source and destination bitmaps. Note that in the following equations SrcConstantAlpha is divided by 255, which produces a value in the range 0 to 1.

### AC_SRC_ALPHA {#AC-SRC-ALPHA}
```
public static final byte AC_SRC_ALPHA
```


Indicates that the source bitmap is 32 bits-per-pixel and specifies an alpha transparency value for each pixel.

