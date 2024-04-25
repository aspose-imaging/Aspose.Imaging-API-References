---
title: Region
second_title: Aspose.Imaging för .NET API-referens
description: Beskriver det inre av en grafisk form som består av rektanglar och banor. Denna klass kan inte ärvas.
type: docs
weight: 10850
url: /sv/aspose.imaging/region/
---
## Region class

Beskriver det inre av en grafisk form som består av rektanglar och banor. Denna klass kan inte ärvas.

```csharp
public sealed class Region
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Region](region#constructor)() | Initierar en ny[`Region`](../region) . |
| [Region](region#constructor_1)(GraphicsPath) | Initierar en ny[`Region`](../region) med det angivna[`GraphicsPath`](../graphicspath) . |
| [Region](region#constructor_2)(Rectangle) | Initierar en ny[`Region`](../region) från det angivna[`Rectangle`](../rectangle) struktur. |
| [Region](region#constructor_3)(RectangleF) | Initierar en ny[`Region`](../region) från det angivna[`RectangleF`](../rectanglef) struktur. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Complement](../../aspose.imaging/region/complement#complement)(GraphicsPath) | Uppdaterar detta[`Region`](../region) att innehålla den del av det angivna[`GraphicsPath`](../graphicspath) som inte korsar detta[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_1)(Rectangle) | Uppdaterar detta[`Region`](../region) att innehålla den del av det angivna[`Rectangle`](../rectangle) struktur som inte korsar detta[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_2)(RectangleF) | Uppdaterar detta[`Region`](../region) att innehålla den del av det angivna[`RectangleF`](../rectanglef) struktur som inte korsar detta[`Region`](../region) . |
| [Complement](../../aspose.imaging/region/complement#complement_3)(Region) | Uppdaterar detta[`Region`](../region) att innehålla den del av det angivna[`Region`](../region) som inte korsar detta[`Region`](../region) . |
| [DeepClone](../../aspose.imaging/region/deepclone)() | Skapar en exakt djup kopia av detta[`Region`](../region) . |
| [Equals](../../aspose.imaging/region/equals#equals)(Region, Graphics) | Testar om den angivna[`Region`](../region) är identisk med detta[`Region`](../region) på den angivna ritytan. |
| [Exclude](../../aspose.imaging/region/exclude#exclude)(GraphicsPath) | Uppdaterar detta[`Region`](../region) att endast innehålla den del av dess inre som inte korsar det specificerade[`GraphicsPath`](../graphicspath) . |
| [Exclude](../../aspose.imaging/region/exclude#exclude_1)(Rectangle) | Uppdaterar detta[`Region`](../region) att endast innehålla den del av dess inre som inte korsar det specificerade[`Rectangle`](../rectangle) struktur. |
| [Exclude](../../aspose.imaging/region/exclude#exclude_2)(RectangleF) | Uppdaterar detta[`Region`](../region) att endast innehålla den del av dess inre som inte korsar det specificerade[`RectangleF`](../rectanglef) struktur. |
| [Exclude](../../aspose.imaging/region/exclude#exclude_3)(Region) | Uppdaterar detta[`Region`](../region) att endast innehålla den del av dess inre som inte korsar det specificerade[`Region`](../region) . |
| [Intersect](../../aspose.imaging/region/intersect#intersect)(GraphicsPath) | Uppdaterar detta[`Region`](../region) till skärningspunkten av sig själv med det angivna[`GraphicsPath`](../graphicspath) . |
| [Intersect](../../aspose.imaging/region/intersect#intersect_1)(Rectangle) | Uppdaterar detta[`Region`](../region) till skärningspunkten av sig själv med det angivna[`Rectangle`](../rectangle) struktur. |
| [Intersect](../../aspose.imaging/region/intersect#intersect_2)(RectangleF) | Uppdaterar detta[`Region`](../region) till skärningspunkten av sig själv med det angivna[`RectangleF`](../rectanglef) struktur. |
| [Intersect](../../aspose.imaging/region/intersect#intersect_3)(Region) | Uppdaterar detta[`Region`](../region) till skärningspunkten av sig själv med det angivna[`Region`](../region) . |
| [IsEmpty](../../aspose.imaging/region/isempty)(Graphics) | Testar om detta[`Region`](../region) har en tom interiör på den angivna ritytan. |
| [IsInfinite](../../aspose.imaging/region/isinfinite)(Graphics) | Testar om detta[`Region`](../region) har en oändlig interiör på den angivna ritytan. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible)(Point) | Testar om den angivna[`Point`](../point) strukturen finns i detta[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_2)(PointF) | Testar om den angivna[`PointF`](../pointf) strukturen finns i detta[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_4)(Rectangle) | Testar om någon del av det angivna[`Rectangle`](../rectangle) strukturen finns i detta[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_6)(RectangleF) | Testar om någon del av det angivna[`RectangleF`](../rectanglef) strukturen finns i detta[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_11)(float, float) | Testar om den angivna punkten finns i denna[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_1)(Point, Graphics) | Testar om den angivna[`Point`](../point) strukturen finns i detta[`Region`](../region)när den ritas med det angivna[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_3)(PointF, Graphics) | Testar om den angivna[`PointF`](../pointf) strukturen finns i detta[`Region`](../region)när den ritas med det angivna[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_5)(Rectangle, Graphics) | Testar om någon del av det angivna[`Rectangle`](../rectangle) strukturen finns i detta[`Region`](../region)när den ritas med det angivna[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_7)(RectangleF, Graphics) | Testar om någon del av det angivna[`RectangleF`](../rectanglef) strukturen finns i detta[`Region`](../region)när den ritas med det angivna[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_12)(float, float, Graphics) | Testar om den angivna punkten finns i denna[`Region`](../region)när den ritas med det angivna[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_8)(int, int, Graphics) | Testar om den angivna punkten finns i denna[`Region`](../region) objekt när det ritas med det angivna[`Graphics`](../graphics) objekt. |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_13)(float, float, float, float) | Testar om någon del av den angivna rektangeln finns i denna[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_9)(int, int, int, int) | Testar om någon del av den angivna rektangeln finns i denna[`Region`](../region) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_14)(float, float, float, float, Graphics) | Testar om någon del av den angivna rektangeln finns i denna[`Region`](../region)när den ritas med det angivna[`Graphics`](../graphics) . |
| [IsVisible](../../aspose.imaging/region/isvisible#isvisible_10)(int, int, int, int, Graphics) | Testar om någon del av den angivna rektangeln finns i denna[`Region`](../region)när den ritas med det angivna[`Graphics`](../graphics) . |
| [MakeEmpty](../../aspose.imaging/region/makeempty)() | Initierar detta[`Region`](../region) till en tom interiör. |
| [MakeInfinite](../../aspose.imaging/region/makeinfinite)() | Initierar detta[`Region`](../region) invända mot en oändlig interiör. |
| [Transform](../../aspose.imaging/region/transform)(Matrix) | Förvandlar detta[`Region`](../region) av den angivna[`Matrix`](../matrix) . |
| [Translate](../../aspose.imaging/region/translate#translate_1)(float, float) | Förskjuter koordinaterna för detta[`Region`](../region) med det angivna beloppet. |
| [Translate](../../aspose.imaging/region/translate#translate)(int, int) | Förskjuter koordinaterna för detta[`Region`](../region) med det angivna beloppet. |
| [Union](../../aspose.imaging/region/union#union)(GraphicsPath) | Uppdaterar detta[`Region`](../region) till föreningen av sig själv och det specificerade[`GraphicsPath`](../graphicspath) . |
| [Union](../../aspose.imaging/region/union#union_1)(Rectangle) | Uppdaterar detta[`Region`](../region) till föreningen av sig själv och det specificerade[`Rectangle`](../rectangle) struktur. |
| [Union](../../aspose.imaging/region/union#union_2)(RectangleF) | Uppdaterar detta[`Region`](../region) till föreningen av sig själv och det specificerade[`RectangleF`](../rectanglef) struktur. |
| [Union](../../aspose.imaging/region/union#union_3)(Region) | Uppdaterar detta[`Region`](../region) till föreningen av sig själv och det specificerade[`Region`](../region) . |
| [Xor](../../aspose.imaging/region/xor#xor)(GraphicsPath) | Uppdaterar detta[`Region`](../region) till facket minus skärningspunkten för sig själv med det angivna[`GraphicsPath`](../graphicspath) . |
| [Xor](../../aspose.imaging/region/xor#xor_1)(Rectangle) | Uppdaterar detta[`Region`](../region) till facket minus skärningspunkten för sig själv med det angivna[`Rectangle`](../rectangle) struktur. |
| [Xor](../../aspose.imaging/region/xor#xor_2)(RectangleF) | Uppdaterar detta[`Region`](../region) till facket minus skärningspunkten för sig själv med det angivna[`RectangleF`](../rectanglef) struktur. |
| [Xor](../../aspose.imaging/region/xor#xor_3)(Region) | Uppdaterar detta[`Region`](../region) till facket minus skärningspunkten för sig själv med det angivna[`Region`](../region) . |

### Se även

* namnutrymme [Aspose.Imaging](../../aspose.imaging)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
