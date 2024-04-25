---
title: BmpImage
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonBmpImageaspose.imaging.fileformats.bmp/bmpimage Klasse.
type: docs
weight: 10
url: /de/aspose.imaging.fileformats.bmp/bmpimage/bmpimage/
---
## BmpImage(string) {#constructor_7}

Initialisiert eine neue Instanz von[`BmpImage`](../../bmpimage) Klasse.

```csharp
public BmpImage(string path)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zum Laden von Bildern und zum Initialisieren von Pixel- und Palettendaten. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Rasterbild ist null;rasterImage |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Die Höhe sollte positiv sein. |
| ArgumentException | Palette sollte für Bilder mit 8 Bit pro Pixel oder weniger angegeben werden.;palette |

### Beispiele

Das Beispiel zeigt, wie ein BmpImage aus einer Datei geladen wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein BMP-Bild aus einer Datei.
// Die Quellpixel werden bei Bedarf in das 32-bpp-Format konvertiert.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp"))
{
    // Führen Sie eine Bildverarbeitung durch.
    // In einer anderen BMP-Datei speichern.
    bmpImage.Save(dir + "sample.output.32bpp.bmp");
}
```

### Siehe auch

* class [BmpImage](../../bmpimage)
* namensraum [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Montage [Aspose.Imaging](../../../)

---

## BmpImage(string, ushort, BitmapCompression, double, double) {#constructor_8}

Initialisiert eine neue Instanz von[`BmpImage`](../../bmpimage) Klasse.

```csharp
public BmpImage(string path, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | String | Der Pfad zum Laden von Bildern und zum Initialisieren von Pixel- und Palettendaten. |
| bitsPerPixel | UInt16 | Die Bits pro Pixel. |
| compression | BitmapCompression | Die zu verwendende Komprimierung. |
| horizontalResolution | Double | Die horizontale Auflösung. Beachten Sie, dass aufgrund der Rundung die resultierende Auflösung geringfügig von der bestandenen abweichen kann. |
| verticalResolution | Double | Die vertikale Auflösung. Beachten Sie, dass aufgrund der Rundung die resultierende Auflösung geringfügig von der bestandenen abweichen kann. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Das Rasterbild darf nicht null;rasterImage sein |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Die Höhe sollte positiv sein. |
| ArgumentException | Palette sollte für Bilder mit 8 Bit pro Pixel oder weniger angegeben werden.;palette |

### Beispiele

Das Beispiel zeigt, wie ein BmpImage aus einer Datei mit der angegebenen Bittiefe und Auflösung geladen wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein BMP-Bild aus einer Datei.
// Die Quellpixel werden bei Bedarf in das 24-bpp-Format konvertiert.
// Die Auflösung wird auf 96 dpi gesetzt.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
    new Aspose.Imaging.FileFormats.Bmp.BmpImage(dir + "sample.bmp", 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    // Führen Sie eine Bildverarbeitung durch.
    // In einer anderen BMP-Datei speichern.
    bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
}
```

### Siehe auch

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* namensraum [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Montage [Aspose.Imaging](../../../)

---

## BmpImage(Stream) {#constructor_5}

Initialisiert eine neue Instanz von[`BmpImage`](../../bmpimage) Klasse.

```csharp
public BmpImage(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream zum Laden von Bildern und zum Initialisieren von Pixel- und Palettendaten. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Das Rasterbild darf nicht null;rasterImage sein |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Die Höhe sollte positiv sein. |
| ArgumentException | Palette sollte für Bilder mit 8 Bit pro Pixel oder weniger angegeben werden.;palette |

### Beispiele

Das Beispiel zeigt, wie ein BmpImage aus einem Dateistream geladen wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein BMP-Bild aus einem Dateistream.
// Die Quellpixel werden bei Bedarf in das 32-bpp-Format konvertiert.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream))
    {
        // Führen Sie eine Bildverarbeitung durch.
        // In einer anderen BMP-Datei speichern.
        bmpImage.Save(dir + "sample.output.32bpp.bmp");
    }
}
```

### Siehe auch

* class [BmpImage](../../bmpimage)
* namensraum [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Montage [Aspose.Imaging](../../../)

---

## BmpImage(Stream, ushort, BitmapCompression, double, double) {#constructor_6}

Initialisiert eine neue Instanz von[`BmpImage`](../../bmpimage) Klasse.

```csharp
public BmpImage(Stream stream, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream zum Laden von Bildern und zum Initialisieren von Pixel- und Palettendaten. |
| bitsPerPixel | UInt16 | Die Bits pro Pixel. |
| compression | BitmapCompression | Die zu verwendende Komprimierung. |
| horizontalResolution | Double | Die horizontale Auflösung. Beachten Sie, dass aufgrund der Rundung die resultierende Auflösung geringfügig von der bestandenen abweichen kann. |
| verticalResolution | Double | Die vertikale Auflösung. Beachten Sie, dass aufgrund der Rundung die resultierende Auflösung geringfügig von der bestandenen abweichen kann. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Das Rasterbild darf nicht null;rasterImage sein |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Die Höhe sollte positiv sein. |
| ArgumentException | Palette sollte für Bilder mit 8 Bit pro Pixel oder weniger angegeben werden.;palette |

### Beispiele

Das Beispiel zeigt, wie ein BmpImage aus einem Dateistream mit der angegebenen Bittiefe und Auflösung geladen wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein BMP-Bild aus einem Dateistream.
// Die Quellpixel werden bei Bedarf in das 24-bpp-Format konvertiert.
// Die Auflösung wird auf 96 dpi gesetzt.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage =
        new Aspose.Imaging.FileFormats.Bmp.BmpImage(stream, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // Führen Sie eine Bildverarbeitung durch.
        // In einer anderen BMP-Datei speichern.
        bmpImage.Save(dir + "sample.output.24bpp.96dpi.bmp");
    }
}
```

### Siehe auch

* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* namensraum [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Montage [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage) {#constructor}

Initialisiert eine neue Instanz von[`BmpImage`](../../bmpimage) Klasse.

```csharp
public BmpImage(RasterImage rasterImage)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | RasterImage | Das Bild, mit dem Pixel- und Palettendaten initialisiert werden sollen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Das Rasterbild darf nicht null;rasterImage sein |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Die Höhe sollte positiv sein. |
| ArgumentException | Palette sollte für Bilder mit 8 Bit pro Pixel oder weniger angegeben werden.;palette |

### Beispiele

Das Beispiel zeigt, wie ein BmpImage von einer anderen Instanz von RasterImage geladen wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Erstellen Sie ein neues PNG-Bild.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Das gesamte PNG-Bild rot füllen.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // Erstellen Sie ein BMP-Bild basierend auf dem PNG-Bild.
    // Die Quellpixel werden bei Bedarf in das 32-bpp-Format konvertiert.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage))
    {
        // In eine BMP-Datei speichern
        bmpImage.Save(dir + "output.32bpp.bmp");
    }
}
```

### Siehe auch

* class [RasterImage](../../../aspose.imaging/rasterimage)
* class [BmpImage](../../bmpimage)
* namensraum [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Montage [Aspose.Imaging](../../../)

---

## BmpImage(RasterImage, ushort, BitmapCompression, double, double) {#constructor_1}

Initialisiert eine neue Instanz von[`BmpImage`](../../bmpimage) Klasse.

```csharp
public BmpImage(RasterImage rasterImage, ushort bitsPerPixel, BitmapCompression compression, 
    double horizontalResolution, double verticalResolution)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | RasterImage | Das Bild, mit dem Pixel- und Palettendaten initialisiert werden sollen. |
| bitsPerPixel | UInt16 | Die Bits pro Pixel. |
| compression | BitmapCompression | Die zu verwendende Komprimierung. |
| horizontalResolution | Double | Die horizontale Auflösung. Beachten Sie, dass aufgrund der Rundung die resultierende Auflösung geringfügig von der bestandenen abweichen kann. |
| verticalResolution | Double | Die vertikale Auflösung. Beachten Sie, dass aufgrund der Rundung die resultierende Auflösung geringfügig von der bestandenen abweichen kann. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Das Rasterbild darf nicht null;rasterImage sein |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Die Höhe sollte positiv sein. |
| ArgumentException | Palette sollte für Bilder mit 8 Bit pro Pixel oder weniger angegeben werden.;palette |

### Beispiele

Das Beispiel zeigt, wie ein BmpImage von einer anderen Instanz von RasterImage mit der angegebenen Bittiefe und Komprimierung geladen wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Erstellen Sie ein neues PNG-Bild.
Aspose.Imaging.ImageOptions.PngOptions createOptions = new Aspose.Imaging.ImageOptions.PngOptions();
createOptions.Source = new Aspose.Imaging.Sources.StreamSource(new System.IO.MemoryStream(), true);
using (Aspose.Imaging.RasterImage rasterImage = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(createOptions, 100, 100))
{
    // Das gesamte PNG-Bild rot füllen.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(rasterImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, rasterImage.Bounds);

    // Erstellen Sie ein BMP-Bild basierend auf dem PNG-Bild.
    // Die Quellpixel werden bei Bedarf in das 24-bpp-Format konvertiert.
    // Die Auflösung wird auf 96 dpi gesetzt.
    using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(rasterImage, 24, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
    {
        // In eine BMP-Datei speichern
        bmpImage.Save(dir + "output.24bpp.96dpi.bmp");
    }
}
```

### Siehe auch

* class [RasterImage](../../../aspose.imaging/rasterimage)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* namensraum [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Montage [Aspose.Imaging](../../../)

---

## BmpImage(int, int) {#constructor_2}

Initialisiert eine neue Instanz von[`BmpImage`](../../bmpimage) Klasse.

```csharp
public BmpImage(int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | Int32 | Die Bildbreite. |
| height | Int32 | Die Bildhöhe. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Die Höhe sollte positiv sein. |
| ArgumentException | Palette sollte für Bilder mit 8 Bit pro Pixel oder weniger angegeben werden.;palette |

### Beispiele

Das Beispiel zeigt, wie ein BmpImage der angegebenen Größe erstellt wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Erstellen Sie ein 32-bpp-BMP-Bild mit 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Das gesamte Bild rot füllen.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    Aspose.Imaging.Brushes.SolidBrush brush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // In eine BMP-Datei speichern
    bmpImage.Save(dir + "output.bmp");
}
```

Das folgende Beispiel zeigt, wie ein BMP-Bild palettiert wird, um seine Ausgabegröße zu reduzieren.

```csharp
[C#]

// Erstellen Sie ein BMP-Bild 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100))
{
    // Der lineare Farbverlauf von der linken oberen zur rechten unteren Ecke des Bildes.
    Aspose.Imaging.Brushes.LinearGradientBrush brush =
        new Aspose.Imaging.Brushes.LinearGradientBrush(
            new Aspose.Imaging.Point(0, 0),
            new Aspose.Imaging.Point(bmpImage.Width, bmpImage.Height),
            Aspose.Imaging.Color.Red,
            Aspose.Imaging.Color.Green);

    // Füllen Sie das gesamte Bild mit dem linearen Verlaufspinsel.
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);
    gr.FillRectangle(brush, bmpImage.Bounds);

    // Holen Sie sich die nächste 8-Bit-Farbpalette, die so viele Pixel wie möglich abdeckt, um ein palettisiertes Bild zu erhalten
    // ist optisch kaum von einem nicht palettierten zu unterscheiden.
    Aspose.Imaging.IColorPalette palette = Aspose.Imaging.ColorPaletteHelper.GetCloseImagePalette(bmpImage, 256);

    // 8-Bit-Palette enthält höchstens 256 Farben.
    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
    saveOptions.Palette = palette;
    saveOptions.BitsPerPixel = 8;

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream, saveOptions);
        System.Console.WriteLine("The palettized image size is {0} bytes.", stream.Length);
    }

    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        bmpImage.Save(stream);
        System.Console.WriteLine("The non-palettized image size is {0} bytes.", stream.Length);
    }
}

// Die Ausgabe sieht so aus:
// Die palettierte Bildgröße beträgt 11078 Bytes.
// Die nicht palettierte Bildgröße beträgt 40054 Byte.
```

### Siehe auch

* class [BmpImage](../../bmpimage)
* namensraum [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Montage [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette) {#constructor_3}

Initialisiert eine neue Instanz von[`BmpImage`](../../bmpimage) Klasse.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | Int32 | Die Bildbreite. |
| height | Int32 | Die Bildhöhe. |
| bitsPerPixel | UInt16 | Die Bits pro Pixel. |
| palette | IColorPalette | Die Farbpalette. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Die Höhe sollte positiv sein. |
| ArgumentException | Palette sollte für Bilder mit 8 Bit pro Pixel oder weniger angegeben werden.;palette |

### Beispiele

Das Beispiel zeigt, wie ein BmpImage der angegebenen Größe mit der angegebenen Palette erstellt wird.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Erstellen Sie eine monochrome Palette, die nur rote und grüne Farben enthält.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// Erstellen Sie ein monochromes 1-bpp-BMP-Bild mit 100 x 100 px.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // Fülle die obere Hälfte des Bildes rot.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // Füllen Sie die untere Hälfte des Bildes grün.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // In BMP speichern
    bmpImage.Save(dir + "output.monochrome.bmp");
}
```

### Siehe auch

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [BmpImage](../../bmpimage)
* namensraum [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Montage [Aspose.Imaging](../../../)

---

## BmpImage(int, int, ushort, IColorPalette, BitmapCompression, double, double) {#constructor_4}

Initialisiert eine neue Instanz von[`BmpImage`](../../bmpimage) Klasse.

```csharp
public BmpImage(int width, int height, ushort bitsPerPixel, IColorPalette palette, 
    BitmapCompression compression, double horizontalResolution, double verticalResolution)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| width | Int32 | Die Bildbreite. |
| height | Int32 | Die Bildhöhe. |
| bitsPerPixel | UInt16 | Die Bits pro Pixel. |
| palette | IColorPalette | Die Farbpalette. |
| compression | BitmapCompression | Die zu verwendende Komprimierung. |
| horizontalResolution | Double | Die horizontale Auflösung. Beachten Sie, dass aufgrund der Rundung die resultierende Auflösung geringfügig von der bestandenen abweichen kann. |
| verticalResolution | Double | Die vertikale Auflösung. Beachten Sie, dass aufgrund der Rundung die resultierende Auflösung geringfügig von der bestandenen abweichen kann. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [BmpImageException](../../../aspose.imaging.coreexceptions.imageformats/bmpimageexception) | Die Höhe sollte positiv sein. |
| ArgumentException | Palette sollte für Bilder mit 8 Bit pro Pixel oder weniger angegeben werden.;palette |

### Beispiele

Das Beispiel zeigt, wie Sie mit verschiedenen Optionen ein BmpImage erstellen.

```csharp
[C#]

string dir = "c:\\temp\\";

Aspose.Imaging.Color[] paletterColors = new Aspose.Imaging.Color[]
{
    Aspose.Imaging.Color.Red,
    Aspose.Imaging.Color.Green,
};

// Erstellen Sie eine monochrome Palette, die nur rote und grüne Farben enthält.
Aspose.Imaging.IColorPalette palette = new Aspose.Imaging.ColorPalette(paletterColors);

// Erstellen Sie ein monochromes 1-bpp-BMP-Bild mit 100 x 100 px.
// Die horizontale und vertikale Auflösung wird auf 96 dpi gesetzt.
using (Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = new Aspose.Imaging.FileFormats.Bmp.BmpImage(100, 100, 1, palette, Aspose.Imaging.FileFormats.Bmp.BitmapCompression.Rgb, 96.0, 96.0))
{
    Aspose.Imaging.Graphics gr = new Aspose.Imaging.Graphics(bmpImage);

    // Fülle die obere Hälfte des Bildes rot.
    Aspose.Imaging.Brushes.SolidBrush redBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Red);
    gr.FillRectangle(redBrush, new Aspose.Imaging.Rectangle(0, 0, bmpImage.Width, bmpImage.Height / 2));

    // Füllen Sie die untere Hälfte des Bildes grün.
    Aspose.Imaging.Brushes.SolidBrush greenBrush = new Aspose.Imaging.Brushes.SolidBrush(Aspose.Imaging.Color.Green);
    gr.FillRectangle(greenBrush, new Aspose.Imaging.Rectangle(0, bmpImage.Height / 2, bmpImage.Width, bmpImage.Height / 2));

    // In eine BMP-Datei speichern
    bmpImage.Save(dir + "output.monochrome.96dpi.bmp");
}
```

### Siehe auch

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* enum [BitmapCompression](../../bitmapcompression)
* class [BmpImage](../../bmpimage)
* namensraum [Aspose.Imaging.FileFormats.Bmp](../../bmpimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
