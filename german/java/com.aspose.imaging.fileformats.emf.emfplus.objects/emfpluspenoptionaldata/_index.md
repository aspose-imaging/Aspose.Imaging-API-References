---
title: "EmfPlusPenOptionalData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusPenOptionalData-Objekt gibt optionale Daten für einen Grafikstift an."
type: docs
weight: 65
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenOptionalData extends EmfPlusStructureObjectType
```

Das EmfPlusPenOptionalData-Objekt gibt optionale Daten für einen Grafikstift an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Liest oder setzt ein optionales EmfPlusTransformMatrix-Objekt (section 2.2.2.47), das eine Transformation vom Welt- in den Geräteraum für den Stift angibt. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Liest oder setzt ein optionales EmfPlusTransformMatrix-Objekt (section 2.2.2.47), das eine Transformation vom Welt- in den Geräteraum für den Stift angibt. |
| [getStartCap()](#getStartCap--) | Liest oder setzt eine optionale 32-Bit-vorzeichenbehaftete Ganzzahl, die die Form für den Anfang einer Linie im Feld CustomStartCapData angibt. |
| [setStartCap(int value)](#setStartCap-int-) | Liest oder setzt eine optionale 32-Bit-vorzeichenbehaftete Ganzzahl, die die Form für den Anfang einer Linie im Feld CustomStartCapData angibt. |
| [getEndCap()](#getEndCap--) | Liest oder setzt eine optionale 32-Bit-vorzeichenbehaftete Ganzzahl, die die Form für das Ende einer Linie im Feld CustomEndCapData angibt. |
| [setEndCap(int value)](#setEndCap-int-) | Liest oder setzt eine optionale 32-Bit-vorzeichenbehaftete Ganzzahl, die die Form für das Ende einer Linie im Feld CustomEndCapData angibt. |
| [getJoin()](#getJoin--) | Liest oder setzt eine optionale 32-Bit-vorzeichenbehaftete Ganzzahl, die angibt, wie zwei Linien, die mit demselben Stift gezeichnet werden und deren Enden zusammenstoßen, verbunden werden. |
| [setJoin(int value)](#setJoin-int-) | Liest oder setzt eine optionale 32-Bit-vorzeichenbehaftete Ganzzahl, die angibt, wie zwei Linien, die mit demselben Stift gezeichnet werden und deren Enden zusammenstoßen, verbunden werden. |
| [getMiterLimit()](#getMiterLimit--) | Liest oder setzt einen optionalen 32-Bit-Gleitkommawert, der die Gehrungsgrenze angibt, also das maximal zulässige Verhältnis von Gehrungslänge zu Linienbreite. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Liest oder setzt einen optionalen 32-Bit-Gleitkommawert, der die Gehrungsgrenze angibt, also das maximal zulässige Verhältnis von Gehrungslänge zu Linienbreite. |
| [getLineStyle()](#getLineStyle--) | Liest oder setzt eine optionale 32-Bit-vorzeichenbehaftete Ganzzahl, die den Stil für mit diesem Stiftobjekt gezeichnete Linien angibt. |
| [setLineStyle(int value)](#setLineStyle-int-) | Liest oder setzt eine optionale 32-Bit-vorzeichenbehaftete Ganzzahl, die den Stil für mit diesem Stiftobjekt gezeichnete Linien angibt. |
| [getDashedLineCapType()](#getDashedLineCapType--) | Liest oder setzt eine optionale 32-Bit-vorzeichenbehaftete Ganzzahl, die die Form für beide Enden jedes Strichs in einer gestrichelten Linie angibt. |
| [setDashedLineCapType(int value)](#setDashedLineCapType-int-) | Liest oder setzt eine optionale 32-Bit-vorzeichenbehaftete Ganzzahl, die die Form für beide Enden jedes Strichs in einer gestrichelten Linie angibt. |
| [getDashOffset()](#getDashOffset--) | Liest oder setzt einen optionalen 32-Bit-Gleitkommawert, der den Abstand vom Beginn einer Linie bis zum Beginn des ersten Leerraums in einem gestrichelten Linienmuster angibt. |
| [setDashOffset(float value)](#setDashOffset-float-) | Liest oder setzt einen optionalen 32-Bit-Gleitkommawert, der den Abstand vom Beginn einer Linie bis zum Beginn des ersten Leerraums in einem gestrichelten Linienmuster angibt. |
| [getDashedLineData()](#getDashedLineData--) | Liest oder setzt ein optionales EmfPlusDashedLineData-Objekt (section 2.2.2.16), das die Längen von Strichen und Lücken in einer benutzerdefinierten gestrichelten Linie angibt. |
| [setDashedLineData(EmfPlusDashedLineData value)](#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-) | Liest oder setzt ein optionales EmfPlusDashedLineData-Objekt (section 2.2.2.16), das die Längen von Strichen und Lücken in einer benutzerdefinierten gestrichelten Linie angibt. |
| [getPenAlignment()](#getPenAlignment--) | Liest oder setzt eine optionale 32-Bit-vorzeichenbehaftete Ganzzahl, die die Verteilung der Stiftbreite in Bezug auf die Koordinaten der gezeichneten Linie angibt. |
| [setPenAlignment(int value)](#setPenAlignment-int-) | Liest oder setzt eine optionale 32-Bit-vorzeichenbehaftete Ganzzahl, die die Verteilung der Stiftbreite in Bezug auf die Koordinaten der gezeichneten Linie angibt. |
| [getCompoundLineData()](#getCompoundLineData--) | Liest oder setzt ein optionales EmfPlusCompoundLineData-Objekt (section 2.2.2.9), das ein Array von Gleitkommawerten angibt, die die Verbundlinie eines Stifts definieren, die aus parallelen Linien und Lücken besteht. |
| [setCompoundLineData(EmfPlusCompoundLineData value)](#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-) | Liest oder setzt ein optionales EmfPlusCompoundLineData-Objekt (section 2.2.2.9), das ein Array von Gleitkommawerten angibt, die die Verbundlinie eines Stifts definieren, die aus parallelen Linien und Lücken besteht. |
| [getCustomStartCapData()](#getCustomStartCapData--) | Liest oder setzt ein optionales EmfPlusCustomStartCapData-Objekt (section 2.2.2.15), das die benutzerdefinierte Startkap-Form definiert, also die Form, die am Anfang einer mit diesem Stift gezeichneten Linie verwendet wird. |
| [setCustomStartCapData(EmfPlusCustomStartCapData value)](#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-) | Liest oder setzt ein optionales EmfPlusCustomStartCapData-Objekt (section 2.2.2.15), das die benutzerdefinierte Startkap-Form definiert, also die Form, die am Anfang einer mit diesem Stift gezeichneten Linie verwendet wird. |
| [getCustomEndCapData()](#getCustomEndCapData--) | Liest oder setzt ein optionales EmfPlusCustomEndCapData-Objekt (section 2.2.2.11), das die benutzerdefinierte Endkap-Form definiert, also die Form, die am Ende einer mit diesem Stift gezeichneten Linie verwendet wird. |
| [setCustomEndCapData(EmfPlusCustomEndCapData value)](#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-) | Liest oder setzt ein optionales EmfPlusCustomEndCapData-Objekt (section 2.2.2.11), das die benutzerdefinierte Endkap-Form definiert, also die Form, die am Ende einer mit diesem Stift gezeichneten Linie verwendet wird. |
### EmfPlusPenOptionalData() {#EmfPlusPenOptionalData--}
```
public EmfPlusPenOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Liest oder setzt ein optionales EmfPlusTransformMatrix-Objekt (section 2.2.2.47), das eine Transformation vom Welt- in den Geräteraum für den Stift angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataTransform-Flag im Feld PenDataFlags des EmfPlusPenData-Objekts gesetzt ist.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Liest oder setzt ein optionales EmfPlusTransformMatrix-Objekt (section 2.2.2.47), das eine Transformation vom Welt- in den Geräteraum für den Stift angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataTransform-Flag im Feld PenDataFlags des EmfPlusPenData-Objekts gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Liest oder setzt eine optionale 32-Bit-vorzeichenbehaftete Ganzzahl, die die Form für den Anfang einer Linie im Feld CustomStartCapData angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataStartCap-Flag im Feld PenDataFlags des EmfPlusPenData-Objekts gesetzt ist, und der Wert MUSS in der LineCapType-Aufzählung (section 2.1.1.18) definiert sein.

