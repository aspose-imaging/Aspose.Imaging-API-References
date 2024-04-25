---
title: Save
second_title: Aspose.Imaging für .NET-API-Referenz
description: Speichert die Bilddaten im zugrunde liegenden Stream.
type: docs
weight: 240
url: /de/aspose.imaging/image/save/
---
## Save() {#save}

Speichert die Bilddaten im zugrunde liegenden Stream.

```csharp
public void Save()
```

### Beispiele

Das folgende Beispiel zeigt, wie ein ganzes BMP-Bild oder ein Teil davon in einer Datei oder einem Stream gespeichert wird.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Konvertiere in ein Schwarz-Weiß-Bild
    bmpImage.BinarizeOtsu();

    // Am selben Ort mit Standardoptionen speichern.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Eine Palette enthält nur zwei Farben: in diesem Fall Schwarz und Weiß.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Für alle monochromen Bilder (einschließlich Schwarz-Weiß-Bilder) reicht es aus, 1 Bit pro Pixel zuzuweisen.
    saveOptions.BitsPerPixel = 1;

    // Mit den angegebenen Optionen an einem anderen Ort speichern.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Nur den zentralen Teil des Bildes speichern.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Speichern Sie das gesamte Bild in einem Speicherstrom
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Speichern Sie den zentralen Teil des Bildes in einem Speicherstrom
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//Die Ausgabe könnte so aussehen:
//Die Größe des gesamten Bildes in Byte: 24062
//Die Größe des zentralen Teils des Bildes in Bytes: 6046
```

### Siehe auch

* class [Image](../../image)
* namensraum [Aspose.Imaging](../../image)
* Montage [Aspose.Imaging](../../../)

---

## Save(string) {#save_4}

Speichert das Bild am angegebenen Dateispeicherort.

```csharp
public override void Save(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad, in dem das Bild gespeichert werden soll. |

### Siehe auch

* class [Image](../../image)
* namensraum [Aspose.Imaging](../../image)
* Montage [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase) {#save_5}

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad. |
| options | ImageOptionsBase | Die Optionen. |

### Beispiele

Das folgende Beispiel lädt ein BMP-Bild aus einer Datei und speichert das Bild dann in einer PNG-Datei.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Speichern Sie das gesamte Bild in einer PNG-Datei.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    image.Save(dir + "output.png", saveOptions);
}
```

Dieses Beispiel zeigt die einfachen Schritte zum Speichern eines Bildes. Um diesen Vorgang zu demonstrieren, laden wir eine vorhandene Datei von einem Speicherort auf der Festplatte, führen einen Drehvorgang für das Bild aus und speichern das Bild im PSD-Format unter Verwendung des Dateipfads

```csharp
[C#]

string dir = "c:\\temp\\";

//Erstellen Sie eine Instanz der Bildklasse und initialisieren Sie sie mit einer vorhandenen Datei über den Dateipfad
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Drehen Sie das Bild um 180 Grad um die X-Achse
    image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

    //Speichern Sie das Bild als PSD im Dateipfad mit den Standardeinstellungen von PsdOptions
    image.Save(dir + "output.psd", new Aspose.Imaging.ImageOptions.PsdOptions());
}
```

Das folgende Beispiel zeigt, wie ein ganzes BMP-Bild oder ein Teil davon in einer Datei oder einem Stream gespeichert wird.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Konvertiere in ein Schwarz-Weiß-Bild
    bmpImage.BinarizeOtsu();

    // Am selben Ort mit Standardoptionen speichern.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Eine Palette enthält nur zwei Farben: in diesem Fall Schwarz und Weiß.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Für alle monochromen Bilder (einschließlich Schwarz-Weiß-Bilder) reicht es aus, 1 Bit pro Pixel zuzuweisen.
    saveOptions.BitsPerPixel = 1;

    // Mit den angegebenen Optionen an einem anderen Ort speichern.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Nur den zentralen Teil des Bildes speichern.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Speichern Sie das gesamte Bild in einem Speicherstrom
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Speichern Sie den zentralen Teil des Bildes in einem Speicherstrom
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//Die Ausgabe könnte so aussehen:
//Die Größe des gesamten Bildes in Byte: 24062
//Die Größe des zentralen Teils des Bildes in Bytes: 6046
```

### Siehe auch

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* namensraum [Aspose.Imaging](../../image)
* Montage [Aspose.Imaging](../../../)

---

## Save(string, ImageOptionsBase, Rectangle) {#save_6}

Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen.

```csharp
public virtual void Save(string filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad. |
| options | ImageOptionsBase | Die Optionen. |
| boundsRectangle | Rectangle | Das Zielbild umgrenzt ein Rechteck. Legen Sie das leere Rechteck für die Verwendung von Quellgrenzen fest. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | Optionen |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Bildspeicherung fehlgeschlagen. |

### Beispiele

Das folgende Beispiel lädt ein BMP-Bild aus einer Datei und speichert dann einen rechteckigen Teil des Bildes in einer PNG-Datei.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    // Speichern Sie die obere Hälfte des Bildes in einer PNG-Datei.
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    image.Save(dir + "output.png", saveOptions, bounds);
}
```

Das folgende Beispiel zeigt, wie ein ganzes BMP-Bild oder ein Teil davon in einer Datei oder einem Stream gespeichert wird.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Konvertiere in ein Schwarz-Weiß-Bild
    bmpImage.BinarizeOtsu();

    // Am selben Ort mit Standardoptionen speichern.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Eine Palette enthält nur zwei Farben: in diesem Fall Schwarz und Weiß.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Für alle monochromen Bilder (einschließlich Schwarz-Weiß-Bilder) reicht es aus, 1 Bit pro Pixel zuzuweisen.
    saveOptions.BitsPerPixel = 1;

    // Mit den angegebenen Optionen an einem anderen Ort speichern.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Nur den zentralen Teil des Bildes speichern.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Speichern Sie das gesamte Bild in einem Speicherstrom
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Speichern Sie den zentralen Teil des Bildes in einem Speicherstrom
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//Die Ausgabe könnte so aussehen:
//Die Größe des gesamten Bildes in Byte: 24062
//Die Größe des zentralen Teils des Bildes in Bytes: 6046
```

### Siehe auch

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* namensraum [Aspose.Imaging](../../image)
* Montage [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase) {#save_2}

Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat.

```csharp
public void Save(Stream stream, ImageOptionsBase optionsBase)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, in dem die Bilddaten gespeichert werden sollen. |
| optionsBase | ImageOptionsBase | Die Speicheroptionen. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | OptionenBasis |
| ArgumentException | Speichern im angegebenen Format nicht möglich, da es derzeit nicht unterstützt wird.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Bildexport fehlgeschlagen. |

### Beispiele

Das folgende Beispiel lädt ein Bild aus einer Datei und speichert das Bild dann in einem PNG-Dateistream.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "output.png", System.IO.FileMode.Create))
    {
        // Das gesamte Bild in einem Dateistream speichern.
        image.Save(outputStream, saveOptions);
    }
}
```

Dieses Beispiel zeigt den Vorgang zum Speichern eines Bildes in MemoryStream. Um diesen Vorgang zu demonstrieren, lädt das Beispiel eine vorhandene Datei von einem Speicherort auf der Festplatte, führt einen Drehvorgang für das Bild aus und speichert das Bild im PSD-Format

```csharp
[C#]

//Eine Instanz von MemoryStream erstellen
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Erstellen Sie eine Instanz der Bildklasse und initialisieren Sie sie mit einer vorhandenen Datei über den Dateipfad
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
    {
        // Drehen Sie das Bild um 180 Grad um die X-Achse
        image.RotateFlip(Aspose.Imaging.RotateFlipType.Rotate180FlipX);

        //Speichern Sie das Bild als PSD in MemoryStream mit den standardmäßigen PsdOptions-Einstellungen
        image.Save(stream, new Aspose.Imaging.ImageOptions.PsdOptions());
    }
}
```

Das folgende Beispiel zeigt, wie ein ganzes BMP-Bild oder ein Teil davon in einer Datei oder einem Stream gespeichert wird.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Konvertiere in ein Schwarz-Weiß-Bild
    bmpImage.BinarizeOtsu();

    // Am selben Ort mit Standardoptionen speichern.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Eine Palette enthält nur zwei Farben: in diesem Fall Schwarz und Weiß.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Für alle monochromen Bilder (einschließlich Schwarz-Weiß-Bilder) reicht es aus, 1 Bit pro Pixel zuzuweisen.
    saveOptions.BitsPerPixel = 1;

    // Mit den angegebenen Optionen an einem anderen Ort speichern.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Nur den zentralen Teil des Bildes speichern.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Speichern Sie das gesamte Bild in einem Speicherstrom
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Speichern Sie den zentralen Teil des Bildes in einem Speicherstrom
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//Die Ausgabe könnte so aussehen:
//Die Größe des gesamten Bildes in Byte: 24062
//Die Größe des zentralen Teils des Bildes in Bytes: 6046
```

