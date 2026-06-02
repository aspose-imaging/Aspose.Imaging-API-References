---
title: "EmfExcludeClipRect"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_EXCLUDECLIPRECT-Datensatz spezifiziert einen neuen Clipping‑Bereich, der aus dem bestehenden Clipping‑Bereich abzüglich des angegebenen Rechtecks besteht."
type: docs
weight: 50
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfexcludecliprect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfClippingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfclippingrecordtype)
```
public final class EmfExcludeClipRect extends EmfClippingRecordType
```

Der EMR\_EXCLUDECLIPRECT-Datensatz spezifiziert einen neuen Clipping‑Bereich, der aus dem bestehenden Clipping‑Bereich abzüglich des angegebenen Rechtecks besteht. Hinweis: Felder, die in diesem Abschnitt nicht beschrieben werden, sind in Abschnitt 2.3.2 angegeben.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfExcludeClipRect(EmfRecord source)](#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfExcludeClipRect`‑Klasse. |
| [EmfExcludeClipRect()](#EmfExcludeClipRect--) | Initialisiert eine neue Instanz der `EmfExcludeClipRect`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getClip()](#getClip--) | Liest ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Clipping‑Rechteck in logischen Einheiten spezifiziert. |
| [setClip(Rectangle value)](#setClip-com.aspose.imaging.Rectangle-) | Setzt ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Clipping‑Rechteck in logischen Einheiten spezifiziert. |
### EmfExcludeClipRect(EmfRecord source) {#EmfExcludeClipRect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExcludeClipRect(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfExcludeClipRect`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfExcludeClipRect() {#EmfExcludeClipRect--}
```
public EmfExcludeClipRect()
```


Initialisiert eine neue Instanz der `EmfExcludeClipRect`‑Klasse.

### getClip() {#getClip--}
```
public Rectangle getClip()
```


Liest ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Clipping‑Rechteck in logischen Einheiten spezifiziert.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setClip(Rectangle value) {#setClip-com.aspose.imaging.Rectangle-}
```
public void setClip(Rectangle value)
```


Setzt ein WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19), das das Clipping‑Rechteck in logischen Einheiten spezifiziert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

