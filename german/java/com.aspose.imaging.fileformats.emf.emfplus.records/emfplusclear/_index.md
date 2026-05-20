---
title: "EmfPlusClear"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusClear-Datensatz löscht den Ausgabekoordinatenraum und initialisiert ihn mit einer Hintergrundfarbe und Transparenz"
type: docs
weight: 12
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusClear extends EmfPlusDrawingRecordType
```

Der EmfPlusClear-Datensatz löscht den Ausgabekoordinatenraum und initialisiert ihn mit einer Hintergrundfarbe und Transparenz
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusClear(EmfPlusRecord source)](#EmfPlusClear-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusClear`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getArgb32Color()](#getArgb32Color--) | Liest oder setzt die Farbe. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Liest oder setzt die Farbe. |
### EmfPlusClear(EmfPlusRecord source) {#EmfPlusClear-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusClear(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusClear`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Liest oder setzt die Farbe. Ein EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1), das die zu malenden Bildschirmfarbe definiert. Alle Farben werden in [IEC-RGB] angegeben, sofern nicht anders vermerkt.

Wert: Die Farbe.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Liest oder setzt die Farbe. Ein EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1), das die zu malenden Bildschirmfarbe definiert. Alle Farben werden in [IEC-RGB] angegeben, sofern nicht anders vermerkt.

Wert: Die Farbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

