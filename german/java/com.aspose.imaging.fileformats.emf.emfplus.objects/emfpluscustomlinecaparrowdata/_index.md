---
title: "EmfPlusCustomLineCapArrowData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusCustomLineCapArrowData-Objekt gibt einstellbare Pfeildaten für eine benutzerdefinierte Linienendkappe an."
type: docs
weight: 35
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecaparrowdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
```
public final class EmfPlusCustomLineCapArrowData extends EmfPlusCustomBaseLineCap
```

Das EmfPlusCustomLineCapArrowData-Objekt gibt einstellbare Pfeildaten für eine benutzerdefinierte Linienendkappe an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusCustomLineCapArrowData()](#EmfPlusCustomLineCapArrowData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getWidth()](#getWidth--) | Liest oder setzt einen 32‑Bit Gleitkommawert, der die Breite der Pfeilspitze angibt. |
| [setWidth(float value)](#setWidth-float-) | Liest oder setzt einen 32‑Bit Gleitkommawert, der die Breite der Pfeilspitze angibt. |
| [getHeight()](#getHeight--) | Liest oder setzt einen 32‑Bit Gleitkommawert, der die Höhe der Pfeilspitze angibt. |
| [setHeight(float value)](#setHeight-float-) | Liest oder setzt einen 32‑Bit Gleitkommawert, der die Höhe der Pfeilspitze angibt. |
| [getMiddleInset()](#getMiddleInset--) | Liest oder setzt einen 32‑Bit Gleitkommawert, der die Anzahl der Pixel zwischen der Kontur der Pfeilspitze und ihrer Füllung angibt. |
| [setMiddleInset(float value)](#setMiddleInset-float-) | Liest oder setzt einen 32‑Bit Gleitkommawert, der die Anzahl der Pixel zwischen der Kontur der Pfeilspitze und ihrer Füllung angibt. |
| [getFillState()](#getFillState--) | Liest oder setzt einen 32‑Bit Booleschen Wert, der angibt, ob die Pfeilspitze gefüllt ist. |
| [setFillState(boolean value)](#setFillState-boolean-) | Liest oder setzt einen 32‑Bit Booleschen Wert, der angibt, ob die Pfeilspitze gefüllt ist. |
| [getLineStartCap()](#getLineStartCap--) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineCap‑Aufzählung angibt, welcher den Linienabschluss am Anfang der zu zeichnenden Linie bestimmt. |
| [setLineStartCap(int value)](#setLineStartCap-int-) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineCap‑Aufzählung angibt, welcher den Linienabschluss am Anfang der zu zeichnenden Linie bestimmt. |
| [getLineEndCap()](#getLineEndCap--) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineCap‑Aufzählung angibt, welcher den Linienabschluss am Ende der zu zeichnenden Linie bestimmt. |
| [setLineEndCap(int value)](#setLineEndCap-int-) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineCap‑Aufzählung angibt, welcher den Linienabschluss am Ende der zu zeichnenden Linie bestimmt. |
| [getLineJoin()](#getLineJoin--) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineJoin‑Aufzählung angibt, der festlegt, wie zwei von demselben Stift gezeichnete Linien, deren Enden zusammenstoßen, verbunden werden. |
| [setLineJoin(int value)](#setLineJoin-int-) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineJoin‑Aufzählung angibt, der festlegt, wie zwei von demselben Stift gezeichnete Linien, deren Enden zusammenstoßen, verbunden werden. |
| [getLineMiterLimit()](#getLineMiterLimit--) | Liest oder setzt einen 32‑Bit Gleitkommawert, der die Begrenzung der Dicke der Verbindung an einer Gehrung festlegt, indem das maximal zulässige Verhältnis von Gehrungslänge zu Linienbreite angegeben wird. |
| [setLineMiterLimit(float value)](#setLineMiterLimit-float-) | Liest oder setzt einen 32‑Bit Gleitkommawert, der die Begrenzung der Dicke der Verbindung an einer Gehrung festlegt, indem das maximal zulässige Verhältnis von Gehrungslänge zu Linienbreite angegeben wird. |
| [getWidthScale()](#getWidthScale--) | Liest oder setzt einen 32‑Bit Gleitkommawert, der angibt, um welchen Faktor ein EmfPlusCustomLineCap‑Objekt in Bezug auf die Breite des Grafikstifts, der zum Zeichnen der Linien verwendet wird, skaliert wird. |
| [setWidthScale(float value)](#setWidthScale-float-) | Liest oder setzt einen 32‑Bit Gleitkommawert, der angibt, um welchen Faktor ein EmfPlusCustomLineCap‑Objekt in Bezug auf die Breite des Grafikstifts, der zum Zeichnen der Linien verwendet wird, skaliert wird. |
| [getFillHotSpot()](#getFillHotSpot--) | Liest oder schreibt das EmfPlusPointF‑Objekt, das derzeit nicht verwendet wird. |
| [setFillHotSpot(PointF value)](#setFillHotSpot-com.aspose.imaging.PointF-) | Liest oder schreibt das EmfPlusPointF‑Objekt, das derzeit nicht verwendet wird. |
| [getLineHotSpot()](#getLineHotSpot--) | Liest oder setzt ein EmfPlusPointF‑Objekt, das derzeit nicht verwendet wird. |
| [setLineHotSpot(PointF value)](#setLineHotSpot-com.aspose.imaging.PointF-) | Liest oder setzt ein EmfPlusPointF‑Objekt, das derzeit nicht verwendet wird. |
### EmfPlusCustomLineCapArrowData() {#EmfPlusCustomLineCapArrowData--}
```
public EmfPlusCustomLineCapArrowData()
```


### getWidth() {#getWidth--}
```
public float getWidth()
```


Liest oder setzt einen 32‑Bit Gleitkommawert, der die Breite der Pfeilspitze angibt.

**Returns:**
float
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Liest oder setzt einen 32‑Bit Gleitkommawert, der die Breite der Pfeilspitze angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Liest oder setzt einen 32‑Bit Gleitkommawert, der die Höhe der Pfeilspitze angibt.

**Returns:**
float
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Liest oder setzt einen 32‑Bit Gleitkommawert, der die Höhe der Pfeilspitze angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getMiddleInset() {#getMiddleInset--}
```
public float getMiddleInset()
```


Liest oder setzt einen 32‑Bit Gleitkommawert, der die Anzahl der Pixel zwischen der Kontur der Pfeilspitze und ihrer Füllung angibt.

**Returns:**
float
### setMiddleInset(float value) {#setMiddleInset-float-}
```
public void setMiddleInset(float value)
```


Liest oder setzt einen 32‑Bit Gleitkommawert, der die Anzahl der Pixel zwischen der Kontur der Pfeilspitze und ihrer Füllung angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getFillState() {#getFillState--}
```
public boolean getFillState()
```


Liest oder setzt einen 32‑Bit Booleschen Wert, der angibt, ob die Pfeilspitze gefüllt ist. Ist die Pfeilspitze nicht gefüllt, wird nur die Kontur gezeichnet.

**Returns:**
boolean
### setFillState(boolean value) {#setFillState-boolean-}
```
public void setFillState(boolean value)
```


Liest oder setzt einen 32‑Bit Booleschen Wert, der angibt, ob die Pfeilspitze gefüllt ist. Ist die Pfeilspitze nicht gefüllt, wird nur die Kontur gezeichnet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### getLineStartCap() {#getLineStartCap--}
```
public int getLineStartCap()
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineCap‑Aufzählung angibt, welcher den Linienabschluss am Anfang der zu zeichnenden Linie bestimmt.

**Returns:**
int
### setLineStartCap(int value) {#setLineStartCap-int-}
```
public void setLineStartCap(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineCap‑Aufzählung angibt, welcher den Linienabschluss am Anfang der zu zeichnenden Linie bestimmt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLineEndCap() {#getLineEndCap--}
```
public int getLineEndCap()
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineCap‑Aufzählung angibt, welcher den Linienabschluss am Ende der zu zeichnenden Linie bestimmt.

**Returns:**
int
### setLineEndCap(int value) {#setLineEndCap-int-}
```
public void setLineEndCap(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineCap‑Aufzählung angibt, welcher den Linienabschluss am Ende der zu zeichnenden Linie bestimmt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineJoin‑Aufzählung angibt, der festlegt, wie zwei von demselben Stift gezeichnete Linien, deren Enden zusammenstoßen, verbunden werden. An der Schnittstelle der beiden Linienenden sorgt ein Linienanschluss für ein kontinuierlicheres Aussehen.

**Returns:**
int
### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineJoin‑Aufzählung angibt, der festlegt, wie zwei von demselben Stift gezeichnete Linien, deren Enden zusammenstoßen, verbunden werden. An der Schnittstelle der beiden Linienenden sorgt ein Linienanschluss für ein kontinuierlicheres Aussehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getLineMiterLimit() {#getLineMiterLimit--}
```
public float getLineMiterLimit()
```


Liest oder setzt einen 32‑Bit Gleitkommawert, der die Begrenzung der Dicke der Verbindung an einer Gehrung festlegt, indem das maximal zulässige Verhältnis von Gehrungslänge zu Linienbreite angegeben wird.

**Returns:**
float
### setLineMiterLimit(float value) {#setLineMiterLimit-float-}
```
public void setLineMiterLimit(float value)
```


Liest oder setzt einen 32‑Bit Gleitkommawert, der die Begrenzung der Dicke der Verbindung an einer Gehrung festlegt, indem das maximal zulässige Verhältnis von Gehrungslänge zu Linienbreite angegeben wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Liest oder setzt einen 32‑Bit Gleitkommawert, der angibt, um welchen Faktor ein EmfPlusCustomLineCap‑Objekt in Bezug auf die Breite des Grafikstifts, der zum Zeichnen der Linien verwendet wird, skaliert wird.

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Liest oder setzt einen 32‑Bit Gleitkommawert, der angibt, um welchen Faktor ein EmfPlusCustomLineCap‑Objekt in Bezug auf die Breite des Grafikstifts, der zum Zeichnen der Linien verwendet wird, skaliert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getFillHotSpot() {#getFillHotSpot--}
```
public PointF getFillHotSpot()
```


Liest oder schreibt das EmfPlusPointF‑Objekt, das derzeit nicht verwendet wird. Es MUSS auf \{0.0, 0.0\} gesetzt werden.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setFillHotSpot(PointF value) {#setFillHotSpot-com.aspose.imaging.PointF-}
```
public void setFillHotSpot(PointF value)
```


Liest oder schreibt das EmfPlusPointF‑Objekt, das derzeit nicht verwendet wird. Es MUSS auf \{0.0, 0.0\} gesetzt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getLineHotSpot() {#getLineHotSpot--}
```
public PointF getLineHotSpot()
```


Liest oder setzt ein EmfPlusPointF‑Objekt, das derzeit nicht verwendet wird. Es MUSS auf \\{0.0, 0.0\\} gesetzt werden.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setLineHotSpot(PointF value) {#setLineHotSpot-com.aspose.imaging.PointF-}
```
public void setLineHotSpot(PointF value)
```


Liest oder setzt ein EmfPlusPointF‑Objekt, das derzeit nicht verwendet wird. Es MUSS auf \\{0.0, 0.0\\} gesetzt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

