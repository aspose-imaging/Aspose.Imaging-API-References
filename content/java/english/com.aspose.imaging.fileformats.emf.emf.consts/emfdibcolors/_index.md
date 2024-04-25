---
title: EmfDibColors
second_title: Aspose.Imaging for Java API Reference
description: The DIBColors enumeration defines how to interpret the values in the color table of a DIB.
type: docs
weight: 17
url: /com.aspose.imaging.fileformats.emf.emf.consts/emfdibcolors/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfDibColors extends System.Enum
```

The DIBColors enumeration defines how to interpret the values in the color table of a DIB.
## Fields

| Field | Description |
| --- | --- |
| [DIB_RGB_COLORS](#DIB-RGB-COLORS) | The color table contains literal RGB values |
| [DIB_PAL_COLORS](#DIB-PAL-COLORS) | The color table consists of an array of 16-bit indexes into the LogPalette object (section 2.2.17) that is currently defined in the playback device context. |
| [DIB_PAL_INDICES](#DIB-PAL-INDICES) | No color table exists. |
### DIB_RGB_COLORS {#DIB-RGB-COLORS}
```
public static final int DIB_RGB_COLORS
```


The color table contains literal RGB values

### DIB_PAL_COLORS {#DIB-PAL-COLORS}
```
public static final int DIB_PAL_COLORS
```


The color table consists of an array of 16-bit indexes into the LogPalette object (section 2.2.17) that is currently defined in the playback device context.

### DIB_PAL_INDICES {#DIB-PAL-INDICES}
```
public static final int DIB_PAL_INDICES
```


No color table exists. The pixels in the DIB are indices into the current logical palette in the playback device context.

