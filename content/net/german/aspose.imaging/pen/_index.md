---
title: Pen
second_title: Aspose.Imaging für .NET-API-Referenz
description: Definiert ein Objekt zum Zeichnen von Linien Kurven und Figuren.
type: docs
weight: 10690
url: /de/aspose.imaging/pen/
---
## Pen class

Definiert ein Objekt zum Zeichnen von Linien, Kurven und Figuren.

```csharp
public class Pen : TransparencySupporter
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [Pen](pen#constructor)(Brush) | Initialisiert eine neue Instanz von[`Pen`](../pen) Klasse mit den angegebenen[`Brush`](./brush) . |
| [Pen](pen#constructor_2)(Color) | Initialisiert eine neue Instanz von[`Pen`](../pen) Klasse mit der angegebenen Farbe. |
| [Pen](pen#constructor_1)(Brush, float) | Initialisiert eine neue Instanz von[`Pen`](../pen) Klasse mit den angegebenen[`Brush`](./brush) und[`Width`](./width) . |
| [Pen](pen#constructor_3)(Color, float) | Initialisiert eine neue Instanz von[`Pen`](../pen) Klasse mit den angegebenen[`Color`](./color) und[`Width`](./width) Eigenschaften. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Alignment](../../aspose.imaging/pen/alignment) { get; set; } | Holt oder setzt die Ausrichtung dafür[`Pen`](../pen) . |
| [Brush](../../aspose.imaging/pen/brush) { get; set; } | Ruft ab oder setzt die[`Brush`](./brush) das bestimmt Attribute davon[`Pen`](../pen) . |
| [Color](../../aspose.imaging/pen/color) { get; set; } | Holt oder setzt die Farbe davon[`Pen`](../pen) . |
| [CompoundArray](../../aspose.imaging/pen/compoundarray) { get; set; } | Ruft ein Array von Werten ab oder legt es fest, das einen zusammengesetzten Stift angibt. Ein zusammengesetzter Stift zeichnet eine zusammengesetzte Linie aus parallelen Linien und Zwischenräumen. |
| [CustomEndCap](../../aspose.imaging/pen/customendcap) { get; set; } | Ruft eine benutzerdefinierte Obergrenze ab oder legt sie fest, die am Ende der damit gezeichneten Linien verwendet wird[`Pen`](../pen) . |
| [CustomStartCap](../../aspose.imaging/pen/customstartcap) { get; set; } | Ruft eine benutzerdefinierte Obergrenze ab oder legt sie fest, die am Anfang der damit gezeichneten Linien verwendet wird[`Pen`](../pen) . |
| [DashCap](../../aspose.imaging/pen/dashcap) { get; set; } | Ermittelt oder setzt den Kappenstil, der am Ende der Bindestriche verwendet wird, aus denen die damit gezeichneten gestrichelten Linien bestehen[`Pen`](../pen) . |
| [DashOffset](../../aspose.imaging/pen/dashoffset) { get; set; } | Ruft den Abstand vom Anfang einer Linie zum Anfang eines Strichmusters ab oder legt ihn fest. |
| [DashPattern](../../aspose.imaging/pen/dashpattern) { get; set; } | Ruft ein Array benutzerdefinierter Bindestriche und Leerzeichen ab oder legt es fest. |
| [DashStyle](../../aspose.imaging/pen/dashstyle) { get; set; } | Ermittelt oder setzt den Stil, der für damit gezeichnete gestrichelte Linien verwendet wird[`Pen`](../pen) . |
| [EndCap](../../aspose.imaging/pen/endcap) { get; set; } | Ermittelt oder setzt den Kappenstil, der am Ende der damit gezeichneten Linien verwendet wird[`Pen`](../pen) . |
| [LineJoin](../../aspose.imaging/pen/linejoin) { get; set; } | Ermittelt oder setzt den Verbindungsstil für die Enden zweier aufeinanderfolgender Linien, die damit gezeichnet werden[`Pen`](../pen) . |
| [MiterLimit](../../aspose.imaging/pen/miterlimit) { get; set; } | Ruft die Grenze der Dicke der Verbindung an einer Gehrungsecke ab oder legt sie fest. |
| [Opacity](../../aspose.imaging/transparencysupporter/opacity) { get; set; } | Ruft die Deckkraft des Objekts ab oder legt sie fest. Der Wert sollte zwischen 0 und 1 liegen. Der Wert 0 bedeutet, dass das Objekt vollständig sichtbar ist, der Wert 1 bedeutet, dass das Objekt vollständig undurchsichtig ist. |
| [PenType](../../aspose.imaging/pen/pentype) { get; } | Ruft den Stil der damit gezeichneten Linien ab[`Pen`](../pen) . |
| [StartCap](../../aspose.imaging/pen/startcap) { get; set; } | Ermittelt oder setzt den Kappenstil, der am Anfang der damit gezeichneten Linien verwendet wird[`Pen`](../pen) . |
| [Transform](../../aspose.imaging/pen/transform) { get; set; } | Holt oder setzt eine Kopie der geometrischen Transformation dafür[`Pen`](../pen) . |
| [Width](../../aspose.imaging/pen/width) { get; set; } | Holt oder setzt die Breite davon[`Pen`](../pen) , in Einheiten des Graphics-Objekts, das zum Zeichnen verwendet wird. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform)(Matrix) | Multipliziert dazu die Transformationsmatrix[`Pen`](../pen) durch die angegebenen[`Matrix`](../matrix) . |
| [MultiplyTransform](../../aspose.imaging/pen/multiplytransform#multiplytransform_1)(Matrix, MatrixOrder) | Multipliziert dazu die Transformationsmatrix[`Pen`](../pen) durch die angegebenen[`Matrix`](../matrix) in der angegebenen Reihenfolge. |
| [ResetTransform](../../aspose.imaging/pen/resettransform)() | Setzt hierfür die geometrische Transformationsmatrix zurück[`Pen`](../pen) zur Identität. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform)(float) | Dreht die lokale geometrische Transformation um den angegebenen Winkel. Diese Methode stellt die Rotation der Transformation voran. |
| [RotateTransform](../../aspose.imaging/pen/rotatetransform#rotatetransform_1)(float, MatrixOrder) | Dreht die lokale geometrische Transformation um den angegebenen Winkel in der angegebenen Reihenfolge. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform)(float, float) | Skaliert die lokale geometrische Transformation um die angegebenen Faktoren. Diese Methode stellt der Transformation die Skalierungsmatrix voran. |
| [ScaleTransform](../../aspose.imaging/pen/scaletransform#scaletransform_1)(float, float, MatrixOrder) | Skaliert die lokale geometrische Transformation um die angegebenen Faktoren in der angegebenen Reihenfolge. |
| [SetLineCap](../../aspose.imaging/pen/setlinecap)(LineCap, LineCap, DashCap) | Legt die Werte fest, die den Stil der Kappe bestimmen, der verwendet wird, um damit gezeichnete Linien zu beenden[`Pen`](../pen) . |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform)(float, float) | Verschiebt die lokale geometrische Transformation um die angegebenen Maße. Diese Methode stellt die Übersetzung der Transformation voran. |
| [TranslateTransform](../../aspose.imaging/pen/translatetransform#translatetransform_1)(float, float, MatrixOrder) | Verschiebt die lokale geometrische Transformation um die angegebenen Dimensionen in der angegebenen Reihenfolge. |

### Beispiele

Dieses Beispiel zeigt die Erstellung und Verwendung von Pen-Objekten. Das Beispiel erstellt ein neues Bild und zeichnet Rechtecke auf der Bildoberfläche.

```csharp
[C#]

//Eine Instanz von BmpOptions erstellen und ihre verschiedenen Eigenschaften festlegen
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Eine Instanz von FileCreateSource erstellen und als Quelle für die Instanz von BmpOptions zuweisen
//Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei Temporär ist oder nicht
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\sample.bmp", false);

//Eine Instanz von Image im angegebenen Pfad erstellen
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    //Eine Instanz von Graphics erstellen und mit dem Image-Objekt initialisieren
    Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

    //Löschen Sie die Grafikoberfläche mit weißer Farbe
    graphics.Clear(Aspose.Imaging.Color.White);

    // Erstellen Sie eine Instanz von Pen mit der Farbe Rot und der Breite 5
    Aspose.Imaging.Pen pen = new Aspose.Imaging.Pen(Aspose.Imaging.Color.Red, 5f);

    //Eine Instanz von HatchBrush erstellen und ihre Eigenschaften festlegen
    Aspose.Imaging.Brushes.HatchBrush brush = new Aspose.Imaging.Brushes.HatchBrush();
    brush.BackgroundColor = Aspose.Imaging.Color.Wheat;
    brush.ForegroundColor = Aspose.Imaging.Color.Red;

    //Eine Instanz von Pen erstellen
    // mit HatchBrush-Objekt und -Breite initialisieren
    Aspose.Imaging.Pen brusedpen = new Pen(brush, 5);

    //Zeichne Rechtecke durch Angabe des Pen-Objekts
    graphics.DrawRectangles(pen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(210, 210), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 310), new Aspose.Imaging.Size(100, 100))
    });

    //Zeichne Rechtecke durch Angabe des Pen-Objekts
    graphics.DrawRectangles(brusedpen, new[]
    {
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(310, 110), new Aspose.Imaging.Size(100, 100)),
        new Aspose.Imaging.Rectangle(new Aspose.Imaging.Point(110, 310), new Aspose.Imaging.Size(100, 100))
    });

    // Alle Änderungen speichern.
    image.Save();
}
```

### Siehe auch

* class [TransparencySupporter](../transparencysupporter)
* namensraum [Aspose.Imaging](../../aspose.imaging)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
