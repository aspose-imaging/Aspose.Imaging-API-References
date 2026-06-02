---
title: "EmfRectangle"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_RECTANGLE-Datensatz zeichnet ein Rechteck."
type: docs
weight: 107
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfrectangle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfRectangle extends EmfDrawingRecordType
```

Der EMR\_RECTANGLE-Datensatz zeichnet ein Rechteck. Das Rechteck wird mit dem aktuellen Stift umrissen und mit dem aktuellen Pinsel gefüllt.

Die aktuelle Position wird von Rectangle weder verwendet noch aktualisiert. Wenn ein PS\_NULL-Stift verwendet wird, sind die Abmessungen des Rechtecks in der Höhe um 1 Pixel und in der Breite um 1 Pixel kleiner.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfRectangle(EmfRecord source)](#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfRectangle`-Klasse. |
| [EmfRectangle()](#EmfRectangle--) | Initialisiert eine neue Instanz der `EmfRectangle`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBox()](#getBox--) | Liest oder setzt ein 128‑Bit WMF RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das inklusiv‑inklusive Rechteck zum Zeichnen angibt. |
| [setBox(Rectangle value)](#setBox-com.aspose.imaging.Rectangle-) | Liest oder setzt ein 128‑Bit WMF RectL‑Objekt, angegeben in [MS-WMF] Abschnitt 2.2.2.19, das das inklusiv‑inklusive Rechteck zum Zeichnen angibt. |
### EmfRectangle(EmfRecord source) {#EmfRectangle-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRectangle(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfRectangle`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfRectangle() {#EmfRectangle--}
```
public EmfRectangle()
```


Initialisiert eine neue Instanz der `EmfRectangle`-Klasse.

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

