---
title: "PointF"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar ett ordnat par av flyttals x- och y-koordinater som definierar en punkt i ett tvådimensionellt plan."
type: docs
weight: 87
url: /sv/java/com.aspose.imaging/pointf/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public final class PointF extends Struct<PointF>
```

Representerar ett ordnat par av flyttals x- och y-koordinater som definierar en punkt i ett tvådimensionellt plan.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PointF()](#PointF--) |  |
| [PointF(float x, float y)](#PointF-float-float-) | Initierar en ny instans av `com.aspose.imaging.PointF`-strukturen med de angivna koordinaterna. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEmpty()](#getEmpty--) | Hämtar en ny instans av `com.aspose.imaging.PointF`-strukturen som har `com.aspose.imaging.PointF.X`- och `com.aspose.imaging.PointF.Y`-värden satta till noll. |
| [op_Addition(PointF point, Size size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Flyttar en `com.aspose.imaging.PointF` med en given `com.aspose.imaging.Size`. |
| [op_Subtraction(PointF point, Size size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Flyttar en `com.aspose.imaging.PointF` med den negativa av en given `com.aspose.imaging.Size`. |
| [op_Addition(PointF point, SizeF size)](#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Flyttar `com.aspose.imaging.PointF` med den angivna `com.aspose.imaging.SizeF`. |
| [op_Subtraction(PointF point, SizeF size)](#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Flyttar en `com.aspose.imaging.PointF` med den negativa av en angiven `com.aspose.imaging.SizeF`. |
| [op_Equality(PointF point1, PointF point2)](#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Jämför två `com.aspose.imaging.PointF`-strukturer. |
| [op_Inequality(PointF point1, PointF point2)](#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Bestämmer om koordinaterna för de angivna punkterna inte är lika. |
| [add(PointF point, Size size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Flyttar en given `com.aspose.imaging.PointF` med den angivna `com.aspose.imaging.Size`. |
| [subtract(PointF point, Size size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-) | Flyttar en `com.aspose.imaging.PointF` med den negativa av en angiven storlek. |
| [add(PointF point, SizeF size)](#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Flyttar en given `com.aspose.imaging.PointF` med en angiven `com.aspose.imaging.SizeF`. |
| [subtract(PointF point, SizeF size)](#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-) | Flyttar en `com.aspose.imaging.PointF` med den negativa av en angiven storlek. |
| [isEquals(PointF obj1, PointF obj2)](#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) |  |
| [isEmpty()](#isEmpty--) | Hämtar ett värde som indikerar om denna `com.aspose.imaging.PointF` är tom. |
| [getX()](#getX--) | Hämtar eller anger x-koordinaten för denna `com.aspose.imaging.PointF`. |
| [setX(float value)](#setX-float-) | Hämtar eller anger x-koordinaten för denna `com.aspose.imaging.PointF`. |
| [getY()](#getY--) | Hämtar eller anger y-koordinaten för denna `com.aspose.imaging.PointF`. |
| [setY(float value)](#setY-float-) | Hämtar eller anger y-koordinaten för denna `com.aspose.imaging.PointF`. |
| [equals(Object obj)](#equals-java.lang.Object-) | Anger om denna `com.aspose.imaging.PointF` innehåller samma koordinater som det angivna `System.Object`. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för denna `com.aspose.imaging.PointF`-struktur. |
| [toString()](#toString--) | Konverterar denna `com.aspose.imaging.PointF` till en människoläsbar sträng. |
| [CloneTo(PointF that)](#CloneTo-com.aspose.imaging.PointF-) |  |
| [Clone()](#Clone--) |  |
### PointF() {#PointF--}
```
public PointF()
```


### PointF(float x, float y) {#PointF-float-float-}
```
public PointF(float x, float y)
```


Initierar en ny instans av `com.aspose.imaging.PointF`-strukturen med de angivna koordinaterna.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | float | Den horisontella positionen för punkten. |
| y | float | Den vertikala positionen för punkten. |

### getEmpty() {#getEmpty--}
```
public static PointF getEmpty()
```


Hämtar en ny instans av `com.aspose.imaging.PointF`-strukturen som har `com.aspose.imaging.PointF.X`- och `com.aspose.imaging.PointF.Y`-värden satta till noll.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### op_Addition(PointF point, Size size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Addition(PointF point, Size size)
```


Flyttar en `com.aspose.imaging.PointF` med en given `com.aspose.imaging.Size`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Den `com.aspose.imaging.PointF` att översätta. |
| size | [Size](../../com.aspose.imaging/size) | En `com.aspose.imaging.Size` som specificerar paret av tal att lägga till koordinaterna för `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - Returns the translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, Size size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF op_Subtraction(PointF point, Size size)
```


Flyttar en `com.aspose.imaging.PointF` med den negativa av en given `com.aspose.imaging.Size`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | En `com.aspose.imaging.PointF` att översätta. |
| size | [Size](../../com.aspose.imaging/size) | En `com.aspose.imaging.Size` som specificerar talen att subtrahera från x- och y-koordinaterna för `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Addition(PointF point, SizeF size) {#op-Addition-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Addition(PointF point, SizeF size)
```


Flyttar `com.aspose.imaging.PointF` med den angivna `com.aspose.imaging.SizeF`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Den `com.aspose.imaging.PointF` att översätta. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Den `com.aspose.imaging.SizeF` som specificerar talen att lägga till x- och y-koordinaterna för `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Subtraction(PointF point, SizeF size) {#op-Subtraction-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF op_Subtraction(PointF point, SizeF size)
```


