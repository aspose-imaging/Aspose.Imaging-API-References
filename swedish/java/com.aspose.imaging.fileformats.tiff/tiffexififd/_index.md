---
title: "TiffExifIfd"
second_title: "Aspose.Imaging för Java API-referens"
description: "TIFF Exif bildfilskatalogklass."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.tiff/tiffexififd/
---
**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

TIFF Exif bildfilskatalogklass.

Inkapslar en pekare till Exif IFD. Interoperabilitet, Exif IFD har samma struktur som den IFD som specificerats i TIFF. Vanligtvis innehåller den dock inte bilddata som i fallet med TIFF. Se http://www.exiv2.org/tags.html och http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html för mer information.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | Initierar en ny instans av klassen `TiffExifIfd`. |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | Initierar en ny instans av klassen `TiffExifIfd`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [hasValue()](#hasValue--) | Hämtar ett värde som indikerar om denna instans har ett värde. |
| [getOffset()](#getOffset--) | Hämtar eller anger pekaren till EXIF IFD. |
| [setOffset(long value)](#setOffset-long-) | Hämtar eller anger pekaren till EXIF IFD. |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


Initierar en ny instans av klassen `TiffExifIfd`.

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


Initierar en ny instans av klassen `TiffExifIfd`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ifdOffset | long | En pekare till Exif IFD. |

Interoperabilitet, Exif IFD har samma struktur som den IFD som specificerats i TIFF. Vanligtvis innehåller den dock inte bilddata som i fallet med TIFF. |

### hasValue() {#hasValue--}
```
public boolean hasValue()
```


Hämtar ett värde som indikerar om denna instans har ett värde.

**Returns:**
boolean - `true` om denna instans har ett värde; annars `false`.
### getOffset() {#getOffset--}
```
public long getOffset()
```


Hämtar eller anger pekaren till EXIF IFD.

**Returns:**
long - Pekaren till EXIF IFD.
### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


Hämtar eller anger pekaren till EXIF IFD.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long | Pekaren till EXIF IFD. |

