---
title: "Rektangel"
second_title: "Aspose.Imaging för Java API-referens"
description: "Lagrar en uppsättning av fyra heltal som representerar positionen och storleken på en rektangel."
type: docs
weight: 93
url: /sv/java/com.aspose.imaging/rectangle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Rectangle extends Struct<Rectangle>
```

Lagrar en uppsättning av fyra heltal som representerar positionen och storleken på en rektangel.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Rectangle()](#Rectangle--) |  |
| [Rectangle(int x, int y, int width, int height)](#Rectangle-int-int-int-int-) | Initierar en ny instans av `com.aspose.imaging.Rectangle`-strukturen med den angivna platsen och storleken. |
| [Rectangle(Point location, Size size)](#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Initierar en ny instans av `com.aspose.imaging.Rectangle`-strukturen med den angivna platsen och storleken. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEmpty()](#getEmpty--) | Hämtar en ny instans av `com.aspose.imaging.Rectangle`-strukturen som har `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` och `com.aspose.imaging.Rectangle.Height`-värden satta till noll. |
| [fromPoints(Point point1, Point point2)](#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Skapar en ny `Rectangle` från två angivna punkter. |
| [ceiling(RectangleF value)](#ceiling-com.aspose.imaging.RectangleF-) | Konverterar den angivna `com.aspose.imaging.RectangleF`-strukturen till en `com.aspose.imaging.Rectangle`-struktur genom att avrunda `com.aspose.imaging.RectangleF`-värdena till nästa högre heltal. |
| [truncate(RectangleF value)](#truncate-com.aspose.imaging.RectangleF-) | Konverterar den angivna `com.aspose.imaging.RectangleF` till en `com.aspose.imaging.Rectangle` genom att trunkera `com.aspose.imaging.RectangleF`-värdena. |
| [round(RectangleF value)](#round-com.aspose.imaging.RectangleF-) | Konverterar den angivna `com.aspose.imaging.RectangleF` till en `com.aspose.imaging.Rectangle` genom att avrunda `com.aspose.imaging.RectangleF`-värdena till närmaste heltalsvärden. |
| [inflate(Rectangle rect, int x, int y)](#inflate-com.aspose.imaging.Rectangle-int-int-) | Skapar och returnerar en uppblåst kopia av den angivna `com.aspose.imaging.Rectangle`-strukturen. |
| [intersect(Rectangle a, Rectangle b)](#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Returnerar en tredje `com.aspose.imaging.Rectangle`-struktur som representerar skärningspunkten mellan två andra `com.aspose.imaging.Rectangle`-strukturer. |
| [union(Rectangle a, Rectangle b)](#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Hämtar en `com.aspose.imaging.Rectangle`-struktur som innehåller föreningen av två `com.aspose.imaging.Rectangle`-strukturer. |
| [op_Equality(Rectangle left, Rectangle right)](#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Testar om två `com.aspose.imaging.Rectangle`-strukturer har samma position och storlek. |
| [op_Inequality(Rectangle left, Rectangle right)](#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) | Testar om två `com.aspose.imaging.Rectangle`-strukturer skiljer sig åt i position eller storlek. |
| [fromLeftTopRightBottom(int left, int top, int right, int bottom)](#fromLeftTopRightBottom-int-int-int-int-) | Skapar en `com.aspose.imaging.Rectangle`-struktur med de angivna kantpositionerna. |
| [isEquals(Rectangle obj1, Rectangle obj2)](#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-) |  |
| [getLocation()](#getLocation--) | Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur. |
| [setLocation(Point value)](#setLocation-com.aspose.imaging.Point-) | Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur. |
| [getSize()](#getSize--) | Hämtar eller anger storleken på denna `com.aspose.imaging.Rectangle`. |
| [setSize(Size value)](#setSize-com.aspose.imaging.Size-) | Hämtar eller anger storleken på denna `com.aspose.imaging.Rectangle`. |
| [getX()](#getX--) | Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur. |
| [setX(int value)](#setX-int-) | Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur. |
| [getY()](#getY--) | Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur. |
| [setY(int value)](#setY-int-) | Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur. |
| [getWidth()](#getWidth--) | Hämtar bredden på denna `com.aspose.imaging.Rectangle`-struktur. |
| [setWidth(int value)](#setWidth-int-) | Anger bredden på denna `com.aspose.imaging.Rectangle`-struktur. |
| [getHeight()](#getHeight--) | Hämtar eller anger höjden på denna `com.aspose.imaging.Rectangle`-struktur. |
| [setHeight(int value)](#setHeight-int-) | Hämtar eller anger höjden på denna `com.aspose.imaging.Rectangle`-struktur. |
| [getLeft()](#getLeft--) | Hämtar eller anger x-koordinaten för vänstra kanten av denna `com.aspose.imaging.Rectangle`-struktur. |
| [setLeft(int value)](#setLeft-int-) | Hämtar eller anger x-koordinaten för vänstra kanten av denna `com.aspose.imaging.Rectangle`-struktur. |
| [getTop()](#getTop--) | Hämtar eller anger y-koordinaten för överkanten av denna `com.aspose.imaging.Rectangle`-struktur. |
| [setTop(int value)](#setTop-int-) | Hämtar eller anger y-koordinaten för överkanten av denna `com.aspose.imaging.Rectangle`-struktur. |
| [getRight()](#getRight--) | Hämtar eller anger x-koordinaten som är summan av `com.aspose.imaging.Rectangle.X`- och `com.aspose.imaging.Rectangle.Width`-egenskapsvärdena för denna `com.aspose.imaging.Rectangle`-struktur. |
| [setRight(int value)](#setRight-int-) | Hämtar eller anger x-koordinaten som är summan av `com.aspose.imaging.Rectangle.X`- och `com.aspose.imaging.Rectangle.Width`-egenskapsvärdena för denna `com.aspose.imaging.Rectangle`-struktur. |
| [getBottom()](#getBottom--) | Hämtar eller anger y-koordinaten som är summan av `com.aspose.imaging.Rectangle.Y`- och `com.aspose.imaging.Rectangle.Height`-egenskapsvärdena för denna `com.aspose.imaging.Rectangle`-struktur. |
| [setBottom(int value)](#setBottom-int-) | Hämtar eller anger y-koordinaten som är summan av `com.aspose.imaging.Rectangle.Y`- och `com.aspose.imaging.Rectangle.Height`-egenskapsvärdena för denna `com.aspose.imaging.Rectangle`-struktur. |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om alla numeriska egenskaper för denna `com.aspose.imaging.Rectangle` har värdet noll. |
| [contains(int x, int y)](#contains-int-int-) | Bestämmer om den angivna punkten finns inom denna `com.aspose.imaging.Rectangle`-struktur. |
| [contains(Point point)](#contains-com.aspose.imaging.Point-) | Bestämmer om den angivna punkten finns inom denna `com.aspose.imaging.Rectangle`-struktur. |
| [contains(Rectangle rect)](#contains-com.aspose.imaging.Rectangle-) | Bestämmer om det rektangulära området som representeras av `rect` är helt innehållet i denna `com.aspose.imaging.Rectangle`-struktur. |
| [inflate(int width, int height)](#inflate-int-int-) | Utökar denna `com.aspose.imaging.Rectangle` med den angivna mängden. |
| [inflate(Size size)](#inflate-com.aspose.imaging.Size-) | Utökar denna `com.aspose.imaging.Rectangle` med den angivna mängden. |
| [intersect(Rectangle rect)](#intersect-com.aspose.imaging.Rectangle-) | Ersätter denna `com.aspose.imaging.Rectangle` med skärningspunkten mellan den själv och den angivna `com.aspose.imaging.Rectangle`. |
| [intersectsWith(Rectangle rect)](#intersectsWith-com.aspose.imaging.Rectangle-) | Bestämmer om detta rektangel skär `rect`. |
| [offset(Point pos)](#offset-com.aspose.imaging.Point-) | Justera placeringen av detta rektangel med det angivna värdet. |
| [offset(int x, int y)](#offset-int-int-) | Justera placeringen av detta rektangel med det angivna värdet. |
| [normalize()](#normalize--) | Normaliserar rektangeln genom att göra dess bredd och höjd positiva, vänster mindre än höger och topp mindre än botten. |
| [equals(Object obj)](#equals-java.lang.Object-) | Testar om `obj` är en `com.aspose.imaging.Rectangle`-struktur med samma position och storlek som denna `com.aspose.imaging.Rectangle`-struktur. |
| [hashCode()](#hashCode--) | Returnerar hashkoden för denna `com.aspose.imaging.Rectangle`-struktur. |
| [toString()](#toString--) | Konverterar attributen för denna `com.aspose.imaging.Rectangle` till en människoläsbar sträng. |
| [CloneTo(Rectangle that)](#CloneTo-com.aspose.imaging.Rectangle-) |  |
| [Clone()](#Clone--) |  |
### Rectangle() {#Rectangle--}
```
public Rectangle()
```


### Rectangle(int x, int y, int width, int height) {#Rectangle-int-int-int-int-}
```
public Rectangle(int x, int y, int width, int height)
```


Initierar en ny instans av `com.aspose.imaging.Rectangle`-strukturen med den angivna platsen och storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X‑koordinaten för rektangelns övre vänstra hörn. |
| y | int | Y‑koordinaten för rektangelns övre vänstra hörn. |
| bredd | int | Rektangelns bredd. |
| höjd | int | Rektangelns höjd. |

### Rectangle(Point location, Size size) {#Rectangle-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public Rectangle(Point location, Size size)
```


