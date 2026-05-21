---
title: "WmfGamutMappingIntent"
second_title: "Aspose.Imaging för Java API-referens"
description: "GamutMappingIntent‑enumerationen specificerar förhållandet mellan logiska och fysiska färger."
type: docs
weight: 20
url: /sv/java/com.aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfGamutMappingIntent extends System.Enum
```

GamutMappingIntent‑enumerationen specificerar förhållandet mellan logiska och fysiska färger.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [LCS_GM_ABS_COLORIMETRIC](#LCS-GM-ABS-COLORIMETRIC) | Anger att vitpunkten SKALL bibehållas. |
| [LCS_GM_BUSINESS](#LCS-GM-BUSINESS) | Anger att mättnad SKALL upprätthållas. |
| [LCS_GM_GRAPHICS](#LCS-GM-GRAPHICS) | Anger att en kolorimetrisk matchning SKALL upprätthållas. |
| [LCS_GM_IMAGES](#LCS-GM-IMAGES) | Anger att kontrast SKALL upprätthållas. |
### LCS_GM_ABS_COLORIMETRIC {#LCS-GM-ABS-COLORIMETRIC}
```
public static final int LCS_GM_ABS_COLORIMETRIC
```


Anger att vitpunkten SKALL upprätthållas. Används vanligtvis när logiska färger MÅSTE matchas till deras närmaste fysiska färg i mål-färgomfånget. Avsikt: Match ICC name: Absolute Colorimetric

### LCS_GM_BUSINESS {#LCS-GM-BUSINESS}
```
public static final int LCS_GM_BUSINESS
```


Anger att mättnad SKALL upprätthållas. Används vanligtvis för affärsgrafer och andra situationer där dithering inte krävs. Avsikt: Graphic ICC name: Saturation

### LCS_GM_GRAPHICS {#LCS-GM-GRAPHICS}
```
public static final int LCS_GM_GRAPHICS
```


Anger att en kolorimetrisk matchning SKALL upprätthållas. Används vanligtvis för grafisk design och namngivna färger. Avsikt: Proof ICC name: Relative Colorimetric

### LCS_GM_IMAGES {#LCS-GM-IMAGES}
```
public static final int LCS_GM_IMAGES
```


Anger att kontrast SKALL upprätthållas. Används vanligtvis för fotografier och naturliga bilder. Avsikt: Picture ICC name: Perceptual