### Siehe auch

* class [ImageOptionsBase](../../imageoptionsbase)
* class [Image](../../image)
* namensraum [Aspose.Imaging](../../image)
* Montage [Aspose.Imaging](../../../)

---

## Save(Stream, ImageOptionsBase, Rectangle) {#save_3}

Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat.

```csharp
public virtual void Save(Stream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, in dem die Bilddaten gespeichert werden sollen. |
| optionsBase | ImageOptionsBase | Die Speicheroptionen. |
| boundsRectangle | Rectangle | Das Zielbild umgrenzt ein Rechteck. Legen Sie das leere Rechteck für die Verwendung von Quellgrenzen fest. |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | OptionenBasis |
| ArgumentException | Speichern im angegebenen Format nicht möglich, da es derzeit nicht unterstützt wird.;optionsBase |
| [ImageSaveException](../../../aspose.imaging.coreexceptions/imagesaveexception) | Bildexport fehlgeschlagen. |

### Beispiele

Das folgende Beispiel lädt ein Bild aus einer Datei und speichert dann einen rechteckigen Teil des Bildes in einem PNG-Dateistream.

```csharp
[C#]

string dir = "c:\\temp\\";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.ImageOptions.PngOptions saveOptions = new Aspose.Imaging.ImageOptions.PngOptions();
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(0, 0, image.Width, image.Height / 2);
    using (System.IO.Stream outputStream = System.IO.File.Open(dir + "sample.output.png", System.IO.FileMode.Create))
    {
        // Speichern Sie die obere Hälfte des Bildes in einem Dateistream.
        image.Save(outputStream, saveOptions, bounds);
    }
}
```

Das folgende Beispiel zeigt, wie ein ganzes BMP-Bild oder ein Teil davon in einer Datei oder einem Stream gespeichert wird.

```csharp
[C#]

string dir = "c:\\temp\\";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormats.Bmp.BmpImage bmpImage = (Aspose.Imaging.FileFormats.Bmp.BmpImage)image;
        
    // Konvertiere in ein Schwarz-Weiß-Bild
    bmpImage.BinarizeOtsu();

    // Am selben Ort mit Standardoptionen speichern.
    image.Save();

    Aspose.Imaging.ImageOptions.BmpOptions saveOptions = new Aspose.Imaging.ImageOptions.BmpOptions();

    // Eine Palette enthält nur zwei Farben: in diesem Fall Schwarz und Weiß.
    saveOptions.Palette = Aspose.Imaging.ColorPaletteHelper.CreateMonochrome();

    // Für alle monochromen Bilder (einschließlich Schwarz-Weiß-Bilder) reicht es aus, 1 Bit pro Pixel zuzuweisen.
    saveOptions.BitsPerPixel = 1;

    // Mit den angegebenen Optionen an einem anderen Ort speichern.
    image.Save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Nur den zentralen Teil des Bildes speichern.
    Aspose.Imaging.Rectangle bounds = new Aspose.Imaging.Rectangle(image.Width / 4, image.Height / 4, image.Width / 2, image.Height / 2);
    image.Save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Speichern Sie das gesamte Bild in einem Speicherstrom
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions);
        System.Console.WriteLine("The size of the whole image in bytes: {0}", stream.Length);
    }

    // Speichern Sie den zentralen Teil des Bildes in einem Speicherstrom
    using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
    {
        image.Save(stream, saveOptions, bounds);
        System.Console.WriteLine("The size of the central part of the image in bytes: {0}", stream.Length);
    }
}
//Die Ausgabe könnte so aussehen:
//Die Größe des gesamten Bildes in Byte: 24062
//Die Größe des zentralen Teils des Bildes in Bytes: 6046
```

### Siehe auch

* class [ImageOptionsBase](../../imageoptionsbase)
* struct [Rectangle](../../rectangle)
* class [Image](../../image)
* namensraum [Aspose.Imaging](../../image)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