Initierar en ny instans av `com.aspose.imaging.Rectangle`-strukturen med den angivna platsen och storleken.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| location | [Point](../../com.aspose.imaging/point) | En `com.aspose.imaging.Point` som representerar det övre vänstra hörnet av det rektangulära området. |
| size | [Size](../../com.aspose.imaging/size) | En `com.aspose.imaging.Size` som representerar bredden och höjden på det rektangulära området. |

### getEmpty() {#getEmpty--}
```
public static Rectangle getEmpty()
```


Hämtar en ny instans av `com.aspose.imaging.Rectangle`-strukturen som har `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` och `com.aspose.imaging.Rectangle.Height`-värden satta till noll.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### fromPoints(Point point1, Point point2) {#fromPoints-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static Rectangle fromPoints(Point point1, Point point2)
```


Skapar en ny `Rectangle` från två angivna punkter. De två vertikalerna i den skapade `Rectangle` kommer att vara lika med de överförda `point1` och `point2`. Dessa är vanligtvis de motsatta hörnen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Den första `Point` för den nya rektangeln. |
| point2 | [Point](../../com.aspose.imaging/point) | Den andra `Point` för den nya rektangeln. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A newly created `Rectangle`.
### ceiling(RectangleF value) {#ceiling-com.aspose.imaging.RectangleF-}
```
public static Rectangle ceiling(RectangleF value)
```


Konverterar den angivna `com.aspose.imaging.RectangleF`-strukturen till en `com.aspose.imaging.Rectangle`-struktur genom att avrunda `com.aspose.imaging.RectangleF`-värdena till nästa högre heltal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF`-strukturen som ska konverteras. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - Returns a `com.aspose.imaging.Rectangle`.
### truncate(RectangleF value) {#truncate-com.aspose.imaging.RectangleF-}
```
public static Rectangle truncate(RectangleF value)
```


