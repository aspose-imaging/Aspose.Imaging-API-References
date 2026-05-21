---
title: "Storlek"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar storlek."
type: docs
weight: 104
url: /sv/java/com.aspose.imaging/size/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class Size extends Struct<Size>
```

Representerar storlek.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Size()](#Size--) |  |
| [Size(Point point)](#Size-com.aspose.imaging.Point-) | Initierar en ny instans av strukturen `Aspose.Imaging.Size` från den angivna `Aspose.Imaging.Point`. |
| [Size(int width, int height)](#Size-int-int-) | Initierar en ny instans av strukturen `Aspose.Imaging.Size` från de angivna dimensionerna. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEmpty()](#getEmpty--) | Hämtar en ny instans av strukturen `Aspose.Imaging.Size` som har värdena `Aspose.Imaging.Size.Width` och `Aspose.Imaging.Size.Height` satta till noll. |
| [to_SizeF(Size size)](#to-SizeF-com.aspose.imaging.Size-) | Konverterar den angivna `Aspose.Imaging.Size` till en `Aspose.Imaging.SizeF`. |
| [op_Addition(Size size1, Size size2)](#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Lägger till bredden och höjden för en `Aspose.Imaging.Size`-struktur till bredden och höjden för en annan `Aspose.Imaging.Size`-struktur. |
| [op_Subtraction(Size size1, Size size2)](#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Subtraherar bredden och höjden för en `Aspose.Imaging.Size`-struktur från bredden och höjden för en annan `Aspose.Imaging.Size`-struktur. |
| [op_Equality(Size size1, Size size2)](#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Testar om två `Aspose.Imaging.Size`-strukturer är lika. |
| [op_Inequality(Size size1, Size size2)](#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Testar om två `Aspose.Imaging.Size`-strukturer är olika. |
| [to_Point(Size size)](#to-Point-com.aspose.imaging.Size-) | Konverterar den angivna `Aspose.Imaging.Size` till en `Aspose.Imaging.Point`. |
| [add(Size size1, Size size2)](#add-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Lägger till bredden och höjden för en `Aspose.Imaging.Size`-struktur till bredden och höjden för en annan `Aspose.Imaging.Size`-struktur. |
| [ceiling(SizeF size)](#ceiling-com.aspose.imaging.SizeF-) | Konverterar den angivna `Aspose.Imaging.SizeF`-strukturen till en `Aspose.Imaging.Size`-struktur genom att avrunda värdena i `Aspose.Imaging.Size`-strukturen till nästa högre heltal. |
| [subtract(Size size1, Size size2)](#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Subtraherar bredden och höjden för en `Aspose.Imaging.Size`-struktur från bredden och höjden för en annan `Aspose.Imaging.Size`-struktur. |
| [truncate(SizeF size)](#truncate-com.aspose.imaging.SizeF-) | Konverterar den angivna `Aspose.Imaging.SizeF`-strukturen till en `Aspose.Imaging.Size`-struktur genom att trunkera värdena i `Aspose.Imaging.SizeF`-strukturen till nästa lägre heltal. |
| [round(SizeF size)](#round-com.aspose.imaging.SizeF-) | Konverterar den angivna `Aspose.Imaging.SizeF`-strukturen till en `Aspose.Imaging.Size`-struktur genom att avrunda värdena i `Aspose.Imaging.SizeF`-strukturen till närmaste heltal. |
| [isEquals(Size obj1, Size obj2)](#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-) |  |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om denna `Aspose.Imaging.Size` har bredd och höjd på 0. |
| [getWidth()](#getWidth--) | Hämtar eller anger den horisontella komponenten för denna `Aspose.Imaging.Size`. |
| [setWidth(int value)](#setWidth-int-) | Hämtar eller anger den horisontella komponenten för denna `Aspose.Imaging.Size`. |
| [getHeight()](#getHeight--) | Hämtar eller anger den vertikala komponenten för detta `Aspose.Imaging.Size`. |
| [setHeight(int value)](#setHeight-int-) | Hämtar eller anger den vertikala komponenten för detta `Aspose.Imaging.Size`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Testar om det angivna objektet är en `Aspose.Imaging.Size` med samma dimensioner som denna `Aspose.Imaging.Size`. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för denna `Aspose.Imaging.Size`-struktur. |
| [toString()](#toString--) | Skapar en människoläsbar sträng som representerar denna `Aspose.Imaging.Size`. |
| [CloneTo(Size that)](#CloneTo-com.aspose.imaging.Size-) |  |
| [Clone()](#Clone--) |  |
### Size() {#Size--}
```
public Size()
```


### Size(Point point) {#Size-com.aspose.imaging.Point-}
```
public Size(Point point)
```


Initierar en ny instans av strukturen `Aspose.Imaging.Size` från den angivna `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | `Aspose.Imaging.Point` som används för att initiera denna `Aspose.Imaging.Size`. |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```


Initierar en ny instans av strukturen `Aspose.Imaging.Size` från de angivna dimensionerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | int | Breddkomponenten för den nya `Aspose.Imaging.Size`. |
| höjd | int | Höjskomponenten för den nya `Aspose.Imaging.Size`. |

### getEmpty() {#getEmpty--}
```
public static Size getEmpty()
```


Hämtar en ny instans av strukturen `Aspose.Imaging.Size` som har värdena `Aspose.Imaging.Size.Width` och `Aspose.Imaging.Size.Height` satta till noll.

**Returns:**
[Size](../../com.aspose.imaging/size)
### to_SizeF(Size size) {#to-SizeF-com.aspose.imaging.Size-}
```
public static SizeF to_SizeF(Size size)
```


Konverterar den angivna `Aspose.Imaging.Size` till en `Aspose.Imaging.SizeF`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size` att konvertera. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - The `Aspose.Imaging.SizeF` structure to which this operator converts.
### op_Addition(Size size1, Size size2) {#op-Addition-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Addition(Size size1, Size size2)
```


Lägger till bredden och höjden för en `Aspose.Imaging.Size`-struktur till bredden och höjden för en annan `Aspose.Imaging.Size`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Den första `Aspose.Imaging.Size` att lägga till. |
| size2 | [Size](../../com.aspose.imaging/size) | Den andra `Aspose.Imaging.Size` att lägga till. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### op_Subtraction(Size size1, Size size2) {#op-Subtraction-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size op_Subtraction(Size size1, Size size2)
```


