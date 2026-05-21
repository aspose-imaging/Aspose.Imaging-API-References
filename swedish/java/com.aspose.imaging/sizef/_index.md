---
title: "SizeF"
second_title: "Aspose.Imaging för Java API-referens"
description: "Lagrar ett ordnat par av flyttal, vanligtvis bredden och höjden på en rektangel."
type: docs
weight: 105
url: /sv/java/com.aspose.imaging/sizef/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class SizeF extends Struct<SizeF>
```

Lagrar ett ordnat par flyttal, vanligtvis bredden och höjden på en rektangel.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [SizeF()](#SizeF--) |  |
| [SizeF(SizeF size)](#SizeF-com.aspose.imaging.SizeF-) | Initierar en ny instans av strukturen `Aspose.Imaging.SizeF` från den angivna `Aspose.Imaging.SizeF`. |
| [SizeF(PointF point)](#SizeF-com.aspose.imaging.PointF-) | Initierar en ny instans av strukturen `Aspose.Imaging.SizeF` från den angivna `Aspose.Imaging.PointF`. |
| [SizeF(float width, float height)](#SizeF-float-float-) | Initierar en ny instans av strukturen `Aspose.Imaging.SizeF` från de angivna dimensionerna. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEmpty()](#getEmpty--) | Hämtar en ny instans av strukturen `Aspose.Imaging.SizeF` som har värdena `Aspose.Imaging.SizeF.Width` och `Aspose.Imaging.SizeF.Height` satta till noll. |
| [op_Addition(SizeF size1, SizeF size2)](#op-Addition-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Lägger till bredden och höjden av en `Aspose.Imaging.SizeF`-struktur till bredden och höjden av en annan `Aspose.Imaging.SizeF`-struktur. |
| [op_Subtraction(SizeF size1, SizeF size2)](#op-Subtraction-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Subtraherar bredden och höjden av en `Aspose.Imaging.SizeF`-struktur från bredden och höjden av en annan `Aspose.Imaging.SizeF`-struktur. |
| [op_Equality(SizeF size1, SizeF size2)](#op-Equality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Testar om två `Aspose.Imaging.SizeF`-strukturer är lika. |
| [op_Inequality(SizeF size1, SizeF size2)](#op-Inequality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Testar om två `Aspose.Imaging.SizeF`-strukturer är olika. |
| [to_PointF(SizeF size)](#to-PointF-com.aspose.imaging.SizeF-) | Konverterar den angivna `Aspose.Imaging.SizeF` till en `Aspose.Imaging.PointF`. |
| [add(SizeF size1, SizeF size2)](#add-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Lägger till bredden och höjden av en `Aspose.Imaging.SizeF`-struktur till bredden och höjden av en annan `Aspose.Imaging.SizeF`-struktur. |
| [subtract(SizeF size1, SizeF size2)](#subtract-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) | Subtraherar bredden och höjden av en `Aspose.Imaging.SizeF`-struktur från bredden och höjden av en annan `Aspose.Imaging.SizeF`-struktur. |
| [isEquals(SizeF obj1, SizeF obj2)](#isEquals-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-) |  |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om detta `Aspose.Imaging.SizeF` har noll bredd och höjd. |
| [getWidth()](#getWidth--) | Hämtar eller anger den horisontella komponenten för detta `Aspose.Imaging.SizeF`. |
| [setWidth(float value)](#setWidth-float-) | Hämtar eller anger den horisontella komponenten för detta `Aspose.Imaging.SizeF`. |
| [getHeight()](#getHeight--) | Hämtar eller anger den vertikala komponenten för detta `Aspose.Imaging.SizeF`. |
| [setHeight(float value)](#setHeight-float-) | Hämtar eller anger den vertikala komponenten för detta `Aspose.Imaging.SizeF`. |
| [toPointF()](#toPointF--) | Konverterar en `Aspose.Imaging.SizeF` till en `Aspose.Imaging.PointF`. |
| [toSize()](#toSize--) | Konverterar en `Aspose.Imaging.SizeF` till en `Aspose.Imaging.Size`-struktur med trunkerade storleksvärden. |
| [equals(Object obj)](#equals-java.lang.Object-) | Testar om det angivna objektet är en `Aspose.Imaging.SizeF` med samma dimensioner som detta `Aspose.Imaging.SizeF`. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för denna `Aspose.Imaging.Size`-struktur. |
| [toString()](#toString--) | Skapar en människoläsbar sträng som representerar detta `Aspose.Imaging.SizeF`. |
| [CloneTo(SizeF that)](#CloneTo-com.aspose.imaging.SizeF-) |  |
| [Clone()](#Clone--) |  |
### SizeF() {#SizeF--}
```
public SizeF()
```


### SizeF(SizeF size) {#SizeF-com.aspose.imaging.SizeF-}
```
public SizeF(SizeF size)
```


Initierar en ny instans av strukturen `Aspose.Imaging.SizeF` från den angivna `Aspose.Imaging.SizeF`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Den `Aspose.Imaging.SizeF` som ska användas för att skapa den nya `Aspose.Imaging.SizeF`. |

### SizeF(PointF point) {#SizeF-com.aspose.imaging.PointF-}
```
public SizeF(PointF point)
```


Initierar en ny instans av strukturen `Aspose.Imaging.SizeF` från den angivna `Aspose.Imaging.PointF`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Den `Aspose.Imaging.PointF` som ska användas för att initiera detta `Aspose.Imaging.SizeF`. |

### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Initierar en ny instans av strukturen `Aspose.Imaging.SizeF` från de angivna dimensionerna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bredd | float | Breddkomponenten för den nya `Aspose.Imaging.SizeF`. |
| höjd | float | Höjdkomponenten för den nya `Aspose.Imaging.SizeF`. |

### getEmpty() {#getEmpty--}
```
public static SizeF getEmpty()
```


Hämtar en ny instans av strukturen `Aspose.Imaging.SizeF` som har värdena `Aspose.Imaging.SizeF.Width` och `Aspose.Imaging.SizeF.Height` satta till noll.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef)
### op_Addition(SizeF size1, SizeF size2) {#op-Addition-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF op_Addition(SizeF size1, SizeF size2)
```