Konverterar den angivna `com.aspose.imaging.RectangleF` till en `com.aspose.imaging.Rectangle` genom att trunkera `com.aspose.imaging.RectangleF`-värdena.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF` som ska konverteras. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### round(RectangleF value) {#round-com.aspose.imaging.RectangleF-}
```
public static Rectangle round(RectangleF value)
```


Konverterar den angivna `com.aspose.imaging.RectangleF` till en `com.aspose.imaging.Rectangle` genom att avrunda `com.aspose.imaging.RectangleF`-värdena till närmaste heltalsvärden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF` som ska konverteras. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A new `com.aspose.imaging.Rectangle`.
### inflate(Rectangle rect, int x, int y) {#inflate-com.aspose.imaging.Rectangle-int-int-}
```
public static Rectangle inflate(Rectangle rect, int x, int y)
```


Skapar och returnerar en uppblåst kopia av den angivna `com.aspose.imaging.Rectangle`-strukturen. Kopian uppblåses med det angivna beloppet. Den ursprungliga `com.aspose.imaging.Rectangle`-strukturen förblir oförändrad.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Den `com.aspose.imaging.Rectangle` som ska startas med. Denna rektangel ändras inte. |
| x | int | Mängden att blåsa upp denna `com.aspose.imaging.Rectangle` horisontellt. |
| y | int | Mängden att blåsa upp denna `com.aspose.imaging.Rectangle` vertikalt. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The inflated `com.aspose.imaging.Rectangle`.
### intersect(Rectangle a, Rectangle b) {#intersect-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle intersect(Rectangle a, Rectangle b)
```


Returnerar en tredje `com.aspose.imaging.Rectangle`-struktur som representerar skärningspunkten mellan två andra `com.aspose.imaging.Rectangle`-strukturer. Om det inte finns någon skärning returneras en tom `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | Den första rektangeln att skära. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | Den andra rektangeln att skära. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` that represents the intersection of `a` and `b`.
### union(Rectangle a, Rectangle b) {#union-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static Rectangle union(Rectangle a, Rectangle b)
```


