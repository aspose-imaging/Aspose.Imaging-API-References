---
title: "EmfPlusInterpolationMode"
second_title: "Aspose.Imaging för Java API-referens"
description: "InterpolationMode‑enumerationen definierar sätt att utföra skalning inklusive sträckning och krympning."
type: docs
weight: 29
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusinterpolationmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusInterpolationMode extends System.Enum
```

InterpolationMode‑enumerationen definierar sätt att utföra skalning, inklusive sträckning och krympning.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [InterpolationModeDefault](#InterpolationModeDefault) | Anger standardinterpolationsläget, som definieras som InterpolationModeBilinear. |
| [InterpolationModeLowQuality](#InterpolationModeLowQuality) | Anger ett lågkvalitativt interpolationsläge, som definieras som InterpolationModeNearestNeighbor. |
| [InterpolationModeHighQuality](#InterpolationModeHighQuality) | Anger ett högkvalitativt interpolationsläge, som definieras som InterpolationModeHighQualityBicubic. |
| [InterpolationModeBilinear](#InterpolationModeBilinear) | Anger bilinjär interpolation, som använder det närmaste 2×2‑grannskapet av kända pixlar runt den interpolerade pixeln. |
| [InterpolationModeBicubic](#InterpolationModeBicubic) | Anger bikubisk interpolering, som använder det närmaste 4x4-grannskapet av kända pixlar kring den interpolerade pixeln. |
| [InterpolationModeNearestNeighbor](#InterpolationModeNearestNeighbor) | Anger närmaste-granne-interpolering, som endast använder värdet på den pixel som är närmast den interpolerade pixeln. |
| [InterpolationModeHighQualityBilinear](#InterpolationModeHighQualityBilinear) | Anger bilinjär interpolering med förfiltrering. |
| [InterpolationModeHighQualityBicubic](#InterpolationModeHighQualityBicubic) | Anger bikubisk interpolering med förfiltrering, vilket ger det högkvalitativaste resultatet bland dessa alternativ. |
### InterpolationModeDefault {#InterpolationModeDefault}
```
public static final byte InterpolationModeDefault
```


Anger standardinterpolationsläget, som definieras som InterpolationModeBilinear.

### InterpolationModeLowQuality {#InterpolationModeLowQuality}
```
public static final byte InterpolationModeLowQuality
```


Anger ett lågkvalitativt interpolationsläge, som definieras som InterpolationModeNearestNeighbor.

### InterpolationModeHighQuality {#InterpolationModeHighQuality}
```
public static final byte InterpolationModeHighQuality
```


Anger ett högkvalitativt interpolationsläge, som definieras som InterpolationModeHighQualityBicubic.

### InterpolationModeBilinear {#InterpolationModeBilinear}
```
public static final byte InterpolationModeBilinear
```


Anger bilinjär interpolering, som använder det närmaste 2x2-grannskapet av kända pixlar kring den interpolerade pixeln. Det viktade genomsnittet av dessa 4 kända pixelvärden bestämmer värdet som ska tilldelas den interpolerade pixeln. Resultatet ser jämnare ut än InterpolationModeNearestNeighbor.

### InterpolationModeBicubic {#InterpolationModeBicubic}
```
public static final byte InterpolationModeBicubic
```


Anger bikubisk interpolering, som använder det närmaste 4x4-grannskapet av kända pixlar kring den interpolerade pixeln. Det viktade genomsnittet av dessa 16 kända pixelvärden bestämmer värdet som ska tilldelas den interpolerade pixeln. Eftersom de kända pixlarna sannolikt befinner sig på olika avstånd från den interpolerade pixeln, får närmare pixlar en högre vikt i beräkningen. Resultatet ser jämnare ut än InterpolationModeBilinear.

### InterpolationModeNearestNeighbor {#InterpolationModeNearestNeighbor}
```
public static final byte InterpolationModeNearestNeighbor
```


Anger närmaste-granne-interpolering, som endast använder värdet på den pixel som är närmast den interpolerade pixeln. Detta läge duplicerar eller tar bort pixlar, vilket ger det lägsta kvalitetsresultatet bland dessa alternativ.

### InterpolationModeHighQualityBilinear {#InterpolationModeHighQualityBilinear}
```
public static final byte InterpolationModeHighQualityBilinear
```


Anger bilinjär interpolering med förfiltrering.

### InterpolationModeHighQualityBicubic {#InterpolationModeHighQualityBicubic}
```
public static final byte InterpolationModeHighQualityBicubic
```


Anger bikubisk interpolering med förfiltrering, vilket ger det högkvalitativaste resultatet bland dessa alternativ.

