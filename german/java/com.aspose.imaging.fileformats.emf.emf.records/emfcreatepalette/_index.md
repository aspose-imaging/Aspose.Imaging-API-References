---
title: "EmfCreatePalette"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_CREATEPALETTE‑Datensatz definiert eine logische Palette für Grafikoperationen."
type: docs
weight: 40
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreatePalette extends EmfObjectCreationRecordType
```

Der EMR\_CREATEPALETTE-Datensatz definiert eine logische Palette für Grafikoperationen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfCreatePalette(EmfRecord source)](#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfCreatePalette`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIhPal()](#getIhPal--) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Index des logischen Palettenobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [setIhPal(int value)](#setIhPal-int-) | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Index des logischen Palettenobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. |
| [getLogPalette()](#getLogPalette--) | Liest oder setzt ein LogPalette‑Objekt (Abschnitt 2.2.17). |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | Liest oder setzt ein LogPalette‑Objekt (Abschnitt 2.2.17). |
### EmfCreatePalette(EmfRecord source) {#EmfCreatePalette-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreatePalette(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfCreatePalette`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getIhPal() {#getIhPal--}
```
public int getIhPal()
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Index des logischen Palettenobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit das Objekt wiederverwendet oder geändert werden kann.

**Returns:**
int
### setIhPal(int value) {#setIhPal-int-}
```
public void setIhPal(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Index des logischen Palettenobjekts in der EMF‑Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit das Objekt wiederverwendet oder geändert werden kann.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


Liest oder setzt ein LogPalette‑Objekt (Abschnitt 2.2.17). Das Versionsfeld dieses Objekts MUSS auf 0x0300 gesetzt werden. Wenn der Wert NumberOfEntries in diesem Objekt null ist, muss die Verarbeitung dieses Datensatzes fehlschlagen.

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette)
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


Liest oder setzt ein LogPalette‑Objekt (Abschnitt 2.2.17). Das Versionsfeld dieses Objekts MUSS auf 0x0300 gesetzt werden. Wenn der Wert NumberOfEntries in diesem Objekt null ist, muss die Verarbeitung dieses Datensatzes fehlschlagen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) |  |

