---
title: StreamSource
second_title: Aspose.Imaging für .NET-API-Referenz
description: Repräsentiert eine Stream-Quelle.
type: docs
weight: 11110
url: /de/aspose.imaging.sources/streamsource/
---
## StreamSource class

Repräsentiert eine Stream-Quelle.

```csharp
public sealed class StreamSource : Source
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [StreamSource](streamsource#constructor)(Stream) | Initialisiert eine neue Instanz von[`StreamSource`](../streamsource) Klasse. |
| [StreamSource](streamsource#constructor_1)(Stream, bool) | Initialisiert eine neue Instanz von[`StreamSource`](../streamsource) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DisposeStream](../../aspose.imaging.sources/streamsource/disposestream) { get; } | Ruft einen Wert ab, der angibt, ob der Stream verworfen werden soll, wenn der Container verworfen wird. |
| [Stream](../../aspose.imaging.sources/streamsource/stream) { get; } | Ruft den Stream ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [GetStreamContainer](../../aspose.imaging.sources/streamsource/getstreamcontainer)() | Ruft den Stream-Container ab. |

### Beispiele

Dieses Beispiel zeigt die Verwendung von System.IO.Stream zum Erstellen einer neuen Bilddatei (ein JPEG-Typ).

```csharp
[C#]

//Erzeugt eine Instanz von JpegOptions und setzt ihre verschiedenen Eigenschaften
Aspose.Imaging.ImageOptions.JpegOptions jpegOptions = new Aspose.Imaging.ImageOptions.JpegOptions();

//Eine Instanz von System.IO.Stream erstellen
System.IO.Stream stream = new System.IO.FileStream(@"C:\temp\sample.jpeg", System.IO.FileMode.Create);

//Definieren Sie die Quelleigenschaft für die Instanz von JPEGOptions
//Der zweite boolesche Parameter bestimmt, ob der Stream verworfen wird, sobald er den Gültigkeitsbereich verlässt
jpegOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream, true);

//Erzeugt eine Instanz von Image und ruft die Create-Methode mit JpegOptions als Parameter auf, um das Image-Objekt zu initialisieren   
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(jpegOptions, 500, 500))
{
    // Bildverarbeitung durchführen
}
```

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

* class [Source](../../aspose.imaging/source)
* namensraum [Aspose.Imaging.Sources](../../aspose.imaging.sources)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
