---
title: Rectangle
second_title: Aspose.Imaging för .NET API-referens
description: Lagrar en uppsättning av fyra heltal som representerar platsen och storleken på en rektangel.
type: docs
weight: 10830
url: /sv/net/aspose.imaging/rectangle/
---
## Rectangle structure

Lagrar en uppsättning av fyra heltal som representerar platsen och storleken på en rektangel.

```csharp
public struct Rectangle
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Rectangle](rectangle#constructor)(Point, Size) | Initierar en ny instans av[`Rectangle`](../rectangle) struktur med angiven plats och storlek. |
| [Rectangle](rectangle#constructor_1)(int, int, int, int) | Initierar en ny instans av[`Rectangle`](../rectangle) struktur med angiven plats och storlek. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [Empty](../../aspose.imaging/rectangle/empty) { get; } | Får en ny instans av[`Rectangle`](../rectangle) struktur som har[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) och[`Height`](./height) värden satt till noll. |
| [Bottom](../../aspose.imaging/rectangle/bottom) { get; set; } | Hämtar eller ställer in y-koordinaten som är summan av[`Y`](./y) och[`Height`](./height) fastighetsvärden av detta[`Rectangle`](../rectangle) struktur. |
| [Height](../../aspose.imaging/rectangle/height) { get; set; } | Hämtar eller ställer in höjden på detta[`Rectangle`](../rectangle) struktur. |
| [IsEmpty](../../aspose.imaging/rectangle/isempty) { get; } | Får ett värde som indikerar om alla numeriska egenskaper för detta[`Rectangle`](../rectangle) har värden noll. |
| [Left](../../aspose.imaging/rectangle/left) { get; set; } | Hämtar eller ställer in x-koordinaten för den vänstra kanten av denna[`Rectangle`](../rectangle) struktur. |
| [Location](../../aspose.imaging/rectangle/location) { get; set; } | Hämtar eller ställer in koordinaterna för det övre vänstra hörnet av denna[`Rectangle`](../rectangle) struktur. |
| [Right](../../aspose.imaging/rectangle/right) { get; set; } | Får eller sätter x-koordinaten som är summan av[`X`](./x) och[`Width`](./width) fastighetsvärden av detta[`Rectangle`](../rectangle) struktur. |
| [Size](../../aspose.imaging/rectangle/size) { get; set; } | Hämtar eller ställer in storleken på detta[`Rectangle`](../rectangle) . |
| [Top](../../aspose.imaging/rectangle/top) { get; set; } | Hämtar eller ställer in y-koordinaten för den övre kanten av denna[`Rectangle`](../rectangle) struktur. |
| [Width](../../aspose.imaging/rectangle/width) { get; set; } | Hämtar eller ställer in bredden på detta[`Rectangle`](../rectangle) struktur. |
| [X](../../aspose.imaging/rectangle/x) { get; set; } | Hämtar eller ställer in x-koordinaten för det övre vänstra hörnet av denna[`Rectangle`](../rectangle) struktur. |
| [Y](../../aspose.imaging/rectangle/y) { get; set; } | Hämtar eller ställer in y-koordinaten för det övre vänstra hörnet av denna[`Rectangle`](../rectangle) struktur. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [Ceiling](../../aspose.imaging/rectangle/ceiling)(RectangleF) | Konverterar den angivna[`RectangleF`](../rectanglef) struktur till en[`Rectangle`](../rectangle) struktur genom att runda av[`RectangleF`](../rectanglef) värden till nästa högre heltalsvärden. |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectangle/fromlefttoprightbottom)(int, int, int, int) | Skapar en[`Rectangle`](../rectangle) struktur med de angivna kantplatserna. |
| static [FromPoints](../../aspose.imaging/rectangle/frompoints)(Point, Point) | Skapar en ny[`Rectangle`](../rectangle) från två angivna punkter. Två vertikaler av det skapade[`Rectangle`](../rectangle) kommer att vara lika med godkänd*point1* och*point2* . Dessa skulle vanligtvis vara motsatta hörn. |
| static [Inflate](../../aspose.imaging/rectangle/inflate)(Rectangle, int, int) | Skapar och returnerar en uppblåst kopia av den angivna[`Rectangle`](../rectangle) strukturera. Kopian är uppblåst med angivet belopp. Originalet[`Rectangle`](../rectangle) strukturen förblir oförändrad. |
| static [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle, Rectangle) | Returnerar en tredjedel[`Rectangle`](../rectangle) struktur som representerar skärningspunkten mellan två andra[`Rectangle`](../rectangle) strukturer. Om det inte finns någon korsning, en tom[`Rectangle`](../rectangle) returneras. |
| static [Round](../../aspose.imaging/rectangle/round)(RectangleF) | Konverterar den angivna[`RectangleF`](../rectanglef) till a[`Rectangle`](../rectangle) genom att runda[`RectangleF`](../rectanglef)värden till närmaste heltalsvärden. |
| static [Truncate](../../aspose.imaging/rectangle/truncate)(RectangleF) | Konverterar den angivna[`RectangleF`](../rectanglef) till a[`Rectangle`](../rectangle) genom att trunkera[`RectangleF`](../rectanglef) värden. |
| static [Union](../../aspose.imaging/rectangle/union)(Rectangle, Rectangle) | Får en[`Rectangle`](../rectangle) struktur som innehåller föreningen av två[`Rectangle`](../rectangle) strukturer. |
| [Contains](../../aspose.imaging/rectangle/contains#contains)(Point) | Bestämmer om den angivna punkten finns inom denna[`Rectangle`](../rectangle) struktur. |
| [Contains](../../aspose.imaging/rectangle/contains#contains_1)(Rectangle) | Bestämmer om det rektangulära området representerat av*rect* är helt innesluten i detta[`Rectangle`](../rectangle) struktur. |
| [Contains](../../aspose.imaging/rectangle/contains#contains_2)(int, int) | Bestämmer om den angivna punkten finns inom denna[`Rectangle`](../rectangle) struktur. |
| override [Equals](../../aspose.imaging/rectangle/equals)(object) | Testar om*obj* är en[`Rectangle`](../rectangle)struktur med samma placering och storlek på denna[`Rectangle`](../rectangle) struktur. |
| override [GetHashCode](../../aspose.imaging/rectangle/gethashcode)() | Returnerar hash-koden för detta[`Rectangle`](../rectangle) struktur. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate)(Size) | Blåser upp detta[`Rectangle`](../rectangle) med det angivna beloppet. |
| [Inflate](../../aspose.imaging/rectangle/inflate#inflate_1)(int, int) | Blåser upp detta[`Rectangle`](../rectangle) med det angivna beloppet. |
| [Intersect](../../aspose.imaging/rectangle/intersect)(Rectangle) | Ersätter detta[`Rectangle`](../rectangle) med skärningspunkten mellan sig själv och det specificerade[`Rectangle`](../rectangle) . |
| [IntersectsWith](../../aspose.imaging/rectangle/intersectswith)(Rectangle) | Bestämmer om denna rektangel skär med*rect* . |
| [Normalize](../../aspose.imaging/rectangle/normalize)() | Normaliserar rektangeln genom att göra dens bredd och höjd positiv, vänster mindre än höger och toppen mindre än botten. |
| [Offset](../../aspose.imaging/rectangle/offset#offset)(Point) | Justerar platsen för denna rektangel med det angivna beloppet. |
| [Offset](../../aspose.imaging/rectangle/offset#offset_1)(int, int) | Justerar platsen för denna rektangel med det angivna beloppet. |
| override [ToString](../../aspose.imaging/rectangle/tostring)() | Konverterar attributen för detta[`Rectangle`](../rectangle) till en läsbar sträng. |
| [operator ==](../../aspose.imaging/rectangle/op_equality) | Testar om två[`Rectangle`](../rectangle)strukturer har samma plats och storlek. |
| [operator !=](../../aspose.imaging/rectangle/op_inequality) | Testar om två[`Rectangle`](../rectangle) strukturer skiljer sig åt i plats eller storlek. |

### Se även

* namnutrymme [Aspose.Imaging](../../aspose.imaging)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
