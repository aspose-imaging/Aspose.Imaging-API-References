---
title: "EmfSetIcmMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SETICMMODE‑Datensatz gibt den Modus des Image Color Management (ICM) für Grafikoperationen an."
type: docs
weight: 125
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfseticmmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetIcmMode extends EmfStateRecordType
```

Der EMR\_SETICMMODE-Datensatz gibt den Modus der Bildfarbverwaltung (ICM) für Grafikoperationen an.

Wenn der ICM‑Modus aktiviert ist, sollten die in EMF‑Datensätzen angegebenen Farben farblich abgeglichen werden, während das Standardfarbprofil im Wiedergabegeräte‑Kontext verwendet werden sollte, wenn ein Bit‑Block‑Transfer durchgeführt wird. Wenn das Standardfarbprofil nicht gewünscht ist, sollte der ICM‑Modus vor dem Bit‑Block‑Transfer deaktiviert werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSetIcmMode(EmfRecord source)](#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSetIcmMode`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIcmMode()](#getIcmMode--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die angibt, ob ICM aktiviert oder deaktiviert werden soll, aus der ICMMode‑Aufzählung (Abschnitt 2.1.18). |
| [setIcmMode(int value)](#setIcmMode-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die angibt, ob ICM aktiviert oder deaktiviert werden soll, aus der ICMMode‑Aufzählung (Abschnitt 2.1.18). |
### EmfSetIcmMode(EmfRecord source) {#EmfSetIcmMode-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetIcmMode(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSetIcmMode`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getIcmMode() {#getIcmMode--}
```
public int getIcmMode()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die angibt, ob ICM aktiviert oder deaktiviert werden soll, aus der ICMMode‑Aufzählung (Abschnitt 2.1.18). Dieser Wert ist Teil des Zustands des Wiedergabegeräte‑Kontexts.

**Returns:**
int
### setIcmMode(int value) {#setIcmMode-int-}
```
public void setIcmMode(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die angibt, ob ICM aktiviert oder deaktiviert werden soll, aus der ICMMode‑Aufzählung (Abschnitt 2.1.18). Dieser Wert ist Teil des Zustands des Wiedergabegeräte‑Kontexts.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

