---
title: "EmfSetBkMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SETBKMODE‑Datensatz gibt den Hintergrund‑Mischmodus des Wiedergabegeräte‑Kontexts an."
type: docs
weight: 120
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetbkmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetBkMode extends EmfStateRecordType
```

Der EMR\_SETBKMODE‑Datensatz gibt den Hintergrund‑Mischmodus des Wiedergabegeräte‑Kontexts an. Der Hintergrund‑Mischmodus wird mit Text, schraffierten Pinseln und Stift‑Stilen verwendet, die keine durchgezogenen Linien sind.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSetBkMode(EmfRecord source)](#EmfSetBkMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSetBkMode`‑Klasse. |
| [EmfSetBkMode()](#EmfSetBkMode--) | Initialisiert eine neue Instanz der `EmfSetBkMode`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Hintergrundmodus angibt und MUSS im BackgroundMode‑Aufzählungstyp (Abschnitt 2.1.4) enthalten sein. |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Hintergrundmodus angibt und MUSS im BackgroundMode‑Aufzählungstyp (Abschnitt 2.1.4) enthalten sein. |
### EmfSetBkMode(EmfRecord source) {#EmfSetBkMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetBkMode(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSetBkMode`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfSetBkMode() {#EmfSetBkMode--}
```
public EmfSetBkMode()
```


Initialisiert eine neue Instanz der `EmfSetBkMode`‑Klasse.

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Hintergrundmodus angibt und MUSS im BackgroundMode‑Aufzählungstyp (Abschnitt 2.1.4) enthalten sein.

**Returns:**
int
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Ruft einen 32‑Bit‑vorzeichenlosen Integer ab oder legt ihn fest, der den Hintergrundmodus angibt und MUSS im BackgroundMode‑Aufzählungstyp (Abschnitt 2.1.4) enthalten sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

