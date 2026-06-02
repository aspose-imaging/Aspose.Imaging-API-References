---
title: "EmfIntersectClipRect"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_INTERSECTCLIPRECT‑Datensatz definiert einen neuen Clipping‑Bereich aus der Schnittmenge des aktuellen Clipping‑Bereichs und des angegebenen Rechtecks."
type: docs
weight: 66
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfintersectcliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfIntersectClipRect extends EmfClippingRecordType
```

Der EMR\_INTERSECTCLIPRECT‑Datensatz definiert einen neuen Clipping‑Bereich aus der Schnittmenge des aktuellen Clipping‑Bereichs und des angegebenen Rechtecks. Hinweis: Felder, die in diesem Abschnitt nicht beschrieben werden, sind in Abschnitt 2.3.2 angegeben.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfIntersectClipRect(EmfRecord source)](#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfIntersectClipRect`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getClip()](#getClip--) | Liest oder setzt ein WMF RectL-Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Rechteck in logischen Einheiten angibt. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | Liest oder setzt ein WMF RectL-Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Rechteck in logischen Einheiten angibt. |
### EmfIntersectClipRect(EmfRecord source) {#EmfIntersectClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfIntersectClipRect(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfIntersectClipRect`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getClip() {#getClip--}
```
public Rectangle getClip()
```


Liest oder setzt ein WMF RectL-Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Rechteck in logischen Einheiten angibt.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


Liest oder setzt ein WMF RectL-Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Rechteck in logischen Einheiten angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

