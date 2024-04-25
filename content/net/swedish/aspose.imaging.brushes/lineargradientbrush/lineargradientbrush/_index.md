---
title: LinearGradientBrush
second_title: Aspose.Imaging för .NET API-referens
description: Initierar en ny instans avLinearGradientBrushaspose.imaging.brushes/lineargradientbrush klass med standardparametrar. Startfärgen är svart slutfärgen är vit vinkeln är 45 grader och rektangeln är placerad i 00 med storlek 11.
type: docs
weight: 10
url: /sv/aspose.imaging.brushes/lineargradientbrush/lineargradientbrush/
---
## LinearGradientBrush() {#constructor}

Initierar en ny instans av[`LinearGradientBrush`](../../lineargradientbrush) klass med standardparametrar. Startfärgen är svart, slutfärgen är vit, vinkeln är 45 grader och rektangeln är placerad i (0,0) med storlek (1,1).

```csharp
public LinearGradientBrush()
```

### Se även

* class [LinearGradientBrush](../../lineargradientbrush)
* namnutrymme [Aspose.Imaging.Brushes](../../lineargradientbrush)
* hopsättning [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Point, Point, Color, Color) {#constructor_1}

Initierar en ny instans av[`LinearGradientBrush`](../../lineargradientbrush) klass med de angivna punkterna och färgerna.

```csharp
public LinearGradientBrush(Point point1, Point point2, Color color1, Color color2)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | Point | A[`Point`](../../../aspose.imaging/point) struktur som representerar startpunkten för den linjära gradienten. |
| point2 | Point | A[`Point`](../../../aspose.imaging/point) struktur som representerar slutpunkten för den linjära gradienten. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) struktur som representerar startfärgen för den linjära gradienten. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) struktur som representerar slutfärgen för den linjära gradienten. |

### Exempel

Följande exempel visar hur du skapar en gråskalekopia av en befintlig ram och lägger till den i en TIFF-bild.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.ImageOptions.TiffOptions createTiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

// Skapa en permanent, inte temporär filkälla.
createTiffOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(dir + "multipage.tif", false);
createTiffOptions.Photometric = Aspose.Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.Rgb;
createTiffOptions.BitsPerSample = new ushort[] { 8, 8, 8 };

using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Image.Create(createTiffOptions, 100, 100))
{
    // Den linjära gradienten från bildens övre vänstra hörn till det nedre högra hörnet.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(tiffImage.Width, tiffImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Fyll den aktiva ramen med en linjär gradientborste.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(tiffImage.ActiveFrame);
    gr.FillRectangle(brush, tiffImage.Bounds);

    // Alternativ för gråskala
    Aspose.Imaging.ImageOptions.TiffOptions createTiffFrameOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream());
    createTiffFrameOptions.Photometric = Imaging.FileFormats.Tiff.Enums.TiffPhotometrics.MinIsBlack;
    createTiffFrameOptions.BitsPerSample = new ushort[] { 8 };

    // Skapa en gråskalekopia av den aktiva ramen.
    // Pixeldata bevaras men konverteras till önskat format.
    Aspose.Imaging.FileFormats.Tiff.TiffFrame grayscaleFrame = Aspose.Imaging.FileFormats.Tiff.TiffFrame.CreateFrameFrom(tiffImage.ActiveFrame, createTiffFrameOptions);

    // Lägg till den nyskapade ramen till TIFF-bilden.
    tiffImage.AddFrame(grayscaleFrame);

    tiffImage.Save();
}
```

### Se även

* struct [Point](../../../aspose.imaging/point)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namnutrymme [Aspose.Imaging.Brushes](../../lineargradientbrush)
* hopsättning [Aspose.Imaging](../../../)

---

## LinearGradientBrush(PointF, PointF, Color, Color) {#constructor_2}

Initierar en ny instans av[`LinearGradientBrush`](../../lineargradientbrush) klass med de angivna punkterna och färgerna.

```csharp
public LinearGradientBrush(PointF point1, PointF point2, Color color1, Color color2)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| point1 | PointF | A[`PointF`](../../../aspose.imaging/pointf) struktur som representerar startpunkten för den linjära gradienten. |
| point2 | PointF | A[`PointF`](../../../aspose.imaging/pointf) struktur som representerar slutpunkten för den linjära gradienten. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) struktur som representerar startfärgen för den linjära gradienten. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) struktur som representerar slutfärgen för den linjära gradienten. |

### Se även

* struct [PointF](../../../aspose.imaging/pointf)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namnutrymme [Aspose.Imaging.Brushes](../../lineargradientbrush)
* hopsättning [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float) {#constructor_3}

Initierar en ny instans av[`LinearGradientBrush`](../../lineargradientbrush) klass baserad på en rektangel, start- och slutfärger och en orienteringsvinkel.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | A[`RectangleF`](../../../aspose.imaging/rectanglef) struktur som specificerar gränserna för den linjära gradienten. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) struktur som representerar startfärgen för gradienten. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) struktur som representerar slutfärgen för gradienten. |
| angle | Single | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |

### Se även

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namnutrymme [Aspose.Imaging.Brushes](../../lineargradientbrush)
* hopsättning [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float) {#constructor_5}

Initierar en ny instans av[`LinearGradientBrush`](../../lineargradientbrush) klass baserad på en rektangel, start- och slutfärger och en orienteringsvinkel.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | RectangleF | A[`RectangleF`](../../../aspose.imaging/rectanglef) struktur som specificerar gränserna för den linjära gradienten. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) struktur som representerar startfärgen för gradienten. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) struktur som representerar slutfärgen för gradienten. |
| angle | Single | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |

### Se även

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namnutrymme [Aspose.Imaging.Brushes](../../lineargradientbrush)
* hopsättning [Aspose.Imaging](../../../)

---

## LinearGradientBrush(Rectangle, Color, Color, float, bool) {#constructor_4}

Initierar en ny instans av[`LinearGradientBrush`](../../lineargradientbrush) klass baserad på en rektangel, start- och slutfärger och en orienteringsvinkel.

```csharp
public LinearGradientBrush(Rectangle rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rectangle | A[`RectangleF`](../../../aspose.imaging/rectanglef) struktur som specificerar gränserna för den linjära gradienten. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) struktur som representerar startfärgen för gradienten. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) struktur som representerar slutfärgen för gradienten. |
| angle | Single | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |
| isAngleScalable | Boolean | om inställt på`Sann` vinkeln ändras vid transformationer med detta[`LinearGradientBrush`](../../lineargradientbrush). |

