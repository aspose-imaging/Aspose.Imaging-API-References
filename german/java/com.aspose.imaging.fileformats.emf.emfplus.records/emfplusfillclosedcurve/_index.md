---
title: "EmfPlusFillClosedCurve"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Der EmfPlusFillClosedCurve-Datensatz gibt das Füllen des Inneren einer geschlossenen Kardinal-Spline an."
type: docs
weight: 32
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusfillclosedcurve/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusFillClosedCurve extends EmfPlusDrawingRecordType
```

Der EmfPlusFillClosedCurve-Datensatz gibt das Füllen des Inneren einer geschlossenen Kardinal-Spline an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusFillClosedCurve(EmfPlusRecord source)](#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initialisiert eine neue Instanz der `EmfPlusFillClosedCurve`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isColor()](#isColor--) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. |
| [setColor(boolean value)](#setColor-boolean-) | Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. |
| [getCompressed()](#getCompressed--) | Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusFillClosedCurve` komprimiert ist. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusFillClosedCurve` komprimiert ist. |
| [getWinding()](#getWinding--) | Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusFillClosedCurve` winding ist. |
| [setWinding(boolean value)](#setWinding-boolean-) | Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusFillClosedCurve` winding ist. |
| [getRelative()](#getRelative--) | Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusFillClosedCurve` relativ ist. |
| [setRelative(boolean value)](#setRelative-boolean-) | Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusFillClosedCurve` relativ ist. |
| [getBrushId()](#getBrushId--) | Liest oder schreibt die Pinselkennung – eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den EmfPlusBrush angibt, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird. |
| [setBrushId(int value)](#setBrushId-int-) | Liest oder schreibt die Pinselkennung – eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den EmfPlusBrush angibt, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird. |
| [getTension()](#getTension--) | Liest oder schreibt die Spannung – einen 32‑Bit‑Gleitkommawert, der angibt, wie stark die Spline beim Durchlaufen der Punkte gebogen wird. |
| [setTension(float value)](#setTension-float-) | Liest oder schreibt die Spannung – einen 32‑Bit‑Gleitkommawert, der angibt, wie stark die Spline beim Durchlaufen der Punkte gebogen wird. |
| [getPointData()](#getPointData--) | Liest oder schreibt die Punktdaten – ein Array von Count‑Punkten, die die Endpunkte der Linien angeben, die die Spline definieren. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Liest oder schreibt die Punktdaten – ein Array von Count‑Punkten, die die Endpunkte der Linien angeben, die die Spline definieren. |
### EmfPlusFillClosedCurve(EmfPlusRecord source) {#EmfPlusFillClosedCurve-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusFillClosedCurve(EmfPlusRecord source)
```


Initialisiert eine neue Instanz der `EmfPlusFillClosedCurve`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Die Quelle. |

### isColor() {#isColor--}
```
public boolean isColor()
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. Ist er gesetzt, gibt BrushId eine Farbe als EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1) an. Ist er nicht gesetzt, enthält BrushId den Index eines EmfPlusBrush‑Objekts (Abschnitt 2.2.1.1) in der EMF+‑Objekttabelle.

Wert: `true`, wenn diese Instanz farbig ist; andernfalls `false`.

**Returns:**
boolean
### setColor(boolean value) {#setColor-boolean-}
```
public void setColor(boolean value)
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob diese Instanz farbig ist. Ist er gesetzt, gibt BrushId eine Farbe als EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1) an. Ist er nicht gesetzt, enthält BrushId den Index eines EmfPlusBrush‑Objekts (Abschnitt 2.2.1.1) in der EMF+‑Objekttabelle.

Wert: `true`, wenn diese Instanz farbig ist; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusFillClosedCurve` komprimiert ist. Dieses Bit gibt an, ob das Feld PointData komprimierte Daten enthält. Ist das Bit gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16‑Bit‑Ganzzahlkoordinaten an. Ist das Bit nicht gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an. ---------------------- Ein "winding"‑Füllvorgang füllt Flächen nach der "even‑odd parity"‑Regel. Nach dieser Regel kann ein Testpunkt wie folgt als innerhalb oder außerhalb einer geschlossenen Kurve bestimmt werden: Ziehe eine Linie vom Testpunkt zu einem Punkt, der weit von der Kurve entfernt ist. Wenn diese Linie die Kurve eine ungerade Anzahl von Malen schneidet, liegt der Testpunkt innerhalb der Kurve; andernfalls liegt er außerhalb der Kurve. --------------------- Ein "alternate"‑Füllvorgang füllt Flächen nach der "non-zero"‑Regel. Nach dieser Regel kann ein Testpunkt wie folgt als innerhalb oder außerhalb einer geschlossenen Kurve bestimmt werden: Ziehe eine Linie von einem Testpunkt zu einem Punkt, der weit von der Kurve entfernt ist. Zähle, wie oft die Kurve die Testlinie von links nach rechts schneidet, und wie oft sie die Testlinie von rechts nach links schneidet. Sind diese beiden Zahlen gleich, liegt der Testpunkt außerhalb der Kurve; andernfalls liegt er innerhalb der Kurve.

Wert: `true`, wenn komprimiert; andernfalls `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusFillClosedCurve` komprimiert ist. Dieses Bit gibt an, ob das Feld PointData komprimierte Daten enthält. Ist das Bit gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16‑Bit‑Ganzzahlkoordinaten an. Ist das Bit nicht gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 32‑Bit‑Gleitkomma‑Koordinaten an. ---------------------- Ein "winding"‑Füllvorgang füllt Flächen nach der "even‑odd parity"‑Regel. Nach dieser Regel kann ein Testpunkt wie folgt als innerhalb oder außerhalb einer geschlossenen Kurve bestimmt werden: Ziehe eine Linie vom Testpunkt zu einem Punkt, der weit von der Kurve entfernt ist. Wenn diese Linie die Kurve eine ungerade Anzahl von Malen schneidet, liegt der Testpunkt innerhalb der Kurve; andernfalls liegt er außerhalb der Kurve. --------------------- Ein "alternate"‑Füllvorgang füllt Flächen nach der "non-zero"‑Regel. Nach dieser Regel kann ein Testpunkt wie folgt als innerhalb oder außerhalb einer geschlossenen Kurve bestimmt werden: Ziehe eine Linie von einem Testpunkt zu einem Punkt, der weit von der Kurve entfernt ist. Zähle, wie oft die Kurve die Testlinie von links nach rechts schneidet, und wie oft sie die Testlinie von rechts nach links schneidet. Sind diese beiden Zahlen gleich, liegt der Testpunkt außerhalb der Kurve; andernfalls liegt er innerhalb der Kurve.

Wert: `true`, wenn komprimiert; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getWinding() {#getWinding--}
```
public boolean getWinding()
```


Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusFillClosedCurve` winding ist. Dieses Bit gibt an, wie der Füllvorgang ausgeführt wird. Ist das Bit gesetzt, ist die Füllung eine "winding"‑Füllung. Ist das Bit nicht gesetzt, ist die Füllung eine "alternate"‑Füllung.

Wert: `true`, wenn winding; andernfalls `false`.

**Returns:**
boolean
### setWinding(boolean value) {#setWinding-boolean-}
```
public void setWinding(boolean value)
```


Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusFillClosedCurve` winding ist. Dieses Bit gibt an, wie der Füllvorgang ausgeführt wird. Ist das Bit gesetzt, ist die Füllung eine "winding"‑Füllung. Ist das Bit nicht gesetzt, ist die Füllung eine "alternate"‑Füllung.

Wert: `true`, wenn winding; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusFillClosedCurve` relativ ist. Dieses Bit gibt an, ob das Feld PointData relative oder absolute Positionen angibt. Ist das Bit gesetzt, gibt jedes Element in PointData eine Position im Koordinatenraum an, die relativ zur vom vorherigen Element im Array angegebenen Position ist. Für das erste Element in PointData wird eine vorherige Position bei den Koordinaten (0,0) angenommen. Ist das Bit nicht gesetzt, gibt PointData absolute Positionen gemäß dem C‑Flag an. Hinweis: Wenn dieses Flag gesetzt ist, ist das C‑Flag (oben) undefiniert und MUSS ignoriert werden.

Wert: `true` wenn relativ; andernfalls `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Liest oder schreibt einen Wert, der angibt, ob dieses `EmfPlusFillClosedCurve` relativ ist. Dieses Bit gibt an, ob das Feld PointData relative oder absolute Positionen angibt. Ist das Bit gesetzt, gibt jedes Element in PointData eine Position im Koordinatenraum an, die relativ zur vom vorherigen Element im Array angegebenen Position ist. Für das erste Element in PointData wird eine vorherige Position bei den Koordinaten (0,0) angenommen. Ist das Bit nicht gesetzt, gibt PointData absolute Positionen gemäß dem C‑Flag an. Hinweis: Wenn dieses Flag gesetzt ist, ist das C‑Flag (oben) undefiniert und MUSS ignoriert werden.

Wert: `true` wenn relativ; andernfalls `false`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getBrushId() {#getBrushId--}
```
public int getBrushId()
```


Liest oder schreibt die Pinselkennung – eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den EmfPlusBrush angibt, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird. Dieser Pinsel wird verwendet, um das Innere der geschlossenen kardinalen Spline zu füllen.

**Returns:**
int
### setBrushId(int value) {#setBrushId-int-}
```
public void setBrushId(int value)
```


Liest oder schreibt die Pinselkennung – eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den EmfPlusBrush angibt, dessen Inhalt durch das S‑Bit im Flags‑Feld bestimmt wird. Dieser Pinsel wird verwendet, um das Innere der geschlossenen kardinalen Spline zu füllen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getTension() {#getTension--}
```
public float getTension()
```


Liest oder schreibt die Spannung – einen 32‑Bit‑Gleitkommawert, der angibt, wie stark die Spline beim Durchlaufen der Punkte gebogen wird. Ein Wert von 0,0 gibt an, dass die Spline aus einer Folge gerader Linien besteht. Mit zunehmendem Wert wird die Kurve runder. Weitere Informationen finden Sie in [SPLINE77] und [PETZOLD].

**Returns:**
float
### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Liest oder schreibt die Spannung – einen 32‑Bit‑Gleitkommawert, der angibt, wie stark die Spline beim Durchlaufen der Punkte gebogen wird. Ein Wert von 0,0 gibt an, dass die Spline aus einer Folge gerader Linien besteht. Mit zunehmendem Wert wird die Kurve runder. Weitere Informationen finden Sie in [SPLINE77] und [PETZOLD].

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Liest oder schreibt die Punktdaten – ein Array von Count‑Punkten, die die Endpunkte der Linien angeben, die die Spline definieren. In einer geschlossenen kardinalen Spline setzt die Kurve nach dem letzten Punkt im PointData‑Array fort und verbindet sich mit dem ersten Punkt im Array.

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Liest oder schreibt die Punktdaten – ein Array von Count‑Punkten, die die Endpunkte der Linien angeben, die die Spline definieren. In einer geschlossenen kardinalen Spline setzt die Kurve nach dem letzten Punkt im PointData‑Array fort und verbindet sich mit dem ersten Punkt im Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

