---
title: FillPie
second_title: Aspose.Imaging för .NET API-referens
description: Fyller det inre av en pajsektion definierad av en ellips specificerad av enRectangleFaspose.imaging/rectanglef struktur och två radiella linjer.
type: docs
weight: 370
url: /sv/net/aspose.imaging/graphics/fillpie/
---
## FillPie(Brush, Rectangle, float, float) {#fillpie}

Fyller det inre av en pajsektion definierad av en ellips specificerad av en[`RectangleF`](../../rectanglef) struktur och två radiella linjer.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) som bestämmer fyllningens egenskaper. |
| rect | Rectangle | [`Rectangle`](../../rectangle)struktur som representerar den avgränsande rektangeln som definierar ellipsen från vilken pajsektionen kommer. |
| startAngle | Single | Vinkel i grader mätt medurs från x-axeln till första sidan av pajsektionen. |
| sweepAngle | Single | Vinkel i grader mätt medurs från*startAngle* parametern till den andra sidan av pajsektionen. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *brush* är inget. |

### Exempel

Följande exempel visar hur man komponerar en animerad GIF-bild från enskilda GIF-block.

```csharp
[C#]

string dir = "c:\\temp\\";

// Skapa en GIF-bild 100 x 100 px.
// Det första blocket är helt svart som standard.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // Den första cirkeln är röd
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Den andra cirkeln är svart
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Öka gradvis vinkeln på den röda bågen.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Öka gradvis vinkeln på den svarta bågen och torka ut den röda bågen.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush2, block.Bounds, 0, angle);
        gr.FillPie(brush1, block.Bounds, angle, 360 - angle);

        gifImage.AddBlock(block);
    }

    gifImage.Save(dir + "animated_radar.gif");
}
```

### Se även

* class [Brush](../../brush)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

Fyller det inre av en pajsektion definierad av en ellips specificerad av en[`RectangleF`](../../rectanglef) struktur och två radiella linjer.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) som bestämmer fyllningens egenskaper. |
| rect | RectangleF | [`RectangleF`](../../rectanglef)struktur som representerar den avgränsande rektangeln som definierar ellipsen från vilken pajsektionen kommer. |
| startAngle | Single | Vinkel i grader mätt medurs från x-axeln till första sidan av pajsektionen. |
| sweepAngle | Single | Vinkel i grader mätt medurs från*startAngle* parametern till den andra sidan av pajsektionen. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *brush* är inget. |

### Se även

* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

Fyller det inre av en pajsektion definierad av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiella linjer.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) som bestämmer fyllningens egenskaper. |
| x | Single | X-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen från vilken pajsektionen kommer. |
| y | Single | Y-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen från vilken pajsektionen kommer. |
| width | Single | Bredden på den avgränsande rektangeln som definierar ellipsen från vilken pajsektionen kommer. |
| height | Single | Höjden på den avgränsande rektangeln som definierar ellipsen från vilken pajsektionen kommer. |
| startAngle | Single | Vinkel i grader mätt medurs från x-axeln till första sidan av pajsektionen. |
| sweepAngle | Single | Vinkel i grader mätt medurs från*startAngle* parametern till den andra sidan av pajsektionen. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *brush* är inget. |

### Se även

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

Fyller det inre av en pajsektion definierad av en ellips specificerad av ett par koordinater, en bredd, en höjd och två radiella linjer.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) som bestämmer fyllningens egenskaper. |
| x | Int32 | X-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen från vilken pajsektionen kommer. |
| y | Int32 | Y-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen från vilken pajsektionen kommer. |
| width | Int32 | Bredden på den avgränsande rektangeln som definierar ellipsen från vilken pajsektionen kommer. |
| height | Int32 | Höjden på den avgränsande rektangeln som definierar ellipsen från vilken pajsektionen kommer. |
| startAngle | Int32 | Vinkel i grader mätt medurs från x-axeln till första sidan av pajsektionen. |
| sweepAngle | Int32 | Vinkel i grader mätt medurs från*startAngle* parametern till den andra sidan av pajsektionen. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *brush* är inget. |

### Se även

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
