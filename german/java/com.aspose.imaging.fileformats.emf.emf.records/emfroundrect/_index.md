---
title: "EmfRoundRect"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_ROUNDRECT-Datensatz definiert ein Rechteck mit abgerundeten Ecken."
type: docs
weight: 111
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfroundrect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRoundRect extends EmfDrawingRecordType
```

Der EMR\_ROUNDRECT-Datensatz definiert ein Rechteck mit abgerundeten Ecken. Das Rechteck wird mit dem aktuellen Stift umrandet und mit dem aktuellen Pinsel gefüllt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfRoundRect(EmfRecord source)](#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfRoundRect`-Klasse. |
| [EmfRoundRect()](#EmfRoundRect--) | Initialisiert eine neue Instanz der [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBox()](#getBox--) | Liest oder setzt ein 128‑Bit WMF RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das inklusiv‑inklusive Rechteck zum Zeichnen angibt. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Liest oder setzt ein 128‑Bit WMF RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das inklusiv‑inklusive Rechteck zum Zeichnen angibt. |
| [getCorner()](#getCorner--) | Liest oder setzt ein 64‑Bit WMF SizeL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.22, das die Breite und Höhe in logischen Koordinaten der zum Zeichnen der abgerundeten Ecken verwendeten Ellipse angibt. |
| [setCorner(Size value)](#setCorner-com.aspose.imaging.Size-) | Liest oder setzt ein 64‑Bit WMF SizeL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.22, das die Breite und Höhe in logischen Koordinaten der zum Zeichnen der abgerundeten Ecken verwendeten Ellipse angibt. |
### EmfRoundRect(EmfRecord source) {#EmfRoundRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRoundRect(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfRoundRect`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfRoundRect() {#EmfRoundRect--}
```
public EmfRoundRect()
```


Initialisiert eine neue Instanz der [EmfRoundRect](../../com.aspose.imaging.fileformats.emf.emf.records/emfroundrect) Klasse.

### getBox() {#getBox--}
```
public Rectangle getBox()
```


Liest oder setzt ein 128‑Bit WMF RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das inklusiv‑inklusive Rechteck zum Zeichnen angibt.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBox(Rectangle value) {#setBox-com.aspose.imaging.Rectangle-}
```
public void setBox(Rectangle value)
```


Liest oder setzt ein 128‑Bit WMF RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das inklusiv‑inklusive Rechteck zum Zeichnen angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getCorner() {#getCorner--}
```
public Size getCorner()
```


Liest oder setzt ein 64‑Bit WMF SizeL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.22, das die Breite und Höhe in logischen Koordinaten der zum Zeichnen der abgerundeten Ecken verwendeten Ellipse angibt.

**Returns:**
[Size](../../com.aspose.imaging/size)
### setCorner(Size value) {#setCorner-com.aspose.imaging.Size-}
```
public void setCorner(Size value)
```


Liest oder setzt ein 64‑Bit WMF SizeL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.22, das die Breite und Höhe in logischen Koordinaten der zum Zeichnen der abgerundeten Ecken verwendeten Ellipse angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) |  |

