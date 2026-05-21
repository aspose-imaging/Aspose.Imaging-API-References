---
title: "EmfSetColorAdjustment"
second_title: "Aspose.Imaging för Java API-referens"
description: "Posten EMR_SETCOLORADJUSTMENT specificerar färgjusteringsegenskaper i uppspelningsenhetens kontext."
type: docs
weight: 122
url: /sv/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetColorAdjustment extends EmfStateRecordType
```

EMR\_SETCOLORADJUSTMENT-posten specificerar färgjusteringsegenskaper i uppspelningsenhetskontexten.

Färgjusteringsvärden används för att justera ingångsfärgen på källbitmapen för grafikoperationer som utförs av EMR\_STRETCHBLT- och EMR\_STRETCHDIBITS-poster när STRETCH\_HALFTONE-läget är inställt från StretchMode‑enumerationen (avsnitt 2.1.32). Det ColorAdjustment‑objekt som specificeras av denna post MÅSTE användas i grafikoperationer som kräver ett ColorAdjustment‑objekt, tills ett annat ColorAdjustment‑objekt specificeras av en annan EMR\_SETCOLORADJUSTMENT-post, eller tills objektet tas bort av en EMR\_DELETEOBJECT-post.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfSetColorAdjustment(EmfRecord source)](#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initierar en ny instans av klassen `EmfSetColorAdjustment`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getColorAdjustment()](#getColorAdjustment--) | Hämtar eller anger ett ColorAdjustment‑objekt (avsnitt 2.2.2) som specificerar färgjusteringsvärden. |
| [setColorAdjustment(EmfColorAdjustment value)](#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-) | Hämtar eller anger ett ColorAdjustment‑objekt (avsnitt 2.2.2) som specificerar färgjusteringsvärden. |
### EmfSetColorAdjustment(EmfRecord source) {#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorAdjustment(EmfRecord source)
```


Initierar en ny instans av klassen `EmfSetColorAdjustment`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Källan. |

### getColorAdjustment() {#getColorAdjustment--}
```
public EmfColorAdjustment getColorAdjustment()
```


Hämtar eller anger ett ColorAdjustment‑objekt (avsnitt 2.2.2) som specificerar färgjusteringsvärden.

**Returns:**
[EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment)
### setColorAdjustment(EmfColorAdjustment value) {#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-}
```
public void setColorAdjustment(EmfColorAdjustment value)
```


Hämtar eller anger ett ColorAdjustment‑objekt (avsnitt 2.2.2) som specificerar färgjusteringsvärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment) |  |

