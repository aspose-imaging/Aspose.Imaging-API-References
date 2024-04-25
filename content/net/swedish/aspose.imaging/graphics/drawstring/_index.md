---
title: DrawString
second_title: Aspose.Imaging för .NET API-referens
description: Ritar den angivna textsträngen på den angivna platsen med den angivnaBrushaspose.imaging/brush ochFontaspose.imaging/font objekt.
type: docs
weight: 320
url: /sv/aspose.imaging/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Ritar den angivna textsträngen på den angivna platsen med den angivna[`Brush`](../../brush) och[`Font`](../../font) objekt.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | String | Sträng att rita. |
| font | Font | [`Font`](../../font) som definierar textformatet för strängen. |
| brush | Brush | [`Brush`](../../brush) som bestämmer färgen och strukturen på den ritade texten. |
| x | Single | X-koordinaten för det övre vänstra hörnet av den ritade texten. |
| y | Single | Y-koordinaten för det övre vänstra hörnet av den ritade texten. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *brush* är null. -eller- *s* är inget. |

### Se även

* class [Font](../../font)
* class [Brush](../../brush)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Ritar den angivna textsträngen på den angivna platsen med den angivna[`Brush`](../../brush) och[`Font`](../../font) objekt.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | String | Sträng att rita. |
| font | Font | [`Font`](../../font) som definierar textformatet för strängen. |
| brush | Brush | [`Brush`](../../brush) som bestämmer färgen och strukturen på den ritade texten. |
| point | PointF | [`PointF`](../../pointf) struktur som anger det övre vänstra hörnet av den ritade texten. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *brush* är null. -eller- *s* är inget. |

### Exempel

Det här exemplet använder klassen Graphics för att skapa primitiva former på bildytan. För att demonstrera operationen skapar exemplet en ny bild i PNG-format och ritar primitiva former på bildytan med ritmetoder exponerade av grafikklassen

```csharp
[C#]

//Skapar en instans av FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //Skapa en instans av PngOptions och ställ in dess olika egenskaper
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //Ställ in källan för PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Skapa en instans av bild 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //Skapa och initiera en instans av klassen Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Rensa grafikytan
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //Rita en båge genom att ange Pen-objektet som har svart färg, 
        //a rektangel som omger bågen, startvinkeln och svepvinkeln
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //Rita en Bezier genom att ange Pen-objektet som har blå färg och koordinatpunkter.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //Rita en kurva genom att ange att Pen-objektet har grön färg och en array av punkter
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //Rita en ellips med hjälp av Pen-objektet och en omgivande rektangel
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //Dra ett streck 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        //Rita ett pajsegment
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //Rita en polygon genom att ange att Pen-objektet har röd färg och en array av punkter
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //Rita en rektangel
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //Skapa ett SolidBrush-objekt och ställ in dess olika egenskaper
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //Rita en sträng med SolidBrush-objektet och Font, vid en viss punkt
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // spara alla ändringar.
        image.Save();
    }
}
```

### Se även

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Ritar den angivna textsträngen på den angivna platsen med den angivna[`Brush`](../../brush) och[`Font`](../../font) objekt som använder formateringsattributen för de angivna[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | String | Sträng att rita. |
| font | Font | [`Font`](../../font) som definierar textformatet för strängen. |
| brush | Brush | [`Brush`](../../brush) som bestämmer färgen och strukturen på den ritade texten. |
| x | Single | X-koordinaten för det övre vänstra hörnet av den ritade texten. |
| y | Single | Y-koordinaten för det övre vänstra hörnet av den ritade texten. |
| format | StringFormat | [`StringFormat`](../../stringformat) som anger formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *brush* är null. -eller- *s* är inget. |

### Se även

* class [Font](../../font)
* class [Brush](../../brush)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Ritar den angivna textsträngen på den angivna platsen med den angivna[`Brush`](../../brush) och[`Font`](../../font) objekt som använder formateringsattributen för de angivna[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | String | Sträng att rita. |
| font | Font | [`Font`](../../font) som definierar textformatet för strängen. |
| brush | Brush | [`Brush`](../../brush) som bestämmer färgen och strukturen på den ritade texten. |
| point | PointF | [`PointF`](../../pointf) struktur som anger det övre vänstra hörnet av den ritade texten. |
| format | StringFormat | [`StringFormat`](../../stringformat) som anger formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *brush* är null. -eller- *s* är inget. |

### Se även

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Ritar den angivna textsträngen i den angivna rektangeln med den angivna[`Brush`](../../brush) och[`Font`](../../font) objekt.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | String | Sträng att rita. |
| font | Font | [`Font`](../../font) som definierar textformatet för strängen. |
| brush | Brush | [`Brush`](../../brush) som bestämmer färgen och strukturen på den ritade texten. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) struktur som anger platsen för den ritade texten. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *brush* är null. -eller- *s* är inget. |

### Se även

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Ritar den angivna textsträngen i den angivna rektangeln med den angivna[`Brush`](../../brush) och[`Font`](../../font) objekt som använder formateringsattributen för de angivna[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| s | String | Sträng att rita. |
| font | Font | [`Font`](../../font) som definierar textformatet för strängen. |
| brush | Brush | [`Brush`](../../brush) som bestämmer färgen och strukturen på den ritade texten. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) struktur som anger platsen för den ritade texten. |
| format | StringFormat | [`StringFormat`](../../stringformat) som anger formateringsattribut, såsom radavstånd och justering, som tillämpas på den ritade texten. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *brush* är null. -eller- *s* är null. -eller- *brush* är inget. |

### Se även

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
