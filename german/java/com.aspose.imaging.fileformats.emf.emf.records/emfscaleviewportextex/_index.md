---
title: "EmfScaleViewportExtex"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EMR_SCALEVIEWPORTEXTEX‑Datensatz legt das Ansichtsfenster für einen Geräte‑Context neu fest, indem er die durch die angegebenen Multiplikatoren und Divisoren gebildeten Verhältnisse verwendet."
type: docs
weight: 113
url: /de/java/com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleViewportExtex extends EmfStateRecordType
```

Der EMR\_SCALEVIEWPORTEXTEX-Datensatz legt das Ansichtsfenster für einen Gerätekontext erneut fest, indem die durch die angegebenen Multiplikatoren und Divisoren gebildeten Verhältnisse verwendet werden.

Der Umfang kann nicht geändert werden, wenn der Geräte‑Context einen festen Skalierungs‑Abbildungmodus verwendet. Nur MM\_ISOTROPIC und MM\_ANISOTROPIC sind nicht fest skaliert. Die Ansichtsfenster‑Umfänge werden wie folgt modifiziert. xNewWE = (xOldWE \* xNum) / xDenom yNewWE = (yOldWE \* yNum) / yDenom
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfScaleViewportExtex(EmfRecord source)](#EmfScaleViewportExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initialisiert eine neue Instanz der `EmfScaleViewportExtex`-Klasse. |
| [EmfScaleViewportExtex()](#EmfScaleViewportExtex--) | Initialisiert eine neue Instanz der [EmfScaleViewportExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex)-Klasse. |
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
### EmfScaleViewportExtex(EmfRecord source) {#EmfScaleViewportExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleViewportExtex(EmfRecord source)
```


Initialisiert eine neue Instanz der `EmfScaleViewportExtex`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Die Quelle. |

### EmfScaleViewportExtex() {#EmfScaleViewportExtex--}
```
public EmfScaleViewportExtex()
```


Initialisiert eine neue Instanz der [EmfScaleViewportExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex)-Klasse.

### getXNum() {#getXNum--}
```
public int getXNum()
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der den horizontalen Multiplikator angibt. Darf nicht null sein.

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der den horizontalen Multiplikator angibt. Darf nicht null sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der den horizontalen Divisor angibt. Darf nicht null sein.

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der den horizontalen Divisor angibt. Darf nicht null sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der den vertikalen Multiplikator angibt. Darf nicht null sein.

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der den vertikalen Multiplikator angibt. Darf nicht null sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der den vertikalen Divisor angibt. Darf nicht null sein.

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


Liest oder setzt einen 32‑Bit‑vorzeichenbehafteten Integer, der den vertikalen Divisor angibt. Darf nicht null sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

