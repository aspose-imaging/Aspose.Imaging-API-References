---
title: "EmfSetColorAdjustment"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SETCOLORADJUSTMENT-Datensatz gibt Farbeanpassungs‑Eigenschaften im Wiedergabegeräte‑Kontext an."
type: docs
weight: 122
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetColorAdjustment extends EmfStateRecordType
```

Der EMR\_SETCOLORADJUSTMENT-Datensatz spezifiziert Farbeinstellungen im Wiedergabe‑Gerätekontext.

Farbeanpassungswerte werden verwendet, um die Eingabefarbe des Quell‑Bitmaps für Grafikoperationen anzupassen, die von EMR\_STRETCHBLT‑ und EMR\_STRETCHDIBITS‑Datensätzen durchgeführt werden, wenn der STRETCH\_HALFTONE‑Modus aus der StretchMode‑Aufzählung (Abschnitt 2.1.32) gesetzt ist. Das von diesem Datensatz angegebene ColorAdjustment‑Objekt MUSS in Grafikoperationen verwendet werden, die ein ColorAdjustment‑Objekt benötigen, bis ein anderes ColorAdjustment‑Objekt durch einen anderen EMR\_SETCOLORADJUSTMENT‑Datensatz angegeben wird oder bis das Objekt durch einen EMR\_DELETEOBJECT‑Datensatz entfernt wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSetColorAdjustment(EmfRecord source)](#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSetColorAdjustment`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColorAdjustment()](#getColorAdjustment--) | Liest oder setzt ein ColorAdjustment‑Objekt (Abschnitt 2.2.2), das Farbeanpassungswerte angibt. |
| [setColorAdjustment(EmfColorAdjustment value)](#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-) | Liest oder setzt ein ColorAdjustment‑Objekt (Abschnitt 2.2.2), das Farbeanpassungswerte angibt. |
### EmfSetColorAdjustment(EmfRecord source) {#EmfSetColorAdjustment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetColorAdjustment(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSetColorAdjustment`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getColorAdjustment() {#getColorAdjustment--}
```
public EmfColorAdjustment getColorAdjustment()
```


Liest oder setzt ein ColorAdjustment‑Objekt (Abschnitt 2.2.2), das Farbeanpassungswerte angibt.

**Returns:**
[EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment)
### setColorAdjustment(EmfColorAdjustment value) {#setColorAdjustment-com.aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment-}
```
public void setColorAdjustment(EmfColorAdjustment value)
```


Liest oder setzt ein ColorAdjustment‑Objekt (Abschnitt 2.2.2), das Farbeanpassungswerte angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfColorAdjustment](../../com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment) |  |