**Returns:**
int
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Liest oder setzt eine optionale 32-Bit-vorzeichenbehaftete Ganzzahl, die die Form für den Anfang einer Linie im Feld CustomStartCapData angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataStartCap-Flag im Feld PenDataFlags des EmfPlusPenData-Objekts gesetzt ist, und der Wert MUSS in der LineCapType-Aufzählung (section 2.1.1.18) definiert sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Liest oder setzt eine optionale 32-Bit-vorzeichenbehaftete Ganzzahl, die die Form für das Ende einer Linie im Feld CustomEndCapData angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataEndCap-Flag im Feld PenDataFlags des EmfPlusPenData-Objekts gesetzt ist, und der Wert MUSS in der LineCapType-Aufzählung definiert sein.

**Returns:**
int
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Liest oder setzt eine optionale 32-Bit-vorzeichenbehaftete Ganzzahl, die die Form für das Ende einer Linie im Feld CustomEndCapData angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataEndCap-Flag im Feld PenDataFlags des EmfPlusPenData-Objekts gesetzt ist, und der Wert MUSS in der LineCapType-Aufzählung definiert sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getJoin() {#getJoin--}
```
public int getJoin()
```


Liest oder schreibt einen optionalen 32‑Bit‑vorzeichenbehafteten Integer, der angibt, wie zwei von derselben Pen gezeichnete Linien, deren Enden zusammenstoßen, verbunden werden. Dieses Feld MUSS vorhanden sein, wenn das PenDataJoin‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist, und der Wert MUSS in der Aufzählung LineJoinType definiert sein (Abschnitt 2.1.1.19).

**Returns:**
int
### setJoin(int value) {#setJoin-int-}
```
public void setJoin(int value)
```


Liest oder schreibt einen optionalen 32‑Bit‑vorzeichenbehafteten Integer, der angibt, wie zwei von derselben Pen gezeichnete Linien, deren Enden zusammenstoßen, verbunden werden. Dieses Feld MUSS vorhanden sein, wenn das PenDataJoin‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist, und der Wert MUSS in der Aufzählung LineJoinType definiert sein (Abschnitt 2.1.1.19).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Liest oder schreibt einen optionalen 32‑Bit‑Gleitkommawert, der die Kehlungsgrenze (Miter‑Limit) angibt, also das maximal zulässige Verhältnis von Kehlungs­länge zur Linienbreite. Die Kehlungs­länge ist der Abstand von der Schnittstelle der Linienwände auf der Innenseite der Verbindung zur Schnittstelle der Linienwände auf der Außenseite der Verbindung. Die Kehlungs­länge kann groß sein, wenn der Winkel zwischen zwei Linien klein ist. Dieses Feld MUSS vorhanden sein, wenn das PenDataMiterLimit‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist.

**Returns:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Liest oder schreibt einen optionalen 32‑Bit‑Gleitkommawert, der die Kehlungsgrenze (Miter‑Limit) angibt, also das maximal zulässige Verhältnis von Kehlungs­länge zur Linienbreite. Die Kehlungs­länge ist der Abstand von der Schnittstelle der Linienwände auf der Innenseite der Verbindung zur Schnittstelle der Linienwände auf der Außenseite der Verbindung. Die Kehlungs­länge kann groß sein, wenn der Winkel zwischen zwei Linien klein ist. Dieses Feld MUSS vorhanden sein, wenn das PenDataMiterLimit‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getLineStyle() {#getLineStyle--}
```
public int getLineStyle()
```


Liest oder schreibt einen optionalen 32‑Bit‑vorzeichenbehafteten Integer, der den Stil angibt, der für mit diesem Pen‑Objekt gezeichnete Linien verwendet wird. Dieses Feld MUSS vorhanden sein, wenn das PenDataLineStyle‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist, und der Wert MUSS in der Aufzählung LineStyle definiert sein (Abschnitt 2.1.1.20).

**Returns:**
int
### setLineStyle(int value) {#setLineStyle-int-}
```
public void setLineStyle(int value)
```


Liest oder schreibt einen optionalen 32‑Bit‑vorzeichenbehafteten Integer, der den Stil angibt, der für mit diesem Pen‑Objekt gezeichnete Linien verwendet wird. Dieses Feld MUSS vorhanden sein, wenn das PenDataLineStyle‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist, und der Wert MUSS in der Aufzählung LineStyle definiert sein (Abschnitt 2.1.1.20).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDashedLineCapType() {#getDashedLineCapType--}
```
public int getDashedLineCapType()
```


Liest oder schreibt einen optionalen 32‑Bit‑vorzeichenbehafteten Integer, der die Form für beide Enden jedes Strichs in einer gestrichelten Linie angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataDashedLineCap‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist, und der Wert MUSS in der Aufzählung DashedLineCapType definiert sein (Abschnitt 2.1.1.10).

**Returns:**
int
### setDashedLineCapType(int value) {#setDashedLineCapType-int-}
```
public void setDashedLineCapType(int value)
```


Liest oder schreibt einen optionalen 32‑Bit‑vorzeichenbehafteten Integer, der die Form für beide Enden jedes Strichs in einer gestrichelten Linie angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataDashedLineCap‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist, und der Wert MUSS in der Aufzählung DashedLineCapType definiert sein (Abschnitt 2.1.1.10).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Liest oder schreibt einen optionalen 32‑Bit‑Gleitkommawert, der den Abstand vom Beginn einer Linie bis zum Beginn des ersten Leerraums in einem gestrichelten Linienmuster angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataDashedLineOffset‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist.

**Returns:**
float
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Liest oder schreibt einen optionalen 32‑Bit‑Gleitkommawert, der den Abstand vom Beginn einer Linie bis zum Beginn des ersten Leerraums in einem gestrichelten Linienmuster angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataDashedLineOffset‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getDashedLineData() {#getDashedLineData--}
```
public EmfPlusDashedLineData getDashedLineData()
```


Liest oder schreibt ein optionales EmfPlusDashedLineData‑Objekt (Abschnitt 2.2.2.16), das die Längen von Strichen und Leerräumen in einer benutzerdefinierten gestrichelten Linie angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataDashedLine‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist.

**Returns:**
[EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata)
### setDashedLineData(EmfPlusDashedLineData value) {#setDashedLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusDashedLineData-}
```
public void setDashedLineData(EmfPlusDashedLineData value)
```


Liest oder schreibt ein optionales EmfPlusDashedLineData‑Objekt (Abschnitt 2.2.2.16), das die Längen von Strichen und Leerräumen in einer benutzerdefinierten gestrichelten Linie angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataDashedLine‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata) |  |

### getPenAlignment() {#getPenAlignment--}
```
public int getPenAlignment()
```


Liest oder schreibt einen optionalen 32‑Bit‑vorzeichenbehafteten Integer, der die Verteilung der Pen‑Breite in Bezug auf die Koordinaten der zu zeichnenden Linie angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataNonCenter‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist, und der Wert MUSS in der Aufzählung PenAlignment definiert sein (Abschnitt 2.1.1.24).

**Returns:**
int
### setPenAlignment(int value) {#setPenAlignment-int-}
```
public void setPenAlignment(int value)
```


Liest oder schreibt einen optionalen 32‑Bit‑vorzeichenbehafteten Integer, der die Verteilung der Pen‑Breite in Bezug auf die Koordinaten der zu zeichnenden Linie angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataNonCenter‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist, und der Wert MUSS in der Aufzählung PenAlignment definiert sein (Abschnitt 2.1.1.24).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getCompoundLineData() {#getCompoundLineData--}
```
public EmfPlusCompoundLineData getCompoundLineData()
```


Liest oder schreibt ein optionales EmfPlusCompoundLineData‑Objekt (Abschnitt 2.2.2.9), das ein Array von Gleitkommawerten angibt, die die Verbundlinie eines Pens definieren, die aus parallelen Linien und Zwischenräumen besteht. Dieses Feld MUSS vorhanden sein, wenn das PenDataCompoundLine‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist

**Returns:**
[EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata)
### setCompoundLineData(EmfPlusCompoundLineData value) {#setCompoundLineData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCompoundLineData-}
```
public void setCompoundLineData(EmfPlusCompoundLineData value)
```


Liest oder schreibt ein optionales EmfPlusCompoundLineData‑Objekt (Abschnitt 2.2.2.9), das ein Array von Gleitkommawerten angibt, die die Verbundlinie eines Pens definieren, die aus parallelen Linien und Zwischenräumen besteht. Dieses Feld MUSS vorhanden sein, wenn das PenDataCompoundLine‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata) |  |

### getCustomStartCapData() {#getCustomStartCapData--}
```
public EmfPlusCustomStartCapData getCustomStartCapData()
```


Liest oder schreibt ein optionales EmfPlusCustomStartCapData‑Objekt (Abschnitt 2.2.2.15), das die benutzerdefinierte Startkap‑Form definiert, also die Form, die am Anfang einer mit diesem Pen gezeichneten Linie verwendet wird. Sie kann eine von verschiedenen Formen sein, z. B. ein Quadrat, ein Kreis oder ein Diamant. Dieses Feld MUSS vorhanden sein, wenn das PenDataCustomStartCap‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist

**Returns:**
[EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata)
### setCustomStartCapData(EmfPlusCustomStartCapData value) {#setCustomStartCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomStartCapData-}
```
public void setCustomStartCapData(EmfPlusCustomStartCapData value)
```


Liest oder schreibt ein optionales EmfPlusCustomStartCapData‑Objekt (Abschnitt 2.2.2.15), das die benutzerdefinierte Startkap‑Form definiert, also die Form, die am Anfang einer mit diesem Pen gezeichneten Linie verwendet wird. Sie kann eine von verschiedenen Formen sein, z. B. ein Quadrat, ein Kreis oder ein Diamant. Dieses Feld MUSS vorhanden sein, wenn das PenDataCustomStartCap‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata) |  |

### getCustomEndCapData() {#getCustomEndCapData--}
```
public EmfPlusCustomEndCapData getCustomEndCapData()
```


Liest oder schreibt ein optionales EmfPlusCustomEndCapData‑Objekt (Abschnitt 2.2.2.11), das die benutzerdefinierte Endkap‑Form definiert, also die Form, die am Ende einer mit diesem Pen gezeichneten Linie verwendet wird. Sie kann eine von verschiedenen Formen sein, z. B. ein Quadrat, ein Kreis oder ein Diamant. Dieses Feld MUSS vorhanden sein, wenn das PenDataCustomEndCap‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist

**Returns:**
[EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata)
### setCustomEndCapData(EmfPlusCustomEndCapData value) {#setCustomEndCapData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomEndCapData-}
```
public void setCustomEndCapData(EmfPlusCustomEndCapData value)
```


Liest oder schreibt ein optionales EmfPlusCustomEndCapData‑Objekt (Abschnitt 2.2.2.11), das die benutzerdefinierte Endkap‑Form definiert, also die Form, die am Ende einer mit diesem Pen gezeichneten Linie verwendet wird. Sie kann eine von verschiedenen Formen sein, z. B. ein Quadrat, ein Kreis oder ein Diamant. Dieses Feld MUSS vorhanden sein, wenn das PenDataCustomEndCap‑Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata) |  |

