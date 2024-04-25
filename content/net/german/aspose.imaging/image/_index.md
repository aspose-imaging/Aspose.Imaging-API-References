---
title: Image
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das Bild ist die Basisklasse für alle Arten von Bildern.
type: docs
weight: 9660
url: /de/aspose.imaging/image/
---
## Image class

Das Bild ist die Basisklasse für alle Arten von Bildern.

```csharp
public abstract class Image : DataStreamSupporter, IObjectWithBounds
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AutoAdjustPalette](../../aspose.imaging/image/autoadjustpalette) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob die Palette automatisch angepasst wird. |
| virtual [BackgroundColor](../../aspose.imaging/image/backgroundcolor) { get; set; } | Ruft einen Wert für die Hintergrundfarbe ab oder legt ihn fest. |
| abstract [BitsPerPixel](../../aspose.imaging/image/bitsperpixel) { get; } | Ruft die Anzahl der Bildbits pro Pixel ab. |
| [Bounds](../../aspose.imaging/image/bounds) { get; } | Ruft die Bildgrenzen ab. |
| [BufferSizeHint](../../aspose.imaging/image/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [Container](../../aspose.imaging/image/container) { get; } | Ruft die ab[`Image`](../image) Container. |
| [DataStreamContainer](../../aspose.imaging/datastreamsupporter/datastreamcontainer) { get; } | Ruft den Datenstrom des Objekts ab. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| virtual [FileFormat](../../aspose.imaging/image/fileformat) { get; } | Ruft einen Wert von Dateiformat ab |
| virtual [HasBackgroundColor](../../aspose.imaging/image/hasbackgroundcolor) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das Bild eine Hintergrundfarbe hat. |
| abstract [Height](../../aspose.imaging/image/height) { get; } | Ruft die Bildhöhe ab. |
| [InterruptMonitor](../../aspose.imaging/image/interruptmonitor) { get; set; } | Holt oder setzt den Interrupt-Monitor. |
| abstract [IsCached](../../aspose.imaging/datastreamsupporter/iscached) { get; } | Ruft einen Wert ab, der angibt, ob die Daten des Objekts derzeit zwischengespeichert sind und kein Datenlesen erforderlich ist. |
| [Palette](../../aspose.imaging/image/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. Die Farbpalette wird nicht verwendet, wenn Pixel direkt dargestellt werden. |
| [Size](../../aspose.imaging/image/size) { get; } | Ruft die Bildgröße ab. |
| virtual [UsePalette](../../aspose.imaging/image/usepalette) { get; } | Ruft einen Wert ab, der angibt, ob die Bildpalette verwendet wird. |
| abstract [Width](../../aspose.imaging/image/width) { get; } | Ruft die Bildbreite ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [Create](../../aspose.imaging/image/create#create_1)(Image[]) | Erstellt ein neues Bild unter Verwendung der angegebenen Bilder als Seiten |
| static [Create](../../aspose.imaging/image/create#create_2)(Image[], bool) | Erstellt ein neues Bild mit den angegebenen Bildern als Seiten. |
| static [Create](../../aspose.imaging/image/create#create)(ImageOptionsBase, int, int) | Erstellt ein neues Bild mit den angegebenen Erstellungsoptionen. |
| static [Load](../../aspose.imaging/image/load#load)(Stream) | Lädt ein neues Bild aus dem angegebenen Stream. |
| static [Load](../../aspose.imaging/image/load#load_2)(string) | Lädt ein neues Bild aus der angegebenen Datei. |
| static [Load](../../aspose.imaging/image/load#load_1)(Stream, LoadOptions) | Lädt ein neues Bild aus dem angegebenen Stream. |
| static [Load](../../aspose.imaging/image/load#load_3)(string, LoadOptions) | Lädt ein neues Bild aus der angegebenen Datei. |
| abstract [CacheData](../../aspose.imaging/datastreamsupporter/cachedata)() | Zwischenspeichert die Daten und stellt sicher, dass kein zusätzliches Laden von Daten aus der zugrunde liegenden Datei durchgeführt wird[`DataStreamContainer`](../datastreamsupporter/datastreamcontainer) . |
| [CanSave](../../aspose.imaging/image/cansave)(ImageOptionsBase) | Legt fest, ob das Bild in dem angegebenen Dateiformat gespeichert werden kann, das durch die übergebenen Speicheroptionen repräsentiert wird. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| virtual [GetDefaultOptions](../../aspose.imaging/image/getdefaultoptions)(object[]) | Ruft die Standardoptionen ab. |
| virtual [GetOriginalOptions](../../aspose.imaging/image/getoriginaloptions)() | Ruft die Optionen basierend auf den ursprünglichen Dateieinstellungen ab. Dies kann hilfreich sein, um die Bittiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz-weißes PNG-Bild mit 1 Bit pro Pixel laden und dann Speichern Sie es mit the [`Save`](../datastreamsupporter/save) -Methode wird das ausgegebene PNG-Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und das PNG-Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um entsprechende Speicheroptionen zu erhalten, und übergeben Sie sie an die[`Save`](./save) Methode als zweiten Parameter. |
| [Resize](../../aspose.imaging/image/resize#resize)(int, int) | Ändert die Bildgröße. Der StandardNearestNeighbourResample wird verwendet. |
| abstract [Resize](../../aspose.imaging/image/resize#resize_1)(int, int, ImageResizeSettings) | Ändert die Bildgröße. |
| abstract [Resize](../../aspose.imaging/image/resize#resize_2)(int, int, ResizeType) | Ändert die Bildgröße. |
| [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally)(int) | Ändert die Höhe proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally_1)(int, ImageResizeSettings) | Ändert die Höhe proportional. |
| virtual [ResizeHeightProportionally](../../aspose.imaging/image/resizeheightproportionally#resizeheightproportionally_2)(int, ResizeType) | Ändert die Höhe proportional. |
| [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally)(int) | Ändert die Breite proportional. Der StandardNearestNeighbourResample wird verwendet. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally_1)(int, ImageResizeSettings) | Ändert die Breite proportional. |
| virtual [ResizeWidthProportionally](../../aspose.imaging/image/resizewidthproportionally#resizewidthproportionally_2)(int, ResizeType) | Ändert die Breite proportional. |
| abstract [RotateFlip](../../aspose.imaging/image/rotateflip)(RotateFlipType) | Dreht, kippt oder dreht und kippt das Bild. |
| [Save](../../aspose.imaging/image/save#save)() | Speichert die Bilddaten im zugrunde liegenden Stream. |
| [Save](../../aspose.imaging/datastreamsupporter/save)(Stream) | Speichert die Daten des Objekts im angegebenen Stream. |
| override [Save](../../aspose.imaging/image/save#save_4)(string) | Speichert das Bild am angegebenen Dateispeicherort. |
| [Save](../../aspose.imaging/image/save#save_2)(Stream, ImageOptionsBase) | Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat. |
| virtual [Save](../../aspose.imaging/datastreamsupporter/save)(string, bool) | Speichert die Daten des Objekts am angegebenen Dateispeicherort. |
| virtual [Save](../../aspose.imaging/image/save#save_5)(string, ImageOptionsBase) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| virtual [Save](../../aspose.imaging/image/save#save_3)(Stream, ImageOptionsBase, Rectangle) | Speichert die Bilddaten gemäß den Speicheroptionen im angegebenen Stream im angegebenen Dateiformat. |
| virtual [Save](../../aspose.imaging/image/save#save_6)(string, ImageOptionsBase, Rectangle) | Speichert die Daten des Objekts am angegebenen Speicherort im angegebenen Dateiformat gemäß den Speicheroptionen. |
| abstract [SetPalette](../../aspose.imaging/image/setpalette)(IColorPalette, bool) | Legt die Bildpalette fest. |
| static [CanLoad](../../aspose.imaging/image/canload#canload)(Stream) | Bestimmt, ob das Bild aus dem angegebenen Stream geladen werden kann. |
| static [CanLoad](../../aspose.imaging/image/canload#canload_2)(string) | Legt fest, ob das Bild aus dem angegebenen Dateipfad geladen werden kann. |
| static [CanLoad](../../aspose.imaging/image/canload#canload_1)(Stream, LoadOptions) | Legt fest, ob das Bild aus dem angegebenen Stream geladen werden kann und optional den angegebenen verwendet*loadOptions* . |
| static [CanLoad](../../aspose.imaging/image/canload#canload_3)(string, LoadOptions) | Legt fest, ob das Bild aus dem angegebenen Dateipfad und optional unter Verwendung der angegebenen Öffnungsoptionen geladen werden kann. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat#getfileformat)(Stream) | Ruft das Dateiformat ab. |
| static [GetFileFormat](../../aspose.imaging/image/getfileformat#getfileformat_1)(string) | Ruft das Dateiformat ab. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle#getfittingrectangle)(Rectangle, int, int) | Ruft ein Rechteck ab, das zum aktuellen Bild passt. |
| static [GetFittingRectangle](../../aspose.imaging/image/getfittingrectangle#getfittingrectangle_1)(Rectangle, int[], int, int) | Ruft ein Rechteck ab, das zum aktuellen Bild passt. |
| static [GetProportionalHeight](../../aspose.imaging/image/getproportionalheight)(int, int, int) | Ruft eine proportionale Höhe ab. |
| static [GetProportionalWidth](../../aspose.imaging/image/getproportionalwidth)(int, int, int) | Ruft eine proportionale Breite ab. |

### Beispiele

Stellen Sie fest, ob die Palette vom Bild verwendet wird.

```csharp
[C#]

using (var image = Image.Load(folder + "Sample.bmp"))
{
    if (image.UsePalette)
    {
        Console.WriteLine("The palette is used by the image");
    }
}
```

Ändern Sie die Bildgröße mit einem bestimmten Größenänderungstyp.

```csharp
[C#]

using (var image = Image.Load("Photo.jpg"))
{
    image.Resize(640, 480, ResizeType.CatmullRom);
    image.Save("ResizedPhoto.jpg");

    image.Resize(1024, 768, ResizeType.CubicConvolution);
    image.Save("ResizedPhoto2.jpg");

    var resizeSettings = new ImageResizeSettings
    {
        Mode = ResizeType.CubicBSpline,
        FilterType = ImageFilterType.SmallRectangular
    };

    image.Resize(800, 800, resizeSettings);
    image.Save("ResizedPhoto3.jpg");
}
```

Dieses Beispiel erstellt eine neue Image-Datei an einem Speicherort auf dem Datenträger, wie von der Source-Eigenschaft der BmpOptions-Instanz angegeben. Mehrere Eigenschaften für die BmpOptions-Instanz werden festgelegt, bevor das eigentliche Bild erstellt wird. Insbesondere die Source-Eigenschaft, die sich in diesem Fall auf den tatsächlichen Speicherort der Festplatte bezieht.

```csharp
[C#]

//Eine Instanz von BmpOptions erstellen und ihre verschiedenen Eigenschaften festlegen
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Eine Instanz von FileCreateSource erstellen und als Quelle für die Instanz von BmpOptions zuweisen
//Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei Temporär ist oder nicht
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//Erstellen Sie eine Instanz von Image und initialisieren Sie sie mit einer Instanz von BmpOptions, indem Sie die Create-Methode aufrufen
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    // Bildverarbeitung durchführen

    // Alle Änderungen speichern
    image.Save();
}
```

### Siehe auch

* class [DataStreamSupporter](../datastreamsupporter)
* interface [IObjectWithBounds](../iobjectwithbounds)
* namensraum [Aspose.Imaging](../../aspose.imaging)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
