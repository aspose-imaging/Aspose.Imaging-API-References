---
title: Pen
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonPenaspose.imaging/pen Klasse mit der angegebenen Farbe.
type: docs
weight: 10
url: /de/net/aspose.imaging/pen/pen/
---
## Pen(Color) {#constructor_2}

Initialisiert eine neue Instanz von[`Pen`](../../pen) Klasse mit der angegebenen Farbe.

```csharp
public Pen(Color color)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | Color | EIN[`Color`](../color) Struktur, die die Farbe davon anzeigt[`Pen`](../../pen). |

### Siehe auch

* struct [Color](../../color)
* class [Pen](../../pen)
* namensraum [Aspose.Imaging](../../pen)
* Montage [Aspose.Imaging](../../../)

---

## Pen(Color, float) {#constructor_3}

Initialisiert eine neue Instanz von[`Pen`](../../pen) Klasse mit den angegebenen[`Color`](../color) und[`Width`](../width) Eigenschaften.

```csharp
public Pen(Color color, float width)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | Color | EIN[`Color`](../color) Struktur, die die Farbe davon anzeigt[`Pen`](../../pen). |
| width | Single | Ein Wert, der die Breite davon angibt[`Pen`](../../pen). |

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

* struct [Color](../../color)
* class [Pen](../../pen)
* namensraum [Aspose.Imaging](../../pen)
* Montage [Aspose.Imaging](../../../)

---

## Pen(Brush) {#constructor}

Initialisiert eine neue Instanz von[`Pen`](../../pen) Klasse mit den angegebenen[`Brush`](../brush) .

```csharp
public Pen(Brush brush)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | Brush | EIN[`Brush`](../brush) das bestimmt die Fülleigenschaften davon[`Pen`](../../pen). |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist Null. |

### Siehe auch

* class [Brush](../../brush)
* class [Pen](../../pen)
* namensraum [Aspose.Imaging](../../pen)
* Montage [Aspose.Imaging](../../../)

---

## Pen(Brush, float) {#constructor_1}

Initialisiert eine neue Instanz von[`Pen`](../../pen) Klasse mit den angegebenen[`Brush`](../brush) und[`Width`](../width) .

```csharp
public Pen(Brush brush, float width)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brush | Brush | EIN[`Brush`](../brush) das bestimmt die Eigenschaften davon[`Pen`](../../pen). |
| width | Single | Die Breite des Neuen[`Pen`](../../pen). |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *brush* ist Null. |

### Siehe auch

* class [Brush](../../brush)
* class [Pen](../../pen)
* namensraum [Aspose.Imaging](../../pen)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
