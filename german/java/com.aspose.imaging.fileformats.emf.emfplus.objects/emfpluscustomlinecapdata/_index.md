---
title: "EmfPlusCustomLineCapData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusCustomLineCapData-Objekt gibt Standarddaten für eine benutzerdefinierte Linienendkappe an."
type: docs
weight: 36
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomBaseLineCap](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustombaselinecap)
```
public final class EmfPlusCustomLineCapData extends EmfPlusCustomBaseLineCap
```

Das EmfPlusCustomLineCapData-Objekt gibt Standarddaten für eine benutzerdefinierte Linienendkappe an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getCustomLineCapDataFlags()](#getCustomLineCapDataFlags--) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Daten im OptionalData‑Feld angibt. |
| [setCustomLineCapDataFlags(int value)](#setCustomLineCapDataFlags-int-) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Daten im OptionalData‑Feld angibt. |
| [getBaseCap()](#getBaseCap--) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert aus der LineCap‑Aufzählung (Abschnitt 2.1.1.18) angibt, auf dem die benutzerdefinierte Linienkapitel basiert. |
| [setBaseCap(int value)](#setBaseCap-int-) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert aus der LineCap‑Aufzählung (Abschnitt 2.1.1.18) angibt, auf dem die benutzerdefinierte Linienkapitel basiert. |
| [getBaseInset()](#getBaseInset--) | Liest oder setzt einen 32‑Bit Fließkommawert, der den Abstand zwischen dem Beginn des Linienabschlusses und dem Ende der Linie angibt. |
| [setBaseInset(float value)](#setBaseInset-float-) | Liest oder setzt einen 32‑Bit Fließkommawert, der den Abstand zwischen dem Beginn des Linienabschlusses und dem Ende der Linie angibt. |
| [getStrokeStartCap()](#getStrokeStartCap--) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineCap‑Aufzählung angibt, der den am Anfang der zu zeichnenden Linie verwendeten Linienabschluss bezeichnet. |
| [setStrokeStartCap(int value)](#setStrokeStartCap-int-) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineCap‑Aufzählung angibt, der den am Anfang der zu zeichnenden Linie verwendeten Linienabschluss bezeichnet. |
| [getStrokeEndCap()](#getStrokeEndCap--) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineCap‑Aufzählung angibt, der den am Ende der zu zeichnenden Linie zu verwendenden Linienabschluss bezeichnet. |
| [setStrokeEndCap(int value)](#setStrokeEndCap-int-) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineCap‑Aufzählung angibt, der den am Ende der zu zeichnenden Linie zu verwendenden Linienabschluss bezeichnet. |
| [getStrokeJoin()](#getStrokeJoin--) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineJoin‑Aufzählung (Abschnitt 2.1.1.19) angibt, die festlegt, wie zwei von demselben Stift gezeichnete Linien, deren Enden aufeinandertreffen, verbunden werden. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineJoin‑Aufzählung (Abschnitt 2.1.1.19) angibt, die festlegt, wie zwei von demselben Stift gezeichnete Linien, deren Enden aufeinandertreffen, verbunden werden. |
| [getStrokeMiterLimit()](#getStrokeMiterLimit--) | Liest oder setzt einen 32‑Bit Fließkommawert, der die Grenze der Dicke der Verbindung an einer Gehrungsecke enthält, indem das maximal zulässige Verhältnis von Gehrungslänge zu Linienbreite festgelegt wird. |
| [setStrokeMiterLimit(float value)](#setStrokeMiterLimit-float-) | Liest oder setzt einen 32‑Bit Fließkommawert, der die Grenze der Dicke der Verbindung an einer Gehrungsecke enthält, indem das maximal zulässige Verhältnis von Gehrungslänge zu Linienbreite festgelegt wird. |
| [getWidthScale()](#getWidthScale--) | Liest oder schreibt einen 32‑Bit‑Gleitkommawert, der die Menge angibt, um die die benutzerdefinierte Linienkappe relativ zur Breite des EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) skaliert wird, das zum Zeichnen der Linien verwendet wird. |
| [setWidthScale(float value)](#setWidthScale-float-) | Liest oder schreibt einen 32‑Bit‑Gleitkommawert, der die Menge angibt, um die die benutzerdefinierte Linienkappe relativ zur Breite des EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) skaliert wird, das zum Zeichnen der Linien verwendet wird. |
| [getFillHotSpot()](#getFillHotSpot--) | Liest oder schreibt das EmfPlusPointF‑Objekt, das derzeit nicht verwendet wird. |
| [setFillHotSpot(PointF value)](#setFillHotSpot-com.aspose.imaging.PointF-) | Liest oder schreibt das EmfPlusPointF‑Objekt, das derzeit nicht verwendet wird. |
| [getStrokeHotSpot()](#getStrokeHotSpot--) | Liest oder schreibt das EmfPlusPointF‑Objekt, das derzeit nicht verwendet wird. |
| [setStrokeHotSpot(PointF value)](#setStrokeHotSpot-com.aspose.imaging.PointF-) | Liest oder schreibt das EmfPlusPointF‑Objekt, das derzeit nicht verwendet wird. |
| [getOptionalData()](#getOptionalData--) | Liest oder schreibt das optionale EmfPlusCustomLineCapOptionalData‑Objekt (Abschnitt 2.2.2.14), das zusätzliche Daten für die benutzerdefinierte Grafik‑Linienkappe angibt. |
| [setOptionalData(EmfPlusCustomLineCapOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-) | Liest oder schreibt das optionale EmfPlusCustomLineCapOptionalData‑Objekt (Abschnitt 2.2.2.14), das zusätzliche Daten für die benutzerdefinierte Grafik‑Linienkappe angibt. |
### EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData--}
```
public EmfPlusCustomLineCapData()
```


### getCustomLineCapDataFlags() {#getCustomLineCapDataFlags--}
```
public int getCustomLineCapDataFlags()
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Daten im OptionalData‑Feld angibt.

**Returns:**
int
### setCustomLineCapDataFlags(int value) {#setCustomLineCapDataFlags-int-}
```
public void setCustomLineCapDataFlags(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Daten im OptionalData‑Feld angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert aus der LineCap‑Aufzählung (Abschnitt 2.1.1.18) angibt, auf dem die benutzerdefinierte Linienkapitel basiert.

**Returns:**
int
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert aus der LineCap‑Aufzählung (Abschnitt 2.1.1.18) angibt, auf dem die benutzerdefinierte Linienkapitel basiert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Liest oder setzt einen 32‑Bit Fließkommawert, der den Abstand zwischen dem Beginn des Linienabschlusses und dem Ende der Linie angibt.

**Returns:**
float
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Liest oder setzt einen 32‑Bit Fließkommawert, der den Abstand zwischen dem Beginn des Linienabschlusses und dem Ende der Linie angibt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getStrokeStartCap() {#getStrokeStartCap--}
```
public int getStrokeStartCap()
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineCap‑Aufzählung angibt, der den am Anfang der zu zeichnenden Linie verwendeten Linienabschluss bezeichnet.

**Returns:**
int
### setStrokeStartCap(int value) {#setStrokeStartCap-int-}
```
public void setStrokeStartCap(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineCap‑Aufzählung angibt, der den am Anfang der zu zeichnenden Linie verwendeten Linienabschluss bezeichnet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getStrokeEndCap() {#getStrokeEndCap--}
```
public int getStrokeEndCap()
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineCap‑Aufzählung angibt, der den am Ende der zu zeichnenden Linie zu verwendenden Linienabschluss bezeichnet.

**Returns:**
int
### setStrokeEndCap(int value) {#setStrokeEndCap-int-}
```
public void setStrokeEndCap(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der den Wert in der LineCap‑Aufzählung angibt, der den am Ende der zu zeichnenden Linie zu verwendenden Linienabschluss bezeichnet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Liest oder schreibt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Wert in der LineJoin‑Aufzählung (Abschnitt 2.1.1.19) angibt, welche festlegt, wie zwei Linien, die mit demselben Stift gezeichnet und deren Enden zusammenlaufen, verbunden werden. An der Schnittstelle der beiden Linienenden sorgt ein Linienzusammenfügen dafür, dass die Verbindung kontinuierlicher wirkt.

**Returns:**
int
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Liest oder schreibt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Wert in der LineJoin‑Aufzählung (Abschnitt 2.1.1.19) angibt, welche festlegt, wie zwei Linien, die mit demselben Stift gezeichnet und deren Enden zusammenlaufen, verbunden werden. An der Schnittstelle der beiden Linienenden sorgt ein Linienzusammenfügen dafür, dass die Verbindung kontinuierlicher wirkt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getStrokeMiterLimit() {#getStrokeMiterLimit--}
```
public float getStrokeMiterLimit()
```


Liest oder setzt einen 32‑Bit Fließkommawert, der die Grenze der Dicke der Verbindung an einer Gehrungsecke enthält, indem das maximal zulässige Verhältnis von Gehrungslänge zu Linienbreite festgelegt wird.

**Returns:**
float
### setStrokeMiterLimit(float value) {#setStrokeMiterLimit-float-}
```
public void setStrokeMiterLimit(float value)
```


Liest oder setzt einen 32‑Bit Fließkommawert, der die Grenze der Dicke der Verbindung an einer Gehrungsecke enthält, indem das maximal zulässige Verhältnis von Gehrungslänge zu Linienbreite festgelegt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Liest oder schreibt einen 32‑Bit‑Gleitkommawert, der die Menge angibt, um die die benutzerdefinierte Linienkappe relativ zur Breite des EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) skaliert wird, das zum Zeichnen der Linien verwendet wird.

**Returns:**
float
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Liest oder schreibt einen 32‑Bit‑Gleitkommawert, der die Menge angibt, um die die benutzerdefinierte Linienkappe relativ zur Breite des EmfPlusPen‑Objekts (Abschnitt 2.2.1.7) skaliert wird, das zum Zeichnen der Linien verwendet wird.

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

### getStrokeHotSpot() {#getStrokeHotSpot--}
```
public PointF getStrokeHotSpot()
```


Liest oder schreibt das EmfPlusPointF‑Objekt, das derzeit nicht verwendet wird. Es MUSS auf \{0.0, 0.0\} gesetzt werden.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setStrokeHotSpot(PointF value) {#setStrokeHotSpot-com.aspose.imaging.PointF-}
```
public void setStrokeHotSpot(PointF value)
```


Liest oder schreibt das EmfPlusPointF‑Objekt, das derzeit nicht verwendet wird. Es MUSS auf \{0.0, 0.0\} gesetzt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusCustomLineCapOptionalData getOptionalData()
```


Liest oder schreibt das optionale EmfPlusCustomLineCapOptionalData‑Objekt (Abschnitt 2.2.2.14), das zusätzliche Daten für die benutzerdefinierte Grafik‑Linienkappe angibt. Der konkrete Inhalt dieses Feldes wird durch den Wert des CustomLineCapDataFlags‑Feldes bestimmt.

**Returns:**
[EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata)
### setOptionalData(EmfPlusCustomLineCapOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapOptionalData-}
```
public void setOptionalData(EmfPlusCustomLineCapOptionalData value)
```


Liest oder schreibt das optionale EmfPlusCustomLineCapOptionalData‑Objekt (Abschnitt 2.2.2.14), das zusätzliche Daten für die benutzerdefinierte Grafik‑Linienkappe angibt. Der konkrete Inhalt dieses Feldes wird durch den Wert des CustomLineCapDataFlags‑Feldes bestimmt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusCustomLineCapOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata) |  |

