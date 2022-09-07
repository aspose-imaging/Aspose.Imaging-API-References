---
title: DrawPie
second_title: Aspose.Imaging för .NET API-referens
description: Ritar en pajform definierad av en ellips specificerad av aRectangleFaspose.imaging/rectanglef struktur och två radiella linjer.
type: docs
weight: 280
url: /sv/net/aspose.imaging/graphics/drawpie/
---
## DrawPie(Pen, RectangleF, float, float) {#drawpie_1}

Ritar en pajform definierad av en ellips specificerad av a[`RectangleF`](../../rectanglef) struktur och två radiella linjer.

```csharp
public void DrawPie(Pen pen, RectangleF rect, float startAngle, float sweepAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) som avgör pajformens färg, bredd och stil. |
| rect | RectangleF | [`RectangleF`](../../rectanglef) struktur som representerar den avgränsande rektangeln som definierar ellipsen från vilken pajformen kommer. |
| startAngle | Single | Vinkel mätt i grader medurs från x-axeln till den första sidan av pajformen. |
| sweepAngle | Single | Vinkel mätt i grader medurs från*startAngle* parametern till den andra sidan av pajformen. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är inget. |

### Se även

* class [Pen](../../pen)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## DrawPie(Pen, float, float, float, float, float, float) {#drawpie_3}

Ritar en cirkelform som definieras av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiella linjer.

```csharp
public void DrawPie(Pen pen, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) som avgör pajformens färg, bredd och stil. |
| x | Single | X-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen från vilken cirkelformen kommer. |
| y | Single | Y-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen från vilken cirkelformen kommer. |
| width | Single | Bredden på den avgränsande rektangeln som definierar ellipsen från vilken pajformen kommer. |
| height | Single | Höjden på den avgränsande rektangeln som definierar ellipsen från vilken pajformen kommer. |
| startAngle | Single | Vinkel mätt i grader medurs från x-axeln till den första sidan av pajformen. |
| sweepAngle | Single | Vinkel mätt i grader medurs från*startAngle* parametern till den andra sidan av pajformen. |

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

## DrawPie(Pen, Rectangle, float, float) {#drawpie}

Ritar en pajform definierad av en ellips specificerad av a[`Rectangle`](../../rectangle) struktur och två radiella linjer.

```csharp
public void DrawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) som avgör pajformens färg, bredd och stil. |
| rect | Rectangle | [`Rectangle`](../../rectangle) struktur som representerar den avgränsande rektangeln som definierar ellipsen från vilken pajformen kommer. |
| startAngle | Single | Vinkel mätt i grader medurs från x-axeln till den första sidan av pajformen. |
| sweepAngle | Single | Vinkel mätt i grader medurs från*startAngle* parametern till den andra sidan av pajformen. |

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
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## DrawPie(Pen, int, int, int, int, int, int) {#drawpie_2}

Ritar en cirkelform som definieras av en ellips specificerad av ett koordinatpar, en bredd, en höjd och två radiella linjer.

```csharp
public void DrawPie(Pen pen, int x, int y, int width, int height, int startAngle, int sweepAngle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) som avgör pajformens färg, bredd och stil. |
| x | Int32 | X-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen från vilken cirkelformen kommer. |
| y | Int32 | Y-koordinaten för det övre vänstra hörnet av den avgränsande rektangeln som definierar ellipsen från vilken cirkelformen kommer. |
| width | Int32 | Bredden på den avgränsande rektangeln som definierar ellipsen från vilken pajformen kommer. |
| height | Int32 | Höjden på den avgränsande rektangeln som definierar ellipsen från vilken pajformen kommer. |
| startAngle | Int32 | Vinkel mätt i grader medurs från x-axeln till den första sidan av pajformen. |
| sweepAngle | Int32 | Vinkel mätt i grader medurs från*startAngle* parametern till den andra sidan av pajformen. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är inget. |

### Se även

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