Hämtar en `com.aspose.imaging.Rectangle`-struktur som innehåller föreningen av två `com.aspose.imaging.Rectangle`-strukturer.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | [Rectangle](../../com.aspose.imaging/rectangle) | Den första rektangeln för förening. |
| b | [Rectangle](../../com.aspose.imaging/rectangle) | Den andra rektangeln för förening. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - A `com.aspose.imaging.Rectangle` structure that bounds the union of the two `com.aspose.imaging.Rectangle` structures.
### op_Equality(Rectangle left, Rectangle right) {#op-Equality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Equality(Rectangle left, Rectangle right)
```


Testar om två `com.aspose.imaging.Rectangle`-strukturer har samma position och storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | `com.aspose.imaging.Rectangle`-strukturen som ligger till vänster om likhetsoperatorn. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | `com.aspose.imaging.Rectangle`-strukturen som ligger till höger om likhetsoperatorn. |

**Returns:**
boolean - Denna operator returnerar true om de två `com.aspose.imaging.Rectangle`-strukturerna har lika `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` och `com.aspose.imaging.Rectangle.Height`-egenskaper.
### op_Inequality(Rectangle left, Rectangle right) {#op-Inequality-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean op_Inequality(Rectangle left, Rectangle right)
```


Testar om två `com.aspose.imaging.Rectangle`-strukturer skiljer sig åt i position eller storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| left | [Rectangle](../../com.aspose.imaging/rectangle) | `com.aspose.imaging.Rectangle`-strukturen som ligger till vänster om ojämlikhetsoperatorn. |
| right | [Rectangle](../../com.aspose.imaging/rectangle) | `com.aspose.imaging.Rectangle`-strukturen som ligger till höger om ojämlikhetsoperatorn. |

