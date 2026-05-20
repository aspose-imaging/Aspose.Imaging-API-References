---
title: "EmfSetMapperFlags"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SETMAPPERFLAGS-Datensatz gibt Parameter des Prozesses an, bei dem logische Schriftarten zu physischen Schriftarten zugeordnet werden, was vom Font‑Mapper durchgeführt wird."
type: docs
weight: 131
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetMapperFlags extends EmfStateRecordType
```

Der EMR\_SETMAPPERFLAGS-Datensatz gibt Parameter des Prozesses zur Zuordnung logischer Schriften zu physischen Schriften an, der vom Font‑Mapper durchgeführt wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSetMapperFlags(EmfRecord source)](#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSetMapperFlags`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFlags()](#getFlags--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die Parameter des Schriftartenabgleichs angibt. |
| [setFlags(int value)](#setFlags-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die Parameter des Schriftartenabgleichs angibt. |
### EmfSetMapperFlags(EmfRecord source) {#EmfSetMapperFlags-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetMapperFlags(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSetMapperFlags`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### getFlags() {#getFlags--}
```
public int getFlags()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die Parameter des Schriftartenabgleichs angibt.

0x00000001 Der Font‑Mapper SOLLTE nur Schriftarten auswählen, die das Seitenverhältnis des Ausgabegeräts entsprechen, wie es derzeit im Wiedergabegeräte‑Kontext definiert ist.

**Returns:**
int
### setFlags(int value) {#setFlags-int-}
```
public void setFlags(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die Parameter des Schriftartenabgleichs angibt.

0x00000001 Der Font‑Mapper SOLLTE nur Schriftarten auswählen, die das Seitenverhältnis des Ausgabegeräts entsprechen, wie es derzeit im Wiedergabegeräte‑Kontext definiert ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

