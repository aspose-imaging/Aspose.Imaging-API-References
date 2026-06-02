---
title: "ColorMatrixFlag"
second_title: "Aspose.Imaging för Java API-referens"
description: "Anger typerna av bilder och färger som kommer att påverkas av färg- och gråskalajusteringens inställningar för en ."
type: docs
weight: 27
url: /sv/java/com.aspose.imaging/colormatrixflag/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ColorMatrixFlag extends System.Enum
```

Anger typerna av bilder och färger som kommer att påverkas av färg- och gråskalajusteringens inställningar för en [ImageAttributes](../../com.aspose.imaging/imageattributes).
## Fält

| Fält | Beskrivning |
| --- | --- |
| [Default](#Default) | Alla färgvärden, inklusive grå nyanser, justeras med samma färgjusteringsmatris. |
| [SkipGrays](#SkipGrays) | Alla färger justeras, men grå nyanser justeras inte. |
| [AltGrays](#AltGrays) | Endast grå nyanser justeras. |
### Default {#Default}
```
public static final int Default
```


Alla färgvärden, inklusive grå nyanser, justeras med samma färgjusteringsmatris.

### SkipGrays {#SkipGrays}
```
public static final int SkipGrays
```


Alla färger justeras, men grå nyanser justeras inte. En grå nyans är vilken färg som helst som har samma värde för sina röda, gröna och blå komponenter.

### AltGrays {#AltGrays}
```
public static final int AltGrays
```


Endast grå nyanser justeras.