Flyttar en `com.aspose.imaging.PointF` med den negativa av en angiven `com.aspose.imaging.SizeF`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Den `com.aspose.imaging.PointF` att översätta. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Den `com.aspose.imaging.SizeF` som specificerar talen att subtrahera från koordinaterna för `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### op_Equality(PointF point1, PointF point2) {#op-Equality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Equality(PointF point1, PointF point2)
```


Jämför två `com.aspose.imaging.PointF`-strukturer. Resultatet specificerar om värdena för `com.aspose.imaging.PointF.X` och `com.aspose.imaging.PointF.Y`-egenskaperna i de två `com.aspose.imaging.PointF`-strukturerna är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | En första `com.aspose.imaging.PointF` att jämföra. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | En andra `com.aspose.imaging.PointF` att jämföra. |

**Returns:**
boolean - Sant om `com.aspose.imaging.PointF.X`- och `com.aspose.imaging.PointF.Y`-värdena för den första och andra `com.aspose.imaging.PointF`-strukturen är lika; annars falskt.
### op_Inequality(PointF point1, PointF point2) {#op-Inequality-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean op_Inequality(PointF point1, PointF point2)
```


Bestämmer om koordinaterna för de angivna punkterna inte är lika.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | [PointF](../../com.aspose.imaging/pointf) | En första `com.aspose.imaging.PointF` att jämföra. |
| point2 | [PointF](../../com.aspose.imaging/pointf) | En andra `com.aspose.imaging.PointF` att jämföra. |

**Returns:**
boolean - Sant för att indikera att `com.aspose.imaging.PointF.X`- och `com.aspose.imaging.PointF.Y`-värdena för `point1` och `point2` inte är lika; annars falskt.
### add(PointF point, Size size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF add(PointF point, Size size)
```


Flyttar en given `com.aspose.imaging.PointF` med den angivna `com.aspose.imaging.Size`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Den `com.aspose.imaging.PointF` att översätta. |
| size | [Size](../../com.aspose.imaging/size) | Den `com.aspose.imaging.Size` som specificerar talen att lägga till koordinaterna för `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, Size size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.Size-}
```
public static PointF subtract(PointF point, Size size)
```


Flyttar en `com.aspose.imaging.PointF` med den negativa av en angiven storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Den `com.aspose.imaging.PointF` att översätta. |
| size | [Size](../../com.aspose.imaging/size) | Den `com.aspose.imaging.Size` som specificerar talen att subtrahera från koordinaterna för `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### add(PointF point, SizeF size) {#add-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF add(PointF point, SizeF size)
```


Flyttar en given `com.aspose.imaging.PointF` med en angiven `com.aspose.imaging.SizeF`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Den `com.aspose.imaging.PointF` att översätta. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Den `com.aspose.imaging.SizeF` som specificerar talen att lägga till koordinaterna för `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### subtract(PointF point, SizeF size) {#subtract-com.aspose.imaging.PointF-com.aspose.imaging.SizeF-}
```
public static PointF subtract(PointF point, SizeF size)
```


Flyttar en `com.aspose.imaging.PointF` med den negativa av en angiven storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Den `com.aspose.imaging.PointF` att översätta. |
| size | [SizeF](../../com.aspose.imaging/sizef) | Den `com.aspose.imaging.SizeF` som specificerar talen att subtrahera från koordinaterna för `point`. |

**Returns:**
[PointF](../../com.aspose.imaging/pointf) - The translated `com.aspose.imaging.PointF`.
### isEquals(PointF obj1, PointF obj2) {#isEquals-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public static boolean isEquals(PointF obj1, PointF obj2)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj1 | [PointF](../../com.aspose.imaging/pointf) |  |
| obj2 | [PointF](../../com.aspose.imaging/pointf) |  |

**Returns:**
boolean
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


Hämtar ett värde som indikerar om denna `com.aspose.imaging.PointF` är tom.

**Returns:**
boolean - Sant om både `com.aspose.imaging.PointF.X` och `com.aspose.imaging.PointF.Y` är 0; annars falskt.
### getX() {#getX--}
```
public float getX()
```


Hämtar eller anger x-koordinaten för denna `com.aspose.imaging.PointF`.

**Returns:**
float
### setX(float value) {#setX-float-}
```
public void setX(float value)
```


Hämtar eller anger x-koordinaten för denna `com.aspose.imaging.PointF`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### getY() {#getY--}
```
public float getY()
```


Hämtar eller anger y-koordinaten för denna `com.aspose.imaging.PointF`.

**Returns:**
float
### setY(float value) {#setY-float-}
```
public void setY(float value)
```


Hämtar eller anger y-koordinaten för denna `com.aspose.imaging.PointF`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Anger om denna `com.aspose.imaging.PointF` innehåller samma koordinater som det angivna `System.Object`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Det `System.Object` att testa. |

**Returns:**
boolean - Denna metod returnerar sant om `obj` är en `com.aspose.imaging.PointF` och har samma koordinater som detta `com.aspose.imaging.Point`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för denna `com.aspose.imaging.PointF`-struktur.

**Returns:**
int - Ett heltalsvärde som specificerar ett hashvärde för denna `com.aspose.imaging.PointF`-struktur.
### toString() {#toString--}
```
public String toString()
```


Konverterar denna `com.aspose.imaging.PointF` till en människoläsbar sträng.

**Returns:**
java.lang.String - En sträng som representerar denna `com.aspose.imaging.PointF`.
### CloneTo(PointF that) {#CloneTo-com.aspose.imaging.PointF-}
```
public void CloneTo(PointF that)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| that | [PointF](../../com.aspose.imaging/pointf) |  |

### Clone() {#Clone--}
```
public PointF Clone()
```




**Returns:**
[PointF](../../com.aspose.imaging/pointf)
