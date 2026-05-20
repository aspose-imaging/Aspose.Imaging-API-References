---
title: "EmfCreateBrushIndirect"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_CREATEBRUSHINDIRECT-Datensatz definiert einen logischen Pinsel für Grafikoperationen."
type: docs
weight: 35
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateBrushIndirect extends EmfObjectCreationRecordType
```

Der EMR\_CREATEBRUSHINDIRECT-Datensatz definiert einen logischen Pinsel für Grafikoperationen.

Das durch diesen Datensatz definierte logische Pinselobjekt kann mittels eines EMR\\_SELECTOBJECT-Datensatzes (Abschnitt 2.3.8.5) in den Wiedergabegerätekontext ausgewählt werden, der den zu verwendenden logischen Pinsel für nachfolgende Grafikoperationen angibt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfCreateBrushIndirect(EmfRecord source)](#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfCreateBrushIndirect`-Klasse. |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect--) | Initialisiert eine neue Instanz der `EmfCreateBrushIndirect`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Ruft ab oder legt fest: Eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des logischen Pinselobjekts in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [setIhBrush(int value)](#setIhBrush-int-) | Ruft ab oder legt fest: Eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des logischen Pinselobjekts in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [getLogBrush()](#getLogBrush--) | Ruft ab oder legt fest: Ein LogBrushEx-Objekt (Abschnitt 2.2.12), das Stil, Farbe und Muster des logischen Pinsels angibt. |
| [setLogBrush(EmfLogBrushEx value)](#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-) | Ruft ab oder legt fest: Ein LogBrushEx-Objekt (Abschnitt 2.2.12), das Stil, Farbe und Muster des logischen Pinsels angibt. |
### EmfCreateBrushIndirect(EmfRecord source) {#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateBrushIndirect(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfCreateBrushIndirect`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfCreateBrushIndirect() {#EmfCreateBrushIndirect--}
```
public EmfCreateBrushIndirect()
```


Initialisiert eine neue Instanz der `EmfCreateBrushIndirect`-Klasse.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Ruft ab oder legt fest: Eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des logischen Pinselobjekts in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit dieses Objekt wiederverwendet oder geändert werden kann.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Ruft ab oder legt fest: Eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des logischen Pinselobjekts in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit dieses Objekt wiederverwendet oder geändert werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLogBrush() {#getLogBrush--}
```
public EmfLogBrushEx getLogBrush()
```


Liest oder setzt ein LogBrushEx-Objekt (Abschnitt 2.2.12), das Stil, Farbe und Muster des logischen Pinsels festlegt. Das Feld BrushStyle in diesem Objekt MUSS BS\_SOLID, BS\_HATCHED oder BS\_NULL sein.

**Returns:**
[EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex)
### setLogBrush(EmfLogBrushEx value) {#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-}
```
public void setLogBrush(EmfLogBrushEx value)
```


Liest oder setzt ein LogBrushEx-Objekt (Abschnitt 2.2.12), das Stil, Farbe und Muster des logischen Pinsels festlegt. Das Feld BrushStyle in diesem Objekt MUSS BS\_SOLID, BS\_HATCHED oder BS\_NULL sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex) |  |

