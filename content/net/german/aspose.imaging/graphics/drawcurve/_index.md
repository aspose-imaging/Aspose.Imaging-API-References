---
title: DrawCurve
second_title: Aspose.Imaging für .NET-API-Referenz
description: Zeichnet einen kardinalen Spline durch ein angegebenes Array vonPointFaspose.imaging/pointf Strukturen. Diese Methode verwendet eine Standardspannung von 05.
type: docs
weight: 200
url: /de/aspose.imaging/graphics/drawcurve/
---
## DrawCurve(Pen, PointF[]) {#drawcurve}

Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`PointF`](../../pointf) Strukturen. Diese Methode verwendet eine Standardspannung von 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) die die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | PointF[] | Anordnung von[`PointF`](../../pointf) Strukturen, die den Spline definieren. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist Null. |

### Siehe auch

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], float) {#drawcurve_3}

Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`PointF`](../../pointf) Strukturen mit einer bestimmten Spannung.

```csharp
public void DrawCurve(Pen pen, PointF[] points, float tension)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) die die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | PointF[] | Anordnung von[`PointF`](../../pointf) Strukturen, die die Punkte darstellen, die die Kurve definieren. |
| tension | Single | Wert größer oder gleich 0,0 F, der die Spannung der Kurve angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist Null. |

### Siehe auch

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int) {#drawcurve_1}

Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`PointF`](../../pointf) Strukturen. Die Zeichnung beginnt versetzt vom Anfang des Arrays. Diese Methode verwendet eine Standardspannung von 0,5.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) die die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | PointF[] | Anordnung von[`PointF`](../../pointf) Strukturen, die den Spline definieren. |
| offset | Int32 | Versatz vom ersten Element im Array der*points* Parameter zum Anfangspunkt der Kurve. |
| numberOfSegments | Int32 | Anzahl der Segmente nach dem Startpunkt, die in die Kurve aufgenommen werden sollen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist Null. |

### Siehe auch

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, PointF[], int, int, float) {#drawcurve_2}

Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`PointF`](../../pointf)Strukturen mit einer bestimmten Spannung. Die Zeichnung beginnt versetzt vom Anfang des Arrays.

```csharp
public void DrawCurve(Pen pen, PointF[] points, int offset, int numberOfSegments, float tension)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) die die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | PointF[] | Anordnung von[`PointF`](../../pointf) Strukturen, die den Spline definieren. |
| offset | Int32 | Versatz vom ersten Element im Array der*points* Parameter zum Anfangspunkt der Kurve. |
| numberOfSegments | Int32 | Anzahl der Segmente nach dem Startpunkt, die in die Kurve aufgenommen werden sollen. |
| tension | Single | Wert größer oder gleich 0,0 F, der die Spannung der Kurve angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist Null. |

### Siehe auch

* class [Pen](../../pen)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[]) {#drawcurve_4}

Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`Point`](../../point) Strukturen.

```csharp
public void DrawCurve(Pen pen, Point[] points)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) die die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | Point[] | Anordnung von[`Point`](../../point) Strukturen, die den Spline definieren. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist Null. |

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

## DrawCurve(Pen, Point[], float) {#drawcurve_6}

Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`Point`](../../point) Strukturen mit einer bestimmten Spannung.

```csharp
public void DrawCurve(Pen pen, Point[] points, float tension)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) die die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | Point[] | Anordnung von[`Point`](../../point) Strukturen, die den Spline definieren. |
| tension | Single | Wert größer oder gleich 0,0 F, der die Spannung der Kurve angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist Null. |

### Siehe auch

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

---

## DrawCurve(Pen, Point[], int, int, float) {#drawcurve_5}

Zeichnet einen kardinalen Spline durch ein angegebenes Array von[`Point`](../../point) Strukturen mit einer bestimmten Spannung.

```csharp
public void DrawCurve(Pen pen, Point[] points, int offset, int numberOfSegments, float tension)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pen | Pen | [`Pen`](../../pen) die die Farbe, Breite und Höhe der Kurve bestimmt. |
| points | Point[] | Anordnung von[`Point`](../../point) Strukturen, die den Spline definieren. |
| offset | Int32 | Versatz vom ersten Element im Array der*points* Parameter zum Anfangspunkt der Kurve. |
| numberOfSegments | Int32 | Anzahl der Segmente nach dem Startpunkt, die in die Kurve aufgenommen werden sollen. |
| tension | Single | Wert größer oder gleich 0,0 F, der die Spannung der Kurve angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *pen* ist null. -oder- *points* ist Null. |

### Siehe auch

* class [Pen](../../pen)
* struct [Point](../../point)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
