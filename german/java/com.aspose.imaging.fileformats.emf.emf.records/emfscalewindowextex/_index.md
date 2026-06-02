---
title: "EmfScaleWindowExtex"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SCALEWINDOWEXTEX‑Datensatz legt das Fenster für einen Wiedergabegerätekontext erneut fest, indem er die durch die angegebenen Multiplikatoren und Divisoren gebildeten Verhältnisse verwendet."
type: docs
weight: 114
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleWindowExtex extends EmfStateRecordType
```

Der EMR\_SCALEWINDOWEXTEX-Datensatz legt das Fenster für einen Wiedergabe-Gerätekontext erneut fest, indem die durch die angegebenen Multiplikatoren und Divisoren gebildeten Verhältnisse verwendet werden.

Der Umfang kann nicht geändert werden, wenn der Geräte‑Kontext einen festen Skalierungs‑Mapping‑Modus verwendet. Nur MM\_ISOTROPIC und MM\_ANISOTROPIC sind nicht fest skaliert. Die Fenster‑Umfänge werden wie folgt modifiziert. xNewWE = (xOldWE \* xNum) / xDenom yNewWE = (yOldWE \* yNum) / yDenom
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfScaleWindowExtex(EmfRecord source)](#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfScaleWindowExtex`-Klasse. |
| [EmfScaleWindowExtex()](#EmfScaleWindowExtex--) | Initialisiert eine neue Instanz der [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex)-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getXNum()](#getXNum--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der den horizontalen Multiplikator angibt. |
| [setXNum(int value)](#setXNum-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der den horizontalen Multiplikator angibt. |
| [getXDenom()](#getXDenom--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der den horizontalen Divisor angibt. |
| [setXDenom(int value)](#setXDenom-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der den horizontalen Divisor angibt. |
| [getYNum()](#getYNum--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der den vertikalen Multiplikator angibt. |
| [setYNum(int value)](#setYNum-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der den vertikalen Multiplikator angibt. |
| [getYDenom()](#getYDenom--) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der den vertikalen Divisor angibt. |
| [setYDenom(int value)](#setYDenom-int-) | Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der den vertikalen Divisor angibt. |
### EmfScaleWindowExtex(EmfRecord source) {#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleWindowExtex(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfScaleWindowExtex`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfScaleWindowExtex() {#EmfScaleWindowExtex--}
```
public EmfScaleWindowExtex()
```


Initialisiert eine neue Instanz der [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex)-Klasse.

### getXNum() {#getXNum--}
```
public int getXNum()
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die den horizontalen Multiplikator angibt. MUSS NICHT null sein.

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die den horizontalen Multiplikator angibt. MUSS NICHT null sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die den horizontalen Divisor angibt. MUSS NICHT null sein.

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die den horizontalen Divisor angibt. MUSS NICHT null sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die den vertikalen Multiplikator angibt. MUSS NICHT null sein.

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die den vertikalen Multiplikator angibt. MUSS NICHT null sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die den vertikalen Divisor angibt. MUSS NICHT null sein.

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


Liest oder setzt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die den vertikalen Divisor angibt. MUSS NICHT null sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

