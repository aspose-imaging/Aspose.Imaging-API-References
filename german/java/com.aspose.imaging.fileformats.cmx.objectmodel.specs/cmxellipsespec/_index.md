---
title: "CmxEllipseSpec"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt geometrische Informationen dar, die für eine Ellipse angegeben wurden."
type: docs
weight: 11
url: /de/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxEllipseSpec implements ICmxObjectSpec
```

Stellt geometrische Informationen dar, die für eine Ellipse angegeben wurden.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [CmxEllipseSpec()](#CmxEllipseSpec--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAngle1()](#getAngle1--) | Ruft den ersten Winkel ab, der zur Definition des Kuchenabschnitts verwendet wird. |
| [setAngle1(float value)](#setAngle1-float-) | Setzt den ersten Winkel, der zur Definition des Kuchenabschnitts verwendet wird. |
| [getAngle2()](#getAngle2--) | Ruft den zweiten Winkel ab, der zur Definition des Kuchenabschnitts verwendet wird. |
| [setAngle2(float value)](#setAngle2-float-) | Setzt den zweiten Winkel, der zur Definition des Kuchenabschnitts verwendet wird. |
| [getRotation()](#getRotation--) | Ruft den Rotationswinkel der Ellipse ab. |
| [setRotation(float value)](#setRotation-float-) | Setzt den Rotationswinkel der Ellipse. |
| [getPie()](#getPie--) | Ruft einen Wert ab, der angibt, ob dieses [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) ein Kuchen ist. |
| [setPie(boolean value)](#setPie-boolean-) | Setzt einen Wert, der angibt, ob dieses [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) ein Kuchen ist. |
| [getCenterX()](#getCenterX--) | Ermittelt die X‑Koordinate für das Zentrum des Rechtecks. |
| [setCenterX(float value)](#setCenterX-float-) | Setzt die X‑Koordinate für das Zentrum des Rechtecks. |
| [getCenterY()](#getCenterY--) | Ermittelt die Y‑Koordinate für das Zentrum des Rechtecks. |
| [setCenterY(float value)](#setCenterY-float-) | Setzt die Y‑Koordinate für das Zentrum des Rechtecks. |
| [getDiameterX()](#getDiameterX--) | Ruft den Durchmesser für die X-Dimension des Rechtecks ab. |
| [setDiameterX(float value)](#setDiameterX-float-) | Setzt den Durchmesser für die X-Dimension des Rechtecks. |
| [getDiameterY()](#getDiameterY--) | Ruft den Durchmesser für die Y-Dimension des Rechtecks ab. |
| [setDiameterY(float value)](#setDiameterY-float-) | Setzt den Durchmesser für die Y-Dimension des Rechtecks. |
| [getBoundingBox()](#getBoundingBox--) | Ruft die Begrenzungsbox ab. |
| [setBoundingBox(RectangleF value)](#setBoundingBox-com.aspose.imaging.RectangleF-) | Setzt die Begrenzungsbox. |
| [toString()](#toString--) | Gibt einen String zurück, der diese Instanz darstellt. |
| [equals(Object o)](#equals-java.lang.Object-) | Überprüft, ob Objekte gleich sind. |
| [hashCode()](#hashCode--) | Gibt den Hashcode des aktuellen Objekts zurück. |
### CmxEllipseSpec() {#CmxEllipseSpec--}
```
public CmxEllipseSpec()
```


### getAngle1() {#getAngle1--}
```
public final float getAngle1()
```


Ruft den ersten Winkel ab, der zur Definition des Kuchenabschnitts verwendet wird. Hat keinen Einfluss, wenn `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) `false` ist. Misst in Radianten.

**Returns:**
float - der erste Winkel, der zur Definition des Kuchenabschnitts verwendet wird.
### setAngle1(float value) {#setAngle1-float-}
```
public final void setAngle1(float value)
```


Setzt den ersten Winkel, der zur Definition des Kuchenabschnitts verwendet wird. Hat keinen Einfluss, wenn `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) `false` ist. Misst in Radianten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | der erste Winkel, der zur Definition des Kuchenabschnitts verwendet wird. |

### getAngle2() {#getAngle2--}
```
public final float getAngle2()
```


Liest den zweiten Winkel, der zur Definition des Kuchenabschnitts verwendet wird. Hat keinen Einfluss, wenn `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) `false` ist. Misst in Radianten.