### Se även

* struct [Rectangle](../../../aspose.imaging/rectangle)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namnutrymme [Aspose.Imaging.Brushes](../../lineargradientbrush)
* hopsättning [Aspose.Imaging](../../../)

---

## LinearGradientBrush(RectangleF, Color, Color, float, bool) {#constructor_6}

Initierar en ny instans av[`LinearGradientBrush`](../../lineargradientbrush) klass baserad på en rektangel, start- och slutfärger och en orienteringsvinkel.

```csharp
public LinearGradientBrush(RectangleF rect, Color color1, Color color2, float angle, 
    bool isAngleScalable)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | RectangleF | A[`RectangleF`](../../../aspose.imaging/rectanglef) struktur som specificerar gränserna för den linjära gradienten. |
| color1 | Color | A[`Color`](../../../aspose.imaging/color) struktur som representerar startfärgen för gradienten. |
| color2 | Color | A[`Color`](../../../aspose.imaging/color) struktur som representerar slutfärgen för gradienten. |
| angle | Single | Vinkeln, mätt i grader medurs från x-axeln, för gradientens orienteringslinje. |
| isAngleScalable | Boolean | om inställt på`Sann` vinkeln ändras vid transformationer med detta[`LinearGradientBrush`](../../lineargradientbrush). |

### Se även

* struct [RectangleF](../../../aspose.imaging/rectanglef)
* struct [Color](../../../aspose.imaging/color)
* class [LinearGradientBrush](../../lineargradientbrush)
* namnutrymme [Aspose.Imaging.Brushes](../../lineargradientbrush)
* hopsättning [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
