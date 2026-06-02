---
title: "EmfPlusBeginContainer"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusBeginContainer-Datensatz öffnet einen neuen Grafikzustandscontainer und gibt eine Transformation dafür an."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainer extends EmfPlusStateRecordType
```

Der EmfPlusBeginContainer-Datensatz öffnet einen neuen Grafikzustandscontainer und gibt eine Transformation dafür an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusBeginContainer(EmfPlusRecord source)](#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusBeginContainer`‑Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | Liest die Seiteneinheit. |
| [getDestRect()](#getDestRect--) | Liest oder schreibt ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das zusammen mit SrcRect eine Transformation für den Container angibt. |
| [setDestRect(RectangleF value)](#setDestRect-com.aspose.imaging.RectangleF-) | Liest oder schreibt ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das zusammen mit SrcRect eine Transformation für den Container angibt. |
| [getSrcRect()](#getSrcRect--) | Liest oder schreibt ein EmfPlusRectF‑Rechteck, das zusammen mit DestRect eine Transformation für den Container angibt. |
| [setSrcRect(RectangleF value)](#setSrcRect-com.aspose.imaging.RectangleF-) | Liest oder schreibt ein EmfPlusRectF‑Rechteck, das zusammen mit DestRect eine Transformation für den Container angibt. |
| [getStackIndex()](#getStackIndex--) | Liefert oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der einen Index angibt, der dem Grafik‑Zustandscontainer zugeordnet wird. |
| [setStackIndex(int value)](#setStackIndex-int-) | Liefert oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der einen Index angibt, der dem Grafik‑Zustandscontainer zugeordnet wird. |
### EmfPlusBeginContainer(EmfPlusRecord source) {#EmfPlusBeginContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainer(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusBeginContainer`‑Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


Liest die Seiteneinheit.

Wert: Die Seiteneinheit.

**Returns:**
int
### getDestRect() {#getDestRect--}
```
public RectangleF getDestRect()
```


Liest oder schreibt ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das zusammen mit SrcRect eine Transformation für den Container angibt. Diese Transformation ergibt SrcRect, wenn sie auf DestRect angewendet wird.

Wert: Das Zielrechteck.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setDestRect(RectangleF value) {#setDestRect-com.aspose.imaging.RectangleF-}
```
public void setDestRect(RectangleF value)
```


Liest oder schreibt ein EmfPlusRectF‑Objekt (Abschnitt 2.2.2.39), das zusammen mit SrcRect eine Transformation für den Container angibt. Diese Transformation ergibt SrcRect, wenn sie auf DestRect angewendet wird.

Wert: Das Zielrechteck.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getSrcRect() {#getSrcRect--}
```
public RectangleF getSrcRect()
```


Liest oder schreibt ein EmfPlusRectF‑Rechteck, das zusammen mit DestRect eine Transformation für den Container angibt. Diese Transformation ergibt SrcRect, wenn sie auf DestRect angewendet wird.

Wert: Das Quell‑Rechteck.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### setSrcRect(RectangleF value) {#setSrcRect-com.aspose.imaging.RectangleF-}
```
public void setSrcRect(RectangleF value)
```


Liest oder schreibt ein EmfPlusRectF‑Rechteck, das zusammen mit DestRect eine Transformation für den Container angibt. Diese Transformation ergibt SrcRect, wenn sie auf DestRect angewendet wird.

Wert: Das Quell‑Rechteck.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Liefert oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der einen Index angibt, der dem Grafik‑Zustandscontainer zugeordnet wird. Der Index MUSS von einem nachfolgenden EmfPlusEndContainer‑Datensatz (Abschnitt 2.3.7.3) referenziert werden, um den Grafik‑Zustandscontainer zu schließen.

Wert: Der Index des Stacks.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Liefert oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der einen Index angibt, der dem Grafik‑Zustandscontainer zugeordnet wird. Der Index MUSS von einem nachfolgenden EmfPlusEndContainer‑Datensatz (Abschnitt 2.3.7.3) referenziert werden, um den Grafik‑Zustandscontainer zu schließen.

Wert: Der Index des Stacks.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

