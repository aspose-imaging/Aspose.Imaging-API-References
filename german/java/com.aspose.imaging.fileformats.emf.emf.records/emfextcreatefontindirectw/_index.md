---
title: "EmfExtCreateFontIndirectW"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_EXTCREATEFONTINDIRECTW‑Datensatz definiert eine logische Schriftart für Grafikoperationen."
type: docs
weight: 51
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfextcreatefontindirectw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfExtCreateFontIndirectW extends EmfObjectCreationRecordType
```

Der EMR\_EXTCREATEFONTINDIRECTW-Datensatz definiert eine logische Schriftart für Grafikoperationen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfExtCreateFontIndirectW(EmfRecord source)](#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfExtCreateFontIndirectW` Klasse. |
| [EmfExtCreateFontIndirectW()](#EmfExtCreateFontIndirectW--) | Initialisiert eine neue Instanz der `EmfExtCreateFontIndirectW` Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIhFonts()](#getIhFonts--) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Index des logischen Schriftart‑Objekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [setIhFonts(int value)](#setIhFonts-int-) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Index des logischen Schriftart‑Objekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [getElw()](#getElw--) | Liest oder setzt ein LogFontExDv‑Objekt (Abschnitt 2.2.15), das die logische Schriftart angibt. |
| [setElw(EmfLogFont value)](#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-) | Liest oder setzt ein LogFontExDv‑Objekt (Abschnitt 2.2.15), das die logische Schriftart angibt. |
### EmfExtCreateFontIndirectW(EmfRecord source) {#EmfExtCreateFontIndirectW-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtCreateFontIndirectW(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfExtCreateFontIndirectW` Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfExtCreateFontIndirectW() {#EmfExtCreateFontIndirectW--}
```
public EmfExtCreateFontIndirectW()
```


Initialisiert eine neue Instanz der `EmfExtCreateFontIndirectW` Klasse.

### getIhFonts() {#getIhFonts--}
```
public int getIhFonts()
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Index des logischen Schriftart‑Objekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit dieses Objekt wiederverwendet oder geändert werden kann.

**Returns:**
int
### setIhFonts(int value) {#setIhFonts-int-}
```
public void setIhFonts(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Index des logischen Schriftart‑Objekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit dieses Objekt wiederverwendet oder geändert werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getElw() {#getElw--}
```
public EmfLogFont getElw()
```


Liest oder setzt ein LogFontExDv‑Objekt (Abschnitt 2.2.15), das die logische Schriftart angibt. Ein LogFont‑Objekt 2.2.13 KANN stattdessen vorhanden sein.[90]Der Vorgang zur Bestimmung des Objekttyps in diesem Feld wird unten beschrieben.

**Returns:**
[EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont)
### setElw(EmfLogFont value) {#setElw-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogFont-}
```
public void setElw(EmfLogFont value)
```


Liest oder setzt ein LogFontExDv‑Objekt (Abschnitt 2.2.15), das die logische Schriftart angibt. Ein LogFont‑Objekt 2.2.13 KANN stattdessen vorhanden sein.[90]Der Vorgang zur Bestimmung des Objekttyps in diesem Feld wird unten beschrieben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfLogFont](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogfont) |  |

