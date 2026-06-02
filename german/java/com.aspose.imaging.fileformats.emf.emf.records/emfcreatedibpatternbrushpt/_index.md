---
title: "EmfCreateDibPatternBrushPt"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_CREATEDIBPATTERNBRUSHPT‑Datensatz definiert einen Musterpinsel für Grafikoperationen."
type: docs
weight: 38
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatedibpatternbrushpt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateDibPatternBrushPt extends EmfObjectCreationRecordType
```

Der EMR\_CREATEDIBPATTERNBRUSHPT‑Datensatz definiert einen Musterpinsel für Grafikoperationen. Das Muster wird durch ein DIB angegeben.

Das durch diesen Datensatz definierte Musterpinsel‑Objekt kann mittels eines EMR\_SELECTOBJECT‑Datensatzes (Abschnitt 2.3.8.5) in den Wiedergabegeräte‑Kontext ausgewählt werden, der den zu verwendenden Musterpinsel für nachfolgende Grafikoperationen angibt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfCreateDibPatternBrushPt(EmfRecord source)](#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfCreateDibPatternBrushPt`‑Klasse. |
| [EmfCreateDibPatternBrushPt()](#EmfCreateDibPatternBrushPt--) | Initialisiert eine neue Instanz der `EmfCreateDibPatternBrushPt`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Index des Musterpinsel‑Objekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [setIhBrush(int value)](#setIhBrush-int-) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Index des Musterpinsel‑Objekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [getUsage()](#getUsage--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der angibt, wie Werte in der Farbtabell im DIB‑Header zu interpretieren sind. |
| [setUsage(int value)](#setUsage-int-) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der angibt, wie Werte in der Farbtabell im DIB‑Header zu interpretieren sind. |
| [getBitmapBuffer()](#getBitmapBuffer--) | Ruft einen Puffer ab oder legt ihn fest, der ein gepacktes DIB in Form eines WMF‑DeviceIndependentBitmap‑Objekts enthält ([MS-WMF] Abschnitt 2.2.2.9). |
| [setBitmapBuffer(WmfDeviceIndependentBitmap value)](#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-) | Ruft einen Puffer ab oder legt ihn fest, der ein gepacktes DIB in Form eines WMF‑DeviceIndependentBitmap‑Objekts enthält ([MS-WMF] Abschnitt 2.2.2.9). |
### EmfCreateDibPatternBrushPt(EmfRecord source) {#EmfCreateDibPatternBrushPt-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateDibPatternBrushPt(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfCreateDibPatternBrushPt`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfCreateDibPatternBrushPt() {#EmfCreateDibPatternBrushPt--}
```
public EmfCreateDibPatternBrushPt()
```


Initialisiert eine neue Instanz der `EmfCreateDibPatternBrushPt`‑Klasse.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Index des Musterpinsel‑Objekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit dieses Objekt wiederverwendet oder geändert werden kann.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Index des Musterpinsel‑Objekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit dieses Objekt wiederverwendet oder geändert werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getUsage() {#getUsage--}
```
public int getUsage()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die angibt, wie Werte in der Farbtafel im DIB‑Header zu interpretieren sind. Dieser Wert MUSS in der DIBColors‑Aufzählung (Abschnitt 2.1.9) liegen.

**Returns:**
int
### setUsage(int value) {#setUsage-int-}
```
public void setUsage(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die angibt, wie Werte in der Farbtafel im DIB‑Header zu interpretieren sind. Dieser Wert MUSS in der DIBColors‑Aufzählung (Abschnitt 2.1.9) liegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBitmapBuffer() {#getBitmapBuffer--}
```
public WmfDeviceIndependentBitmap getBitmapBuffer()
```


Liest oder setzt einen Puffer, der ein gepacktes DIB in Form eines WMF DeviceIndependentBitmap‑Objekts enthält ([MS‑WMF] Abschnitt 2.2.2.9). Es ist nicht erforderlich, dass er zusammenhängend mit dem festen Teil des EMR\_CREATEDIBPATTERNBRUSHPT‑Datensatzes ist.

**Returns:**
[WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap)
### setBitmapBuffer(WmfDeviceIndependentBitmap value) {#setBitmapBuffer-com.aspose.imaging.fileformats.wmf.objects.WmfDeviceIndependentBitmap-}
```
public void setBitmapBuffer(WmfDeviceIndependentBitmap value)
```


Liest oder setzt einen Puffer, der ein gepacktes DIB in Form eines WMF DeviceIndependentBitmap‑Objekts enthält ([MS‑WMF] Abschnitt 2.2.2.9). Es ist nicht erforderlich, dass er zusammenhängend mit dem festen Teil des EMR\_CREATEDIBPATTERNBRUSHPT‑Datensatzes ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [WmfDeviceIndependentBitmap](../../com.aspose.imaging.fileformats.wmf.objects/wmfdeviceindependentbitmap) |  |

