---
title: "EmfCreatePen"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_CREATEPEN‑Datensatz definiert einen logischen Stift für Grafikoperationen."
type: docs
weight: 41
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePen extends EmfObjectCreationRecordType
```

Der EMR\_CREATEPEN-Datensatz definiert einen logischen Stift für Grafikoperationen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfCreatePen(EmfRecord source)](#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfCreatePen`‑Klasse. |
| [EmfCreatePen()](#EmfCreatePen--) | Initialisiert eine neue Instanz der `EmfCreatePen`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIhPen()](#getIhPen--) | Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des logischen Stiftobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [setIhPen(int value)](#setIhPen-int-) | Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des logischen Stiftobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [getLogPen()](#getLogPen--) | Liest oder schreibt ein LogPen‑Objekt (Abschnitt 2.2.19), das Stil, Breite und Farbe des logischen Stifts angibt. |
| [setLogPen(EmfLogPen value)](#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-) | Liest oder schreibt ein LogPen‑Objekt (Abschnitt 2.2.19), das Stil, Breite und Farbe des logischen Stifts angibt. |
### EmfCreatePen(EmfRecord source) {#EmfCreatePen-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePen(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfCreatePen`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfCreatePen() {#EmfCreatePen--}
```
public EmfCreatePen()
```


Initialisiert eine neue Instanz der `EmfCreatePen`‑Klasse.

### getIhPen() {#getIhPen--}
```
public int getIhPen()
```


Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des logischen Stiftobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit das Objekt wiederverwendet oder geändert werden kann.

**Returns:**
int
### setIhPen(int value) {#setIhPen-int-}
```
public void setIhPen(int value)
```


Liest oder schreibt eine 32‑Bit‑vorzeichenlose Ganzzahl, die den Index des logischen Stiftobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit das Objekt wiederverwendet oder geändert werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLogPen() {#getLogPen--}
```
public EmfLogPen getLogPen()
```


Liest oder schreibt ein LogPen‑Objekt (Abschnitt 2.2.19), das Stil, Breite und Farbe des logischen Stifts angibt.

**Returns:**
[EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen)
### setLogPen(EmfLogPen value) {#setLogPen-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPen-}
```
public void setLogPen(EmfLogPen value)
```


Liest oder schreibt ein LogPen‑Objekt (Abschnitt 2.2.19), das Stil, Breite und Farbe des logischen Stifts angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfLogPen](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpen) |  |

