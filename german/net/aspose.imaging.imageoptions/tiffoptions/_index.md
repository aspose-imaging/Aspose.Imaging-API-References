---
title: TiffOptions
second_title: Aspose.Imaging für .NET-API-Referenz
description: Die TIFF-Dateiformatoptionen. Beachten Sie dass Breiten- und Höhen-Tags bei der Bilderzeugung durch Breiten- und Höhenparameter überschrieben werden sodass sie nicht direkt angegeben werden müssen. Beachten Sie dass viele Optionen einen Standardwert zurückgeben aber das bedeutet nicht diese Option wird explizit als Tag-Wert festgelegt. Um zu überprüfen ob das Tag vorhanden ist verwenden Sie die Tags-Eigenschaft oder die entsprechende IsTagPresent-Methode.
type: docs
weight: 10220
url: /de/net/aspose.imaging.imageoptions/tiffoptions/
---
## TiffOptions class

Die TIFF-Dateiformatoptionen. Beachten Sie, dass Breiten- und Höhen-Tags bei der Bilderzeugung durch Breiten- und Höhenparameter überschrieben werden, sodass sie nicht direkt angegeben werden müssen. Beachten Sie, dass viele Optionen einen Standardwert zurückgeben, aber das bedeutet nicht diese Option wird explizit als Tag-Wert festgelegt. Um zu überprüfen, ob das Tag vorhanden ist, verwenden Sie die Tags-Eigenschaft oder die entsprechende IsTagPresent-Methode.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TiffOptions](tiffoptions#constructor_2)(TiffDataType[]) | Initialisiert eine neue Instanz von[`TiffOptions`](../tiffoptions) Klasse. |
| [TiffOptions](tiffoptions#constructor)(TiffExpectedFormat) | Initialisiert eine neue Instanz von[`TiffOptions`](../tiffoptions)Klasse. Standardmäßig wird die Little-Endian-Konvention verwendet. |
| [TiffOptions](tiffoptions#constructor_3)(TiffOptions) | Initialisiert eine neue Instanz von[`TiffOptions`](../tiffoptions) Klasse. |
| [TiffOptions](tiffoptions#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Initialisiert eine neue Instanz von[`TiffOptions`](../tiffoptions) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlphaStorage](../../aspose.imaging.imageoptions/tiffoptions/alphastorage) { get; set; } | Ruft die Alpha-Speicheroption ab oder legt sie fest. Andere Optionen alsUnspecified werden verwendet, wenn es mehr als 3 gibt[`SamplesPerPixel`](./samplesperpixel) definiert. |
| [Artist](../../aspose.imaging.imageoptions/tiffoptions/artist) { get; set; } | Ruft den Künstler ab oder legt ihn fest. |
| [BitsPerPixel](../../aspose.imaging.imageoptions/tiffoptions/bitsperpixel) { get; } | Ruft die Bits pro Pixel ab. |
| [BitsPerSample](../../aspose.imaging.imageoptions/tiffoptions/bitspersample) { get; set; } | Holt oder setzt die Bits pro Sample. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Ruft den Puffergrößenhinweis ab oder legt ihn fest, der als maximal zulässige Größe für alle internen Puffer definiert ist. |
| [ByteOrder](../../aspose.imaging.imageoptions/tiffoptions/byteorder) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der die TIFF-Byte-Reihenfolge angibt. |
| [ColorMap](../../aspose.imaging.imageoptions/tiffoptions/colormap) { get; set; } | Ruft die Farbkarte ab oder legt sie fest. |
| [CompressedQuality](../../aspose.imaging.imageoptions/tiffoptions/compressedquality) { get; set; } | Ruft die komprimierte Bildqualität ab oder legt sie fest. Wird mit der JPEG-Komprimierung verwendet. |
| [Compression](../../aspose.imaging.imageoptions/tiffoptions/compression) { get; set; } | Ruft die Komprimierung ab oder legt sie fest. |
| [Copyright](../../aspose.imaging.imageoptions/tiffoptions/copyright) { get; set; } | Ruft das Urheberrecht ab oder legt es fest. |
| [DateTime](../../aspose.imaging.imageoptions/tiffoptions/datetime) { get; set; } | Ruft Datum und Uhrzeit ab oder legt sie fest. |
| [DisableIccExport](../../aspose.imaging.imageoptions/tiffoptions/disableiccexport) { get; set; } | Ruft oder setzt einen Wert, der angibt, ob der ICC-Profilexport deaktiviert ist (das ICC-Profil wird vorher auf die Quellpixel angewendet). |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Ruft einen Wert ab, der angibt, ob diese Instanz verworfen wird. |
| [DocumentName](../../aspose.imaging.imageoptions/tiffoptions/documentname) { get; set; } | Ruft den Namen des Dokuments ab oder legt ihn fest. |
| [ExifIfd](../../aspose.imaging.imageoptions/tiffoptions/exififd) { get; } | Holt oder setzt den Zeiger auf EXIF IFD. |
| [ExtraSamples](../../aspose.imaging.imageoptions/tiffoptions/extrasamples) { get; } | Ruft die zusätzlichen Abtastwerte ab. |
| [FaxT4Options](../../aspose.imaging.imageoptions/tiffoptions/faxt4options) { get; set; } | Ruft die Fax-t4-Optionen ab oder legt sie fest. |
| [FileStandard](../../aspose.imaging.imageoptions/tiffoptions/filestandard) { get; set; } | Ruft den TIFF-Dateistandard ab oder legt ihn fest. |
| [FillOrder](../../aspose.imaging.imageoptions/tiffoptions/fillorder) { get; set; } | Ruft die Füllreihenfolge der Byte-Bits ab oder legt sie fest. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [Vollbild]. |
| [HalfToneHints](../../aspose.imaging.imageoptions/tiffoptions/halftonehints) { get; set; } | Ruft die Halbtonhinweise ab oder legt sie fest. |
| [IccProfile](../../aspose.imaging.imageoptions/tiffoptions/iccprofile) { get; set; } | Ruft den Icc-Profilstream ab oder legt ihn fest. |
| [ImageDescription](../../aspose.imaging.imageoptions/tiffoptions/imagedescription) { get; set; } | Ruft die Bildbeschreibung ab oder legt sie fest. |
| [ImageLength](../../aspose.imaging.imageoptions/tiffoptions/imagelength) { get; set; } | Ruft die Bildlänge ab oder legt sie fest. |
| [ImageWidth](../../aspose.imaging.imageoptions/tiffoptions/imagewidth) { get; set; } | Ruft die Bildbreite ab oder legt sie fest. |
| [InkNames](../../aspose.imaging.imageoptions/tiffoptions/inknames) { get; set; } | Ruft die Tintennamen ab oder legt sie fest. |
| [IsExtraSamplesPresent](../../aspose.imaging.imageoptions/tiffoptions/isextrasamplespresent) { get; } | Ruft einen Wert ab, der angibt, ob die zusätzlichen Proben vorhanden sind. |
| [IsTiled](../../aspose.imaging.imageoptions/tiffoptions/istiled) { get; } | Ruft einen Wert ab, der angibt, ob das Bild gekachelt ist. |
| [IsValid](../../aspose.imaging.imageoptions/tiffoptions/isvalid) { get; } | Ruft einen Wert ab, der angibt, ob die[`TiffOptions`](../tiffoptions) richtig konfiguriert wurden. Verwenden Sie die Validate-Methode, um die Fehlerursache zu finden. |
| [MaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/maxsamplevalue) { get; set; } | Ruft den maximalen Abtastwert ab oder legt ihn fest. |
| [MinSampleValue](../../aspose.imaging.imageoptions/tiffoptions/minsamplevalue) { get; set; } | Ruft den minimalen Abtastwert ab oder legt ihn fest. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Die mehrseitigen Optionen |
| [Orientation](../../aspose.imaging.imageoptions/tiffoptions/orientation) { get; set; } | Ruft die Ausrichtung ab oder legt sie fest. |
| [PageName](../../aspose.imaging.imageoptions/tiffoptions/pagename) { get; set; } | Ruft den Seitennamen ab oder legt ihn fest. |
| [PageNumber](../../aspose.imaging.imageoptions/tiffoptions/pagenumber) { get; set; } | Ruft das Seitenzahl-Tag ab oder legt es fest. |
| override [Palette](../../aspose.imaging.imageoptions/tiffoptions/palette) { get; set; } | Ruft die Farbpalette ab oder legt sie fest. |
| [Photometric](../../aspose.imaging.imageoptions/tiffoptions/photometric) { get; set; } | Ruft die photometrischen Daten ab oder legt sie fest. |
| [PlanarConfiguration](../../aspose.imaging.imageoptions/tiffoptions/planarconfiguration) { get; set; } | Ruft die planare Konfiguration ab oder legt sie fest. |
| [Predictor](../../aspose.imaging.imageoptions/tiffoptions/predictor) { get; set; } | Ruft den Prädiktor für die LZW-Komprimierung ab oder legt ihn fest. |
| [PremultiplyComponents](../../aspose.imaging.imageoptions/tiffoptions/premultiplycomponents) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob Komponenten vormultipliziert werden müssen. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Ruft den Fortschrittsereignishandler ab oder legt ihn fest. |
| override [ResolutionSettings](../../aspose.imaging.imageoptions/tiffoptions/resolutionsettings) { get; set; } | Ruft die Auflösungseinstellungen ab oder legt sie fest. |
| [ResolutionUnit](../../aspose.imaging.imageoptions/tiffoptions/resolutionunit) { get; set; } | Ruft die Auflösungseinheit ab oder legt sie fest. |
| [RowsPerStrip](../../aspose.imaging.imageoptions/tiffoptions/rowsperstrip) { get; set; } | Ruft die Zeilen pro Streifen ab oder legt sie fest. |
| [SampleFormat](../../aspose.imaging.imageoptions/tiffoptions/sampleformat) { get; set; } | Ruft das Beispielformat ab oder legt es fest. |
| [SamplesPerPixel](../../aspose.imaging.imageoptions/tiffoptions/samplesperpixel) { get; } | Ruft die Samples pro Pixel ab. Um diesen Eigenschaftswert zu ändern, verwenden Sie die[`BitsPerSample`](./bitspersample) Property-Setter. |
| [ScannerManufacturer](../../aspose.imaging.imageoptions/tiffoptions/scannermanufacturer) { get; set; } | Ruft den Scannerhersteller ab oder legt ihn fest. |
| [ScannerModel](../../aspose.imaging.imageoptions/tiffoptions/scannermodel) { get; set; } | Ruft das Scannermodell ab oder legt es fest. |
| [SmaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/smaxsamplevalue) { get; set; } | Ruft den maximalen Abtastwert ab oder setzt ihn. Der Wert hat einen Feldtyp, der am besten zu den Beispieldaten passt (Typ Byte, Short oder Long). |
| [SminSampleValue](../../aspose.imaging.imageoptions/tiffoptions/sminsamplevalue) { get; set; } | Ruft den minimalen Abtastwert ab oder setzt ihn. Der Wert hat einen Feldtyp, der am besten zu den Beispieldaten passt (Typ Byte, Short oder Long). |
| [SoftwareType](../../aspose.imaging.imageoptions/tiffoptions/softwaretype) { get; set; } | Ruft den Softwaretyp ab oder legt ihn fest. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Ruft die Quelle zum Erstellen des Bildes ab oder legt sie fest. |
| [StripByteCounts](../../aspose.imaging.imageoptions/tiffoptions/stripbytecounts) { get; set; } | Ruft die Anzahl der Strip-Bytes ab oder legt sie fest. |
| [StripOffsets](../../aspose.imaging.imageoptions/tiffoptions/stripoffsets) { get; set; } | Holt oder setzt die Streifen-Offsets. |
| [SubFileType](../../aspose.imaging.imageoptions/tiffoptions/subfiletype) { get; set; } | Holt oder setzt einen allgemeinen Hinweis auf die Art der Daten, die in dieser Unterdatei enthalten sind. |
| [Tags](../../aspose.imaging.imageoptions/tiffoptions/tags) { get; set; } | Ruft die Tags ab oder legt sie fest. |
| [TargetPrinter](../../aspose.imaging.imageoptions/tiffoptions/targetprinter) { get; set; } | Ruft den Zieldrucker ab oder setzt ihn. |
| [Threshholding](../../aspose.imaging.imageoptions/tiffoptions/threshholding) { get; set; } | Ruft den Schwellenwert ab oder legt ihn fest. |
| [TileByteCounts](../../aspose.imaging.imageoptions/tiffoptions/tilebytecounts) { get; set; } | Ruft die Tile-Byte-Anzahl ab oder legt sie fest. |
| [TileLength](../../aspose.imaging.imageoptions/tiffoptions/tilelength) { get; set; } | Ruft ot-Sets-Kachellänge ab. |
| [TileOffsets](../../aspose.imaging.imageoptions/tiffoptions/tileoffsets) { get; set; } | Ruft die Kachel-Offsets ab oder legt sie fest. |
| [TileWidth](../../aspose.imaging.imageoptions/tiffoptions/tilewidth) { get; set; } | Ruft die Kachelbreite ab. |
| [TotalPages](../../aspose.imaging.imageoptions/tiffoptions/totalpages) { get; } | Ruft die Gesamtzahl der Seiten ab. |
| [ValidTagCount](../../aspose.imaging.imageoptions/tiffoptions/validtagcount) { get; } | Ruft die gültige Tag-Anzahl ab. Dies ist nicht die Gesamtzahl der Tags, sondern die Anzahl der Tags, die beibehalten werden können. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Ruft die Optionen für die Vektorrasterung ab oder legt sie fest. |
| override [XmpData](../../aspose.imaging.imageoptions/tiffoptions/xmpdata) { get; set; } | Ruft den XMP-Metadatencontainer ab oder legt ihn fest. |
| [XPAuthor](../../aspose.imaging.imageoptions/tiffoptions/xpauthor) { get; set; } | Ruft den Bildautor ab oder legt ihn fest, der von Windows Explorer verwendet wird. |
| [XPComment](../../aspose.imaging.imageoptions/tiffoptions/xpcomment) { get; set; } | Holt oder setzt Kommentar zum Bild, das von Windows Explorer verwendet wird. |
| [XPKeywords](../../aspose.imaging.imageoptions/tiffoptions/xpkeywords) { get; set; } | Ruft das Motivbild ab oder legt es fest, das von Windows Explorer verwendet wird. |
| [Xposition](../../aspose.imaging.imageoptions/tiffoptions/xposition) { get; set; } | Ruft die x-Position ab oder legt sie fest. |
| [XPSubject](../../aspose.imaging.imageoptions/tiffoptions/xpsubject) { get; set; } | Ruft Informationen über Bilder ab oder legt sie fest, die von Windows Explorer verwendet werden. |
| [XPTitle](../../aspose.imaging.imageoptions/tiffoptions/xptitle) { get; set; } | Ruft Informationen über Bilder ab oder legt sie fest, die von Windows Explorer verwendet werden. |
| [Xresolution](../../aspose.imaging.imageoptions/tiffoptions/xresolution) { get; set; } | Ruft die x-Auflösung ab oder legt sie fest. |
| [YCbCrCoefficients](../../aspose.imaging.imageoptions/tiffoptions/ycbcrcoefficients) { get; set; } | Ruft die YCbCrCoefficients ab oder setzt sie. |
| [YCbCrSubsampling](../../aspose.imaging.imageoptions/tiffoptions/ycbcrsubsampling) { get; set; } | Liest oder setzt die Subsampling-Faktoren für YCbCr photometric. |
| [Yposition](../../aspose.imaging.imageoptions/tiffoptions/yposition) { get; set; } | Ruft die y-Position ab oder legt sie fest. |
| [Yresolution](../../aspose.imaging.imageoptions/tiffoptions/yresolution) { get; set; } | Ruft die y-Auflösung ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [AddTag](../../aspose.imaging.imageoptions/tiffoptions/addtag)(TiffDataType) | Fügt ein neues Tag hinzu. |
| [AddTags](../../aspose.imaging.imageoptions/tiffoptions/addtags)(TiffDataType[]) | Fügt die Tags hinzu. |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Klont diese Instanz. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Verwirft die aktuelle Instanz. |
| [GetTagByType](../../aspose.imaging.imageoptions/tiffoptions/gettagbytype)(TiffTags) | Ruft die Instanz des Tags nach Typ ab. |
| [IsTagPresent](../../aspose.imaging.imageoptions/tiffoptions/istagpresent)(TiffTags) | Legt fest, ob Tag in den Optionen vorhanden ist oder nicht. |
| [RemoveTag](../../aspose.imaging.imageoptions/tiffoptions/removetag)(TiffTags) | Entfernt das Tag. |
| [Validate](../../aspose.imaging.imageoptions/tiffoptions/validate)() | Prüft, ob Optionen eine gültige Kombination von Tags haben |
| static [GetValidTagsCount](../../aspose.imaging.imageoptions/tiffoptions/getvalidtagscount)(TiffDataType[]) | Ruft die Anzahl gültiger Tags ab. |

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

Das folgende Beispiel zeigt, wie Sie ein mehrseitiges Vektorbild auf allgemeine Weise in das TIFF-Format konvertieren, ohne auf einen bestimmten Bildtyp zu verweisen.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.tiff");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Nur die ersten beiden Seiten exportieren. Diese Seiten werden im Ausgabe-TIFF als Rahmen dargestellt.
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

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* namensraum [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
