---
title: "Lager"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar Photoshop-textlager."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.xmp.schemas.photoshop/layer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.xmp.types.XmpTypeBase](../../com.aspose.imaging.xmp.types/xmptypebase)

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public class Layer extends XmpTypeBase implements System.IEquatable<Layer>
```

Representerar Photoshop-textlager.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Layer(String layerName, String layerText)](#Layer-java.lang.String-java.lang.String-) | Initierar en ny instans av klassen `Layer`. |
| [Layer()](#Layer--) | Initierar en ny instans av klassen `Layer`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getName()](#getName--) | Hämtar eller anger namnet på textlagret. |
| [setName(String value)](#setName-java.lang.String-) | Hämtar eller anger namnet på textlagret. |
| [getText()](#getText--) | Hämtar eller anger textinnehållet i lagret. |
| [setText(String value)](#setText-java.lang.String-) | Hämtar eller anger textinnehållet i lagret. |
| [getXmpRepresentation()](#getXmpRepresentation--) | Returnerar strängens innehållsvärde i XMP-format. |
| [equals(Object obj)](#equals-java.lang.Object-) | Bestämmer om det angivna `System.Object` är lika med den här instansen. |
| [isEquals(Layer other)](#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-) | Indikerar om det aktuella objektet är lika med ett annat objekt av samma typ. |
| [hashCode()](#hashCode--) | Returnerar en hashkod för detta objekt. |
### Layer(String layerName, String layerText) {#Layer-java.lang.String-java.lang.String-}
```
public Layer(String layerName, String layerText)
```


Initierar en ny instans av klassen `Layer`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layerName | java.lang.String | Namn på lagret. |
| layerText | java.lang.String | Lagrets text. |

### Layer() {#Layer--}
```
public Layer()
```


Initierar en ny instans av klassen `Layer`.

### getName() {#getName--}
```
public String getName()
```


Hämtar eller anger namnet på textlagret.

Värde: Namnet på textlagret.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Hämtar eller anger namnet på textlagret.

Värde: Namnet på textlagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getText() {#getText--}
```
public String getText()
```


Hämtar eller anger textinnehållet i lagret.

Värde: Textinnehållet i lagret.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Hämtar eller anger textinnehållet i lagret.

Värde: Textinnehållet i lagret.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getXmpRepresentation() {#getXmpRepresentation--}
```
public String getXmpRepresentation()
```


Returnerar strängens innehållsvärde i XMP-format.

**Returns:**
java.lang.String - Returnerar strängens innehållsvärde i XMP-format.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Bestämmer om det angivna `System.Object` är lika med den här instansen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object | Den `System.Object` att jämföra med denna instans. |

**Returns:**
boolean - `true` om det angivna `System.Object` är lika med denna instans; annars `false`.
### isEquals(Layer other) {#isEquals-com.aspose.imaging.xmp.schemas.photoshop.Layer-}
```
public boolean isEquals(Layer other)
```


Indikerar om det aktuella objektet är lika med ett annat objekt av samma typ.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| other | [Layer](../../com.aspose.imaging.xmp.schemas.photoshop/layer) | Ett objekt att jämföra med detta objekt. |

**Returns:**
boolean - true om det aktuella objektet är lika med parametern `other`; annars false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returnerar en hashkod för detta objekt.

**Returns:**
int - En hashkod för denna instans, lämplig för användning i hash-algoritmer och datastrukturer som en hash‑tabell.
