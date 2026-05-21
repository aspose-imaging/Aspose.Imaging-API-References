---
title: "Interpolationsläge"
second_title: "Aspose.Imaging för Java API-referens"
description: "Enumen com.aspose.imaging.InterpolationMode specificerar den algoritm som används när bilder skalas eller roteras."
type: docs
weight: 65
url: /sv/java/com.aspose.imaging/interpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class InterpolationMode extends System.Enum
```

`com.aspose.imaging.InterpolationMode`-enumerationen anger den algoritm som används när bilder skalas eller roteras.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Invalid](#Invalid) | Ogiltigt interpolationsläge. |
| [Default](#Default) | Anger standardläge. |
| [Low](#Low) | Anger interpolering med låg kvalitet. |
| [High](#High) | Anger interpolering med hög kvalitet. |
| [Bilinear](#Bilinear) | Anger bilinjär interpolering. |
| [Bicubic](#Bicubic) | Anger bikubisk interpolering. |
| [NearestNeighbor](#NearestNeighbor) | Anger närmaste-granneinterpolering. |
| [HighQualityBilinear](#HighQualityBilinear) | Anger högkvalitativ, bilinjär interpolering. |
| [HighQualityBicubic](#HighQualityBicubic) | Anger högkvalitativ, bikubisk interpolering. |
### Invalid {#Invalid}
```
public static final int Invalid
```


Ogiltigt interpolationsläge.

### Default {#Default}
```
public static final int Default
```


Anger standardläge.

### Low {#Low}
```
public static final int Low
```


Anger interpolering med låg kvalitet.

### High {#High}
```
public static final int High
```


Anger interpolering med hög kvalitet.

### Bilinear {#Bilinear}
```
public static final int Bilinear
```


Anger bilinjär interpolering. Ingen förfiltrering utförs. Detta läge är inte lämpligt för att minska en bild till under 50 procent av dess ursprungliga storlek.

### Bicubic {#Bicubic}
```
public static final int Bicubic
```


Anger bikubisk interpolering. Ingen förfiltrering utförs. Detta läge är inte lämpligt för att minska en bild till under 25 procent av dess ursprungliga storlek.

### NearestNeighbor {#NearestNeighbor}
```
public static final int NearestNeighbor
```


Anger närmaste-granneinterpolering.

### HighQualityBilinear {#HighQualityBilinear}
```
public static final int HighQualityBilinear
```


Anger högkvalitativ, bilinjär interpolering. Förfiltrering utförs för att säkerställa högkvalitativ krympning.

### HighQualityBicubic {#HighQualityBicubic}
```
public static final int HighQualityBicubic
```


Anger högkvalitativ, bikubisk interpolering. Förfiltrering utförs för att säkerställa högkvalitativ krympning. Detta läge producerar de högsta kvaliteten på transformerade bilder.

