---
title: "Os22XBitmapHeader"
second_title: "Aspose.Imaging för Java API-referens"
description: "En OS/2 2.x OS22XBITMAPHEADER, även känd som BITMAPCOREHEADER2."
type: docs
weight: 16
url: /sv/java/com.aspose.imaging.fileformats.bmp/os22xbitmapheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class Os22XBitmapHeader extends BitmapInfoHeader
```

En OS/2 2.x OS22XBITMAPHEADER, även känd som BITMAPCOREHEADER2.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getUnits()](#getUnits--) | Hämtar enheterna. |
| [getReserved()](#getReserved--) | Hämtar reserverade. |
| [getRecording()](#getRecording--) | Hämtar inspelningen. |
| [getRendering()](#getRendering--) | Hämtar rendering. |
| [getSize1()](#getSize1--) | Hämtar storlek1. |
| [getSize2()](#getSize2--) | Hämtar storlek2. |
| [getColorEncoding()](#getColorEncoding--) | Hämtar färgkodning. |
| [getIdentifier()](#getIdentifier--) | Hämtar identifieraren. |
### getUnits() {#getUnits--}
```
public int getUnits()
```


Hämtar enheterna.

**Returns:**
int - Typ av enheter som används för att mäta upplösning
### getReserved() {#getReserved--}
```
public int getReserved()
```


Hämtar reserverade.

**Returns:**
int - Fyllstruktur till 4-byte gräns
### getRecording() {#getRecording--}
```
public int getRecording()
```


Hämtar inspelningen.

**Returns:**
int - Inspelningsalgoritm
### getRendering() {#getRendering--}
```
public int getRendering()
```


Hämtar rendering.

**Returns:**
int - Halvtoningsalgoritm som används
### getSize1() {#getSize1--}
```
public int getSize1()
```


Hämtar storlek1.

**Returns:**
int - Reserverad för användning av halvtoningsalgoritm
### getSize2() {#getSize2--}
```
public int getSize2()
```


Hämtar storlek2.

**Returns:**
int - Reserverad för användning av halvtoningsalgoritm
### getColorEncoding() {#getColorEncoding--}
```
public int getColorEncoding()
```


Hämtar färgkodning.

**Returns:**
int - Färgsmodell som används i bitmap
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


Hämtar identifieraren.

**Returns:**
int - Reserverad för applikationsbruk
