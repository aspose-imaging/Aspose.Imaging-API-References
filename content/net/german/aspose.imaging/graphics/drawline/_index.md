---
title: DrawLine
second_title: Aspose.Imaging für .NET-API-Referenz
description: Zeichnet eine Linie die zwei verbindetPointaspose.imaging/point Strukturen.
type: docs
weight: 250
url: /de/aspose.imaging/graphics/drawline/
---
## DrawLine(Pen, Point, Point) {#drawline}

Zeichnet eine Linie, die zwei verbindet[`Point`](../../point) Strukturen.

```csharp
public void DrawLine(Pen pen, Point point1, Point point2)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) die Farbe, Breite und Stil der Linie bestimmt. |
| point1 | Point | [`Point`](../../point) Struktur, die den ersten Verbindungspunkt darstellt. |
| point2 | Point | [`Point`](../../point) Struktur, die den zweiten Verbindungspunkt darstellt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist Null. |

### Beispiele

Dieses Beispiel verwendet die Graphics-Klasse, um primitive Formen auf der Image-Oberfläche zu erstellen. Um den Vorgang zu demonstrieren, erstellt das Beispiel ein neues Image im PNG-Format und zeichnet primitive Formen auf der Image-Oberfläche unter Verwendung von Draw-Methoden, die von der Graphics-Klasse verfügbar gemacht werden

```csharp
[C#]

//Erzeugt eine Instanz von FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.png", System.IO.FileMode.Create))
{
    //Eine Instanz von PngOptions erstellen und ihre verschiedenen Eigenschaften festlegen
    Aspose.Imaging.ImageOptions.PngOptions pngOptions = new Aspose.Imaging.ImageOptions.PngOptions();

    //Setzen Sie die Quelle für PngOptions
    pngOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Eine Instanz von Image erstellen 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(pngOptions, 500, 500))
    {
        //Eine Instanz der Graphics-Klasse erstellen und initialisieren
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Grafikoberfläche löschen
        graphics.Clear(Aspose.Imaging.Color.Wheat);

        //Zeichnen Sie einen Bogen, indem Sie das Stiftobjekt mit schwarzer Farbe angeben, 
        //ein Rechteck, das den Bogen, den Startwinkel und den Sweep-Winkel umgibt
        graphics.DrawArc(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), new Aspose.Imaging.Rectangle(200, 200, 100, 200), 0, 300);

        //Zeichnen Sie einen Bezier, indem Sie das Stiftobjekt mit blauer Farbe und Koordinatenpunkten angeben.
        graphics.DrawBezier(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Blue, 2), new Aspose.Imaging.Point(250, 100), new Aspose.Imaging.Point(300, 30), new Aspose.Imaging.Point(450, 100), new Aspose.Imaging.Point(235, 25));

        //Zeichnen Sie eine Kurve, indem Sie das Stiftobjekt mit grüner Farbe und einem Array von Punkten angeben
        graphics.DrawCurve(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Green, 2), new[] { new Aspose.Imaging.Point(100, 200), new Aspose.Imaging.Point(100, 350), new Aspose.Imaging.Point(200, 450) });

        //Zeichne eine Ellipse mit dem Pen-Objekt und einem umgebenden Rectangle
        graphics.DrawEllipse(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Yellow, 2), new Aspose.Imaging.Rectangle(300, 300, 100, 100));

        //Zeichne eine Linie 
        graphics.DrawLine(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Violet, 2), new Aspose.Imaging.Point(100, 100), new Aspose.Imaging.Point(200, 200));

        // Zeichne ein Kreissegment
        graphics.DrawPie(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Silver, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(200, 20), new Aspose.Imaging.Size(200, 200)), 0, 45);

        //Zeichnen Sie ein Polygon, indem Sie das Stiftobjekt mit roter Farbe und einem Array von Punkten angeben
        graphics.DrawPolygon(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 2), new[] { new Aspose.Imaging.Point(20, 100), new Aspose.Imaging.Point(20, 200), new Aspose.Imaging.Point(220, 20) });

        //Zeichne ein Rechteck
        graphics.DrawRectangle(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Orange, 2), new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(250, 250), new Aspose.Imaging.Size(100, 100)));

        //Ein SolidBrush-Objekt erstellen und seine verschiedenen Eigenschaften festlegen
        Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush();
        brush.Color = Color.Purple;
        brush.Opacity = 100;

        //Zeichne einen String mit dem SolidBrush-Objekt und der Schriftart an einem bestimmten Punkt
        graphics.DrawString("This image is created by Aspose.Imaging API", new Aspose.Imaging.Font("Times New Roman", 16), brush, new Aspose.Imaging.PointF(50, 400));

        // Alle Änderungen speichern.
        image.Save();
    }
}
```

### Siehe auch

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

---

## DrawLine(Pen, PointF, PointF) {#drawline_1}

Zeichnet eine Linie, die zwei verbindet[`PointF`](../../pointf) Strukturen.

```csharp
public void DrawLine(Pen pen, PointF point1, PointF point2)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) die Farbe, Breite und Stil der Linie bestimmt. |
| point1 | PointF | [`PointF`](../../pointf) Struktur, die den ersten Verbindungspunkt darstellt. |
| point2 | PointF | [`PointF`](../../pointf) Struktur, die den zweiten Verbindungspunkt darstellt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist Null. |

### Siehe auch

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

---

## DrawLine(Pen, int, int, int, int) {#drawline_2}

Zeichnet eine Linie, die die beiden durch die Koordinatenpaare angegebenen Punkte verbindet.

```csharp
public void DrawLine(Pen pen, int x1, int y1, int x2, int y2)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) die Farbe, Breite und Stil der Linie bestimmt. |
| x1 | Int32 | Die x-Koordinate des ersten Punktes. |
| y1 | Int32 | Die y-Koordinate des ersten Punktes. |
| x2 | Int32 | Die x-Koordinate des zweiten Punktes. |
| y2 | Int32 | Die y-Koordinate des zweiten Punktes. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist Null. |

### Siehe auch

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

---

## DrawLine(Pen, float, float, float, float) {#drawline_3}

Zeichnet eine Linie, die die beiden durch die Koordinatenpaare angegebenen Punkte verbindet.

```csharp
public void DrawLine(Pen pen, float x1, float y1, float x2, float y2)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) die Farbe, Breite und Stil der Linie bestimmt. |
| x1 | Single | Die x-Koordinate des ersten Punktes. |
| y1 | Single | Die y-Koordinate des ersten Punktes. |
| x2 | Single | Die x-Koordinate des zweiten Punktes. |
| y2 | Single | Die y-Koordinate des zweiten Punktes. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist Null. |

### Siehe auch

* class [Pen](../../pen)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
