---
title: "EmfPlusSetPageTransform"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusSetPageTransform-Datensatz gibt Skalierungsfaktoren und Einheiten für die Umwandlung von Seitenkoordinaten in Gerätekoordinaten an."
type: docs
weight: 61
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetPageTransform extends EmfPlusTerminalServerRecordType
```

Der EmfPlusSetPageTransform-Datensatz gibt Skalierungsfaktoren und Einheiten für die Umwandlung von Seitenkoordinaten in Gerätekoordinaten an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusSetPageTransform(EmfPlusRecord source)](#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusSetPageTransform`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | Liest die Maßeinheit für Seitenraumkoordinaten aus der UnitType‑Aufzählung (Abschnitt 2.1.1.33). |
| [getPageScale()](#getPageScale--) | Liest oder setzt einen 32‑Bit‑Floating‑Point‑Wert, der den Skalierungsfaktor für die Umwandlung von Seitenraumkoordinaten in Geräte­raumkoordinaten angibt. |
| [setPageScale(float value)](#setPageScale-float-) | Liest oder setzt einen 32‑Bit‑Floating‑Point‑Wert, der den Skalierungsfaktor für die Umwandlung von Seitenraumkoordinaten in Geräte­raumkoordinaten angibt. |
### EmfPlusSetPageTransform(EmfPlusRecord source) {#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetPageTransform(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusSetPageTransform`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Liest die Maßeinheit für Seitenraumkoordinaten aus der UnitType‑Aufzählung (Abschnitt 2.1.1.33). Dieser Wert SOLLTE NICHT UnitTypeDisplay oder UnitTypeWorld sein.

Wert: Die Seiteneinheit.

**Returns:**
int
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


Liest oder setzt einen 32‑Bit‑Floating‑Point‑Wert, der den Skalierungsfaktor für die Umwandlung von Seitenraumkoordinaten in Geräte­raumkoordinaten angibt.

Wert: Die Seitenskala.

**Returns:**
float
### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


Liest oder setzt einen 32‑Bit‑Floating‑Point‑Wert, der den Skalierungsfaktor für die Umwandlung von Seitenraumkoordinaten in Geräte­raumkoordinaten angibt.

Wert: Die Seitenskala.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

