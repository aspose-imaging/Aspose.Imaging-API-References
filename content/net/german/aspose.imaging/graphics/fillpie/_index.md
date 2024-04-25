---
title: FillPie
second_title: Aspose.Imaging für .NET-API-Referenz
description: Füllt das Innere eines Tortenabschnitts der durch eine durch a angegebene Ellipse definiert istRectangleFaspose.imaging/rectanglef Struktur und zwei radiale Linien.
type: docs
weight: 370
url: /de/aspose.imaging/graphics/fillpie/
---
## FillPie(Brush, Rectangle, float, float) {#fillpie}

Füllt das Innere eines Tortenabschnitts, der durch eine durch a angegebene Ellipse definiert ist[`RectangleF`](../../rectanglef) Struktur und zwei radiale Linien.

```csharp
public void FillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) die die Eigenschaften der Füllung bestimmt. |
| rect | Rectangle | [`Rectangle`](../../rectangle)-Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der der Kreisabschnitt stammt. |
| startAngle | Single | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zur ersten Seite des Tortenabschnitts. |
| sweepAngle | Single | Winkel in Grad im Uhrzeigersinn gemessen von der*startAngle* -Parameter auf die zweite Seite des Tortenabschnitts. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist Null. |

### Beispiele

Das folgende Beispiel zeigt, wie Sie aus einzelnen GIF-Blöcken ein animiertes GIF-Bild zusammenstellen.

```csharp
[C#]

string dir = "c:\\temp\\";

// Erstellen Sie ein GIF-Bild 100 x 100 px.
// Der erste Block ist standardmäßig komplett schwarz.
using (Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock firstBlock = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100))
using (Aspose.Imaging.FileFormats.Gif.GifImage gifImage = new Aspose.Imaging.FileFormats.Gif.GifImage(firstBlock))
{
    // Der erste Kreis ist rot
    Aspose.Imaging.Brushes.SolidBrush brush1 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);

    // Der zweite Kreis ist schwarz
    Aspose.Imaging.Brushes.SolidBrush brush2 = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Black);

    // Erhöhen Sie allmählich den Winkel der roten Bogenform.
    for (int angle = 10; angle <= 360; angle += 10)
    {
        Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock block = new Aspose.Imaging.FileFormats.Gif.Blocks.GifFrameBlock(100, 100);

        Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(block);
        gr.FillPie(brush1, block.Bounds, 0, angle);

        gifImage.AddBlock(block);
    }

    // Erhöhen Sie allmählich den Winkel des schwarzen Bogens und löschen Sie den roten Bogen.
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

### Siehe auch

* class [Brush](../../brush)
* struct [Rectangle](../../rectangle)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

---

## FillPie(Brush, RectangleF, float, float) {#fillpie_1}

Füllt das Innere eines Tortenabschnitts, der durch eine durch a angegebene Ellipse definiert ist[`RectangleF`](../../rectanglef) Struktur und zwei radiale Linien.

```csharp
public void FillPie(Brush brush, RectangleF rect, float startAngle, float sweepAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) die die Eigenschaften der Füllung bestimmt. |
| rect | RectangleF | [`RectangleF`](../../rectanglef)-Struktur, die das Begrenzungsrechteck darstellt, das die Ellipse definiert, aus der der Kreisabschnitt stammt. |
| startAngle | Single | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zur ersten Seite des Tortenabschnitts. |
| sweepAngle | Single | Winkel in Grad im Uhrzeigersinn gemessen von der*startAngle* -Parameter auf die zweite Seite des Tortenabschnitts. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist Null. |

### Siehe auch

* class [Brush](../../brush)
* struct [RectangleF](../../rectanglef)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

---

## FillPie(Brush, float, float, float, float, float, float) {#fillpie_3}

Füllt das Innere eines Tortenabschnitts, der durch eine Ellipse definiert ist, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei radiale Linien angegeben wird.

```csharp
public void FillPie(Brush brush, float x, float y, float width, float height, float startAngle, 
    float sweepAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) die die Eigenschaften der Füllung bestimmt. |
| x | Single | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kreisabschnitt stammt. |
| y | Single | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kreisabschnitt stammt. |
| width | Single | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kreisabschnitt stammt. |
| height | Single | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Tortenabschnitt stammt. |
| startAngle | Single | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zur ersten Seite des Tortenabschnitts. |
| sweepAngle | Single | Winkel in Grad im Uhrzeigersinn gemessen von der*startAngle* -Parameter auf die zweite Seite des Tortenabschnitts. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist Null. |

### Siehe auch

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

---

## FillPie(Brush, int, int, int, int, int, int) {#fillpie_2}

Füllt das Innere eines Tortenabschnitts, der durch eine Ellipse definiert ist, die durch ein Koordinatenpaar, eine Breite, eine Höhe und zwei radiale Linien angegeben wird.

```csharp
public void FillPie(Brush brush, int x, int y, int width, int height, int startAngle, 
    int sweepAngle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | Brush | [`Brush`](../../brush) die die Eigenschaften der Füllung bestimmt. |
| x | Int32 | Die x-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kreisabschnitt stammt. |
| y | Int32 | Die y-Koordinate der oberen linken Ecke des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kreisabschnitt stammt. |
| width | Int32 | Breite des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Kreisabschnitt stammt. |
| height | Int32 | Höhe des Begrenzungsrechtecks, das die Ellipse definiert, aus der der Tortenabschnitt stammt. |
| startAngle | Int32 | Winkel in Grad, gemessen im Uhrzeigersinn von der x-Achse zur ersten Seite des Tortenabschnitts. |
| sweepAngle | Int32 | Winkel in Grad im Uhrzeigersinn gemessen von der*startAngle* -Parameter auf die zweite Seite des Tortenabschnitts. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist Null. |

### Siehe auch

* class [Brush](../../brush)
* class [Graphics](../../graphics)
* namensraum [Aspose.Imaging](../../graphics)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
