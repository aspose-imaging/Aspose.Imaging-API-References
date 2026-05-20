---
title: "EmfSaveDc"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Speichert den aktuellen Zustand des Wiedergabegeräte‑Kontexts auf einem Stapel von Zuständen, die durch vorherige EMR_SAVEDC‑Datensätze gespeichert wurden, falls vorhanden."
type: docs
weight: 112
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfsavedc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSaveDc extends EmfStateRecordType
```

Speichert den aktuellen Zustand des Wiedergabegeräte‑Kontexts auf einem Stapel von Zuständen, die durch vorherige EMR\_SAVEDC‑Datensätze gespeichert wurden, falls vorhanden. Der Zustand besteht aus Grafikeigenschaften und -objekten, einschließlich des aktuell ausgewählten Bitmaps, Pinsels, Palettes, Schriftart, Stifts und Region. Ein EMR\_RESTOREDC‑Datensatz wird verwendet, um den Zustand wiederherzustellen. Dieser EMF‑Datensatz gibt keine Parameter an.

Der Stapel kann Zustandsinformationen für mehrere Instanzen des Wiedergabegeräte‑Kontexts enthalten. Wenn ein Zustand wiederhergestellt wird, müssen alle Zustandsinstanzen, die später gespeichert wurden, verworfen werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfSaveDc(EmfRecord source)](#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfSaveDc`‑Klasse. |
| [EmfSaveDc()](#EmfSaveDc--) | Initialisiert eine neue Instanz der `EmfSaveDc`‑Klasse. |
### EmfSaveDc(EmfRecord source) {#EmfSaveDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSaveDc(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfSaveDc`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfSaveDc() {#EmfSaveDc--}
```
public EmfSaveDc()
```


Initialisiert eine neue Instanz der `EmfSaveDc`‑Klasse.

