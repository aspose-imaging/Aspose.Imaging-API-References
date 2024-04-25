---
title: WmfColorUsageEnum
second_title: Aspose.Imaging for Java API Reference
description: The ColorUsage Enumeration specifies whether a color table exists in a device-independent bitmapDIB and how to interpret its values.
type: docs
weight: 15
url: /com.aspose.imaging.fileformats.wmf.consts/wmfcolorusageenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfColorUsageEnum extends System.Enum
```

The ColorUsage Enumeration specifies whether a color table exists in a device-independent bitmap(DIB) and how to interpret its values.
## Fields

| Field | Description |
| --- | --- |
| [DIB_RGB_COLORS](#DIB-RGB-COLORS) | The color table contains RGB values specified by RGBQuad Objects (section 2.2.2.20). |
| [DIB_PAL_COLORS](#DIB-PAL-COLORS) | The color table contains 16-bit indices into the current logical palette in the playback device context. |
| [DIB_PAL_INDICES](#DIB-PAL-INDICES) | No color table exists. |
### DIB_RGB_COLORS {#DIB-RGB-COLORS}
```
public static final int DIB_RGB_COLORS
```


The color table contains RGB values specified by RGBQuad Objects (section 2.2.2.20).

### DIB_PAL_COLORS {#DIB-PAL-COLORS}
```
public static final int DIB_PAL_COLORS
```


The color table contains 16-bit indices into the current logical palette in the playback device context.

### DIB_PAL_INDICES {#DIB-PAL-INDICES}
```
public static final int DIB_PAL_INDICES
```


No color table exists. The pixels in the DIB are indices into the current logical palette in the playback device context.

