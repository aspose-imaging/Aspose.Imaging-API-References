---
title: "EmfRestoreDc"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_RESTOREDC‑Datensatz stellt den Wiedergabegerätekontext auf den angegebenen Zustand wieder her."
type: docs
weight: 109
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfRestoreDc extends EmfStateRecordType
```

Der EMR\_RESTOREDC‑Datensatz stellt den Wiedergabegerätekontext auf den angegebenen Zustand wieder her. Der Wiedergabegerätekontext wird wiederhergestellt, indem Zustandsinformationen von einem Stapel entfernt werden, der durch vorherige EMR\_SAVEDC‑Datensätze (Abschnitt 2.3.11) erzeugt wurde.

Der Stapel kann Zustandsinformationen für mehrere Instanzen des Wiedergabegeräte‑Kontexts enthalten. Wenn ein Zustand wiederhergestellt wird, müssen alle Zustandsinstanzen, die später gespeichert wurden, verworfen werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfRestoreDc(EmfRecord source)](#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfRestoreDc`‑Klasse. |
| [EmfRestoreDc()](#EmfRestoreDc--) | Initialisiert eine neue Instanz der `EmfRestoreDc`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSavedDc()](#getSavedDc--) | Liest oder setzt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die den zu restaurierenden gespeicherten Zustand relativ zum aktuellen Zustand angibt. |
| [setSavedDc(int value)](#setSavedDc-int-) | Liest oder setzt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die den zu restaurierenden gespeicherten Zustand relativ zum aktuellen Zustand angibt. |
### EmfRestoreDc(EmfRecord source) {#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRestoreDc(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfRestoreDc`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfRestoreDc() {#EmfRestoreDc--}
```
public EmfRestoreDc()
```


Initialisiert eine neue Instanz der `EmfRestoreDc`‑Klasse.

### getSavedDc() {#getSavedDc--}
```
public int getSavedDc()
```


Liest oder setzt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die den zu restaurierenden gespeicherten Zustand relativ zum aktuellen Zustand angibt. Dieser Wert MUSS negativ sein; \\u20131 steht für den Zustand, der zuletzt auf dem Stapel gespeichert wurde, \\u20132 für den davor, usw.

**Returns:**
int
### setSavedDc(int value) {#setSavedDc-int-}
```
public void setSavedDc(int value)
```


Liest oder setzt eine 32‑Bit‑Ganzzahl mit Vorzeichen, die den zu restaurierenden gespeicherten Zustand relativ zum aktuellen Zustand angibt. Dieser Wert MUSS negativ sein; \\u20131 steht für den Zustand, der zuletzt auf dem Stapel gespeichert wurde, \\u20132 für den davor, usw.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