Lägger till bredden och höjden av en `Aspose.Imaging.SizeF`-struktur till bredden och höjden av en annan `Aspose.Imaging.SizeF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | Den första `Aspose.Imaging.SizeF` att lägga till. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | Den andra `Aspose.Imaging.SizeF` att lägga till. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` structure that is the result of the addition operation.
### op_Subtraction(SizeF size1, SizeF size2) {#op-Subtraction-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF op_Subtraction(SizeF size1, SizeF size2)
```


Subtraherar bredden och höjden av en `Aspose.Imaging.SizeF`-struktur från bredden och höjden av en annan `Aspose.Imaging.SizeF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | Den `Aspose.Imaging.SizeF` på vänster sida av subtraktionsoperatorn. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | Den `Aspose.Imaging.SizeF` på högra sidan av subtraktionsoperatorn. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` that is the result of the subtraction operation.
### op_Equality(SizeF size1, SizeF size2) {#op-Equality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean op_Equality(SizeF size1, SizeF size2)
```


Testar om två `Aspose.Imaging.SizeF`-strukturer är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | Strukturen `Aspose.Imaging.SizeF` på vänster sida av likhetsoperatorn. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | Strukturen `Aspose.Imaging.SizeF` på högra sidan av likhetsoperatorn. |

**Returns:**
boolean - Denna operator returnerar true om `size1` och `size2` har lika bredd och höjd; annars false.
### op_Inequality(SizeF size1, SizeF size2) {#op-Inequality-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean op_Inequality(SizeF size1, SizeF size2)
```


Testar om två `Aspose.Imaging.SizeF`-strukturer är olika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | Strukturen `Aspose.Imaging.SizeF` på vänster sida av olikhetsoperatorn. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | Strukturen `Aspose.Imaging.SizeF` på högra sidan av olikhetsoperatorn. |

**Returns:**
boolean - Denna operator returnerar true om `size1` och `size2` skiljer sig i bredd eller höjd; false om `size1` och `size2` är lika.
### to_PointF(SizeF size) {#to-PointF-com.aspose.imaging.SizeF-}
```
public static PointF to_PointF(SizeF size)
```


Konverterar den angivna `Aspose.Imaging.SizeF` till en `Aspose.Imaging.PointF`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size | [SizeF](../../com.aspose.imaging/sizef) | Strukturen `Aspose.Imaging.SizeF` som ska konverteras |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The `Aspose.Imaging.PointF` structure to which this operator converts.
### add(SizeF size1, SizeF size2) {#add-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF add(SizeF size1, SizeF size2)
```