**Returns:**
float - der zweite Winkel, der zur Definition des Kuchenabschnitts verwendet wird.
### setAngle2(float value) {#setAngle2-float-}
```
public final void setAngle2(float value)
```


Setzt den zweiten Winkel, der zur Definition des Kuchenabschnitts verwendet wird. Hat keinen Einfluss, wenn `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) `false` ist. Misst in Radianten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | der zweite Winkel, der zur Definition des Kuchenabschnitts verwendet wird. |

### getRotation() {#getRotation--}
```
public final float getRotation()
```


Liest den Rotationswinkel der Ellipse. Misst in Radianten.

**Returns:**
float - der Rotationswinkel der Ellipse.
### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```


Setzt den Rotationswinkel der Ellipse. Misst in Radianten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | der Rotationswinkel der Ellipse. |

### getPie() {#getPie--}
```
public final boolean getPie()
```


Ruft einen Wert ab, der angibt, ob dieses [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) ein Kuchen ist.

**Returns:**
boolean - ein Wert, der angibt, ob dieses [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) ein Kuchen ist.
### setPie(boolean value) {#setPie-boolean-}
```
public final void setPie(boolean value)
```


Setzt einen Wert, der angibt, ob dieses [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) ein Kuchen ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean | ein Wert, der angibt, ob dieses [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) ein Kuchen ist. |

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


Ermittelt die X‑Koordinate für das Zentrum des Rechtecks. Gemessen in üblichen Dokumentabstandseinheiten.

**Returns:**
float - die X‑Koordinate für das Zentrum des Rechtecks.
### setCenterX(float value) {#setCenterX-float-}
```
public final void setCenterX(float value)
```


Setzt die X‑Koordinate für das Zentrum des Rechtecks. Gemessen in üblichen Dokumentabstandseinheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | die X‑Koordinate für das Zentrum des Rechtecks. |

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


Liefert die Y‑Koordinate für die Mitte des Rechtecks. Gemessen in üblichen Dokumentabstandseinheiten.

**Returns:**
float - die Y‑Koordinate für die Mitte des Rechtecks.
### setCenterY(float value) {#setCenterY-float-}
```
public final void setCenterY(float value)
```


Setzt die Y‑Koordinate für die Mitte des Rechtecks. Gemessen in üblichen Dokumentabstandseinheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | die Y‑Koordinate für die Mitte des Rechtecks. |

### getDiameterX() {#getDiameterX--}
```
public final float getDiameterX()
```


Liest den Durchmesser für die X-Dimension des Rechtecks. Misst in üblichen Dokumentabstandseinheiten.

**Returns:**
float - der Durchmesser für die X-Dimension des Rechtecks.
### setDiameterX(float value) {#setDiameterX-float-}
```
public final void setDiameterX(float value)
```


Setzt den Durchmesser für die X-Dimension des Rechtecks. Misst in üblichen Dokumentabstandseinheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | der Durchmesser für die X-Dimension des Rechtecks. |

### getDiameterY() {#getDiameterY--}
```
public final float getDiameterY()
```


Liest den Durchmesser für die Y-Dimension des Rechtecks. Misst in üblichen Dokumentabstandseinheiten.

**Returns:**
float - der Durchmesser für die Y-Dimension des Rechtecks.
### setDiameterY(float value) {#setDiameterY-float-}
```
public final void setDiameterY(float value)
```


Setzt den Durchmesser für die Y-Dimension des Rechtecks. Misst in üblichen Dokumentabstandseinheiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | der Durchmesser für die Y-Dimension des Rechtecks. |

### getBoundingBox() {#getBoundingBox--}
```
public final RectangleF getBoundingBox()
```


Ruft die Begrenzungsbox ab.

Wert: Die Begrenzungsbox.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bounding box.
### setBoundingBox(RectangleF value) {#setBoundingBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundingBox(RectangleF value)
```


Setzt die Begrenzungsbox.

Wert: Die Begrenzungsbox.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | die Begrenzungsbox. |

### toString() {#toString--}
```
public String toString()
```


Gibt einen String zurück, der diese Instanz darstellt.

**Returns:**
java.lang.String - Ein String, der diese Instanz darstellt.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Überprüft, ob Objekte gleich sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| o | java.lang.Object | Das andere Objekt. |

**Returns:**
boolean - Das Ergebnis des Gleichheitsvergleichs.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Gibt den Hashcode des aktuellen Objekts zurück.

**Returns:**
int - Der Hashcode.
