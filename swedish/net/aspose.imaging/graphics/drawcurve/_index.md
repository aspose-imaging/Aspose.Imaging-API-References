---
title: DrawCurve
second_title: Aspose.Imaging för .NET API-referens
description: Ritar en kardinal spline genom en specificerad array avPointFaspose.imaging/pointf strukturer. Den här metoden använder en standardspänning på 0.5.
type: docs
weight: 200
url: /sv/net/aspose.imaging/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

Ritar en kardinal spline genom en specificerad array av[`PointF`](../../pointf) strukturer. Den här metoden använder en standardspänning på 0.5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) som bestämmer kurvans färg, bredd och höjd. |
| points | PointF[] | Uppsättning av[`PointF`](../../pointf) strukturer som definierar spline. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är inget. |

### Se även

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Ritar en kardinal spline genom en specificerad array av[`PointF`](../../pointf) strukturer med en specificerad spänning.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) som bestämmer kurvans färg, bredd och höjd. |
| points | PointF[] | Uppsättning av[`PointF`](../../pointf) strukturer som representerar de punkter som definierar kurvan. |
| tension | Single | Värde större än eller lika med 0,0F som anger kurvans spänning. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är inget. |

### Se även

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Ritar en kardinal spline genom en specificerad array av[`PointF`](../../pointf) strukturer. Ritningen börjar offset från början av arrayen. Denna metod använder en standardspänning på 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) som bestämmer kurvans färg, bredd och höjd. |
| points | PointF[] | Uppsättning av[`PointF`](../../pointf) strukturer som definierar spline. |
| offset | Int32 | Offset från det första elementet i arrayen av*points* parametern till startpunkten i kurvan. |
| numberOfSegments | Int32 | Antal segment efter startpunkten som ska inkluderas i kurvan. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är inget. |

### Se även

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Ritar en kardinal spline genom en specificerad array av[`PointF`](../../pointf)strukturer med en specificerad spänning. Ritningen börjar offset från början av arrayen.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) som bestämmer kurvans färg, bredd och höjd. |
| points | PointF[] | Uppsättning av[`PointF`](../../pointf) strukturer som definierar spline. |
| offset | Int32 | Offset från det första elementet i arrayen av*points* parametern till startpunkten i kurvan. |
| numberOfSegments | Int32 | Antal segment efter startpunkten som ska inkluderas i kurvan. |
| tension | Single | Värde större än eller lika med 0,0F som anger kurvans spänning. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är inget. |

### Se även

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Ritar en kardinal spline genom en specificerad array av[`Point`](../../point) strukturer.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) som bestämmer kurvans färg, bredd och höjd. |
| points | Point[] | Uppsättning av[`Point`](../../point) strukturer som definierar spline. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är inget. |

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

---

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Ritar en kardinal spline genom en specificerad array av[`Point`](../../point) strukturer med en specificerad spänning.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) som bestämmer kurvans färg, bredd och höjd. |
| points | Point[] | Uppsättning av[`Point`](../../point) strukturer som definierar spline. |
| tension | Single | Värde större än eller lika med 0,0F som anger kurvans spänning. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är inget. |

### Se även

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Ritar en kardinal spline genom en specificerad array av[`Point`](../../point) strukturer med en specificerad spänning.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) som bestämmer kurvans färg, bredd och höjd. |
| points | Point[] | Uppsättning av[`Point`](../../point) strukturer som definierar spline. |
| offset | Int32 | Offset från det första elementet i arrayen av*points* parametern till startpunkten i kurvan. |
| numberOfSegments | Int32 | Antal segment efter startpunkten som ska inkluderas i kurvan. |
| tension | Single | Värde större än eller lika med 0,0F som anger kurvans spänning. |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *pen* är null. -eller- *points* är inget. |

### Se även

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* namnutrymme [Aspose.Imaging](../../graphics)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