Lägger till bredden och höjden av en `Aspose.Imaging.SizeF`-struktur till bredden och höjden av en annan `Aspose.Imaging.SizeF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | Den första `Aspose.Imaging.SizeF` att lägga till. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | Den andra `Aspose.Imaging.SizeF` att lägga till. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - A `Aspose.Imaging.SizeF` structure that is the result of the addition operation.
### subtract(SizeF size1, SizeF size2) {#subtract-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static SizeF subtract(SizeF size1, SizeF size2)
```


Subtraherar bredden och höjden av en `Aspose.Imaging.SizeF`-struktur från bredden och höjden av en annan `Aspose.Imaging.SizeF`-struktur.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| size1 | [SizeF](../../com.aspose.imaging/sizef) | Strukturen `Aspose.Imaging.SizeF` på vänster sida av subtraktionsoperatorn. |
| size2 | [SizeF](../../com.aspose.imaging/sizef) | Strukturen `Aspose.Imaging.SizeF` på högra sidan av subtraktionsoperatorn. |

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - The `Aspose.Imaging.SizeF` that is a result of the subtraction operation.
### isEquals(SizeF obj1, SizeF obj2) {#isEquals-com.aspose.imaging.SizeF-com.aspose.imaging.SizeF-}
```
public static boolean isEquals(SizeF obj1, SizeF obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj1 | [SizeF](../../com.aspose.imaging/sizef) |  |
| obj2 | [SizeF](../../com.aspose.imaging/sizef) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Hämtar ett värde som indikerar om detta `Aspose.Imaging.SizeF` har noll bredd och höjd.

**Returns:**
boolean - Denna egenskap returnerar true när detta `Aspose.Imaging.SizeF` har både bredd och höjd lika med noll; annars false.
### getWidth() {#getWidth--}
```
public float getWidth()
```


Hämtar eller anger den horisontella komponenten för detta `Aspose.Imaging.SizeF`.

**Returns:**
float - Den horisontella komponenten av detta `Aspose.Imaging.SizeF`, vanligtvis mätt i pixlar.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Hämtar eller anger den horisontella komponenten för detta `Aspose.Imaging.SizeF`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getHeight() {#getHeight--}
```
public float getHeight()
```


Hämtar eller anger den vertikala komponenten för detta `Aspose.Imaging.SizeF`.

**Returns:**
float - Den vertikala komponenten av detta `Aspose.Imaging.SizeF`, vanligtvis mätt i pixlar.
### setHeight(float value) {#setHeight-float-}
```
public void setHeight(float value)
```


Hämtar eller anger den vertikala komponenten för detta `Aspose.Imaging.SizeF`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### toPointF() {#toPointF--}
```
public PointF toPointF()
```


Konverterar en `Aspose.Imaging.SizeF` till en `Aspose.Imaging.PointF`.

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - Returns a `Aspose.Imaging.PointF` structure.
### toSize() {#toSize--}
```
public Size toSize()
```


Konverterar en `Aspose.Imaging.SizeF` till en `Aspose.Imaging.Size`-struktur med trunkerade storleksvärden.

**Returns:**
[Size](../../com.aspose.imaging/size) - Returns a `Aspose.Imaging.Size` structure.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Testar om det angivna objektet är en `Aspose.Imaging.SizeF` med samma dimensioner som detta `Aspose.Imaging.SizeF`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det `System.Object` att testa. |

**Returns:**
boolean - Denna metod returnerar true om `obj` är en `Aspose.Imaging.SizeF` och har samma bredd och höjd som detta `Aspose.Imaging.SizeF`; annars false.
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


Skapar en människoläsbar sträng som representerar detta `Aspose.Imaging.SizeF`.

**Returns:**
java.lang.String - En sträng som representerar detta `Aspose.Imaging.SizeF`.
### CloneTo(SizeF that) {#CloneTo-com.aspose.imaging.SizeF-}
```
public void CloneTo(SizeF that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [SizeF](../../com.aspose.imaging/sizef) |  |

### Clone() {#Clone--}
```
public SizeF Clone()
```




**Returns:**
[SizeF](../../com.aspose.imaging/sizef)
