---
title: "EmfStretchMode"
second_title: "Aspose.Imaging för Java API-referens"
description: "StretchMode‑uppräkningen används för att ange hur färgdata läggs till eller tas bort från bitmaps som sträcks eller komprimeras."
type: docs
weight: 43
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStretchMode extends System.Enum
```

StretchMode‑uppräkningen används för att ange hur färgdata läggs till eller tas bort från bitmaps som sträcks eller komprimeras.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [STRETCH_ANDSCANS](#STRETCH-ANDSCANS) | Utför en Boolean AND‑operation med färgvärdena för de eliminerade och befintliga pixlarna. |
| [STRETCH_ORSCANS](#STRETCH-ORSCANS) | Utför en Boolean OR‑operation med färgvärdena för de eliminerade och befintliga pixlarna. |
| [STRETCH_DELETESCANS](#STRETCH-DELETESCANS) | Tar bort pixlarna. |
| [STRETCH_HALFTONE](#STRETCH-HALFTONE) | Mappar pixlar från källrektangeln till block av pixlar i destinationsrektangeln. |
### STRETCH_ANDSCANS {#STRETCH-ANDSCANS}
```
public static final int STRETCH_ANDSCANS
```


Utför en boolesk AND‑operation med färgvärdena för de eliminerade och befintliga pixlarna. Om bitmapen är en monokrom bitmap bevarar detta läge svarta pixlar på bekostnad av vita pixlar

### STRETCH_ORSCANS {#STRETCH-ORSCANS}
```
public static final int STRETCH_ORSCANS
```


Utför en boolesk OR‑operation med färgvärdena för de eliminerade och befintliga pixlarna. Om bitmapen är en monokrom bitmap bevarar detta läge vita pixlar på bekostnad av svarta pixlar.

### STRETCH_DELETESCANS {#STRETCH-DELETESCANS}
```
public static final int STRETCH_DELETESCANS
```


Tar bort pixlarna. Detta läge tar bort alla eliminerade pixelrader utan att försöka bevara deras information.

### STRETCH_HALFTONE {#STRETCH-HALFTONE}
```
public static final int STRETCH_HALFTONE
```


Mappar pixlar från källrektangeln till block av pixlar i destinationsrektangeln. Den genomsnittliga färgen över destinationsblocket av pixlar approximera färgen på källpixlarna.

