---
title: "TiffExifIfd"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die TIFF‑Exif‑Bilddateiverzeichnis‑Klasse."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.tiff/tiffexififd/
---
**Inheritance:**
java.lang.Object
```
public class TiffExifIfd
```

Die TIFF‑Exif‑Bilddateiverzeichnis‑Klasse.

Kapselt einen Zeiger auf das Exif IFD. Interoperabilität, das Exif IFD hat dieselbe Struktur wie das im TIFF spezifizierte IFD. Normalerweise enthält es jedoch keine Bilddaten, wie im Fall von TIFF. Siehe http://www.exiv2.org/tags.html und http://www.awaresystems.be/imaging/tiff/tifftags/exififd.html für weitere Details.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TiffExifIfd()](#TiffExifIfd--) | Initialisiert eine neue Instanz der `TiffExifIfd`-Klasse. |
| [TiffExifIfd(long ifdOffset)](#TiffExifIfd-long-) | Initialisiert eine neue Instanz der `TiffExifIfd`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [hasValue()](#hasValue--) | Gibt einen Wert zurück, der angibt, ob diese Instanz einen Wert hat. |
| [getOffset()](#getOffset--) | Liest oder setzt den Zeiger auf das EXIF IFD. |
| [setOffset(long value)](#setOffset-long-) | Liest oder setzt den Zeiger auf das EXIF IFD. |
### TiffExifIfd() {#TiffExifIfd--}
```
public TiffExifIfd()
```


Initialisiert eine neue Instanz der `TiffExifIfd`-Klasse.

### TiffExifIfd(long ifdOffset) {#TiffExifIfd-long-}
```
public TiffExifIfd(long ifdOffset)
```


Initialisiert eine neue Instanz der `TiffExifIfd`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | ifdOffset | long | Ein Zeiger auf das Exif IFD. |

Interoperabilität, das Exif IFD hat dieselbe Struktur wie das im TIFF spezifizierte IFD. Normalerweise enthält es jedoch keine Bilddaten, wie im Fall von TIFF. |

### hasValue() {#hasValue--}
```
public boolean hasValue()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz einen Wert hat.

**Returns:**
boolean - `true`, wenn diese Instanz einen Wert hat; andernfalls `false`.
### getOffset() {#getOffset--}
```
public long getOffset()
```


Liest oder setzt den Zeiger auf das EXIF IFD.

**Returns:**
long - Der Zeiger auf das EXIF IFD.
### setOffset(long value) {#setOffset-long-}
```
public void setOffset(long value)
```


Liest oder setzt den Zeiger auf das EXIF IFD.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | long | Der Zeiger auf das EXIF IFD. |

