---
title: "EmfPlusSetCompositingMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusSetCompositingMode-Datensatz gibt an, wie Quellfarben mit Hintergrundfarben kombiniert werden."
type: docs
weight: 58
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetcompositingmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetCompositingMode extends EmfPlusPropertyRecordType
```

Der EmfPlusSetCompositingMode-Datensatz gibt an, wie Quellfarben mit Hintergrundfarben kombiniert werden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusSetCompositingMode(EmfPlusRecord source)](#EmfPlusSetCompositingMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusSetCompositingMode`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCompositingMode()](#getCompositingMode--) | Liest oder legt den Kompositierungsmoduswert fest, aus der CompositingMode‑Aufzählung (Abschnitt 2.1.1.5). |
| [setCompositingMode(byte value)](#setCompositingMode-byte-) | Liest oder legt den Kompositierungsmoduswert fest, aus der CompositingMode‑Aufzählung (Abschnitt 2.1.1.5). |
### EmfPlusSetCompositingMode(EmfPlusRecord source) {#EmfPlusSetCompositingMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetCompositingMode(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusSetCompositingMode`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getCompositingMode() {#getCompositingMode--}
```
public byte getCompositingMode()
```


Liest oder legt den Kompositierungsmoduswert fest, aus der CompositingMode‑Aufzählung (Abschnitt 2.1.1.5). Kompositierung kann als Zustand des Alpha‑Blending ausgedrückt werden, der entweder ein- oder ausgeschaltet sein kann.

Wert: Der Compositing‑Modus.

**Returns:**
byte
### setCompositingMode(byte value) {#setCompositingMode-byte-}
```
public void setCompositingMode(byte value)
```


Liest oder legt den Kompositierungsmoduswert fest, aus der CompositingMode‑Aufzählung (Abschnitt 2.1.1.5). Kompositierung kann als Zustand des Alpha‑Blending ausgedrückt werden, der entweder ein- oder ausgeschaltet sein kann.

Wert: Der Compositing‑Modus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

