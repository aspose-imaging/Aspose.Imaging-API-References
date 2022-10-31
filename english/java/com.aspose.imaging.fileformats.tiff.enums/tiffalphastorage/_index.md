---
title: TiffAlphaStorage
second_title: Aspose.Imaging for Java API Reference
description: Specifies the alpha storage for tiff documents.
type: docs
weight: 11
url: /java/com.aspose.imaging.fileformats.tiff.enums/tiffalphastorage/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TiffAlphaStorage extends System.Enum
```

Specifies the alpha storage for tiff documents.
## Fields

| Field | Description |
| --- | --- |
| [Unspecified](#Unspecified) | The alpha is not specified and stored in the tiff file. |
| [Associated](#Associated) | The alpha value is stored in premultiplied form. |
| [Unassociated](#Unassociated) | The alpha value is stored in unassociated form. |
### Unspecified {#Unspecified}
```
public static final int Unspecified
```


The alpha is not specified and stored in the tiff file.

### Associated {#Associated}
```
public static final int Associated
```


The alpha value is stored in premultiplied form. When alpha is restored there may be some rounding effects and restored value may be different from the original.

### Unassociated {#Unassociated}
```
public static final int Unassociated
```


The alpha value is stored in unassociated form. That means that alpha restored is exactly the same as it was stored to the tiff.

