---
title: WmfOutPrecision
second_title: Aspose.Imaging for Java API Reference
description: The OutPrecision enumeration defines values for output precision which is the requirement for the font mapper to match specific font parameters including height width character orientation escapement pitch and font type.
type: docs
weight: 27
url: /com.aspose.imaging.fileformats.wmf.consts/wmfoutprecision/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfOutPrecision extends System.Enum
```

The OutPrecision enumeration defines values for output precision, which is the requirement for the font mapper to match specific font parameters, including height, width, character orientation, escapement, pitch, and font type.
## Fields

| Field | Description |
| --- | --- |
| [Default](#Default) | A value that specifies default behavior. |
| [String](#String) | A value that is returned when rasterized fonts are enumerated. |
| [Stroke](#Stroke) | A value that is returned when TrueType and other outline fonts, and vector fonts are enumerated. |
| [Tt](#Tt) | A value that specifies the choice of a TrueType font when the system contains multiple fonts with the same name. |
| [Device](#Device) | A value that specifies the choice of a device font when the system contains multiple fonts with the same name. |
| [Raster](#Raster) | A value that specifies the choice of a rasterized font when the system contains multiple fonts with the same name. |
| [TtOnly](#TtOnly) | A value that specifies the requirement for only TrueType fonts. |
| [Outline](#Outline) | A value that specifies the requirement for TrueType and other outline fonts. |
| [ScreenOutline](#ScreenOutline) | A value that specifies a preference for TrueType and other outline fonts. |
| [PsOnly](#PsOnly) | A value that specifies a requirement for only PostScript fonts. |
### Default {#Default}
```
public static final byte Default
```


A value that specifies default behavior.

### String {#String}
```
public static final byte String
```


A value that is returned when rasterized fonts are enumerated.

### Stroke {#Stroke}
```
public static final byte Stroke
```


A value that is returned when TrueType and other outline fonts, and vector fonts are enumerated.

### Tt {#Tt}
```
public static final byte Tt
```


A value that specifies the choice of a TrueType font when the system contains multiple fonts with the same name.

### Device {#Device}
```
public static final byte Device
```


A value that specifies the choice of a device font when the system contains multiple fonts with the same name.

### Raster {#Raster}
```
public static final byte Raster
```


A value that specifies the choice of a rasterized font when the system contains multiple fonts with the same name.

### TtOnly {#TtOnly}
```
public static final byte TtOnly
```


A value that specifies the requirement for only TrueType fonts. If there are no TrueType fonts installed in the system, default behavior is specified.

### Outline {#Outline}
```
public static final byte Outline
```


A value that specifies the requirement for TrueType and other outline fonts.

### ScreenOutline {#ScreenOutline}
```
public static final byte ScreenOutline
```


A value that specifies a preference for TrueType and other outline fonts.

### PsOnly {#PsOnly}
```
public static final byte PsOnly
```


A value that specifies a requirement for only PostScript fonts. If there are no PostScript fonts installed in the system, default behavior is specified.

