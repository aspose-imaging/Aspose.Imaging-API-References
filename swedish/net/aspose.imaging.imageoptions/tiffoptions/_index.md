---
title: TiffOptions
second_title: Aspose.Imaging för .NET API-referens
description: Alternativen för tiff-filformat. Observera att bredd- och höjdtaggar kommer att skrivas över vid bildskapande av parametrar för bredd och höjd så det finns ingen anledning att ange dem direkt. Observera att många alternativ returnerar ett standardvärde men det betyder inte att det här alternativet är uttryckligen inställt som ett taggvärde. För att verifiera att taggen finns använd Tags-egenskapen eller motsvarande IsTagPresent-metod.
type: docs
weight: 10220
url: /sv/net/aspose.imaging.imageoptions/tiffoptions/
---
## TiffOptions class

Alternativen för tiff-filformat. Observera att bredd- och höjdtaggar kommer att skrivas över vid bildskapande av parametrar för bredd och höjd, så det finns ingen anledning att ange dem direkt. Observera att många alternativ returnerar ett standardvärde men det betyder inte att det här alternativet är uttryckligen inställt som ett taggvärde. För att verifiera att taggen finns, använd Tags-egenskapen eller motsvarande IsTagPresent-metod.

```csharp
public class TiffOptions : ImageOptionsBase
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [TiffOptions](tiffoptions#constructor_2)(TiffDataType[]) | Initierar en ny instans av[`TiffOptions`](../tiffoptions) class. |
| [TiffOptions](tiffoptions#constructor)(TiffExpectedFormat) | Initierar en ny instans av[`TiffOptions`](../tiffoptions)klass. Som standard används little endian-konventionen. |
| [TiffOptions](tiffoptions#constructor_3)(TiffOptions) | Initierar en ny instans av[`TiffOptions`](../tiffoptions) class. |
| [TiffOptions](tiffoptions#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Initierar en ny instans av[`TiffOptions`](../tiffoptions) class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AlphaStorage](../../aspose.imaging.imageoptions/tiffoptions/alphastorage) { get; set; } | Hämtar eller ställer in alfalagringsalternativet. Andra alternativ änUnspecified används när det finns fler än 3[`SamplesPerPixel`](./samplesperpixel) definierad. |
| [Artist](../../aspose.imaging.imageoptions/tiffoptions/artist) { get; set; } | Hämtar eller ställer in artisten. |
| [BitsPerPixel](../../aspose.imaging.imageoptions/tiffoptions/bitsperpixel) { get; } | Hämtar bitarna per pixel. |
| [BitsPerSample](../../aspose.imaging.imageoptions/tiffoptions/bitspersample) { get; set; } | Hämtar eller ställer in bitarna per sampel. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Hämtar eller ställer in buffertstorlekstipset som är definierat som högsta tillåtna storlek för alla interna buffertar. |
| [ByteOrder](../../aspose.imaging.imageoptions/tiffoptions/byteorder) { get; set; } | Hämtar eller ställer in ett värde som anger tiff-byteordningen. |
| [ColorMap](../../aspose.imaging.imageoptions/tiffoptions/colormap) { get; set; } | Hämtar eller ställer in färgkartan. |
| [CompressedQuality](../../aspose.imaging.imageoptions/tiffoptions/compressedquality) { get; set; } | Hämtar eller ställer in komprimerad bildkvalitet. Används med Jpeg-komprimeringen. |
| [Compression](../../aspose.imaging.imageoptions/tiffoptions/compression) { get; set; } | Hämtar eller ställer in komprimeringen. |
| [Copyright](../../aspose.imaging.imageoptions/tiffoptions/copyright) { get; set; } | Får eller anger upphovsrätten. |
| [DateTime](../../aspose.imaging.imageoptions/tiffoptions/datetime) { get; set; } | Hämtar eller ställer in datum och tid. |
| [DisableIccExport](../../aspose.imaging.imageoptions/tiffoptions/disableiccexport) { get; set; } | Hämtar eller ställer in ett värde som anger om ICC-profilexport är inaktiverat (ICC-profil tillämpas på källpixlarna i förväg). |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Får ett värde som indikerar om denna instans är bortskaffad. |
| [DocumentName](../../aspose.imaging.imageoptions/tiffoptions/documentname) { get; set; } | Hämtar eller ställer in namnet på dokumentet. |
| [ExifIfd](../../aspose.imaging.imageoptions/tiffoptions/exififd) { get; } | Hämtar eller ställer in pekaren till EXIF IFD. |
| [ExtraSamples](../../aspose.imaging.imageoptions/tiffoptions/extrasamples) { get; } | Hämtar de extra sampelvärdena. |
| [FaxT4Options](../../aspose.imaging.imageoptions/tiffoptions/faxt4options) { get; set; } | Hämtar eller ställer in fax t4-alternativen. |
| [FileStandard](../../aspose.imaging.imageoptions/tiffoptions/filestandard) { get; set; } | Hämtar eller ställer in TIFF-filstandarden. |
| [FillOrder](../../aspose.imaging.imageoptions/tiffoptions/fillorder) { get; set; } | Hämtar eller ställer in bytebitarnas fyllningsordning. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | Hämtar eller ställer in ett värde som anger om [helbild]. |
| [HalfToneHints](../../aspose.imaging.imageoptions/tiffoptions/halftonehints) { get; set; } | Hämtar eller ställer in halvtonstipsen. |
| [IccProfile](../../aspose.imaging.imageoptions/tiffoptions/iccprofile) { get; set; } | Hämtar eller ställer in Icc-profilströmmen. |
| [ImageDescription](../../aspose.imaging.imageoptions/tiffoptions/imagedescription) { get; set; } | Hämtar eller ställer in bildbeskrivningen. |
| [ImageLength](../../aspose.imaging.imageoptions/tiffoptions/imagelength) { get; set; } | Hämtar eller ställer in bildlängden. |
| [ImageWidth](../../aspose.imaging.imageoptions/tiffoptions/imagewidth) { get; set; } | Hämtar eller ställer in bildbredden. |
| [InkNames](../../aspose.imaging.imageoptions/tiffoptions/inknames) { get; set; } | Hämtar eller ställer in bläcknamnen. |
| [IsExtraSamplesPresent](../../aspose.imaging.imageoptions/tiffoptions/isextrasamplespresent) { get; } | Får ett värde som indikerar om de extra samplen finns. |
| [IsTiled](../../aspose.imaging.imageoptions/tiffoptions/istiled) { get; } | Får ett värde som indikerar om bilden är sida vid sida. |
| [IsValid](../../aspose.imaging.imageoptions/tiffoptions/isvalid) { get; } | Får ett värde som indikerar om[`TiffOptions`](../tiffoptions) har konfigurerats korrekt. Använd metoden Validera för att hitta orsaken till felet. |
| [MaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/maxsamplevalue) { get; set; } | Hämtar eller ställer in det maximala sampelvärdet. |
| [MinSampleValue](../../aspose.imaging.imageoptions/tiffoptions/minsamplevalue) { get; set; } | Hämtar eller ställer in det minsta sampelvärdet. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Alternativen för flera sidor |
| [Orientation](../../aspose.imaging.imageoptions/tiffoptions/orientation) { get; set; } | Hämtar eller ställer in orienteringen. |
| [PageName](../../aspose.imaging.imageoptions/tiffoptions/pagename) { get; set; } | Hämtar eller ställer in sidnamnet. |
| [PageNumber](../../aspose.imaging.imageoptions/tiffoptions/pagenumber) { get; set; } | Hämtar eller ställer in sidnummertaggen. |
| override [Palette](../../aspose.imaging.imageoptions/tiffoptions/palette) { get; set; } | Hämtar eller ställer in färgpaletten. |
| [Photometric](../../aspose.imaging.imageoptions/tiffoptions/photometric) { get; set; } | Hämtar eller ställer in fotometrisk. |
| [PlanarConfiguration](../../aspose.imaging.imageoptions/tiffoptions/planarconfiguration) { get; set; } | Hämtar eller ställer in den plana konfigurationen. |
| [Predictor](../../aspose.imaging.imageoptions/tiffoptions/predictor) { get; set; } | Hämtar eller ställer in prediktorn för LZW-komprimering. |
| [PremultiplyComponents](../../aspose.imaging.imageoptions/tiffoptions/premultiplycomponents) { get; set; } | Hämtar eller ställer in ett värde som anger om komponenter måste förmultipliceras. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | Hämtar eller ställer in förloppshändelsehanteraren. |
| override [ResolutionSettings](../../aspose.imaging.imageoptions/tiffoptions/resolutionsettings) { get; set; } | Hämtar eller ställer in upplösningsinställningarna. |
| [ResolutionUnit](../../aspose.imaging.imageoptions/tiffoptions/resolutionunit) { get; set; } | Hämtar eller ställer in upplösningsenheten. |
| [RowsPerStrip](../../aspose.imaging.imageoptions/tiffoptions/rowsperstrip) { get; set; } | Hämtar eller ställer in raderna per remsa. |
| [SampleFormat](../../aspose.imaging.imageoptions/tiffoptions/sampleformat) { get; set; } | Hämtar eller ställer in exempelformatet. |
| [SamplesPerPixel](../../aspose.imaging.imageoptions/tiffoptions/samplesperpixel) { get; } | Hämtar samplen per pixel. För att ändra detta egenskapsvärde använd[`BitsPerSample`](./bitspersample) egenskapsinställare. |
| [ScannerManufacturer](../../aspose.imaging.imageoptions/tiffoptions/scannermanufacturer) { get; set; } | Hämtar eller ställer in skannertillverkaren. |
| [ScannerModel](../../aspose.imaging.imageoptions/tiffoptions/scannermodel) { get; set; } | Hämtar eller ställer in skannermodellen. |
| [SmaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/smaxsamplevalue) { get; set; } | Hämtar eller ställer in det maximala sampelvärdet. Värdet har en fälttyp som bäst matchar exempeldata (Byte, Short eller Long type). |
| [SminSampleValue](../../aspose.imaging.imageoptions/tiffoptions/sminsamplevalue) { get; set; } | Hämtar eller ställer in det minsta sampelvärdet. Värdet har en fälttyp som bäst matchar exempeldata (Byte, Short eller Long type). |
| [SoftwareType](../../aspose.imaging.imageoptions/tiffoptions/softwaretype) { get; set; } | Hämtar eller ställer in mjukvarutypen. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Hämtar eller ställer in källan för att skapa bild i. |
| [StripByteCounts](../../aspose.imaging.imageoptions/tiffoptions/stripbytecounts) { get; set; } | Hämtar eller ställer in remsantalet byte. |
| [StripOffsets](../../aspose.imaging.imageoptions/tiffoptions/stripoffsets) { get; set; } | Får eller ställer in remsoffset. |
| [SubFileType](../../aspose.imaging.imageoptions/tiffoptions/subfiletype) { get; set; } | Hämtar eller ställer in en allmän indikation på vilken typ av data som finns i denna underfil. |
| [Tags](../../aspose.imaging.imageoptions/tiffoptions/tags) { get; set; } | Hämtar eller ställer in taggarna. |
| [TargetPrinter](../../aspose.imaging.imageoptions/tiffoptions/targetprinter) { get; set; } | Hämtar eller ställer in målskrivaren. |
| [Threshholding](../../aspose.imaging.imageoptions/tiffoptions/threshholding) { get; set; } | Hämtar eller ställer in tröskelvärdet. |
| [TileByteCounts](../../aspose.imaging.imageoptions/tiffoptions/tilebytecounts) { get; set; } | Hämtar eller ställer in antalet brickbyte. |
| [TileLength](../../aspose.imaging.imageoptions/tiffoptions/tilelength) { get; set; } | Får ot sets kakellängd. |
| [TileOffsets](../../aspose.imaging.imageoptions/tiffoptions/tileoffsets) { get; set; } | Hämtar eller ställer in brickförskjutningarna. |
| [TileWidth](../../aspose.imaging.imageoptions/tiffoptions/tilewidth) { get; set; } | Får ot set kakelbredd. |
| [TotalPages](../../aspose.imaging.imageoptions/tiffoptions/totalpages) { get; } | Får det totala antalet sidor. |
| [ValidTagCount](../../aspose.imaging.imageoptions/tiffoptions/validtagcount) { get; } | Får det giltiga taggantalet. Detta är inte det totala antalet taggar utan antalet taggar som kan bevaras. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Hämtar eller ställer in vektorrasteriseringsalternativen. |
| override [XmpData](../../aspose.imaging.imageoptions/tiffoptions/xmpdata) { get; set; } | Hämtar eller ställer in XMP-metadatabehållaren. |
| [XPAuthor](../../aspose.imaging.imageoptions/tiffoptions/xpauthor) { get; set; } | Hämtar eller ställer in bildförfattare, som används av Utforskaren i Windows. |
| [XPComment](../../aspose.imaging.imageoptions/tiffoptions/xpcomment) { get; set; } | Hämtar eller ställer in en kommentar till bilden, som används av Windows Explorer. |
| [XPKeywords](../../aspose.imaging.imageoptions/tiffoptions/xpkeywords) { get; set; } | Hämtar eller ställer in ämnesbild, som används av Utforskaren i Windows. |
| [Xposition](../../aspose.imaging.imageoptions/tiffoptions/xposition) { get; set; } | Hämtar eller ställer in x-positionen. |
| [XPSubject](../../aspose.imaging.imageoptions/tiffoptions/xpsubject) { get; set; } | Hämtar eller ställer in information om bild, som används av Windows Explorer. |
| [XPTitle](../../aspose.imaging.imageoptions/tiffoptions/xptitle) { get; set; } | Hämtar eller ställer in information om bild, som används av Windows Explorer. |
| [Xresolution](../../aspose.imaging.imageoptions/tiffoptions/xresolution) { get; set; } | Hämtar eller ställer in x-upplösningen. |
| [YCbCrCoefficients](../../aspose.imaging.imageoptions/tiffoptions/ycbcrcoefficients) { get; set; } | Hämtar eller ställer in YCbCrCoefficients. |
| [YCbCrSubsampling](../../aspose.imaging.imageoptions/tiffoptions/ycbcrsubsampling) { get; set; } | Hämtar eller ställer in delsamplingsfaktorerna för YCbCr fotometrisk. |
| [Yposition](../../aspose.imaging.imageoptions/tiffoptions/yposition) { get; set; } | Hämtar eller ställer in y-positionen. |
| [Yresolution](../../aspose.imaging.imageoptions/tiffoptions/yresolution) { get; set; } | Hämtar eller ställer in y-upplösningen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [AddTag](../../aspose.imaging.imageoptions/tiffoptions/addtag)(TiffDataType) | Lägger till en ny tagg. |
| [AddTags](../../aspose.imaging.imageoptions/tiffoptions/addtags)(TiffDataType[]) | Lägger till taggarna. |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Klonar den här instansen. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Tar bort den aktuella instansen. |
| [GetTagByType](../../aspose.imaging.imageoptions/tiffoptions/gettagbytype)(TiffTags) | Hämtar instansen av taggen efter typ. |
| [IsTagPresent](../../aspose.imaging.imageoptions/tiffoptions/istagpresent)(TiffTags) | Avgör om tagg finns i alternativen eller inte. |
| [RemoveTag](../../aspose.imaging.imageoptions/tiffoptions/removetag)(TiffTags) | Tar bort taggen. |
| [Validate](../../aspose.imaging.imageoptions/tiffoptions/validate)() | Validerar om alternativen har en giltig kombination av taggar |
| static [GetValidTagsCount](../../aspose.imaging.imageoptions/tiffoptions/getvalidtagscount)(TiffDataType[]) | Får antalet giltiga taggar. |

### Exempel

Det här exemplet visar användningen av olika klasser från SaveOptions Namespace för exportändamål. En bild av typen Gif laddas in i en instans av Image och exporteras sedan ut till flera format.

```csharp
[C#]

string dir = "c:\\temp\\";

//Ladda in en befintlig bild (av typen Gif) i en instans av klassen Image
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    //Exportera till BMP-filformat med standardalternativen
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    //Exportera till JPEG-filformat med standardalternativen
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    //Exportera till PNG-filformat med standardalternativen
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    //Exportera till TIFF-filformat med standardalternativen
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

Följande exempel visar hur man konverterar en flersidig vektorbild till TIFF-format på ett allmänt sätt utan att referera till en viss bildtyp.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.tiff");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Exportera endast de två första sidorna. Dessa sidor kommer att presenteras som ramar i utdata-TIFF.
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

I det här exemplet används GraphicsPath och Graphics-klassen för att skapa och manipulera figurer på en bildyta. Exempel skapar en ny bild (av typen Tiff), rensar ytan och ritar banor med hjälp av klassen GraphicsPath. I slutet anropas DrawPath-metoden som exponeras av Graphics-klassen för att rendera banorna på ytan.

```csharp
[C#]

//Skapa en instans av FileStream
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    //Skapa en instans av TiffOptions och ställ in dess olika egenskaper
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    //Ställ in källan för instansen av ImageOptions
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Skapa en instans av bild 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        //Skapa och initiera en instans av klassen Graphics
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Rensa grafikytan
        graphics.Clear(Color.Wheat);

        //Skapa en instans av klassen GraphicsPath
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        //Skapa en instans av figurklassen
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        //Lägg till former till figurobjekt
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        //Lägg till figurobjekt till GraphicsPath
        graphicspath.AddFigure(figure);

        //Rita bana med pennobjekt av färg svart
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // spara alla ändringar.
        image.Save();
    }
}
```

### Se även

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* namnutrymme [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
