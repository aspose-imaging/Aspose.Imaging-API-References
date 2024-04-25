---
title: EmfPlusCompositingQuality
second_title: Aspose.Imaging for Java API Reference
description: The CompositingQuality enumeration defines levels of quality for creating composite images
type: docs
weight: 15
url: /com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCompositingQuality extends System.Enum
```

The CompositingQuality enumeration defines levels of quality for creating composite images
## Fields

| Field | Description |
| --- | --- |
| [CompositingQualityDefault](#CompositingQualityDefault) | No gamma correction is performed. |
| [CompositingQualityHighSpeed](#CompositingQualityHighSpeed) | No gamma correction is performed. |
| [CompositingQualityHighQuality](#CompositingQualityHighQuality) | Gamma correction is performed. |
| [CompositingQualityGammaCorrected](#CompositingQualityGammaCorrected) | Enable gamma correction for higher-quality compositing with lower speed. |
| [CompositingQualityAssumeLinear](#CompositingQualityAssumeLinear) | No gamma correction is performed; however, using linear values results in better quality than the default at a slightly lower speed. |
### CompositingQualityDefault {#CompositingQualityDefault}
```
public static final byte CompositingQualityDefault
```


No gamma correction is performed. Gamma correction controls the overall brightness and contrast of an image. Without gamma correction, composited images can appear too light or too dark.

### CompositingQualityHighSpeed {#CompositingQualityHighSpeed}
```
public static final byte CompositingQualityHighSpeed
```


No gamma correction is performed. Compositing speed is favored at the expense of quality. In terms of the result, there is no difference between this value and CompositingQualityDefault.

### CompositingQualityHighQuality {#CompositingQualityHighQuality}
```
public static final byte CompositingQualityHighQuality
```


Gamma correction is performed. Compositing quality is favored at the expense of speed.

### CompositingQualityGammaCorrected {#CompositingQualityGammaCorrected}
```
public static final byte CompositingQualityGammaCorrected
```


Enable gamma correction for higher-quality compositing with lower speed. In terms of the result, there is no difference between this value and CompositingQualityHighQuality.

### CompositingQualityAssumeLinear {#CompositingQualityAssumeLinear}
```
public static final byte CompositingQualityAssumeLinear
```


No gamma correction is performed; however, using linear values results in better quality than the default at a slightly lower speed.

