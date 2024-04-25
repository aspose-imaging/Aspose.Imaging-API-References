---
title: DrawString
second_title: Aspose.Imaging für .NET-API-Referenz
description: Zeichnet die angegebene Textzeichenfolge an der angegebenen Stelle mit dem angegebenenBrushaspose.imaging/brush undFontaspose.imaging/font Objekte.
type: docs
weight: 320
url: /de/aspose.imaging/graphics/drawstring/
---
## DrawString(string, Font, Brush, float, float) {#drawstring_4}

Zeichnet die angegebene Textzeichenfolge an der angegebenen Stelle mit dem angegebenen[`Brush`](../../brush) und[`Font`](../../font) Objekte.

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Schnur zum Zeichnen. |
| font | Font | [`Font`](../../font) die das Textformat der Zeichenfolge definiert. |
| brush | Brush | [`Brush`](../../brush) die die Farbe und Textur des gezeichneten Textes bestimmt. |
| x | Single | Die x-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | Single | Die y-Koordinate der oberen linken Ecke des gezeichneten Textes. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist Null. |

### Siehe auch

* class [Font](../../font)
* class [Brush](../../brush)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF) {#drawstring}

Zeichnet die angegebene Textzeichenfolge an der angegebenen Stelle mit dem angegebenen[`Brush`](../../brush) und[`Font`](../../font) Objekte.

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Schnur zum Zeichnen. |
| font | Font | [`Font`](../../font) die das Textformat der Zeichenfolge definiert. |
| brush | Brush | [`Brush`](../../brush) die die Farbe und Textur des gezeichneten Textes bestimmt. |
| point | PointF | [`PointF`](../../pointf) -Struktur, die die obere linke Ecke des gezeichneten Textes angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist Null. |

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

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, float, float, StringFormat) {#drawstring_5}

Zeichnet die angegebene Textzeichenfolge an der angegebenen Stelle mit dem angegebenen[`Brush`](../../brush) und[`Font`](../../font) Objekte mit den Formatierungsattributen der angegebenen[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, float x, float y, StringFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Schnur zum Zeichnen. |
| font | Font | [`Font`](../../font) die das Textformat der Zeichenfolge definiert. |
| brush | Brush | [`Brush`](../../brush) die die Farbe und Textur des gezeichneten Textes bestimmt. |
| x | Single | Die x-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| y | Single | Die y-Koordinate der oberen linken Ecke des gezeichneten Textes. |
| format | StringFormat | [`StringFormat`](../../stringformat) die Formatierungsattribute wie Zeilenabstand und Ausrichtung angibt, die auf den gezeichneten Text angewendet werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist Null. |

### Siehe auch

* class [Font](../../font)
* class [Brush](../../brush)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, PointF, StringFormat) {#drawstring_1}

Zeichnet die angegebene Textzeichenfolge an der angegebenen Stelle mit dem angegebenen[`Brush`](../../brush) und[`Font`](../../font) Objekte mit den Formatierungsattributen der angegebenen[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, PointF point, StringFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Schnur zum Zeichnen. |
| font | Font | [`Font`](../../font) die das Textformat der Zeichenfolge definiert. |
| brush | Brush | [`Brush`](../../brush) die die Farbe und Textur des gezeichneten Textes bestimmt. |
| point | PointF | [`PointF`](../../pointf) -Struktur, die die obere linke Ecke des gezeichneten Textes angibt. |
| format | StringFormat | [`StringFormat`](../../stringformat) die Formatierungsattribute wie Zeilenabstand und Ausrichtung angibt, die auf den gezeichneten Text angewendet werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist Null. |

### Siehe auch

* class [Font](../../font)
* class [Brush](../../brush)
* struct [PointF](../../pointf)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF) {#drawstring_2}

Zeichnet die angegebene Textzeichenfolge in das angegebene Rechteck mit dem angegebenen[`Brush`](../../brush) und[`Font`](../../font) Objekte.

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Schnur zum Zeichnen. |
| font | Font | [`Font`](../../font) die das Textformat der Zeichenfolge definiert. |
| brush | Brush | [`Brush`](../../brush) die die Farbe und Textur des gezeichneten Textes bestimmt. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) Struktur, die die Position des gezeichneten Textes angibt. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist Null. |

### Siehe auch

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

---

## DrawString(string, Font, Brush, RectangleF, StringFormat) {#drawstring_3}

Zeichnet die angegebene Textzeichenfolge in das angegebene Rechteck mit dem angegebenen[`Brush`](../../brush) und[`Font`](../../font) Objekte mit den Formatierungsattributen der angegebenen[`StringFormat`](../../stringformat) .

```csharp
public void DrawString(string s, Font font, Brush brush, RectangleF layoutRectangle, 
    StringFormat format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| s | String | Schnur zum Zeichnen. |
| font | Font | [`Font`](../../font) die das Textformat der Zeichenfolge definiert. |
| brush | Brush | [`Brush`](../../brush) die die Farbe und Textur des gezeichneten Textes bestimmt. |
| layoutRectangle | RectangleF | [`RectangleF`](../../rectanglef) Struktur, die die Position des gezeichneten Textes angibt. |
| format | StringFormat | [`StringFormat`](../../stringformat) die Formatierungsattribute wie Zeilenabstand und Ausrichtung angibt, die auf den gezeichneten Text angewendet werden. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist null. -oder- *s* ist null. -oder- *brush* ist Null. |

### Siehe auch

* class [Font](../../font)
* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [StringFormat](../../stringformat)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
