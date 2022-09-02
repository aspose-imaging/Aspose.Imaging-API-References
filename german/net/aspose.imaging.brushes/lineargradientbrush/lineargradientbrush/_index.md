---
title: LinearGradientBrush
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonLinearGradientBrushaspose.imaging.brushes/lineargradientbrush Klasse mit Standardparametern. Die Startfarbe ist Schwarz die Endfarbe Weiß der Winkel beträgt 45 Grad und das Rechteck befindet sich in 00 mit der Größe 11.
type: docs
weight: 10
url: /de/net/aspose.imaging.brushes/lineargradientbrush/lineargradientbrush/
---
## LinearGradientBrush() {#constructor}

Initialisiert eine neue Instanz von[`LinearGradientBrush`](../../lineargradientbrush) Klasse mit Standardparametern. Die Startfarbe ist Schwarz, die Endfarbe Weiß, der Winkel beträgt 45 Grad und das Rechteck befindet sich in (0,0) mit der Größe (1,1).

```csharp
public LinearGradientBrush()
```

### Siehe auch

* class [LinearGradientBrush](../../lineargradientbrush)
* namensraum [Aspose.Imaging.Brushes](../../lineargradientbrush)
* Montage [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Point, Point, Color, Color) {#constructor_1}

Initialisiert eine neue Instanz von[`LinearGradientBrush`](../../lineargradientbrush) Klasse mit den angegebenen Punkten und Farben.

```csharp
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | Point | EIN[`Point`](../../../aspose.imaging/point) Struktur, die den Startpunkt des linearen Gradienten darstellt. |
| point2 | Point | EIN[`Point`](../../../aspose.imaging/point) Struktur, die den Endpunkt des linearen Farbverlaufs darstellt. |
| color1 | Color | EIN[`Color`](../../../aspose.imaging/color) Struktur, die die Startfarbe des linearen Farbverlaufs darstellt. |
| color2 | Color | EIN[`Color`](../../../aspose.imaging/color) Struktur, die die Endfarbe des linearen Farbverlaufs darstellt. |

### Beispiele

Das folgende Beispiel zeigt, wie Sie eine Graustufenkopie eines vorhandenen Rahmens erstellen und einem TIFF-Bild hinzufügen.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Erstellen Sie eine permanente, nicht temporäre Dateiquelle.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Der lineare Farbverlauf von der linken oberen zur rechten unteren Ecke des Bildes.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Den aktiven Rahmen mit einem linearen Verlaufspinsel füllen.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Graustufenoptionen
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // Erstellen Sie eine Graustufenkopie des aktiven Frames.
    // Die Pixeldaten bleiben erhalten, werden aber in das gewünschte Format konvertiert.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // Fügen Sie den neu erstellten Rahmen zum TIFF-Bild hinzu.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

### Siehe auch

* struct [Point](../../../aspose.imaging/point)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namensraum [Aspose.Imaging.Brushes](../../lineargradientbrush)
* Montage [Aspose.Imaging](../../../)

---

## LinearGradientBrush(PointF, PointF, Color, Color) {#constructor_2}

Initialisiert eine neue Instanz von[`LinearGradientBrush`](../../lineargradientbrush) Klasse mit den angegebenen Punkten und Farben.

```csharp
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| point1 | PointF | EIN[`PointF`](../../../aspose.imaging/pointf) Struktur, die den Startpunkt des linearen Gradienten darstellt. |
| point2 | PointF | EIN[`PointF`](../../../aspose.imaging/pointf) Struktur, die den Endpunkt des linearen Farbverlaufs darstellt. |
| color1 | Color | EIN[`Color`](../../../aspose.imaging/color) Struktur, die die Startfarbe des linearen Farbverlaufs darstellt. |
| color2 | Color | EIN[`Color`](../../../aspose.imaging/color) Struktur, die die Endfarbe des linearen Farbverlaufs darstellt. |

### Siehe auch

* struct [PointF](../../../aspose.imaging/pointf)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namensraum [Aspose.Imaging.Brushes](../../lineargradientbrush)
* Montage [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float) {#constructor_3}

Initialisiert eine neue Instanz von[`LinearGradientBrush`](../../lineargradientbrush) Klasse basierend auf einem Rechteck, Start- und Endfarben und einem Ausrichtungswinkel.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | EIN[`RectangleF`](../../../aspose.imaging/rectanglef) Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| color1 | Color | EIN[`Color`](../../../aspose.imaging/color) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | Color | EIN[`Color`](../../../aspose.imaging/color) Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| angle | Single | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |

### Siehe auch

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namensraum [Aspose.Imaging.Brushes](../../lineargradientbrush)
* Montage [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float) {#constructor_5}

Initialisiert eine neue Instanz von[`LinearGradientBrush`](../../lineargradientbrush) Klasse basierend auf einem Rechteck, Start- und Endfarben und einem Ausrichtungswinkel.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | RectangleF | EIN[`RectangleF`](../../../aspose.imaging/rectanglef) Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| color1 | Color | EIN[`Color`](../../../aspose.imaging/color) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | Color | EIN[`Color`](../../../aspose.imaging/color) Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| angle | Single | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |

### Siehe auch

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namensraum [Aspose.Imaging.Brushes](../../lineargradientbrush)
* Montage [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float, bool) {#constructor_4}

Initialisiert eine neue Instanz von[`LinearGradientBrush`](../../lineargradientbrush) Klasse basierend auf einem Rechteck, Start- und Endfarben und einem Ausrichtungswinkel.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | Rectangle | EIN[`RectangleF`](../../../aspose.imaging/rectanglef) Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| color1 | Color | EIN[`Color`](../../../aspose.imaging/color) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | Color | EIN[`Color`](../../../aspose.imaging/color) Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| angle | Single | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |
| isAngleScalable | Boolean | wenn eingestellt`Stimmt` damit wird der Winkel bei Transformationen verändert[`LinearGradientBrush`](../../lineargradientbrush). |

### Siehe auch

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namensraum [Aspose.Imaging.Brushes](../../lineargradientbrush)
* Montage [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float, bool) {#constructor_6}

Initialisiert eine neue Instanz von[`LinearGradientBrush`](../../lineargradientbrush) Klasse basierend auf einem Rechteck, Start- und Endfarben und einem Ausrichtungswinkel.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rect | RectangleF | EIN[`RectangleF`](../../../aspose.imaging/rectanglef) Struktur, die die Grenzen des linearen Farbverlaufs angibt. |
| color1 | Color | EIN[`Color`](../../../aspose.imaging/color) Struktur, die die Startfarbe für den Farbverlauf darstellt. |
| color2 | Color | EIN[`Color`](../../../aspose.imaging/color) Struktur, die die Endfarbe für den Farbverlauf darstellt. |
| angle | Single | Der Winkel, gemessen in Grad im Uhrzeigersinn von der x-Achse, der Orientierungslinie des Farbverlaufs. |
| isAngleScalable | Boolean | wenn eingestellt`Stimmt` damit wird der Winkel bei Transformationen verändert[`LinearGradientBrush`](../../lineargradientbrush). |

### Siehe auch

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namensraum [Aspose.Imaging.Brushes](../../lineargradientbrush)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
