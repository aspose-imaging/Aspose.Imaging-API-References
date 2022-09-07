---
title: DrawBezier
second_title: Aspose.Imaging för .NET API-referens
description: Ritar en Bézier-spline definierad av fyra ordnade par av koordinater som representerar punkter.
type: docs
weight: 170
url: /sv/net/aspose.imaging/graphics/drawbezier/
---
## DrawBezier(Pen, float, float, float, float, float, float, float, float) {#drawbezier_2}

Ritar en Bézier-spline definierad av fyra ordnade par av koordinater som representerar punkter.

```csharp
public void DrawBezier(Pen pen, float x1, float y1, float x2, float y2, float x3, float y3, 
    float x4, float y4)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) som bestämmer kurvans färg, bredd och stil. |
| x1 | Single | X-koordinaten för kurvans startpunkt. |
| y1 | Single | Y-koordinaten för kurvans startpunkt. |
| x2 | Single | X-koordinaten för kurvans första kontrollpunkt. |
| y2 | Single | Y-koordinaten för kurvans första kontrollpunkt. |
| x3 | Single | X-koordinaten för kurvans andra kontrollpunkt. |
| y3 | Single | Y-koordinaten för kurvans andra kontrollpunkt. |
| x4 | Single | X-koordinaten för kurvans slutpunkt. |
| y4 | Single | Y-koordinaten för kurvans slutpunkt. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är inget. |

### Se även

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## DrawBezier(Pen, PointF, PointF, PointF, PointF) {#drawbezier_1}

Ritar en Bézier-spline definierad av fyra[`PointF`](../../pointf) strukturer.

```csharp
public void DrawBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) som bestämmer kurvans färg, bredd och stil. |
| pt1 | PointF | [`PointF`](../../pointf) struktur som representerar kurvans startpunkt. |
| pt2 | PointF | [`PointF`](../../pointf) struktur som representerar den första kontrollpunkten för kurvan. |
| pt3 | PointF | [`PointF`](../../pointf) struktur som representerar den andra kontrollpunkten för kurvan. |
| pt4 | PointF | [`PointF`](../../pointf) struktur som representerar kurvans slutpunkt. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är inget. |

### Se även

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## DrawBezier(Pen, Point, Point, Point, Point) {#drawbezier}

Ritar en Bézier-spline definierad av fyra[`Point`](../../point) strukturer.

```csharp
public void DrawBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) struktur som bestämmer kurvans färg, bredd och stil. |
| pt1 | Point | [`Point`](../../point) struktur som representerar kurvans startpunkt. |
| pt2 | Point | [`Point`](../../point) struktur som representerar den första kontrollpunkten för kurvan. |
| pt3 | Point | [`Point`](../../point) struktur som representerar den andra kontrollpunkten för kurvan. |
| pt4 | Point | [`Point`](../../point) struktur som representerar kurvans slutpunkt. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är inget. |

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

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
