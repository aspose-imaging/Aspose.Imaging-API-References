---
title: "EmfPlusSetTsClip"
second_title: "Aspose.Imaging för Java API-referens"
description: "Den EmfPlusSetTSClip-posten specificerar klippningsområden i grafikens enhetskontext för en terminalserver."
type: docs
weight: 66
url: /sv/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussettsclip/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetTsClip extends EmfPlusTerminalServerRecordType
```

Den EmfPlusSetTSClip-posten specificerar klippningsområden i grafikens enhetskontext för en terminalserver.

Komprimeringsschemat för data i denna post använder följande algoritm. Varje punkt i varje rektangel kodas antingen i en enda byte eller i 2 byte. Om punkten kodas i en enda byte måste den högsta biten (0x80) i byten vara satt, och värdet är ett signerat tal representerat av de lägre 7 bitarna. Om den högsta biten inte är satt kodas värdet i 2 byte, där högordningsbyten kodas i de 7 lägre bitarna i den första byten, och lågordningsbytevärdet kodas i den andra byten. Varje punkt kodas som skillnaden mellan punkten i den aktuella rektangeln och punkten i föregående rektangel. Den nedre punkten i rektangeln kodas som skillnaden mellan den nedre koordinaten och den övre koordinaten i den aktuella rektangeln.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [EmfPlusSetTsClip(EmfPlusRecord source)](#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initierar en ny instans av klassen `EmfPlusSetTsClip`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getCompressed()](#getCompressed--) | Hämtar ett värde som indikerar om denna `EmfPlusSetTsClip` är komprimerad. |
| [getNumRects()](#getNumRects--) | Hämtar antalet rects. |
| [getRects()](#getRects--) | Hämtar eller anger en array av NumRects-rectangles som definierar beskärningsområden. |
| [setRects(Rectangle[] value)](#setRects-com.aspose.imaging.Rectangle---) | Hämtar eller anger en array av NumRects-rectangles som definierar beskärningsområden. |
### EmfPlusSetTsClip(EmfPlusRecord source) {#EmfPlusSetTsClip-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetTsClip(EmfPlusRecord source)
```


Initierar en ny instans av klassen `EmfPlusSetTsClip`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Källan. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Hämtar ett värde som indikerar om detta `EmfPlusSetTsClip` är komprimerat. Denna bit specificerar formatet för rektangeldata i fältet rects. Om den är satt definieras varje rektangel med 4 byte. Om den är rensad definieras varje rektangel med 8 byte.

Värde: `true` om komprimerad; annars `false`.

**Returns:**
boolean
### getNumRects() {#getNumRects--}
```
public short getNumRects()
```


Hämtar antalet rects. Detta fält specificerar antalet rektanglar som är definierade i fältet rect.

Värde: Antalet rects.

**Returns:**
short
### getRects() {#getRects--}
```
public Rectangle[] getRects()
```


Hämtar eller anger en array av NumRects-rectangles som definierar beskärningsområden. Formatet för dessa data bestäms av C-biten i Flags-fältet.

Värde: rects.

**Returns:**
com.aspose.imaging.Rectangle[]
### setRects(Rectangle[] value) {#setRects-com.aspose.imaging.Rectangle---}
```
public void setRects(Rectangle[] value)
```


Hämtar eller anger en array av NumRects-rectangles som definierar beskärningsområden. Formatet för dessa data bestäms av C-biten i Flags-fältet.

Värde: rects.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) |  |

