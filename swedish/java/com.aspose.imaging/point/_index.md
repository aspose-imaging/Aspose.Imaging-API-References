---
title: "Point"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar ett ordnat par av heltals x- och y-koordinater som definierar en punkt i ett tvådimensionellt plan."
type: docs
weight: 86
url: /sv/java/com.aspose.imaging/point/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Point extends Struct<Point>
```

Representerar ett ordnat par av heltals x- och y-koordinater som definierar en punkt i ett tvådimensionellt plan.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Point()](#Point--) |  |
| [Point(int x, int y)](#Point-int-int-) | Initierar en ny instans av strukturen `Aspose.Imaging.Point` med de angivna koordinaterna. |
| [Point(Size size)](#Point-com.aspose.imaging.Size-) | Initierar en ny instans av strukturen `Aspose.Imaging.Point` från strukturen `Aspose.Imaging.Size`. |
| [Point(int dw)](#Point-int-) | Initierar en ny instans av strukturen `Aspose.Imaging.Point` med koordinater angivna av ett heltalsvärde. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEmpty()](#getEmpty--) | Hämtar en ny instans av strukturen `Aspose.Imaging.Point` som har värdena `Aspose.Imaging.Point.X` och `Aspose.Imaging.Point.Y` satta till noll. |
| [add(Point point, Size size)](#add-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Lägger till den angivna `Aspose.Imaging.Size` till den angivna `Aspose.Imaging.Point`. |
| [subtract(Point point, Size size)](#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Returnerar resultatet av att subtrahera den angivna `Aspose.Imaging.Size` från den angivna `Aspose.Imaging.Point`. |
| [ceiling(PointF point)](#ceiling-com.aspose.imaging.PointF-) | Konverterar den angivna `Aspose.Imaging.PointF` till en `Aspose.Imaging.Point` genom att avrunda värdena i `Aspose.Imaging.PointF` till nästa högre heltalsvärde. |
| [round(PointF point)](#round-com.aspose.imaging.PointF-) | Konverterar den angivna `Aspose.Imaging.PointF` till ett `Aspose.Imaging.Point`-objekt genom att avrunda `Aspose.Imaging.Point`-värdena till närmaste heltal. |
| [truncate(PointF point)](#truncate-com.aspose.imaging.PointF-) | Konverterar den angivna `Aspose.Imaging.PointF` till en `Aspose.Imaging.Point` genom att trunkera värdena i `Aspose.Imaging.Point`. |
| [op_Addition(Point point, Size size)](#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Förflyttar en `Aspose.Imaging.Point` med en given `Aspose.Imaging.Size`. |
| [op_Subtraction(Point point, Size size)](#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Förflyttar en `Aspose.Imaging.Point` med den negativa av en given `Aspose.Imaging.Size`. |
| [op_Equality(Point point1, Point point2)](#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Jämför två `Aspose.Imaging.Point`-objekt. |
| [op_Inequality(Point point1, Point point2)](#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Jämför två `Aspose.Imaging.Point`-objekt. |
| [to_Size(Point point)](#to-Size-com.aspose.imaging.Point-) | Konverterar den angivna `Aspose.Imaging.Point`-strukturen till en `Aspose.Imaging.Size`-struktur. |
| [to_PointF(Point point)](#to-PointF-com.aspose.imaging.Point-) | Konverterar den angivna `Point`-strukturen till `PointF`-strukturen. |
| [fromLong(long packedPoint, int[] x, int[] y)](#fromLong-long-int---int---) | Dekonstruerar ett Point-objekt packat i ett long-objekt till separata X- och Y-int-värden. |
| [isEquals(Point obj1, Point obj2)](#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-) |  |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om detta `Aspose.Imaging.Point` är tomt. |
| [getX()](#getX--) | Hämtar eller anger x-koordinaten för detta `Aspose.Imaging.Point`. |
| [setX(int value)](#setX-int-) | Hämtar eller anger x-koordinaten för detta `Aspose.Imaging.Point`. |
| [getY()](#getY--) | Hämtar eller anger y-koordinaten för detta `Aspose.Imaging.Point`. |
| [setY(int value)](#setY-int-) | Hämtar eller anger y-koordinaten för detta `Aspose.Imaging.Point`. |
| [offset(Point point)](#offset-com.aspose.imaging.Point-) | Förflyttar detta `Aspose.Imaging.Point` med den angivna `Aspose.Imaging.Point`. |
| [offset(int dx, int dy)](#offset-int-int-) | Förflyttar detta `Aspose.Imaging.Point` med den angivna mängden. |
| [equals(Object obj)](#equals-java.lang.Object-) | Anger om detta `Aspose.Imaging.Point` innehåller samma koordinater som det angivna `System.Object`. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta `Aspose.Imaging.Point`. |
| [toLong()](#toLong--) | Konvertera detta Point till ett enda long‑värde som innehåller X- och Y-koordinater i hög- respektive lågbit. |
| [toString()](#toString--) | Konverterar detta `Aspose.Imaging.Point` till en människoläsbar sträng. |
| [CloneTo(Point that)](#CloneTo-com.aspose.imaging.Point-) |  |
| [Clone()](#Clone--) |  |
### Point() {#Point--}
```
public Point()
```


### Point(int x, int y) {#Point-int-int-}
```
public Point(int x, int y)
```


Initierar en ny instans av strukturen `Aspose.Imaging.Point` med de angivna koordinaterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | int | Den horisontella positionen för punkten. |
| y | int | Den vertikala positionen för punkten. |

### Point(Size size) {#Point-com.aspose.imaging.Size-}
```
public Point(Size size)
```


Initierar en ny instans av strukturen `Aspose.Imaging.Point` från strukturen `Aspose.Imaging.Size`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | Innehåller de nya punktkoordinaterna. |

### Point(int dw) {#Point-int-}
```
public Point(int dw)
```


Initierar en ny instans av strukturen `Aspose.Imaging.Point` med koordinater angivna av ett heltalsvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dw | int | Ett 32‑bitars heltal som specificerar koordinaterna för den nya punkten. |

### getEmpty() {#getEmpty--}
```
public static Point getEmpty()
```


Hämtar en ny instans av strukturen `Aspose.Imaging.Point` som har värdena `Aspose.Imaging.Point.X` och `Aspose.Imaging.Point.Y` satta till noll.

**Returns:**
[Point](../../com.aspose.imaging/point)
### add(Point point, Size size) {#add-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point add(Point point, Size size)
```


