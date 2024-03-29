---
title: Figure
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die Figur. Ein Behälter für Formen.
type: docs
weight: 1290
url: /de/net/aspose.imaging/figure/
---
## Figure class

Die Figur. Ein Behälter für Formen.

```csharp
public class Figure : ObjectWithBounds
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Figure](figure)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| override [Bounds](../../aspose.imaging/figure/bounds) { get; } | Ruft die Grenzen des Objekts ab oder legt sie fest. |
| [IsClosed](../../aspose.imaging/figure/isclosed) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob diese Figur geschlossen ist. Eine geschlossene Figur macht nur dann einen Unterschied, wenn die Formen der ersten und der letzten Figur fortlaufende Formen sind. In diesem Fall wird der erste Punkt der ersten Form durch eine gerade Linie mit dem letzten Punkt der letzten Form verbunden |
| [Segments](../../aspose.imaging/figure/segments) { get; } | Ruft die ganzen Figursegmente ab. |
| [Shapes](../../aspose.imaging/figure/shapes) { get; } | Ruft die Figurenformen ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddShape](../../aspose.imaging/figure/addshape)(Shape) | Fügt der Figur eine Form hinzu. |
| [AddShapes](../../aspose.imaging/figure/addshapes)(Shape[]) | Fügt der Figur eine Reihe von Formen hinzu. |
| override [GetBounds](../../aspose.imaging/figure/getbounds#getbounds)(Matrix) | Ruft die Grenzen des Objekts ab. |
| override [GetBounds](../../aspose.imaging/figure/getbounds#getbounds_1)(Matrix, Pen) | Ruft die Grenzen des Objekts ab. |
| [RemoveShape](../../aspose.imaging/figure/removeshape)(Shape) | Entfernt eine Form aus der Figur. |
| [RemoveShapes](../../aspose.imaging/figure/removeshapes)(Shape[]) | Entfernt eine Reihe von Formen aus der Figur. |
| [Reverse](../../aspose.imaging/figure/reverse)() | Kehrt die Reihenfolge dieser Figurformen und die Punktreihenfolge um. |
| override [Transform](../../aspose.imaging/figure/transform)(Matrix) | Wendet die angegebene Transformation auf die Form an. |

### Beispiele

Dieses Beispiel verwendet GraphicsPath und die Graphics-Klasse, um Figuren auf einer Bildoberfläche zu erstellen und zu manipulieren. Beispiel erstellt ein neues Bild (vom Typ Tiff), löscht die Oberfläche und zeichnet Pfade mit Hilfe der GraphicsPath-Klasse. Am Ende wird die DrawPath-Methode aufgerufen, die von der Graphics-Klasse bereitgestellt wird, um die Pfade auf der Oberfläche zu rendern.

```csharp
[C#]

//Eine Instanz von FileStream erstellen
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //Eine Instanz von TiffOptions erstellen und ihre verschiedenen Eigenschaften festlegen
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //Setzen Sie die Quelle für die Instanz von ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Eine Instanz von Image erstellen 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //Eine Instanz der Graphics-Klasse erstellen und initialisieren
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Grafikoberfläche löschen
        graphics.Clear(Color.Wheat);

        //Eine Instanz der GraphicsPath-Klasse erstellen
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //Eine Instanz der Figure-Klasse erstellen
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //Formen zum Figurobjekt hinzufügen
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //Figure-Objekt zu GraphicsPath hinzufügen
        graphicspath.AddFigure(figure);

        // Pfad mit Stiftobjekt der Farbe Schwarz zeichnen
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // Alle Änderungen speichern.
        image.Save();
    }
}
```

### Siehe auch

* class [ObjectWithBounds](../objectwithbounds)
* namensraum [Aspose.Imaging](../../aspose.imaging)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
