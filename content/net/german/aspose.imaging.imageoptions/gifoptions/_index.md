---
title: GifOptions
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die Optionen zum Erstellen des GIF-Dateiformats.
type: docs
weight: 10000
url: /de/aspose.imaging.imageoptions/gifoptions/
---
## GifOptions class

Die Optionen zum Erstellen des GIF-Dateiformats.

```csharp
public class GifOptions : ImageOptionsBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [GifOptions](gifoptions#constructor)() | Initialisiert eine neue Instanz von[`GifOptions`](../gifoptions) Klasse. |
| [GifOptions](gifoptions#constructor_1)(GifOptions) | Initialisiert eine neue Instanz von[`GifOptions`](../gifoptions) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/gifoptions/backgroundcolor) { get; set; } | Ruft die Hintergrundfarbe ab oder legt sie fest. |
| [BackgroundColorIndex](../../aspose.imaging.imageoptions/gifoptions/backgroundcolorindex) { get; set; } | Ruft den GIF-Hintergrundfarbindex ab oder legt ihn fest. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [ColorResolution](../../aspose.imaging.imageoptions/gifoptions/colorresolution) { get; set; } | Ruft die GIF-Farbauflösung ab oder legt sie fest. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [DoPaletteCorrection](../../aspose.imaging.imageoptions/gifoptions/dopalettecorrection) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Palettenkorrektur angewendet wird. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Vollbild]. |
| [HasTrailer](../../aspose.imaging.imageoptions/gifoptions/hastrailer) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob GIF einen Trailer hat. |
| [HasTransparentColor](../../aspose.imaging.imageoptions/gifoptions/hastransparentcolor) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das GIF-Bild eine transparente Farbe hat. |
| [Interlaced](../../aspose.imaging.imageoptions/gifoptions/interlaced) { get; set; } | Wahr, wenn das Bild interlaced sein soll. |
| [IsPaletteSorted](../../aspose.imaging.imageoptions/gifoptions/ispalettesorted) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob Paletteneinträge sortiert sind. |
| [LoopsCount](../../aspose.imaging.imageoptions/gifoptions/loopscount) { get; set; } | Ruft die Anzahl der Schleifen ab oder setzt sie (Standard 1 Schleife) |
| [MaxDiff](../../aspose.imaging.imageoptions/gifoptions/maxdiff) { get; set; } | Holt oder setzt den maximal erlaubten Pixelunterschied. Wenn größer als Null, wird verlustbehaftete Komprimierung verwendet. Der empfohlene Wert für eine optimale verlustbehaftete Komprimierung ist 80. 30 ist eine sehr leichte Komprimierung, 200 ist stark. Es funktioniert am besten, wenn nur wenig Verlust eingeführt wird, und aufgrund der Beschränkung des Komprimierungsalgorithmus sehr hohe Verlustniveaus ergeben nicht so viel Gewinn. Der zulässige Wertebereich ist [0, 1000]. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Die mehrseitigen Optionen |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. |
| [PixelAspectRatio](../../aspose.imaging.imageoptions/gifoptions/pixelaspectratio) { get; set; } | Ruft das GIF-Pixel-Seitenverhältnis ab oder legt es fest. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ruft den Fortschrittsereignishandler ab oder legt ihn fest. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ruft die Quelle zum Erstellen des Bildes ab oder legt sie fest. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ruft die Optionen für die Vektorrasterung ab oder legt sie fest. |
| override [XmpData](../../aspose.imaging.imageoptions/gifoptions/xmpdata) { get; set; } | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Klont diese Instanz. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |

### Beispiele

Dieses Beispiel demonstriert die Verwendung verschiedener Klassen aus dem SaveOptions-Namespace für Exportzwecke. Ein Bild vom Typ Gif wird in eine Instanz von Image geladen und dann in mehrere Formate exportiert.

```csharp
[C#]

string dir = "c:\\temp\\";

//Ein vorhandenes Bild (vom Typ Gif) in eine Instanz der Image-Klasse laden
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    //Export in das BMP-Dateiformat unter Verwendung der Standardoptionen
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    // Mit den Standardoptionen in das JPEG-Dateiformat exportieren
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    // Mit den Standardoptionen in das PNG-Dateiformat exportieren
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    // Mit den Standardoptionen in das TIFF-Dateiformat exportieren
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

Das folgende Beispiel zeigt, wie ein mehrseitiges Vektorbild auf allgemeine Weise in das GIF-Format konvertiert wird, ohne auf einen bestimmten Bildtyp zu verweisen.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.gif");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.GifOptions();

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Nur die ersten beiden Seiten exportieren. Diese Seiten werden im Ausgabe-GIF als animierte Frames dargestellt.
    Aspose.Imaging.IMultipageImage multipageImage = image as Aspose.Imaging.IMultipageImage;
    if (multipageImage != null && (multipageImage.Pages != null && multipageImage.PageCount > 2))
    {
        exportOptions.MultiPageOptions = new Aspose.Imaging.ImageOptions.MultiPageOptions(new Aspose.Imaging.IntRange(0, 2));
    }

    if (image is Aspose.Imaging.VectorImage)
    {
        exportOptions.VectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Aspose.Imaging.Color.White, image.Width, image.Height });
        exportOptions.VectorRasterizationOptions.TextRenderingHint = Aspose.Imaging.TextRenderingHint.SingleBitPerPixel;
        exportOptions.VectorRasterizationOptions.SmoothingMode = Aspose.Imaging.SmoothingMode.None;
    }

    image.Save(outputFilePath, exportOptions);
}
```

Dieses Beispiel zeigt, wie Pixelinformationen in ein Array vom Typ Color geladen, das Array manipuliert und wieder auf das Bild gesetzt wird. Um diese Vorgänge auszuführen, erstellt dieses Beispiel eine neue Bilddatei (im GIF-Format) mit dem MemoryStream-Objekt.

```csharp
[C#]

//Eine Instanz von MemoryStream erstellen
using (System.IO.MemoryStream stream = new System.IO.MemoryStream())
{
    //Erstellen Sie eine Instanz von GifOptions und legen Sie ihre verschiedenen Eigenschaften einschließlich der Source-Eigenschaft fest
    Aspose.Imaging.ImageOptions.GifOptions gifOptions = new Aspose.Imaging.ImageOptions.GifOptions();
    gifOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Eine Instanz von Image erstellen
    using (Aspose.Imaging.RasterImage image = (Aspose.Imaging.RasterImage)Aspose.Imaging.Image.Create(gifOptions, 500, 500))
    {
        //Die Pixel des Bildes abrufen, indem der Bereich als Bildgrenze angegeben wird
        Aspose.Imaging.Color[] pixels = image.LoadPixels(image.Bounds);

        // Schleife über das Array und setzt die Farbe des alternativen indizierten Pixels
        for (int index = 0; index < pixels.Length; index++)
        {
            if (index % 2 == 0)
            {
                //Indizierte Pixelfarbe auf gelb setzen
                pixels[index] = Aspose.Imaging.Color.Yellow;
            }
            else
            {
                //Indizierte Pixelfarbe auf Blau setzen
                pixels[index] = Aspose.Imaging.Color.Blue;
            }
        }

        // Pixeländerungen auf das Bild anwenden
        image.SavePixels(image.Bounds, pixels);

        // Alle Änderungen speichern.
        image.Save();
    }

    // MemoryStream in Datei schreiben
    using (System.IO.FileStream fileStream = new System.IO.FileStream(@"C:\temp\output.gif", System.IO.FileMode.Create))
    {
        stream.WriteTo(fileStream);
    }   
}
```

### Siehe auch

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* namensraum [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