Lägger till den angivna `Aspose.Imaging.Size` till den angivna `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Den `Aspose.Imaging.Point` som ska läggas till. |
| size | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size` att lägga till `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the addition operation.
### subtract(Point point, Size size) {#subtract-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point subtract(Point point, Size size)
```


Returnerar resultatet av att subtrahera den angivna `Aspose.Imaging.Size` från den angivna `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Den `Aspose.Imaging.Point` som ska subtraheras från. |
| size | [Size](../../com.aspose.imaging/size) | Den `Aspose.Imaging.Size` som ska subtraheras från `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` that is the result of the subtraction operation.
### ceiling(PointF point) {#ceiling-com.aspose.imaging.PointF-}
```
public static Point ceiling(PointF point)
```


Konverterar den angivna `Aspose.Imaging.PointF` till en `Aspose.Imaging.Point` genom att avrunda värdena i `Aspose.Imaging.PointF` till nästa högre heltalsvärde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Den `Aspose.Imaging.PointF` som ska konverteras. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### round(PointF point) {#round-com.aspose.imaging.PointF-}
```
public static Point round(PointF point)
```


Konverterar den angivna `Aspose.Imaging.PointF` till ett `Aspose.Imaging.Point`-objekt genom att avrunda `Aspose.Imaging.Point`-värdena till närmaste heltal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Den `Aspose.Imaging.PointF` som ska konverteras. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### truncate(PointF point) {#truncate-com.aspose.imaging.PointF-}
```
public static Point truncate(PointF point)
```


Konverterar den angivna `Aspose.Imaging.PointF` till en `Aspose.Imaging.Point` genom att trunkera värdena i `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Den `Aspose.Imaging.PointF` som ska konverteras. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` this method converts to.
### op_Addition(Point point, Size size) {#op-Addition-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Addition(Point point, Size size)
```


Förflyttar en `Aspose.Imaging.Point` med en given `Aspose.Imaging.Size`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Den `Aspose.Imaging.Point` som ska översättas. |
| size | [Size](../../com.aspose.imaging/size) | En `Aspose.Imaging.Size` som specificerar paret av tal att lägga till koordinaterna för `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The translated `Aspose.Imaging.Point`.
### op_Subtraction(Point point, Size size) {#op-Subtraction-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public static Point op_Subtraction(Point point, Size size)
```


Förflyttar en `Aspose.Imaging.Point` med den negativa av en given `Aspose.Imaging.Size`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Den `Aspose.Imaging.Point` som ska översättas. |
| size | [Size](../../com.aspose.imaging/size) | En `Aspose.Imaging.Size` som specificerar paret av tal att subtrahera från koordinaterna för `point`. |

**Returns:**
[Point](../../com.aspose.imaging/point) - A `Aspose.Imaging.Point` structure that is translated by the negative of a given `Aspose.Imaging.Size` structure.
### op_Equality(Point point1, Point point2) {#op-Equality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Equality(Point point1, Point point2)
```


Jämför två `Aspose.Imaging.Point`-objekt. Resultatet anger om värdena för egenskaperna `Aspose.Imaging.Point.X` och `Aspose.Imaging.Point.Y` i de två `Aspose.Imaging.Point`-objekten är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Ett första `Aspose.Imaging.Point` att jämföra. |
| point2 | [Point](../../com.aspose.imaging/point) | Ett andra `Aspose.Imaging.Point` att jämföra. |

**Returns:**
boolean - Sant om värdena `Aspose.Imaging.Point.X` och `Aspose.Imaging.Point.Y` för `point1` och `point2` är lika; annars falskt.
### op_Inequality(Point point1, Point point2) {#op-Inequality-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean op_Inequality(Point point1, Point point2)
```


