---
title: "EmfPolyDraw"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_POLYDRAW‑Record gibt eine Menge von Liniensegmenten und Bézier‑Kurven an."
type: docs
weight: 89
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw extends EmfPolyShape
```

Der EMR\\_POLYDRAW-Datensatz spezifiziert einen Satz von Liniensegmenten und Bézier-Kurven.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPolyDraw(EmfRecord source)](#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfPolyDraw`‑Klasse. |
| [EmfPolyDraw()](#EmfPolyDraw--) | Initialisiert eine neue Instanz der [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw)‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | Liest ein Array der Länge Count mit Byte‑Werten, das angibt, wie jeder Punkt im Gets or sets aPoints‑Array verwendet wird. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Setzt ein Array der Länge Count mit Byte‑Werten, das angibt, wie jeder Punkt im Gets or sets aPoints‑Array verwendet wird. |
### EmfPolyDraw(EmfRecord source) {#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfPolyDraw`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfPolyDraw() {#EmfPolyDraw--}
```
public EmfPolyDraw()
```


Initialisiert eine neue Instanz der [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw)‑Klasse.

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Liest ein Array der Länge Count mit Byte‑Werten, das angibt, wie jeder Punkt im Gets or sets aPoints‑Array verwendet wird. Dieser Wert MUSS in der Point‑Aufzählung (Abschnitt 2.1.26) liegen.

**Returns:**
byte[] – ein Array der Länge Count mit Byte‑Werten, das angibt, wie jeder Punkt im Gets or sets aPoints‑Array verwendet wird.
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Setzt ein Array der Länge Count mit Byte‑Werten, das angibt, wie jeder Punkt im Gets or sets aPoints‑Array verwendet wird. Dieser Wert MUSS in der Point‑Aufzählung (Abschnitt 2.1.26) liegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte[] | ein Array der Länge Count mit Byte‑Werten, das angibt, wie jeder Punkt im Gets or sets aPoints‑Array verwendet wird. |

