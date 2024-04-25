---
title: WmfGamutMappingIntent
second_title: Aspose.Imaging for Java API Reference
description: The GamutMappingIntent Enumeration specifies the relationship between logical and physical colors.
type: docs
weight: 20
url: /com.aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfGamutMappingIntent extends System.Enum
```

The GamutMappingIntent Enumeration specifies the relationship between logical and physical colors.
## Fields

| Field | Description |
| --- | --- |
| [LCS_GM_ABS_COLORIMETRIC](#LCS-GM-ABS-COLORIMETRIC) | Specifies that the white point SHOULD be maintained. |
| [LCS_GM_BUSINESS](#LCS-GM-BUSINESS) | Specifies that saturation SHOULD be maintained. |
| [LCS_GM_GRAPHICS](#LCS-GM-GRAPHICS) | Specifies that a colorimetric match SHOULD be maintained. |
| [LCS_GM_IMAGES](#LCS-GM-IMAGES) | Specifies that contrast SHOULD be maintained. |
### LCS_GM_ABS_COLORIMETRIC {#LCS-GM-ABS-COLORIMETRIC}
```
public static final int LCS_GM_ABS_COLORIMETRIC
```


Specifies that the white point SHOULD be maintained. Typically used when logical colors MUST be matched to their nearest physical color in the destination color gamut. Intent: Match ICC name: Absolute Colorimetric

### LCS_GM_BUSINESS {#LCS-GM-BUSINESS}
```
public static final int LCS_GM_BUSINESS
```


Specifies that saturation SHOULD be maintained. Typically used for business charts and other situations in which dithering is not required. Intent: Graphic ICC name: Saturation

### LCS_GM_GRAPHICS {#LCS-GM-GRAPHICS}
```
public static final int LCS_GM_GRAPHICS
```


Specifies that a colorimetric match SHOULD be maintained. Typically used for graphic designs and named colors. Intent: Proof ICC name: Relative Colorimetric

### LCS_GM_IMAGES {#LCS-GM-IMAGES}
```
public static final int LCS_GM_IMAGES
```


Specifies that contrast SHOULD be maintained. Typically used for photographs and natural images. Intent: Picture ICC name: Perceptual