**Returns:**
boolean - Denna operator returnerar true om någon av `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` eller `com.aspose.imaging.Rectangle.Height`-egenskaperna i de två `com.aspose.imaging.Rectangle`-strukturerna är olika; annars false.
### fromLeftTopRightBottom(int left, int top, int right, int bottom) {#fromLeftTopRightBottom-int-int-int-int-}
```
public static Rectangle fromLeftTopRightBottom(int left, int top, int right, int bottom)
```


Skapar en `com.aspose.imaging.Rectangle`-struktur med de angivna kantpositionerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | int | X‑koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur. |
| övre | int | Y‑koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur. |
| höger | int | X‑koordinaten för det nedre högra hörnet av denna `com.aspose.imaging.Rectangle`-struktur. |
| nedre | int | Y‑koordinaten för det nedre högra hörnet av denna `com.aspose.imaging.Rectangle`-struktur. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The new `com.aspose.imaging.Rectangle` that this method creates.
### isEquals(Rectangle obj1, Rectangle obj2) {#isEquals-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-}
```
public static boolean isEquals(Rectangle obj1, Rectangle obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj1 | [Rectangle](../../com.aspose.imaging/rectangle) |  |
| obj2 | [Rectangle](../../com.aspose.imaging/rectangle) |  |

**Returns:**
boolean
### getLocation() {#getLocation--}
```
public Point getLocation()
```


Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur.

**Returns:**
[Point](../../com.aspose.imaging/point) - A `com.aspose.imaging.Point` that represents the upper-left corner of this `com.aspose.imaging.Rectangle` structure.
### setLocation(Point value) {#setLocation-com.aspose.imaging.Point-}
```
public void setLocation(Point value)
```


Hämtar eller anger koordinaterna för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) | En `Point` som representerar det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur. |

### getSize() {#getSize--}
```
public Size getSize()
```


Hämtar eller anger storleken på denna `com.aspose.imaging.Rectangle`.

**Returns:**
[Size](../../com.aspose.imaging/size) - A `com.aspose.imaging.Size` that represents the width and height of this `com.aspose.imaging.Rectangle` structure.
### setSize(Size value) {#setSize-com.aspose.imaging.Size-}
```
public void setSize(Size value)
```


Hämtar eller anger storleken på denna `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Size](../../com.aspose.imaging/size) | En `com.aspose.imaging.Size` som representerar bredden och höjden av denna `com.aspose.imaging.Rectangle`-struktur. |

### getX() {#getX--}
```
public int getX()
```


Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur.

**Returns:**
int - X‑koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur.
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Hämtar eller anger x-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | X‑koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur. |

### getY() {#getY--}
```
public int getY()
```


Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur.

**Returns:**
int - Y-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur.
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Hämtar eller anger y-koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Y‑koordinaten för det övre vänstra hörnet av denna `com.aspose.imaging.Rectangle`-struktur. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bredden på denna `com.aspose.imaging.Rectangle`-struktur.

**Returns:**
int - Bredden på denna `com.aspose.imaging.Rectangle`-struktur.
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Anger bredden på denna `com.aspose.imaging.Rectangle`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Bredden på denna `com.aspose.imaging.Rectangle`-struktur. |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar eller anger höjden på denna `com.aspose.imaging.Rectangle`-struktur.

**Returns:**
int - Höjden på denna `com.aspose.imaging.Rectangle`-struktur.
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Hämtar eller anger höjden på denna `com.aspose.imaging.Rectangle`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Höjden på denna `com.aspose.imaging.Rectangle`-struktur. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Hämtar eller anger x-koordinaten för vänstra kanten av denna `com.aspose.imaging.Rectangle`-struktur.

**Returns:**
int - X-koordinaten för den vänstra kanten av denna `com.aspose.imaging.Rectangle`-struktur.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Hämtar eller anger x-koordinaten för vänstra kanten av denna `com.aspose.imaging.Rectangle`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | X-koordinaten för den vänstra kanten av denna `com.aspose.imaging.Rectangle`-struktur. |

