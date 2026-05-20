---
title: "EmfSetPixelV"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SETPIXELV-Datensatz definiert die Farbe des Pixels an den angegebenen logischen Koordinaten."
type: docs
weight: 135
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfSetPixelV extends EmfDrawingRecordType
```

Der EMR\_SETPIXELV-Datensatz definiert die Farbe des Pixels an den angegebenen logischen Koordinaten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSetPixelV(EmfRecord source)](#EmfSetPixelV-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSetPixelV`-Klasse. |
| [EmfSetPixelV()](#EmfSetPixelV--) | Initialisiert eine neue Instanz der [EmfSetPixelV](../../com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPixel()](#getPixel--) | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15), das die logischen Koordinaten für das Pixel angibt. |
| [setPixel(Point value)](#setPixel-com.aspose.imaging.Point-) | Liest oder setzt ein 64‑Bit WMF PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15), das die logischen Koordinaten für das Pixel angibt. |
| [getArgb32Color()](#getArgb32Color--) | Liest oder setzt ein 32‑Bit WMF ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.8), das die Pixel‑Farbe angibt. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Liest oder setzt ein 32‑Bit WMF ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.8), das die Pixel‑Farbe angibt. |
### EmfSetPixelV(EmfRecord source) {#EmfSetPixelV-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetPixelV(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSetPixelV`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfSetPixelV() {#EmfSetPixelV--}
```
public EmfSetPixelV()
```


Initialisiert eine neue Instanz der [EmfSetPixelV](../../com.aspose.imaging.fileformats.emf.emf.records/emfsetpixelv)-Klasse.

### getPixel() {#getPixel--}
```
public Point getPixel()
```


Liest oder setzt ein 64‑Bit WMF PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15), das die logischen Koordinaten für das Pixel angibt.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setPixel(Point value) {#setPixel-com.aspose.imaging.Point-}
```
public void setPixel(Point value)
```


Liest oder setzt ein 64‑Bit WMF PointL‑Objekt ([MS-WMF] Abschnitt 2.2.2.15), das die logischen Koordinaten für das Pixel angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Liest oder setzt ein 32‑Bit WMF ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.8), das die Pixel‑Farbe angibt.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Liest oder setzt ein 32‑Bit WMF ColorRef‑Objekt ([MS-WMF] Abschnitt 2.2.8), das die Pixel‑Farbe angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