Jämför två `Aspose.Imaging.Point`-objekt. Resultatet anger om värdena för egenskaperna `Aspose.Imaging.Point.X` eller `Aspose.Imaging.Point.Y` i de två `Aspose.Imaging.Point`-objekten är olika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [Point](../../com.aspose.imaging/point) | Ett första `Aspose.Imaging.Point` att jämföra. |
| point2 | [Point](../../com.aspose.imaging/point) | Ett andra `Aspose.Imaging.Point` att jämföra. |

**Returns:**
boolean - Sant om värdena för antingen `Aspose.Imaging.Point.X`-egenskaperna eller `Aspose.Imaging.Point.Y`-egenskaperna för `point1` och `point2` skiljer sig; annars falskt.
### to_Size(Point point) {#to-Size-com.aspose.imaging.Point-}
```
public static Size to_Size(Point point)
```


Konverterar den angivna `Aspose.Imaging.Point`-strukturen till en `Aspose.Imaging.Size`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Den `Aspose.Imaging.Point` som ska konverteras. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that results from the conversion.
### to_PointF(Point point) {#to-PointF-com.aspose.imaging.Point-}
```
public static PointF to_PointF(Point point)
```


Konverterar den angivna `Point`-strukturen till `PointF`-strukturen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Den `Point` som ska konverteras. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The `PointF` that results from the conversion.
### fromLong(long packedPoint, int[] x, int[] y) {#fromLong-long-int---int---}
```
public static void fromLong(long packedPoint, int[] x, int[] y)
```


Dekonstruerar ett Point-objekt packat i ett long-objekt till separata X- och Y-int-värden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| packedPoint | long | Point-objektet packat i ett långt värde. |
| x | int[] | Det extraherade X‑värdet från det packade Point. |
| y | int[] | Det extraherade Y‑värdet från det packade Point. |

### isEquals(Point obj1, Point obj2) {#isEquals-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public static boolean isEquals(Point obj1, Point obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj1 | [Point](../../com.aspose.imaging/point) |  |
| obj2 | [Point](../../com.aspose.imaging/point) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Hämtar ett värde som indikerar om detta `Aspose.Imaging.Point` är tomt.

**Returns:**
boolean - Sant om både `Aspose.Imaging.Point.X` och `Aspose.Imaging.Point.Y` är 0; annars falskt.
### getX() {#getX--}
```
public int getX()
```


Hämtar eller anger x-koordinaten för detta `Aspose.Imaging.Point`.

**Returns:**
int
### setX(int value) {#setX-int-}
```
public void setX(int value)
```


Hämtar eller anger x-koordinaten för detta `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getY() {#getY--}
```
public int getY()
```


Hämtar eller anger y-koordinaten för detta `Aspose.Imaging.Point`.

**Returns:**
int
### setY(int value) {#setY-int-}
```
public void setY(int value)
```


Hämtar eller anger y-koordinaten för detta `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### offset(Point point) {#offset-com.aspose.imaging.Point-}
```
public void offset(Point point)
```


Förflyttar detta `Aspose.Imaging.Point` med den angivna `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Den `Aspose.Imaging.Point` som används för att förskjuta detta `Aspose.Imaging.Point`. |

### offset(int dx, int dy) {#offset-int-int-}
```
public void offset(int dx, int dy)
```


Förflyttar detta `Aspose.Imaging.Point` med den angivna mängden.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| dx | int | Mängden för att förskjuta x‑koordinaten. |
| dy | int | Mängden för att förskjuta y‑koordinaten. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Anger om detta `Aspose.Imaging.Point` innehåller samma koordinater som det angivna `System.Object`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det `System.Object` att testa. |

**Returns:**
boolean - Sant om `obj` är en `Aspose.Imaging.Point` och har samma koordinater som detta `Aspose.Imaging.Point`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta `Aspose.Imaging.Point`.

**Returns:**
int - En hashkod för denna instans, lämplig för användning i hash-algoritmer och datastrukturer som en hash‑tabell.
### toLong() {#toLong--}
```
public final long toLong()
```


Konvertera detta Point till ett enda long‑värde som innehåller X- och Y-koordinater i hög- respektive lågbit.

**Returns:**
long - Point-objektet packat i ett långt värde.
### toString() {#toString--}
```
public String toString()
```


Konverterar detta `Aspose.Imaging.Point` till en människoläsbar sträng.

**Returns:**
java.lang.String - En `System.String` som representerar denna instans.
### CloneTo(Point that) {#CloneTo-com.aspose.imaging.Point-}
```
public void CloneTo(Point that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [Point](../../com.aspose.imaging/point) |  |

### Clone() {#Clone--}
```
public Point Clone()
```




**Returns:**
[Point](../../com.aspose.imaging/point)