### getTop() {#getTop--}
```
public int getTop()
```


Hämtar eller anger y-koordinaten för överkanten av denna `com.aspose.imaging.Rectangle`-struktur.

**Returns:**
int - Y-koordinaten för den övre kanten av denna `com.aspose.imaging.Rectangle`-struktur.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Hämtar eller anger y-koordinaten för överkanten av denna `com.aspose.imaging.Rectangle`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Y-koordinaten för den övre kanten av denna `com.aspose.imaging.Rectangle`-struktur. |

### getRight() {#getRight--}
```
public int getRight()
```


Hämtar eller anger x-koordinaten som är summan av `com.aspose.imaging.Rectangle.X`- och `com.aspose.imaging.Rectangle.Width`-egenskapsvärdena för denna `com.aspose.imaging.Rectangle`-struktur.

**Returns:**
int - X-koordinaten som är summan av `com.aspose.imaging.Rectangle.X` och `com.aspose.imaging.Rectangle.Width` för denna `com.aspose.imaging.Rectangle`.
### setRight(int value) {#setRight-int-}
```
public void setRight(int value)
```


Hämtar eller anger x-koordinaten som är summan av `com.aspose.imaging.Rectangle.X`- och `com.aspose.imaging.Rectangle.Width`-egenskapsvärdena för denna `com.aspose.imaging.Rectangle`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | X-koordinaten som är summan av `com.aspose.imaging.Rectangle.X` och `com.aspose.imaging.Rectangle.Width` för denna `com.aspose.imaging.Rectangle`. |

### getBottom() {#getBottom--}
```
public int getBottom()
```


Hämtar eller anger y-koordinaten som är summan av `com.aspose.imaging.Rectangle.Y`- och `com.aspose.imaging.Rectangle.Height`-egenskapsvärdena för denna `com.aspose.imaging.Rectangle`-struktur.

**Returns:**
int - Y-koordinaten som är summan av `com.aspose.imaging.Rectangle.Y` och `com.aspose.imaging.Rectangle.Height` för denna `com.aspose.imaging.Rectangle`.
### setBottom(int value) {#setBottom-int-}
```
public void setBottom(int value)
```


Hämtar eller anger y-koordinaten som är summan av `com.aspose.imaging.Rectangle.Y`- och `com.aspose.imaging.Rectangle.Height`-egenskapsvärdena för denna `com.aspose.imaging.Rectangle`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Y-koordinaten som är summan av `com.aspose.imaging.Rectangle.Y` och `com.aspose.imaging.Rectangle.Height` för denna `com.aspose.imaging.Rectangle`. |

### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Hämtar ett värde som indikerar om alla numeriska egenskaper för denna `com.aspose.imaging.Rectangle` har värdet noll.

**Returns:**
boolean - Denna egenskap returnerar true om `com.aspose.imaging.Rectangle.Width`, `com.aspose.imaging.Rectangle.Height`, `com.aspose.imaging.Rectangle.X` och `com.aspose.imaging.Rectangle.Y` för denna `com.aspose.imaging.Rectangle` alla har värdet noll; annars false.
### contains(int x, int y) {#contains-int-int-}
```
public boolean contains(int x, int y)
```


Bestämmer om den angivna punkten finns inom denna `com.aspose.imaging.Rectangle`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | X-koordinaten för punkten som ska testas. |
| y | int | Y-koordinaten för punkten som ska testas. |

**Returns:**
boolean - Denna metod returnerar true om punkten definierad av `x` och `y` finns inom denna `com.aspose.imaging.Rectangle`-struktur; annars false.
### contains(Point point) {#contains-com.aspose.imaging.Point-}
```
public boolean contains(Point point)
```


Bestämmer om den angivna punkten finns inom denna `com.aspose.imaging.Rectangle`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Den `com.aspose.imaging.Point` som ska testas. |

