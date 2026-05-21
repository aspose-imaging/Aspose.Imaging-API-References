---
title: "EmfPlusPathGradientBrushData"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusPathGradientBrushData-objektet specificerar ett bangradient för en grafikpensel."
type: docs
weight: 59
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusPathGradientBrushData extends EmfPlusBaseBrushData
```

EmfPlusPathGradientBrushData-objektet specificerar ett bangradient för en grafikpensel.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i fältet OptionalData. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Hämtar eller anger ett 32-bitars osignerat heltal som specificerar data i fältet OptionalData. |
| [getWrapMode()](#getWrapMode--) | Hämtar eller anger ett 32-bitars signerat heltal från WrapMode‑enumerationen (avsnitt 2.1.1.34) som specificerar om området utanför penselns gräns ska målas. |
| [setWrapMode(int value)](#setWrapMode-int-) | Hämtar eller anger ett 32-bitars signerat heltal från WrapMode‑enumerationen (avsnitt 2.1.1.34) som specificerar om området utanför penselns gräns ska målas. |
| [getCenterArgb32Color()](#getCenterArgb32Color--) | Hämtar eller anger EmfPlusARGB object (avsnitt 2.2.2.1) som specificerar mittfärgen för path gradient brush, vilket är färgen som visas vid mittpunkten av brushen. |
| [setCenterArgb32Color(int value)](#setCenterArgb32Color-int-) | Hämtar eller anger EmfPlusARGB object (avsnitt 2.2.2.1) som specificerar mittfärgen för path gradient brush, vilket är färgen som visas vid mittpunkten av brushen. |
| [getCenterPointF()](#getCenterPointF--) | Hämtar eller anger EmfPlusARGB object (avsnitt 2.2.2.1) som specificerar mittfärgen för path gradient brush, vilket är färgen som visas vid mittpunkten av brushen. |
| [setCenterPointF(PointF value)](#setCenterPointF-com.aspose.imaging.PointF-) | Hämtar eller anger EmfPlusARGB object (avsnitt 2.2.2.1) som specificerar mittfärgen för path gradient brush, vilket är färgen som visas vid mittpunkten av brushen. |
| [getSurroundingArgb32Colors()](#getSurroundingArgb32Colors--) | Hämtar eller anger en array av SurroundingColorCount EmfPlusARGB objects som specificerar färgerna för diskreta punkter på brushens gräns. |
| [setSurroundingArgb32Colors(int[] value)](#setSurroundingArgb32Colors-int---) | Hämtar eller anger en array av SurroundingColorCount EmfPlusARGB objects som specificerar färgerna för diskreta punkter på brushens gräns. |
| [getBoundaryData()](#getBoundaryData--) | Hämtar eller anger gränsen för path gradient brush, som specificeras antingen av en path eller en sluten cardinal spline. |
| [setBoundaryData(EmfPlusBoundaryBase value)](#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-) | Hämtar eller anger gränsen för path gradient brush, som specificeras antingen av en path eller en sluten cardinal spline. |
| [getOptionalData()](#getOptionalData--) | Hämtar eller anger ett valfritt EmfPlusPathGradientBrushOptionalData object (avsnitt 2.2.2.30) som specificerar ytterligare data för path gradient brush. |
| [setOptionalData(EmfPlusPathGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-) | Hämtar eller anger ett valfritt EmfPlusPathGradientBrushOptionalData object (avsnitt 2.2.2.30) som specificerar ytterligare data för path gradient brush. |
### EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData--}
```
public EmfPlusPathGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Hämtar eller anger ett 32‑bit osignerat heltal som specificerar data i OptionalData-fältet. Detta värde MÅSTE bestå av BrushData-flaggor (avsnitt 2.1.2.1). Följande flaggor är relevanta för en path gradient brush:

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Hämtar eller anger ett 32‑bit osignerat heltal som specificerar data i OptionalData-fältet. Detta värde MÅSTE bestå av BrushData-flaggor (avsnitt 2.1.2.1). Följande flaggor är relevanta för en path gradient brush:

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Hämtar eller anger ett 32‑bit signerat heltal från WrapMode-enumerationen (avsnitt 2.1.1.34) som specificerar om området utanför brushens gräns ska målas. Vid målning utanför gränsen anger wrap-läget hur färggradienten upprepas

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Hämtar eller anger ett 32‑bit signerat heltal från WrapMode-enumerationen (avsnitt 2.1.1.34) som specificerar om området utanför brushens gräns ska målas. Vid målning utanför gränsen anger wrap-läget hur färggradienten upprepas

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCenterArgb32Color() {#getCenterArgb32Color--}
```
public int getCenterArgb32Color()
```


Hämtar eller anger EmfPlusARGB object (avsnitt 2.2.2.1) som specificerar mittfärgen för path gradient brush, vilket är färgen som visas vid brushens mittpunkt. Brushens färg förändras gradvis från gränsfärgen till mittfärgen när den går från gränsen till mittpunkten.

**Returns:**
int
### setCenterArgb32Color(int value) {#setCenterArgb32Color-int-}
```
public void setCenterArgb32Color(int value)
```


Hämtar eller anger EmfPlusARGB object (avsnitt 2.2.2.1) som specificerar mittfärgen för path gradient brush, vilket är färgen som visas vid brushens mittpunkt. Brushens färg förändras gradvis från gränsfärgen till mittfärgen när den går från gränsen till mittpunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getCenterPointF() {#getCenterPointF--}
```
public PointF getCenterPointF()
```


Hämtar eller anger EmfPlusARGB object (avsnitt 2.2.2.1) som specificerar mittfärgen för path gradient brush, vilket är färgen som visas vid brushens mittpunkt. Brushens färg förändras gradvis från gränsfärgen till mittfärgen när den går från gränsen till mittpunkten.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setCenterPointF(PointF value) {#setCenterPointF-com.aspose.imaging.PointF-}
```
public void setCenterPointF(PointF value)
```


Hämtar eller anger EmfPlusARGB object (avsnitt 2.2.2.1) som specificerar mittfärgen för path gradient brush, vilket är färgen som visas vid brushens mittpunkt. Brushens färg förändras gradvis från gränsfärgen till mittfärgen när den går från gränsen till mittpunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSurroundingArgb32Colors() {#getSurroundingArgb32Colors--}
```
public int[] getSurroundingArgb32Colors()
```


Hämtar eller anger en array av SurroundingColorCount EmfPlusARGB objects som specificerar färgerna för diskreta punkter på brushens gräns.

**Returns:**
int[]
### setSurroundingArgb32Colors(int[] value) {#setSurroundingArgb32Colors-int---}
```
public void setSurroundingArgb32Colors(int[] value)
```


Hämtar eller anger en array av SurroundingColorCount EmfPlusARGB objects som specificerar färgerna för diskreta punkter på brushens gräns.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int[] |  |

### getBoundaryData() {#getBoundaryData--}
```
public EmfPlusBoundaryBase getBoundaryData()
```


Hämtar eller anger gränsen för path gradient brush, som specificeras antingen av en path eller en sluten cardinal spline. Om BrushDataPath-flaggan är satt i BrushDataFlags-fältet, MÅSTE detta fält innehålla ett EmfPlusBoundaryPathData object (avsnitt 2.2.2.6); annars MÅSTE detta fält innehålla ett EmfPlusBoundaryPointData object (avsnitt 2.2.2.7).

**Returns:**
[EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase)
### setBoundaryData(EmfPlusBoundaryBase value) {#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-}
```
public void setBoundaryData(EmfPlusBoundaryBase value)
```


Hämtar eller anger gränsen för path gradient brush, som specificeras antingen av en path eller en sluten cardinal spline. Om BrushDataPath-flaggan är satt i BrushDataFlags-fältet, MÅSTE detta fält innehålla ett EmfPlusBoundaryPathData object (avsnitt 2.2.2.6); annars MÅSTE detta fält innehålla ett EmfPlusBoundaryPointData object (avsnitt 2.2.2.7).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData getOptionalData()
```


Hämtar eller anger ett valfritt EmfPlusPathGradientBrushOptionalData object (avsnitt 2.2.2.30) som specificerar ytterligare data för path gradient brush. Det specifika innehållet i detta fält bestäms av värdet i BrushDataFlags-fältet.

**Returns:**
[EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata)
### setOptionalData(EmfPlusPathGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusPathGradientBrushOptionalData value)
```


Hämtar eller anger ett valfritt EmfPlusPathGradientBrushOptionalData object (avsnitt 2.2.2.30) som specificerar ytterligare data för path gradient brush. Det specifika innehållet i detta fält bestäms av värdet i BrushDataFlags-fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata) |  |

