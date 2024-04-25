---
title: EmfPlusDriverStringOptionsFlags
second_title: Aspose.Imaging for Java API Reference
description: The DriverStringOptions flags specify properties of graphics text positioning and rendering.
type: docs
weight: 21
url: /com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusdriverstringoptionsflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusDriverStringOptionsFlags extends System.Enum
```

The DriverStringOptions flags specify properties of graphics text positioning and rendering. These flags can be combined to specify multiple options.

--------------------

Graphics text output is specified in [EmfPlusDrawDriverString](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawdriverstring) records
## Fields

| Field | Description |
| --- | --- |
| [DriverStringOptionsCmapLookup](#DriverStringOptionsCmapLookup) | If set, the positions of character glyphs SHOULD be specified in a character map lookup table. |
| [DriverStringOptionsVertical](#DriverStringOptionsVertical) | If set, the string SHOULD be rendered vertically. |
| [DriverStringOptionsRealizedAdvance](#DriverStringOptionsRealizedAdvance) | If set, character glyph positions SHOULD be calculated relative to the position of the first glyph. |
| [DriverStringOptionsLimitSubpixel](#DriverStringOptionsLimitSubpixel) | If set, less memory SHOULD be used to cache anti-aliased glyphs, which produces lower quality text rendering. |
### DriverStringOptionsCmapLookup {#DriverStringOptionsCmapLookup}
```
public static final int DriverStringOptionsCmapLookup
```


If set, the positions of character glyphs SHOULD be specified in a character map lookup table. If clear, the glyph positions SHOULD be obtained from an array of coordinates.

### DriverStringOptionsVertical {#DriverStringOptionsVertical}
```
public static final int DriverStringOptionsVertical
```


If set, the string SHOULD be rendered vertically. If clear, the string SHOULD be rendered horizontally.

### DriverStringOptionsRealizedAdvance {#DriverStringOptionsRealizedAdvance}
```
public static final int DriverStringOptionsRealizedAdvance
```


If set, character glyph positions SHOULD be calculated relative to the position of the first glyph. If clear, the glyph positions SHOULD be obtained from an array of coordinates.

### DriverStringOptionsLimitSubpixel {#DriverStringOptionsLimitSubpixel}
```
public static final int DriverStringOptionsLimitSubpixel
```


If set, less memory SHOULD be used to cache anti-aliased glyphs, which produces lower quality text rendering. If clear, more memory SHOULD be used, which produces higher quality text rendering.