**Returns:**
boolean - Denna metod returnerar true om punkten som representeras av `point` finns inom denna `com.aspose.imaging.Rectangle`-struktur; annars false.
### contains(Rectangle rect) {#contains-com.aspose.imaging.Rectangle-}
```
public boolean contains(Rectangle rect)
```


Bestämmer om det rektangulära området som representeras av `rect` är helt innehållet i denna `com.aspose.imaging.Rectangle`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Den `com.aspose.imaging.Rectangle` som ska testas. |

**Returns:**
boolean - Denna metod returnerar true om det rektangulära området som representeras av `rect` är helt innehållet i denna `com.aspose.imaging.Rectangle`-struktur; annars false.
### inflate(int width, int height) {#inflate-int-int-}
```
public void inflate(int width, int height)
```


Utökar denna `com.aspose.imaging.Rectangle` med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Mängden att blåsa upp denna `com.aspose.imaging.Rectangle` horisontellt. |
| höjd | int | Mängden att blåsa upp denna `com.aspose.imaging.Rectangle` vertikalt. |

### inflate(Size size) {#inflate-com.aspose.imaging.Size-}
```
public void inflate(Size size)
```


Utökar denna `com.aspose.imaging.Rectangle` med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Mängden att expandera denna rektangel. |

### intersect(Rectangle rect) {#intersect-com.aspose.imaging.Rectangle-}
```
public void intersect(Rectangle rect)
```


Ersätter denna `com.aspose.imaging.Rectangle` med skärningspunkten mellan den själv och den angivna `com.aspose.imaging.Rectangle`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Den `com.aspose.imaging.Rectangle` att intersecta med. |

### intersectsWith(Rectangle rect) {#intersectsWith-com.aspose.imaging.Rectangle-}
```
public boolean intersectsWith(Rectangle rect)
```


Bestämmer om detta rektangel skär `rect`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Rektangeln att testa. |

**Returns:**
boolean - Denna metod returnerar true om det finns någon korsning, annars false.
### offset(Point pos) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point pos)
```


Justera placeringen av detta rektangel med det angivna värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pos | [Point](../../com.aspose.imaging/point) | Mängd att förskjuta platsen. |

### offset(int x, int y) {#offset-int-int-}
```
public void offset(int x, int y)
```


Justera placeringen av detta rektangel med det angivna värdet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Den horisontella förskjutningen. |
| y | int | Den vertikala förskjutningen. |

### normalize() {#normalize--}
```
public void normalize()
```


Normaliserar rektangeln genom att göra dess bredd och höjd positiva, vänster mindre än höger och topp mindre än botten.

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Testar om `obj` är en `com.aspose.imaging.Rectangle`-struktur med samma position och storlek som denna `com.aspose.imaging.Rectangle`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det `System.Object` att testa. |

**Returns:**
boolean - Denna metod returnerar true om `obj` är en `com.aspose.imaging.Rectangle`-struktur och dess `com.aspose.imaging.Rectangle.X`, `com.aspose.imaging.Rectangle.Y`, `com.aspose.imaging.Rectangle.Width` och `com.aspose.imaging.Rectangle.Height`-egenskaper är lika med motsvarande egenskaper för denna `com.aspose.imaging.Rectangle`-struktur; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar hashkoden för denna `com.aspose.imaging.Rectangle`-struktur.

**Returns:**
int - Ett heltal som representerar hash-koden för denna rektangel.
### toString() {#toString--}
```
public String toString()
```


Konverterar attributen för denna `com.aspose.imaging.Rectangle` till en människoläsbar sträng.

**Returns:**
java.lang.String - En sträng som innehåller positionen, bredden och höjden för denna `com.aspose.imaging.Rectangle`-struktur.
### CloneTo(Rectangle that) {#CloneTo-com.aspose.imaging.Rectangle-}
```
public void CloneTo(Rectangle that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### Clone() {#Clone--}
```
public Rectangle Clone()
```




**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