Subtraherar bredden och höjden för en `Aspose.Imaging.Size`-struktur från bredden och höjden för en annan `Aspose.Imaging.Size`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size`-strukturen på vänster sida av subtraktionsoperatorn. |
| size2 | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size`-strukturen på höger sida av subtraktionsoperatorn. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the subtraction operation.
### op_Equality(Size size1, Size size2) {#op-Equality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Equality(Size size1, Size size2)
```


Testar om två `Aspose.Imaging.Size`-strukturer är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size`-strukturen på vänster sida av likhetsoperatorn. |
| size2 | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size`-strukturen på höger sida av likhetsoperatorn. |

**Returns:**
boolean - Sant om `size1` och `size2` har lika bredd och höjd; annars falskt.
### op_Inequality(Size size1, Size size2) {#op-Inequality-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean op_Inequality(Size size1, Size size2)
```


Testar om två `Aspose.Imaging.Size`-strukturer är olika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size`-strukturen på vänster sida av olikhetsoperatorn. |
| size2 | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size`-strukturen på höger sida av olikhetsoperatorn. |

**Returns:**
boolean - Sant om `size1` och `size2` skiljer sig i bredd eller höjd; falskt om `size1` och `size2` är lika.
### to_Point(Size size) {#to-Point-com.aspose.imaging.Size-}
```
public static Point to_Point(Size size)
```


Konverterar den angivna `Aspose.Imaging.Size` till en `Aspose.Imaging.Point`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size` att konvertera. |

**Returns:**
[Point](../../com.aspose.imaging/point) - The `Aspose.Imaging.Point` structure to which this operator converts.
### add(Size size1, Size size2) {#add-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size add(Size size1, Size size2)
```


