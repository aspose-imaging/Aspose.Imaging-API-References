---
title: "EmfPlusSetAntiAliasMode"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusSetAntiAliasMode-Datensatz gibt den Antialiasing‑Modus für die Textausgabe an."
type: docs
weight: 54
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetantialiasmode/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusPropertyRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfpluspropertyrecordtype)
```
public final class EmfPlusSetAntiAliasMode extends EmfPlusPropertyRecordType
```

Der EmfPlusSetAntiAliasMode-Datensatz gibt den Antialiasing‑Modus für die Textausgabe an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusSetAntiAliasMode(EmfPlusRecord source)](#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusSetAntiAliasMode`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | Liefert oder setzt den Glättungsmodus. |
| [setSmoothingMode(byte value)](#setSmoothingMode-byte-) | Liefert oder setzt den Glättungsmodus. |
| [getAntiAliasing()](#getAntiAliasing--) | Liefert oder setzt einen Wert, der angibt, ob [anti aliasing] aktiviert ist. |
| [setAntiAliasing(boolean value)](#setAntiAliasing-boolean-) | Liefert oder setzt einen Wert, der angibt, ob [anti aliasing] aktiviert ist. |
### EmfPlusSetAntiAliasMode(EmfPlusRecord source) {#EmfPlusSetAntiAliasMode-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetAntiAliasMode(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusSetAntiAliasMode`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getSmoothingMode() {#getSmoothingMode--}
```
public byte getSmoothingMode()
```


Liefert oder setzt den Glättungsmodus. (7 Bits): Der Glättungsmoduswert, aus der Aufzählung SmoothingMode (Abschnitt 2.1.1.28).

Wert: Der Glättungsmodus.

**Returns:**
byte
### setSmoothingMode(byte value) {#setSmoothingMode-byte-}
```
public void setSmoothingMode(byte value)
```


Liefert oder setzt den Glättungsmodus. (7 Bits): Der Glättungsmoduswert, aus der Aufzählung SmoothingMode (Abschnitt 2.1.1.28).

Wert: Der Glättungsmodus.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte |  |

### getAntiAliasing() {#getAntiAliasing--}
```
public boolean getAntiAliasing()
```


Liefert oder setzt einen Wert, der angibt, ob [anti aliasing] aktiviert ist. Ist er gesetzt, SOLLTE Anti‑Aliasing durchgeführt werden. Ist er nicht gesetzt, SOLLTE Anti‑Aliasing NICHT durchgeführt werden.

Wert: `true`, wenn [anti aliasing]; andernfalls `false`.

**Returns:**
boolean
### setAntiAliasing(boolean value) {#setAntiAliasing-boolean-}
```
public void setAntiAliasing(boolean value)
```


Liefert oder setzt einen Wert, der angibt, ob [anti aliasing] aktiviert ist. Ist er gesetzt, SOLLTE Anti‑Aliasing durchgeführt werden. Ist er nicht gesetzt, SOLLTE Anti‑Aliasing NICHT durchgeführt werden.

Wert: `true`, wenn [anti aliasing]; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

