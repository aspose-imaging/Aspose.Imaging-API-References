---
title: "CmxEllipseSpec"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar geometrisk information specificerad för en ellips."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxEllipseSpec implements ICmxObjectSpec
```

Representerar geometrisk information specificerad för en ellips.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [CmxEllipseSpec()](#CmxEllipseSpec--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAngle1()](#getAngle1--) | Hämtar den första vinkeln som används för att definiera pajsektorn. |
| [setAngle1(float value)](#setAngle1-float-) | Ställer in den första vinkeln som används för att definiera pajsektorn. |
| [getAngle2()](#getAngle2--) | Hämtar den andra vinkeln som används för att definiera pajsektorn. |
| [setAngle2(float value)](#setAngle2-float-) | Ställer in den andra vinkeln som används för att definiera pajsektorn. |
| [getRotation()](#getRotation--) | Hämtar ellipsens rotationsvinkel. |
| [setRotation(float value)](#setRotation-float-) | Ställer in ellipsens rotationsvinkel. |
| [getPie()](#getPie--) | Hämtar ett värde som indikerar om detta [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) är en paj. |
| [setPie(boolean value)](#setPie-boolean-) | Ställer in ett värde som indikerar om detta [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) är en paj. |
| [getCenterX()](#getCenterX--) | Hämtar X-koordinaten för rektangelns centrum. |
| [setCenterX(float value)](#setCenterX-float-) | Ställer in X-koordinaten för rektangelns centrum. |
| [getCenterY()](#getCenterY--) | Hämtar Y-koordinaten för rektangelns centrum. |
| [setCenterY(float value)](#setCenterY-float-) | Ställer in Y-koordinaten för rektangelns centrum. |
| [getDiameterX()](#getDiameterX--) | Hämtar diametern för X-dimensionen av rektangeln. |
| [setDiameterX(float value)](#setDiameterX-float-) | Ställer in diametern för X-dimensionen av rektangeln. |
| [getDiameterY()](#getDiameterY--) | Hämtar diametern för Y-dimensionen av rektangeln. |
| [setDiameterY(float value)](#setDiameterY-float-) | Ställer in diametern för Y-dimensionen av rektangeln. |
| [getBoundingBox()](#getBoundingBox--) | Hämtar den omgivande rutan. |
| [setBoundingBox(RectangleF value)](#setBoundingBox-com.aspose.imaging.RectangleF-) | Ställer in den omgivande rutan. |
| [toString()](#toString--) | Returnerar en String som representerar detta objekt. |
| [equals(Object o)](#equals-java.lang.Object-) | Kontrollera om objekt är lika. |
| [hashCode()](#hashCode--) | Hämta hashkoden för det aktuella objektet. |
### CmxEllipseSpec() {#CmxEllipseSpec--}
```
public CmxEllipseSpec()
```


### getAngle1() {#getAngle1--}
```
public final float getAngle1()
```


Hämtar den första vinkeln som används för att definiera pajsektorn. Påverkar inte om `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) är `false`. Mäter i radianer.

**Returns:**
float - den första vinkeln som används för att definiera pajsektorn.
### setAngle1(float value) {#setAngle1-float-}
```
public final void setAngle1(float value)
```


Ställer in den första vinkeln som används för att definiera pajsektorn. Påverkar inte om `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) är `false`. Mäter i radianer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | den första vinkeln som används för att definiera en pajsektor. |

### getAngle2() {#getAngle2--}
```
public final float getAngle2()
```


Hämtar den andra vinkeln som används för att definiera en pajsektor. Påverkar inte om `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) är `false`. Mäts i radianer.

**Returns:**
float - den andra vinkeln som används för att definiera en pajsektor.
### setAngle2(float value) {#setAngle2-float-}
```
public final void setAngle2(float value)
```


Ställer in den andra vinkeln som används för att definiera en pajsektor. Påverkar inte om `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) är `false`. Mäts i radianer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | den andra vinkeln som används för att definiera en pajsektor. |

### getRotation() {#getRotation--}
```
public final float getRotation()
```


Hämtar ellipsens rotationsvinkel. Mäts i radianer.

**Returns:**
float - ellipsens rotationsvinkel.
### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```


Ställer in ellipsens rotationsvinkel. Mäts i radianer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | ellipsens rotationsvinkel. |

### getPie() {#getPie--}
```
public final boolean getPie()
```


Hämtar ett värde som indikerar om detta [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) är en paj.

**Returns:**
boolean - ett värde som indikerar om denna [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) är en paj.
### setPie(boolean value) {#setPie-boolean-}
```
public final void setPie(boolean value)
```


Ställer in ett värde som indikerar om detta [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) är en paj.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean | ett värde som indikerar om denna [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) är en paj. |

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


Hämtar X-koordinaten för rektangelns centrum. Mäts i vanliga dokumentavståndsenheter.

**Returns:**
float - X-koordinaten för rektangelns centrum.
### setCenterX(float value) {#setCenterX-float-}
```
public final void setCenterX(float value)
```


Ställer in X-koordinaten för rektangelns centrum. Mäts i vanliga dokumentavståndsenheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | X-koordinaten för rektangelns centrum. |

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


Hämtar Y‑koordinaten för rektangelns centrum. Mäts i vanliga dokumentavståndsenheter.

**Returns:**
float - Y‑koordinaten för rektangelns centrum.
### setCenterY(float value) {#setCenterY-float-}
```
public final void setCenterY(float value)
```


Ställer in Y‑koordinaten för rektangelns centrum. Mäts i vanliga dokumentavståndsenheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Y‑koordinaten för rektangelns centrum. |

### getDiameterX() {#getDiameterX--}
```
public final float getDiameterX()
```


Hämtar diametern för X-dimensionen av rektangeln. Mäts i vanliga dokumentavståndsenheter.

**Returns:**
float - diametern för X-dimensionen av rektangeln.
### setDiameterX(float value) {#setDiameterX-float-}
```
public final void setDiameterX(float value)
```


Ställer in diametern för X-dimensionen av rektangeln. Mäts i vanliga dokumentavståndsenheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | diametern för X-dimensionen av rektangeln. |

### getDiameterY() {#getDiameterY--}
```
public final float getDiameterY()
```


Hämtar diametern för Y-dimensionen av rektangeln. Mäts i vanliga dokumentavståndsenheter.

**Returns:**
float - diametern för Y-dimensionen av rektangeln.
### setDiameterY(float value) {#setDiameterY-float-}
```
public final void setDiameterY(float value)
```


Ställer in diametern för Y-dimensionen av rektangeln. Mäts i vanliga dokumentavståndsenheter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | diametern för Y-dimensionen av rektangeln. |

### getBoundingBox() {#getBoundingBox--}
```
public final RectangleF getBoundingBox()
```


Hämtar den omgivande rutan.

Värde: Begränsningsrutan.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bounding box.
### setBoundingBox(RectangleF value) {#setBoundingBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundingBox(RectangleF value)
```


Ställer in den omgivande rutan.

Värde: Begränsningsrutan.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | begränsningsrutan. |

### toString() {#toString--}
```
public String toString()
```


Returnerar en String som representerar detta objekt.

**Returns:**
java.lang.String - En sträng som representerar detta objekt.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Kontrollera om objekt är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| o | java.lang.Object | Det andra objektet. |

**Returns:**
boolean - Resultatet av likhetsjämförelsen.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämta hashkoden för det aktuella objektet.

**Returns:**
int - Hashkoden.
