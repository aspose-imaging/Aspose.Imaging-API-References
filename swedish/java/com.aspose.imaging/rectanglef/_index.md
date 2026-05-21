---
title: "RectangleF"
second_title: "Aspose.Imaging för Java API-referens"
description: "Lagrar en uppsättning av fyra flyttal som representerar positionen och storleken på en rektangel."
type: docs
weight: 94
url: /sv/java/com.aspose.imaging/rectanglef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class RectangleF extends Struct<RectangleF>
```

Lagrar en uppsättning av fyra flyttal som representerar positionen och storleken på en rektangel.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [RectangleF()](#RectangleF--) |  |
| [RectangleF(float x, float y, float width, float height)](#RectangleF-float-float-float-float-) | Initierar en ny instans av strukturen `com.aspose.imaging.RectangleF` med den angivna positionen och storleken. |
| [RectangleF(PointF location, SizeF size)](#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Initierar en ny instans av strukturen `com.aspose.imaging.RectangleF` med den angivna positionen och storleken. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEmpty()](#getEmpty--) | Hämtar en ny instans av strukturen `com.aspose.imaging.RectangleF` där värdena `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` och `com.aspose.imaging.RectangleF.Height` är satta till noll. |
| [getLocation()](#getLocation--) | Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna `com.aspose.imaging.RectangleF`-struktur. |
| [setLocation(PointF value)](#setLocation-com.aspose.imaging.PointF-) | Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna `com.aspose.imaging.RectangleF`-struktur. |
| [getSize()](#getSize--) | Hämtar eller anger storleken på denna `com.aspose.imaging.RectangleF`. |
| [setSize(SizeF value)](#setSize-com.aspose.imaging.SizeF-) | Hämtar eller anger storleken på denna `com.aspose.imaging.RectangleF`. |
| [getX()](#getX--) | Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.RectangleF`-struktur. |
| [setX(float value)](#setX-float-) | Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.RectangleF`-struktur. |
| [getY()](#getY--) | Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.RectangleF`-struktur. |
| [setY(float value)](#setY-float-) | Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.RectangleF`-struktur. |
| [getWidth()](#getWidth--) | Hämtar eller anger bredden på denna `com.aspose.imaging.RectangleF`-struktur. |
| [setWidth(float value)](#setWidth-float-) | Hämtar eller anger bredden på denna `com.aspose.imaging.RectangleF`-struktur. |
| [getHeight()](#getHeight--) | Hämtar eller anger höjden på denna `com.aspose.imaging.RectangleF`-struktur. |
| [setHeight(float value)](#setHeight-float-) | Hämtar eller anger höjden på denna `com.aspose.imaging.RectangleF`-struktur. |
| [getLeft()](#getLeft--) | Hämtar eller anger x-koordinaten för den vänstra kanten av denna `com.aspose.imaging.RectangleF`-struktur. |
| [setLeft(float value)](#setLeft-float-) | Hämtar eller anger x-koordinaten för den vänstra kanten av denna `com.aspose.imaging.RectangleF`-struktur. |
| [getTop()](#getTop--) | Hämtar eller anger y-koordinaten för den övre kanten av denna `com.aspose.imaging.RectangleF`-struktur. |
| [setTop(float value)](#setTop-float-) | Hämtar eller anger y-koordinaten för den övre kanten av denna `com.aspose.imaging.RectangleF`-struktur. |
| [getRight()](#getRight--) | Hämtar eller anger x-koordinaten som är summan av `com.aspose.imaging.RectangleF.X` och `com.aspose.imaging.RectangleF.Width` för denna `com.aspose.imaging.RectangleF`-struktur. |
| [setRight(float value)](#setRight-float-) | Hämtar eller anger x-koordinaten som är summan av `com.aspose.imaging.RectangleF.X` och `com.aspose.imaging.RectangleF.Width` för denna `com.aspose.imaging.RectangleF`-struktur. |
| [getBottom()](#getBottom--) | Hämtar eller anger y-koordinaten som är summan av `com.aspose.imaging.RectangleF.Y` och `com.aspose.imaging.RectangleF.Height` för denna `com.aspose.imaging.RectangleF`-struktur. |
| [setBottom(float value)](#setBottom-float-) | Hämtar eller anger y-koordinaten som är summan av `com.aspose.imaging.RectangleF.Y` och `com.aspose.imaging.RectangleF.Height` för denna `com.aspose.imaging.RectangleF`-struktur. |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om egenskapen `com.aspose.imaging.RectangleF.Width` eller `com.aspose.imaging.RectangleF.Height` för denna `com.aspose.imaging.RectangleF` har värdet noll. |
| [fromPoints(PointF point1, PointF point2)](#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Skapar en ny `Rectangle` från två angivna punkter. |
| [inflate(RectangleF rect, float x, float y)](#inflate-com.aspose.imaging.RectangleF-float-float-) | Skapar och returnerar en uppblåst kopia av den angivna `com.aspose.imaging.RectangleF`-strukturen. |
| [intersect(RectangleF a, RectangleF b)](#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Returnerar en `com.aspose.imaging.RectangleF`-struktur som representerar skärningspunkten mellan två rektanglar. |
| [union(RectangleF a, RectangleF b)](#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Skapar den minsta möjliga tredje rektangeln som kan innehålla båda två rektanglar som bildar en union. |
| [op_Equality(RectangleF left, RectangleF right)](#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Testar om två `com.aspose.imaging.RectangleF`-strukturer har samma position och storlek. |
| [op_Inequality(RectangleF left, RectangleF right)](#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) | Testar om två `com.aspose.imaging.RectangleF`-strukturer skiljer sig åt i position eller storlek. |
| [op_Multiply(RectangleF rectangle, float multiplier)](#op-Multiply-com.aspose.imaging.RectangleF-float-) | Implementerar operatorn \*. |
| [op_Division(RectangleF rectangle, float divider)](#op-Division-com.aspose.imaging.RectangleF-float-) | Implementerar operatorn /. |
| [to_RectangleF(Rectangle rect)](#to-RectangleF-com.aspose.imaging.Rectangle-) | Konverterar den angivna `com.aspose.imaging.Rectangle`-strukturen till en `com.aspose.imaging.RectangleF`-struktur. |
| [fromLeftTopRightBottom(float left, float top, float right, float bottom)](#fromLeftTopRightBottom-float-float-float-float-) | Skapar en `com.aspose.imaging.RectangleF`-struktur med övre vänstra hörnet och nedre högra hörnet på de angivna positionerna. |
| [normalize()](#normalize--) | Normaliserar rektangeln genom att göra dess bredd och höjd positiva, vänster mindre än höger och topp mindre än botten. |
| [contains(float x, float y)](#contains-float-float-) | Bestämmer om den angivna punkten finns inom denna `com.aspose.imaging.RectangleF`-struktur. |
| [contains(PointF point)](#contains-com.aspose.imaging.PointF-) | Bestämmer om den angivna punkten finns inom denna `com.aspose.imaging.RectangleF`-struktur. |
| [contains(RectangleF rect)](#contains-com.aspose.imaging.RectangleF-) | Bestämmer om det rektangulära området som representeras av `rect` är helt innehållet inom denna `com.aspose.imaging.RectangleF`-struktur. |
| [inflate(float x, float y)](#inflate-float-float-) | Utökar denna `com.aspose.imaging.RectangleF`-struktur med det angivna värdet. |
| [inflate(SizeF size)](#inflate-com.aspose.imaging.SizeF-) | Utökar denna `com.aspose.imaging.RectangleF` med det angivna värdet. |
| [intersect(RectangleF rect)](#intersect-com.aspose.imaging.RectangleF-) | Ersätter denna `com.aspose.imaging.RectangleF`-struktur med skärningspunkten mellan den själv och den angivna `com.aspose.imaging.RectangleF`-strukturen. |
| [intersectsWith(RectangleF rect)](#intersectsWith-com.aspose.imaging.RectangleF-) | Bestämmer om detta rektangel skär `rect`. |
| [offset(PointF pos)](#offset-com.aspose.imaging.PointF-) | Justera placeringen av detta rektangel med det angivna värdet. |
| [offset(float x, float y)](#offset-float-float-) | Justera placeringen av detta rektangel med det angivna värdet. |
| [equals(Object obj)](#equals-java.lang.Object-) | Testar om `obj` är en `com.aspose.imaging.RectangleF` med samma placering och storlek som denna `com.aspose.imaging.RectangleF`. |
| [hashCode()](#hashCode--) | Hämtar hash‑koden för denna `com.aspose.imaging.RectangleF`-struktur. |
| [toString()](#toString--) | Konverterar attributen för denna `com.aspose.imaging.RectangleF` till en människoläsbar sträng. |
| [CloneTo(RectangleF that)](#CloneTo-com.aspose.imaging.RectangleF-) |  |
| [Clone()](#Clone--) |  |
| [isEquals(RectangleF obj1, RectangleF obj2)](#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-) |  |
### RectangleF() {#RectangleF--}
```
public RectangleF()
```


### RectangleF(float x, float y, float width, float height) {#RectangleF-float-float-float-float-}
```
public RectangleF(float x, float y, float width, float height)
```


Initierar en ny instans av strukturen `com.aspose.imaging.RectangleF` med den angivna positionen och storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X‑koordinaten för rektangelns övre vänstra hörn. |
| y | float | Y‑koordinaten för rektangelns övre vänstra hörn. |
| bredd | float | Rektangelns bredd. |
| höjd | float | Rektangelns höjd. |

### RectangleF(PointF location, SizeF size) {#RectangleF-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public RectangleF(PointF location, SizeF size)
```


Initierar en ny instans av strukturen `com.aspose.imaging.RectangleF` med den angivna positionen och storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location | [PointF](../../com.aspose.imaging/pointf) | Ett `com.aspose.imaging.PointF` som representerar den övre vänstra hörnet av det rektangulära området. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Ett `com.aspose.imaging.SizeF` som representerar bredden och höjden av det rektangulära området. |

### getEmpty() {#getEmpty--}
```
public static RectangleF getEmpty()
```


Hämtar en ny instans av strukturen `com.aspose.imaging.RectangleF` där värdena `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` och `com.aspose.imaging.RectangleF.Height` är satta till noll.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getLocation() {#getLocation--}
```
public PointF getLocation()
```


Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna `com.aspose.imaging.RectangleF`-struktur.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - A `com.aspose.imaging.PointF` that represents the upper-left corner of this `com.aspose.imaging.RectangleF` structure.
### setLocation(PointF value) {#setLocation-com.aspose.imaging.PointF-}
```
public void setLocation(PointF value)
```


Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna `com.aspose.imaging.RectangleF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSize() {#getSize--}
```
public SizeF getSize()
```


Hämtar eller anger storleken på denna `com.aspose.imaging.RectangleF`.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `com.aspose.imaging.SizeF` that represents the width and height of this `com.aspose.imaging.RectangleF` structure.
### setSize(SizeF value) {#setSize-com.aspose.imaging.SizeF-}
```
public void setSize(SizeF value)
```


Hämtar eller anger storleken på denna `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) |  |

### getX() {#getX--}
```
public float getX()
```


Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.RectangleF`-struktur.

**Returns:**
float – X‑koordinaten för den övre vänstra hörnet av denna `com.aspose.imaging.RectangleF`-struktur.
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.RectangleF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getY() {#getY--}
```
public float getY()
```


Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.RectangleF`-struktur.

**Returns:**
float – Y‑koordinaten för den övre vänstra hörnet av denna `com.aspose.imaging.RectangleF`-struktur.
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.RectangleF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Hämtar eller anger bredden på denna `com.aspose.imaging.RectangleF`-struktur.

**Returns:**
float – Bredden på denna `com.aspose.imaging.RectangleF`-struktur.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Hämtar eller anger bredden på denna `com.aspose.imaging.RectangleF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Hämtar eller anger höjden på denna `com.aspose.imaging.RectangleF`-struktur.

**Returns:**
float – Höjden på denna `com.aspose.imaging.RectangleF`-struktur.
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Hämtar eller anger höjden på denna `com.aspose.imaging.RectangleF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getLeft() {#getLeft--}
```
public float getLeft()
```


Hämtar eller anger x-koordinaten för den vänstra kanten av denna `com.aspose.imaging.RectangleF`-struktur.

**Returns:**
float – X‑koordinaten för vänsterkanten av denna `com.aspose.imaging.RectangleF`-struktur.
### setLeft(float value) {#setLeft-float-}
```
public void setLeft(float value)
```


Hämtar eller anger x-koordinaten för den vänstra kanten av denna `com.aspose.imaging.RectangleF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getTop() {#getTop--}
```
public float getTop()
```


Hämtar eller anger y-koordinaten för den övre kanten av denna `com.aspose.imaging.RectangleF`-struktur.

**Returns:**
float – Y‑koordinaten för överkanten av denna `com.aspose.imaging.RectangleF`-struktur.
### setTop(float value) {#setTop-float-}
```
public void setTop(float value)
```


Hämtar eller anger y-koordinaten för den övre kanten av denna `com.aspose.imaging.RectangleF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getRight() {#getRight--}
```
public float getRight()
```


Hämtar eller anger x-koordinaten som är summan av `com.aspose.imaging.RectangleF.X` och `com.aspose.imaging.RectangleF.Width` för denna `com.aspose.imaging.RectangleF`-struktur.

**Returns:**
float - X-koordinaten som är summan av `com.aspose.imaging.RectangleF.X` och `com.aspose.imaging.RectangleF.Width` för denna `com.aspose.imaging.RectangleF`-struktur.
### setRight(float value) {#setRight-float-}
```
public void setRight(float value)
```


Hämtar eller anger x-koordinaten som är summan av `com.aspose.imaging.RectangleF.X` och `com.aspose.imaging.RectangleF.Width` för denna `com.aspose.imaging.RectangleF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getBottom() {#getBottom--}
```
public float getBottom()
```


Hämtar eller anger y-koordinaten som är summan av `com.aspose.imaging.RectangleF.Y` och `com.aspose.imaging.RectangleF.Height` för denna `com.aspose.imaging.RectangleF`-struktur.

**Returns:**
float - Y-koordinaten som är summan av `com.aspose.imaging.RectangleF.Y` och `com.aspose.imaging.RectangleF.Height` för denna `com.aspose.imaging.RectangleF`-struktur.
### setBottom(float value) {#setBottom-float-}
```
public void setBottom(float value)
```


Hämtar eller anger y-koordinaten som är summan av `com.aspose.imaging.RectangleF.Y` och `com.aspose.imaging.RectangleF.Height` för denna `com.aspose.imaging.RectangleF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Hämtar ett värde som indikerar om egenskapen `com.aspose.imaging.RectangleF.Width` eller `com.aspose.imaging.RectangleF.Height` för denna `com.aspose.imaging.RectangleF` har värdet noll.

**Returns:**
boolean - Denna egenskap returnerar true om `com.aspose.imaging.RectangleF.Width` eller `com.aspose.imaging.RectangleF.Height` för detta `com.aspose.imaging.RectangleF` har värdet noll; annars false.
### fromPoints(PointF point1, PointF point2) {#fromPoints-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static RectangleF fromPoints(PointF point1, PointF point2)
```


Skapar en ny `Rectangle` från två angivna punkter. Två hörn av den skapade `Rectangle` kommer att vara lika med de överförda `point1` och `point2`. Dessa är vanligtvis de motsatta hörnen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | Den första `Point` för den nya rektangeln. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | Den andra `Point` för den nya rektangeln. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A newly created `Rectangle`.
### inflate(RectangleF rect, float x, float y) {#inflate-com.aspose.imaging.RectangleF-float-float-}
```
public static RectangleF inflate(RectangleF rect, float x, float y)
```


Skapar och returnerar en uppblåst kopia av den angivna `com.aspose.imaging.RectangleF`-strukturen. Kopian uppblås med den angivna mängden. Den ursprungliga rektangeln förblir oförändrad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF` som ska kopieras. Denna rektangel ändras inte. |
| x | float | Mängden för att uppblåsa kopian av rektangeln horisontellt. |
| y | float | Mängden för att uppblåsa kopian av rektangeln vertikalt. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The inflated `com.aspose.imaging.RectangleF`.
### intersect(RectangleF a, RectangleF b) {#intersect-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF intersect(RectangleF a, RectangleF b)
```


Returnerar en `com.aspose.imaging.RectangleF`-struktur som representerar skärningspunkten mellan två rektanglar. Om det inte finns någon skärning returneras en tom `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | Den första rektangeln att skära. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | Den andra rektangeln att skära. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure the size of which represents the overlapped area of the two specified rectangles.
### union(RectangleF a, RectangleF b) {#union-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static RectangleF union(RectangleF a, RectangleF b)
```


Skapar den minsta möjliga tredje rektangeln som kan innehålla båda två rektanglar som bildar en union.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [RectangleF](../../com.aspose.imaging/rectanglef) | Den första rektangeln för förening. |
| b | [RectangleF](../../com.aspose.imaging/rectanglef) | Den andra rektangeln för förening. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - A third `com.aspose.imaging.RectangleF` structure that contains both of the two rectangles that form the union.
### op_Equality(RectangleF left, RectangleF right) {#op-Equality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Equality(RectangleF left, RectangleF right)
```


Testar om två `com.aspose.imaging.RectangleF`-strukturer har samma position och storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF`-strukturen som är till vänster om likhetsoperatorn. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF`-strukturen som är till höger om likhetsoperatorn. |

**Returns:**
boolean - Denna operator returnerar true om de två angivna `com.aspose.imaging.RectangleF`-strukturerna har lika `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` och `com.aspose.imaging.RectangleF.Height`-egenskaper.
### op_Inequality(RectangleF left, RectangleF right) {#op-Inequality-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean op_Inequality(RectangleF left, RectangleF right)
```


Testar om två `com.aspose.imaging.RectangleF`-strukturer skiljer sig åt i position eller storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF`-strukturen som är till vänster om olikhetsoperatorn. |
| right | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF`-strukturen som är till höger om olikhetsoperatorn. |

**Returns:**
boolean - Denna operator returnerar true om någon av `com.aspose.imaging.RectangleF.X`, `com.aspose.imaging.RectangleF.Y`, `com.aspose.imaging.RectangleF.Width` eller `com.aspose.imaging.RectangleF.Height`-egenskaperna för de två `com.aspose.imaging.RectangleF`-strukturerna är olika; annars false.
### op_Multiply(RectangleF rectangle, float multiplier) {#op-Multiply-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Multiply(RectangleF rectangle, float multiplier)
```


Implementerar operatorn \*.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Rektangeln. |
| multiplikator | float | Multiplikatorn. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### op_Division(RectangleF rectangle, float divider) {#op-Division-com.aspose.imaging.RectangleF-float-}
```
public static RectangleF op_Division(RectangleF rectangle, float divider)
```


Implementerar operatorn /.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Rektangeln. |
| delare | float | Delaren. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The result of the operator.
### to_RectangleF(Rectangle rect) {#to-RectangleF-com.aspose.imaging.Rectangle-}
```
public static RectangleF to_RectangleF(Rectangle rect)
```


Konverterar den angivna `com.aspose.imaging.Rectangle`-strukturen till en `com.aspose.imaging.RectangleF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Den `com.aspose.imaging.Rectangle`-strukturen att konvertera. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The `com.aspose.imaging.RectangleF` structure that is converted from the specified `com.aspose.imaging.Rectangle` structure.
### fromLeftTopRightBottom(float left, float top, float right, float bottom) {#fromLeftTopRightBottom-float-float-float-float-}
```
public static RectangleF fromLeftTopRightBottom(float left, float top, float right, float bottom)
```


Skapar en `com.aspose.imaging.RectangleF`-struktur med övre vänstra hörnet och nedre högra hörnet på de angivna positionerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | float | X-koordinaten för det övre vänstra hörnet av det rektangulära området. |
| övre | float | Y-koordinaten för det övre vänstra hörnet av det rektangulära området. |
| höger | float | X-koordinaten för det nedre högra hörnet av det rektangulära området. |
| nedre | float | Y-koordinaten för det nedre högra hörnet av det rektangulära området. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The new `com.aspose.imaging.RectangleF` that this method creates.
### normalize() {#normalize--}
```
public void normalize()
```


Normaliserar rektangeln genom att göra dess bredd och höjd positiva, vänster mindre än höger och topp mindre än botten.

### contains(float x, float y) {#contains-float-float-}
```
public boolean contains(float x, float y)
```


Bestämmer om den angivna punkten finns inom denna `com.aspose.imaging.RectangleF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | X-koordinaten för punkten som ska testas. |
| y | float | Y-koordinaten för punkten som ska testas. |

**Returns:**
boolean - Denna metod returnerar true om punkten definierad av `x` och `y` finns inom denna `com.aspose.imaging.RectangleF`-struktur; annars false.
### contains(PointF point) {#contains-com.aspose.imaging.PointF-}
```
public boolean contains(PointF point)
```


Bestämmer om den angivna punkten finns inom denna `com.aspose.imaging.RectangleF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Den `com.aspose.imaging.PointF` att testa. |

**Returns:**
boolean - Denna metod returnerar true om punkten som representeras av parametern `point` finns inom denna `com.aspose.imaging.RectangleF`-struktur; annars false.
### contains(RectangleF rect) {#contains-com.aspose.imaging.RectangleF-}
```
public boolean contains(RectangleF rect)
```


Bestämmer om det rektangulära området som representeras av `rect` är helt innehållet inom denna `com.aspose.imaging.RectangleF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Den `com.aspose.imaging.RectangleF` att testa. |

**Returns:**
boolean - Denna metod returnerar true om det rektangulära området som representeras av `rect` är helt innehållet inom det rektangulära området som representeras av denna `com.aspose.imaging.RectangleF`; annars false.
### inflate(float x, float y) {#inflate-float-float-}
```
public void inflate(float x, float y)
```


Utökar denna `com.aspose.imaging.RectangleF`-struktur med det angivna värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | Mängden att expandera denna `com.aspose.imaging.RectangleF`-struktur horisontellt. |
| y | float | Mängden att expandera denna `com.aspose.imaging.RectangleF`-struktur vertikalt. |

### inflate(SizeF size) {#inflate-com.aspose.imaging.SizeF-}
```
public void inflate(SizeF size)
```


Utökar denna `com.aspose.imaging.RectangleF` med det angivna värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Mängden att expandera denna rektangel. |

### intersect(RectangleF rect) {#intersect-com.aspose.imaging.RectangleF-}
```
public void intersect(RectangleF rect)
```


Ersätter denna `com.aspose.imaging.RectangleF`-struktur med skärningspunkten mellan den själv och den angivna `com.aspose.imaging.RectangleF`-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Rektangeln att skära av. |

### intersectsWith(RectangleF rect) {#intersectsWith-com.aspose.imaging.RectangleF-}
```
public boolean intersectsWith(RectangleF rect)
```


Bestämmer om detta rektangel skär `rect`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Rektangeln att testa. |

**Returns:**
boolean - Denna metod returnerar true om det finns någon skärning.
### offset(PointF pos) {#offset-com.aspose.imaging.PointF-}
```
public void offset(PointF pos)
```


Justera placeringen av detta rektangel med det angivna värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pos | [PointF](../../com.aspose.imaging/pointf) | Mängden att förskjuta platsen. |

### offset(float x, float y) {#offset-float-float-}
```
public void offset(float x, float y)
```


Justera placeringen av detta rektangel med det angivna värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | Mängden att förskjuta platsen horisontellt. |
| y | float | Mängden att förskjuta platsen vertikalt. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Testar om `obj` är en `com.aspose.imaging.RectangleF` med samma placering och storlek som denna `com.aspose.imaging.RectangleF`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det `System.Object` att testa. |

**Returns:**
boolean - Denna metod returnerar true om `obj` är en `com.aspose.imaging.RectangleF` och dess X-, Y-, Width- och Height-egenskaper är lika med motsvarande egenskaper för detta `com.aspose.imaging.RectangleF`; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Hämtar hash‑koden för denna `com.aspose.imaging.RectangleF`-struktur.

**Returns:**
int - Hashkoden för detta `com.aspose.imaging.RectangleF`.
### toString() {#toString--}
```
public String toString()
```


Konverterar attributen för denna `com.aspose.imaging.RectangleF` till en människoläsbar sträng.

**Returns:**
java.lang.String - En sträng som innehåller positionen, bredden och höjden för denna `com.aspose.imaging.RectangleF`-struktur.
### CloneTo(RectangleF that) {#CloneTo-com.aspose.imaging.RectangleF-}
```
public void CloneTo(RectangleF that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

### Clone() {#Clone--}
```
public RectangleF Clone()
```




**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### isEquals(RectangleF obj1, RectangleF obj2) {#isEquals-com.aspose.imaging.RectangleF-com.aspose.imaging.RectangleF-}
```
public static boolean isEquals(RectangleF obj1, RectangleF obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj1 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |
| obj2 | [RectangleF](../../com.aspose.imaging/rectanglef) |  |

**Returns:**
boolean
