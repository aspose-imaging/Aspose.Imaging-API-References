---
title: "EmfPlusLinearGradientBrushData"
second_title: "Aspose.Imaging för Java API-referens"
description: "EmfPlusLinearGradientBrushData-objektet specificerar en linjär gradient för en grafikpensel."
type: docs
weight: 53
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusLinearGradientBrushData extends EmfPlusBaseBrushData
```

EmfPlusLinearGradientBrushData-objektet specificerar en linjär gradient för en grafikpensel.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusLinearGradientBrushData()](#EmfPlusLinearGradientBrushData--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Hämtar eller anger penseldatabflagorna. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Hämtar eller anger penseldatabflagorna. |
| [getEndArgb32Color()](#getEndArgb32Color--) | Hämtar eller anger slutfärgen. |
| [setEndArgb32Color(int value)](#setEndArgb32Color-int-) | Hämtar eller anger slutfärgen. |
| [getOptionalData()](#getOptionalData--) | Hämtar eller anger valfri data. |
| [setOptionalData(EmfPlusLinearGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-) | Hämtar eller anger valfri data. |
| [getRectF()](#getRectF--) | Hämtar eller anger rect f. |
| [setRectF(RectangleF value)](#setRectF-com.aspose.imaging.RectangleF-) | Hämtar eller anger rect f. |
| [getStartArgb32Color()](#getStartArgb32Color--) | Hämtar eller anger startfärgen. |
| [setStartArgb32Color(int value)](#setStartArgb32Color-int-) | Hämtar eller anger startfärgen. |
| [getWrapMode()](#getWrapMode--) | Hämtar eller anger omslagsläget. |
| [setWrapMode(int value)](#setWrapMode-int-) | Hämtar eller anger omslagsläget. |
### EmfPlusLinearGradientBrushData() {#EmfPlusLinearGradientBrushData--}
```
public EmfPlusLinearGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Hämtar eller anger penseldatabflagorna.

Värde: BrushDataFlags (4 byte): Ett 32-bitars osignerat heltal som specificerar data i fältet OptionalData. Detta värde MÅSTE bestå av `EmfPlusBrushDataFlags` (avsnitt 2.1.2.1).

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Hämtar eller anger penseldatabflagorna.

Värde: BrushDataFlags (4 byte): Ett 32-bitars osignerat heltal som specificerar data i fältet OptionalData. Detta värde MÅSTE bestå av `EmfPlusBrushDataFlags` (avsnitt 2.1.2.1).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getEndArgb32Color() {#getEndArgb32Color--}
```
public int getEndArgb32Color()
```


Hämtar eller anger slutfärgen.

Värde: Ett EmfPlusARGB-objekt som specificerar färgen vid den avslutande gränspunkten för den linjära gradientpenseln.

**Returns:**
int
### setEndArgb32Color(int value) {#setEndArgb32Color-int-}
```
public void setEndArgb32Color(int value)
```


Hämtar eller anger slutfärgen.

Värde: Ett EmfPlusARGB-objekt som specificerar färgen vid den avslutande gränspunkten för den linjära gradientpenseln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData getOptionalData()
```


Hämtar eller anger valfri data.

Värde: Ett valfritt `EmfPlusLinearGradientBrushOptionalData`-objekt (avsnitt 2.2.2.25) som specificerar ytterligare data för den linjära gradientpenseln. Det specifika innehållet i detta fält bestäms av värdet i BrushDataFlags-fältet.

**Returns:**
[EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata)
### setOptionalData(EmfPlusLinearGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusLinearGradientBrushOptionalData value)
```


Hämtar eller anger valfri data.

Värde: Ett valfritt `EmfPlusLinearGradientBrushOptionalData`-objekt (avsnitt 2.2.2.25) som specificerar ytterligare data för den linjära gradientpenseln. Det specifika innehållet i detta fält bestäms av värdet i BrushDataFlags-fältet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfPlusLinearGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata) |  |

### getRectF() {#getRectF--}
```
public RectangleF getRectF()
```


Hämtar eller anger rect f.

Värde: Ett EmfPlusRectF-objekt (avsnitt 2.2.2.39) som specificerar start- och slutpunkterna för gradientlinjen. Det övre vänstra hörnet av rektangeln är startpunkten. Det nedre högra hörnet är slutpunkten.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setRectF(RectangleF value) {#setRectF-com.aspose.imaging.RectangleF-}
```
public void setRectF(RectangleF value)
```


Hämtar eller anger rect f.

Värde: Ett EmfPlusRectF-objekt (avsnitt 2.2.2.39) som specificerar start- och slutpunkterna för gradientlinjen. Det övre vänstra hörnet av rektangeln är startpunkten. Det nedre högra hörnet är slutpunkten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStartArgb32Color() {#getStartArgb32Color--}
```
public int getStartArgb32Color()
```


Hämtar eller anger startfärgen.

Värde: Ett EmfPlusARGB-objekt (avsnitt 2.2.2.1) som specificerar färgen vid startgränspunkten för den linjära gradientpenseln.

**Returns:**
int
### setStartArgb32Color(int value) {#setStartArgb32Color-int-}
```
public void setStartArgb32Color(int value)
```


Hämtar eller anger startfärgen.

Värde: Ett EmfPlusARGB-objekt (avsnitt 2.2.2.1) som specificerar färgen vid startgränspunkten för den linjära gradientpenseln.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Hämtar eller anger omslagsläget.

Värde: Ett 32-bitars signerat heltal från WrapMode‑enumerationen (avsnitt 2.1.1.34) som specificerar om området utanför penselns gräns ska målas. Vid målning utanför gränsen anger omslagsläget hur färggradienten upprepas.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Hämtar eller anger omslagsläget.

Värde: Ett 32-bitars signerat heltal från WrapMode‑enumerationen (avsnitt 2.1.1.34) som specificerar om området utanför penselns gräns ska målas. Vid målning utanför gränsen anger omslagsläget hur färggradienten upprepas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

