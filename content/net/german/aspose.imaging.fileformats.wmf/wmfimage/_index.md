---
title: WmfImage
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das Wmf-Bild
type: docs
weight: 9280
url: /de/aspose.imaging.fileformats.wmf/wmfimage/
---
## WmfImage class

Das Wmf-Bild

```csharp
public class WmfImage : MetaImage
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [WmfImage](wmfimage#constructor)() | Initialisiert eine neue Instanz von[`WmfImage`](../wmfimage) Klasse. |
| [WmfImage](wmfimage#constructor_1)(int, int) | Initialisiert eine neue Instanz von[`WmfImage`](../wmfimage) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Palette automatisch angepasst wird. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Ruft einen Wert für die Hintergrundfarbe ab oder legt ihn fest. |
| override [BitsPerPixel](../../aspose.imaging.fileformats.wmf/wmfimage/bitsperpixel) { get; } | Ruft die Anzahl der Bildbits pro Pixel ab. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Ruft die Bildgrenzen ab. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [Container](../../aspose.imaging/image/container) { get; } | Ruft die ab[`Image`](../../aspose.imaging/image) Container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Ruft den Datenstrom des Objekts ab. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| override [FileFormat](../../aspose.imaging.fileformats.wmf/wmfimage/fileformat) { get; } | Ruft einen Wert von Dateiformat ab |
| [FrameBounds](../../aspose.imaging.fileformats.wmf/wmfimage/framebounds) { get; } | Ruft die Rahmengrenzen ab. |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| override [Height](../../aspose.imaging.fileformats.wmf/wmfimage/height) { get; } | Ruft die Bildhöhe ab. |
| virtual [HeightF](../../aspose.imaging/vectorimage/heightf) { get; } | Ruft die Objekthöhe in Zoll ab. |
| [Inch](../../aspose.imaging.fileformats.wmf/wmfimage/inch) { get; set; } | Holt oder setzt den Zoll. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Holt oder setzt den Interrupt-Monitor. |
| override [IsCached](../../aspose.imaging.fileformats.wmf/wmfimage/iscached) { get; } | Ruft einen Wert ab, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| virtual [Records](../../aspose.imaging.fileformats.emf/metaimage/records) { get; set; } | Ruft die Datensätze ab oder legt sie fest. |
| [Size](../../aspose.imaging/image/size) { get; } | Ruft die Bildgröße ab. |
| [SizeF](../../aspose.imaging/vectorimage/sizef) { get; } | Ruft die Objektgröße in Zoll ab. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Ruft einen Wert ab, der angibt, ob die Bildpalette verwendet wird. |
| override [Width](../../aspose.imaging.fileformats.wmf/wmfimage/width) { get; } | Ruft die Bildbreite ab. |
| virtual [WidthF](../../aspose.imaging/vectorimage/widthf) { get; } | Ruft die Objektbreite in Zoll ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddRecord](../../aspose.imaging.fileformats.wmf/wmfimage/addrecord)(WmfObject) | Fügt den Datensatz hinzu. |
| override [CacheData](../../aspose.imaging.fileformats.wmf/wmfimage/cachedata)() | Cachet die Daten und stellt sicher, dass kein zusätzliches Laden von Daten aus dem zugrunde liegenden durchgeführt wird[`DataStreamContainer`](../../aspose.imaging/datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Legt fest, ob das Bild in dem angegebenen Dateiformat gespeichert werden kann, das durch die übergebenen Speicheroptionen repräsentiert wird. |
| override [Crop](../../aspose.imaging.fileformats.wmf/wmfimage/crop#crop)(Rectangle) | Beschneidet das angegebene Rechteck. |
| virtual [Crop](../../aspose.imaging.fileformats.emf/metaimage/crop)(int, int, int, int) | Bild mit Verschiebungen zuschneiden. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| override [GetDefaultOptions](../../aspose.imaging.fileformats.wmf/wmfimage/getdefaultoptions)(object[]) | Ruft die Standardoptionen ab. |
| virtual [GetEmbeddedImages](../../aspose.imaging/vectorimage/getembeddedimages)() | Ruft die eingebetteten Bilder ab. |
| [GetMissedFonts](../../aspose.imaging.fileformats.emf/metaimage/getmissedfonts)() | Gibt die Liste der Schriftarten zurück, die in der Metadatei verwendet, aber nicht gefunden wurden. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz-weißes PNG-Bild mit 1 Bit pro Pixel laden und dann Speichern Sie es mit the [`Save`](../../aspose.imaging/datastreamsupporter/save) -Methode wird das ausgegebene PNG-Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und das PNG-Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um entsprechende Speicheroptionen zu erhalten, und übergeben Sie sie an die[`Save`](../../aspose.imaging/image/save) Methode als zweiten Parameter. |
| [GetPostScript](../../aspose.imaging.fileformats.wmf/wmfimage/getpostscript)() | Ruft das Postskript ab. |
| override [GetUsedFonts](../../aspose.imaging.fileformats.wmf/wmfimage/getusedfonts)() | Gibt die Liste der Schriftarten zurück, die in der Metadatei verwendet wurden. |
| [Resize](../../aspose.imaging/image/resize)(int, int) | Ändert die Bildgröße. Der StandardNearestNeighbourResample wird verwendet. |
| override [Resize](../../aspose.imaging.fileformats.wmf/wmfimage/resize#resize_1)(int, int, ImageResizeSettings) | Ändert die Bildgröße. |
| override [Resize](../../aspose.imaging.fileformats.wmf/wmfimage/resize#resize_2)(int, int, ResizeType) | Ändert die Bildgröße. |
| override [ResizeCanvas](../../aspose.imaging.fileformats.wmf/wmfimage/resizecanvas)(Rectangle) | Ändert die Leinwandgröße. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int) | Ändert die Höhe proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally)(int, ResizeType) | Ändert die Höhe proportional. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int) | Ändert die Breite proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ImageResizeSettings) | Ändert die Breite proportional. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally)(int, ResizeType) | Ändert die Breite proportional. |
| override [RotateFlip](../../aspose.imaging.fileformats.wmf/wmfimage/rotateflip)(RotateFlipType) | Dreht, kippt oder dreht und kippt das Bild. |
| [Save](../../aspose.imaging/image/save)() | Speichert die Bilddaten im zugrunde liegenden Stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Speichert die Daten des Objekts im angegebenen Stream. |
| override [Save](../../aspose.imaging/image/save)(string) | Speichert das Bild am angegebenen Dateispeicherort. |
| [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase) | Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Speichert die Daten des Objekts am angegebenen Dateispeicherort. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| virtual [Save](../../aspose.imaging/image/save)(Stream, ImageOptionsBase, Rectangle) | Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat. |
| virtual [Save](../../aspose.imaging/image/save)(string, ImageOptionsBase, Rectangle) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| override [SetPalette](../../aspose.imaging.fileformats.wmf/wmfimage/setpalette)(IColorPalette, bool) | Legt die Bildpalette fest. |

### Beispiele

Das folgende Beispiel zeigt, wie Sie ein wmz-Bild in ein wmf-Format konvertieren

```csharp
[C#]

string file = "example.wmz";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmf";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions});
}
```

Das folgende Beispiel zeigt, wie Sie ein WMF-Bild in ein WMF-Format konvertieren

```csharp
[C#]

string file = "castle.wmf";
string baseFolder = System.IO.Path.Combine("D:", "Compressed");
string inputFile = System.IO.Path.Combine(baseFolder, file);
string outFile = inputFile + ".wmz";
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
{
    Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions() { PageSize = image.Size};
    image.Save(outFile, new Aspose.Imaging.ImageOptions.WmfOptions() {VectorRasterizationOptions = vectorRasterizationOptions, Compress = true});
}
```

Das folgende Beispiel zeigt, wie ein komprimiertes Bild (*.emz,*.wmz, *.svgz) in ein Rasterformat konvertiert wird

```csharp
[C#]

string[] files = new[] {"example.emz", "example.wmz", "example.svgz"};
string baseFolder = System.IO.Path.Combine("D:","Compressed");
foreach (var file in files)
{
    string inputFile = System.IO.Path.Combine(baseFolder, file);
    string outFile = inputFile + ".png";
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFile))
    {
        Aspose.Imaging.ImageOptions.VectorRasterizationOptions vectorRasterizationOptions = (Aspose.Imaging.ImageOptions.VectorRasterizationOptions)image.GetDefaultOptions(new object[] { Color.White, image.Width, image.Height });
        image.Save(outFile, new Aspose.Imaging.ImageOptions.PngOptions(){VectorRasterizationOptions = vectorRasterizationOptions});
    }
}
```

Dieses Beispiel zeigt, wie ein WMF-Bild aus einer Datei geladen und mit WmfRasterizationOptions in SVG konvertiert wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist eine einheitliche Methode zum Laden aller Arten von Bildern, einschließlich WMF.
using (Aspose.Imaging.FileFormats.Wmf.WmfImage wmfImage = (Aspose.Imaging.FileFormats.Wmf.WmfImage)Aspose.Imaging.Image.Load(dir + "test.wmf"))
{
    Aspose.Imaging.ImageOptions.SvgOptions saveOptions = new Aspose.Imaging.ImageOptions.SvgOptions();
        
    // Text wird in Formen umgewandelt.
    saveOptions.TextAsShapes = true;

    Aspose.Imaging.ImageOptions.WmfRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.WmfRasterizationOptions();

    // Die Hintergrundfarbe der Zeichenfläche.
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.WhiteSmoke;

    // Die Seitengröße.
    rasterizationOptions.PageSize = wmfImage.Size;

    // Wenn eingebettetes emf existiert, dann emf rendern; andernfalls wmf rendern.
    rasterizationOptions.RenderMode = Aspose.Imaging.FileFormats.Wmf.WmfRenderMode.Auto;

    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    wmfImage.Save(dir + "test.output.svg", saveOptions);
}
```

### Siehe auch

* class [MetaImage](../../aspose.imaging.fileformats.emf/metaimage)
* namensraum [Aspose.Imaging.FileFormats.Wmf](../../aspose.imaging.fileformats.wmf)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
