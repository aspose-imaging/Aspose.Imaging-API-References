---
title: RectangleF
second_title: Aspose.Imaging för .NET API-referens
description: Lagrar en uppsättning av fyra flyttalstal som representerar platsen och storleken på en rektangel.
type: docs
weight: 10840
url: /sv/aspose.imaging/rectanglef/
---
## RectangleF structure

Lagrar en uppsättning av fyra flyttalstal som representerar platsen och storleken på en rektangel.

```csharp
public struct RectangleF
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [RectangleF](rectanglef#constructor)(PointF, SizeF) | Initierar en ny instans av[`RectangleF`](../rectanglef) struktur med angiven plats och storlek. |
| [RectangleF](rectanglef#constructor_1)(float, float, float, float) | Initierar en ny instans av[`RectangleF`](../rectanglef) struktur med angiven plats och storlek. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| static [Empty](../../aspose.imaging/rectanglef/empty) { get; } | Får en ny instans av[`RectangleF`](../rectanglef) struktur som har[`X`](./x) ,[`Y`](./y) ,[`Width`](./width) och[`Height`](./height) värden satt till noll. |
| [Bottom](../../aspose.imaging/rectanglef/bottom) { get; set; } | Hämtar eller sätter y-koordinaten som är summan av[`Y`](./y) och[`Height`](./height) av detta[`RectangleF`](../rectanglef) struktur. |
| [Height](../../aspose.imaging/rectanglef/height) { get; set; } | Hämtar eller ställer in höjden på detta[`RectangleF`](../rectanglef) struktur. |
| [IsEmpty](../../aspose.imaging/rectanglef/isempty) { get; } | Får ett värde som indikerar om[`Width`](./width) eller[`Height`](./height) egendom av denna[`RectangleF`](../rectanglef) har värdet noll. |
| [Left](../../aspose.imaging/rectanglef/left) { get; set; } | Hämtar eller ställer in x-koordinaten för den vänstra kanten av denna[`RectangleF`](../rectanglef) struktur. |
| [Location](../../aspose.imaging/rectanglef/location) { get; set; } | Hämtar eller ställer in koordinaterna för det övre vänstra hörnet av denna[`RectangleF`](../rectanglef) struktur. |
| [Right](../../aspose.imaging/rectanglef/right) { get; set; } | Får eller sätter x-koordinaten som är summan av[`X`](./x) och[`Width`](./width) av detta[`RectangleF`](../rectanglef) struktur. |
| [Size](../../aspose.imaging/rectanglef/size) { get; set; } | Hämtar eller ställer in storleken på detta[`RectangleF`](../rectanglef) . |
| [Top](../../aspose.imaging/rectanglef/top) { get; set; } | Hämtar eller ställer in y-koordinaten för den övre kanten av denna[`RectangleF`](../rectanglef) struktur. |
| [Width](../../aspose.imaging/rectanglef/width) { get; set; } | Hämtar eller ställer in bredden på detta[`RectangleF`](../rectanglef) struktur. |
| [X](../../aspose.imaging/rectanglef/x) { get; set; } | Hämtar eller ställer in x-koordinaten för det övre vänstra hörnet av denna[`RectangleF`](../rectanglef) struktur. |
| [Y](../../aspose.imaging/rectanglef/y) { get; set; } | Hämtar eller ställer in y-koordinaten för det övre vänstra hörnet av denna[`RectangleF`](../rectanglef) struktur. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| static [FromLeftTopRightBottom](../../aspose.imaging/rectanglef/fromlefttoprightbottom)(float, float, float, float) | Skapar en[`RectangleF`](../rectanglef) struktur med övre vänstra hörnet och nedre högra hörnet på de angivna platserna. |
| static [FromPoints](../../aspose.imaging/rectanglef/frompoints)(PointF, PointF) | Skapar en ny[`Rectangle`](../rectangle) från två angivna punkter. Två hörn av det skapade[`Rectangle`](../rectangle) kommer att vara lika med godkänd*point1* och*point2* . Dessa skulle vanligtvis vara motsatta hörn. |
| static [Inflate](../../aspose.imaging/rectanglef/inflate)(RectangleF, float, float) | Skapar och returnerar en uppblåst kopia av den angivna[`RectangleF`](../rectanglef)strukturera. Kopian är uppblåst med angivet belopp. Den ursprungliga rektangeln förblir oförändrad. |
| static [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF, RectangleF) | Returnerar en[`RectangleF`](../rectanglef) struktur som representerar skärningspunkten mellan två rektanglar. Om det inte finns någon korsning, och tom[`RectangleF`](../rectanglef) returneras. |
| static [Union](../../aspose.imaging/rectanglef/union)(RectangleF, RectangleF) | Skapar den minsta möjliga tredje rektangeln som kan innehålla båda de två rektanglarna som bildar en union. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains)(PointF) | Bestämmer om den angivna punkten finns inom denna[`RectangleF`](../rectanglef) struktur. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_1)(RectangleF) | Bestämmer om det rektangulära området representerat av*rect* är helt innesluten i detta[`RectangleF`](../rectanglef) struktur. |
| [Contains](../../aspose.imaging/rectanglef/contains#contains_2)(float, float) | Bestämmer om den angivna punkten finns inom denna[`RectangleF`](../rectanglef) struktur. |
| override [Equals](../../aspose.imaging/rectanglef/equals)(object) | Testar om*obj* är en[`RectangleF`](../rectanglef) med samma placering och storlek på denna[`RectangleF`](../rectanglef) . |
| override [GetHashCode](../../aspose.imaging/rectanglef/gethashcode)() | Hämtar hashkoden för detta[`RectangleF`](../rectanglef) struktur. |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate)(SizeF) | Blåser upp detta[`RectangleF`](../rectanglef) med det angivna beloppet. |
| [Inflate](../../aspose.imaging/rectanglef/inflate#inflate_1)(float, float) | Blåser upp detta[`RectangleF`](../rectanglef) struktur med angivet belopp. |
| [Intersect](../../aspose.imaging/rectanglef/intersect)(RectangleF) | Ersätter detta[`RectangleF`](../rectanglef)struktur med skärningspunkten mellan sig själv och det specificerade[`RectangleF`](../rectanglef) struktur. |
| [IntersectsWith](../../aspose.imaging/rectanglef/intersectswith)(RectangleF) | Bestämmer om denna rektangel skär med*rect* . |
| [Normalize](../../aspose.imaging/rectanglef/normalize)() | Normaliserar rektangeln genom att göra dens bredd och höjd positiv, vänster mindre än höger och toppen mindre än botten. |
| [Offset](../../aspose.imaging/rectanglef/offset#offset)(PointF) | Justerar platsen för denna rektangel med det angivna beloppet. |
| [Offset](../../aspose.imaging/rectanglef/offset#offset_1)(float, float) | Justerar platsen för denna rektangel med det angivna beloppet. |
| override [ToString](../../aspose.imaging/rectanglef/tostring)() | Konverterar attributen för detta[`RectangleF`](../rectanglef) till en läsbar sträng. |
| [operator /](../../aspose.imaging/rectanglef/op_division) | Implementerar operatorn /. |
| [operator ==](../../aspose.imaging/rectanglef/op_equality) | Testar om två[`RectangleF`](../rectanglef)strukturer har samma plats och storlek. |
| [implicit operator](../../aspose.imaging/rectanglef/op_implicit) | Konverterar den angivna[`Rectangle`](../rectangle) struktur till en[`RectangleF`](../rectanglef) struktur. |
| [operator !=](../../aspose.imaging/rectanglef/op_inequality) | Testar om två[`RectangleF`](../rectanglef) strukturer skiljer sig åt i plats eller storlek. |
| [operator *](../../aspose.imaging/rectanglef/op_multiply) | Implementerar operatorn *. |

### Se även

* namnutrymme [Aspose.Imaging](../../aspose.imaging)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