Lägger till bredden och höjden för en `Aspose.Imaging.Size`-struktur till bredden och höjden för en annan `Aspose.Imaging.Size`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | Den första `Aspose.Imaging.Size` att lägga till. |
| size2 | [Size](../../com.aspose.imaging/size) | Den andra `Aspose.Imaging.Size` att lägga till. |

**Returns:**
[Size](../../com.aspose.imaging/size) - A `Aspose.Imaging.Size` structure that is the result of the addition operation.
### ceiling(SizeF size) {#ceiling-com.aspose.imaging.SizeF-}
```
public static Size ceiling(SizeF size)
```


Konverterar den angivna `Aspose.Imaging.SizeF`-strukturen till en `Aspose.Imaging.Size`-struktur genom att avrunda värdena i `Aspose.Imaging.Size`-strukturen till nästa högre heltal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | `Aspose.Imaging.SizeF`-strukturen att konvertera. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### subtract(Size size1, Size size2) {#subtract-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static Size subtract(Size size1, Size size2)
```


Subtraherar bredden och höjden för en `Aspose.Imaging.Size`-struktur från bredden och höjden för en annan `Aspose.Imaging.Size`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size1 | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size`-strukturen på vänster sida av subtraktionsoperatorn. |
| size2 | [Size](../../com.aspose.imaging/size) | `Aspose.Imaging.Size`-strukturen på höger sida av subtraktionsoperatorn. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` that is a result of the subtraction operation.
### truncate(SizeF size) {#truncate-com.aspose.imaging.SizeF-}
```
public static Size truncate(SizeF size)
```


Konverterar den angivna `Aspose.Imaging.SizeF`-strukturen till en `Aspose.Imaging.Size`-struktur genom att trunkera värdena i `Aspose.Imaging.SizeF`-strukturen till nästa lägre heltal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | `Aspose.Imaging.SizeF`-strukturen att konvertera. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### round(SizeF size) {#round-com.aspose.imaging.SizeF-}
```
public static Size round(SizeF size)
```


Konverterar den angivna `Aspose.Imaging.SizeF`-strukturen till en `Aspose.Imaging.Size`-struktur genom att avrunda värdena i `Aspose.Imaging.SizeF`-strukturen till närmaste heltal.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | `Aspose.Imaging.SizeF`-strukturen att konvertera. |

**Returns:**
[Size](../../com.aspose.imaging/size) - The `Aspose.Imaging.Size` structure this method converts to.
### isEquals(Size obj1, Size obj2) {#isEquals-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public static boolean isEquals(Size obj1, Size obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj1 | [Size](../../com.aspose.imaging/size) |  |
| obj2 | [Size](../../com.aspose.imaging/size) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Hämtar ett värde som indikerar om denna `Aspose.Imaging.Size` har bredd och höjd på 0.

**Returns:**
boolean
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar eller anger den horisontella komponenten för denna `Aspose.Imaging.Size`.

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


Hämtar eller anger den horisontella komponenten för denna `Aspose.Imaging.Size`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar eller anger den vertikala komponenten för detta `Aspose.Imaging.Size`.

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


Hämtar eller anger den vertikala komponenten för detta `Aspose.Imaging.Size`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Testar om det angivna objektet är en `Aspose.Imaging.Size` med samma dimensioner som denna `Aspose.Imaging.Size`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det `System.Object` att testa. |

**Returns:**
boolean - Sant om `obj` är en `Aspose.Imaging.Size` och har samma bredd och höjd som denna `Aspose.Imaging.Size`; annars falskt.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för denna `Aspose.Imaging.Size`-struktur.

**Returns:**
int - Ett heltalsvärde som specificerar ett hashvärde för denna `Aspose.Imaging.Size`-struktur.
### toString() {#toString--}
```
public String toString()
```


Skapar en människoläsbar sträng som representerar denna `Aspose.Imaging.Size`.

**Returns:**
java.lang.String - En sträng som representerar denna `Aspose.Imaging.Size`.
### CloneTo(Size that) {#CloneTo-com.aspose.imaging.Size-}
```
public void CloneTo(Size that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [Size](../../com.aspose.imaging/size) |  |

### Clone() {#Clone--}
```
public Size Clone()
```




**Returns:**
[Size](../../com.aspose.imaging/size)
