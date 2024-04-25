---
title: TiffOptions
second_title: Aspose.Imaging for .NET API Referansı
description: tiff dosya biçimi seçenekleri. Görüntü oluşturulurken genişlik ve yükseklik etiketlerinin üzerine genişlik ve yükseklik parametreleriyle yazılacağını unutmayın bu nedenle bunları doğrudan belirtmeye gerek yoktur. Birçok seçeneğin varsayılan bir değer döndürdüğünü unutmayın ancak bunun anlamı şu değildir. bu seçenek açıkça bir etiket değeri olarak ayarlanır. Etiketin mevcut olduğunu doğrulamak için Tags özelliğini veya ilgili IsTagPresent yöntemini kullanın.
type: docs
weight: 10220
url: /tr/aspose.imaging.imageoptions/tiffoptions/
---
## TiffOptions class

tiff dosya biçimi seçenekleri. Görüntü oluşturulurken genişlik ve yükseklik etiketlerinin üzerine genişlik ve yükseklik parametreleriyle yazılacağını unutmayın, bu nedenle bunları doğrudan belirtmeye gerek yoktur. Birçok seçeneğin varsayılan bir değer döndürdüğünü unutmayın, ancak bunun anlamı şu değildir. bu seçenek açıkça bir etiket değeri olarak ayarlanır. Etiketin mevcut olduğunu doğrulamak için Tags özelliğini veya ilgili IsTagPresent yöntemini kullanın.

```csharp
public class TiffOptions : ImageOptionsBase
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [TiffOptions](tiffoptions#constructor_2)(TiffDataType[]) | Yeni bir örneğini başlatır[`TiffOptions`](../tiffoptions) sınıf. |
| [TiffOptions](tiffoptions#constructor)(TiffExpectedFormat) | Yeni bir örneğini başlatır[`TiffOptions`](../tiffoptions)sınıf. Varsayılan olarak küçük endian kuralı kullanılır. |
| [TiffOptions](tiffoptions#constructor_3)(TiffOptions) | Yeni bir örneğini başlatır[`TiffOptions`](../tiffoptions) sınıf. |
| [TiffOptions](tiffoptions#constructor_1)(TiffExpectedFormat, TiffByteOrder) | Yeni bir örneğini başlatır[`TiffOptions`](../tiffoptions) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AlphaStorage](../../aspose.imaging.imageoptions/tiffoptions/alphastorage) { get; set; } | Alfa depolama seçeneğini alır veya ayarlar. Bunun dışındaki seçeneklerUnspecified 3'ten fazla olduğunda kullanılır[`SamplesPerPixel`](./samplesperpixel) tanımlı. |
| [Artist](../../aspose.imaging.imageoptions/tiffoptions/artist) { get; set; } | Sanatçıyı alır veya ayarlar. |
| [BitsPerPixel](../../aspose.imaging.imageoptions/tiffoptions/bitsperpixel) { get; } | Piksel başına bitleri alır. |
| [BitsPerSample](../../aspose.imaging.imageoptions/tiffoptions/bitspersample) { get; set; } | Örnek başına bitleri alır veya ayarlar. |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [ByteOrder](../../aspose.imaging.imageoptions/tiffoptions/byteorder) { get; set; } | Tiff bayt sırasını belirten bir değer alır veya ayarlar. |
| [ColorMap](../../aspose.imaging.imageoptions/tiffoptions/colormap) { get; set; } | Renk haritasını alır veya ayarlar. |
| [CompressedQuality](../../aspose.imaging.imageoptions/tiffoptions/compressedquality) { get; set; } | Sıkıştırılmış görüntü kalitesini alır veya ayarlar. Jpeg sıkıştırmasıyla kullanılır. |
| [Compression](../../aspose.imaging.imageoptions/tiffoptions/compression) { get; set; } | Sıkıştırmayı alır veya ayarlar. |
| [Copyright](../../aspose.imaging.imageoptions/tiffoptions/copyright) { get; set; } | Telif hakkını alır veya ayarlar. |
| [DateTime](../../aspose.imaging.imageoptions/tiffoptions/datetime) { get; set; } | Tarih ve saati alır veya ayarlar. |
| [DisableIccExport](../../aspose.imaging.imageoptions/tiffoptions/disableiccexport) { get; set; } | ICC profili dışa aktarmanın devre dışı bırakılıp bırakılmadığını belirten bir değer alır veya ayarlar (ICC profili önceden kaynak piksellere uygulanır). |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [DocumentName](../../aspose.imaging.imageoptions/tiffoptions/documentname) { get; set; } | Belgenin adını alır veya ayarlar. |
| [ExifIfd](../../aspose.imaging.imageoptions/tiffoptions/exififd) { get; } | İşaretçiyi alır veya EXIF IFD'ye ayarlar. |
| [ExtraSamples](../../aspose.imaging.imageoptions/tiffoptions/extrasamples) { get; } | Ekstra örnek değerlerini alır. |
| [FaxT4Options](../../aspose.imaging.imageoptions/tiffoptions/faxt4options) { get; set; } | Faks t4 seçeneklerini alır veya ayarlar. |
| [FileStandard](../../aspose.imaging.imageoptions/tiffoptions/filestandard) { get; set; } | TIFF dosya standardını alır veya ayarlar. |
| [FillOrder](../../aspose.imaging.imageoptions/tiffoptions/fillorder) { get; set; } | Bayt bitleri doldurma sırasını alır veya ayarlar. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | [tam kare]. olup olmadığını belirten bir değer alır veya ayarlar. |
| [HalfToneHints](../../aspose.imaging.imageoptions/tiffoptions/halftonehints) { get; set; } | Noktalı resim ipuçlarını alır veya ayarlar. |
| [IccProfile](../../aspose.imaging.imageoptions/tiffoptions/iccprofile) { get; set; } | Icc profil akışını alır veya ayarlar. |
| [ImageDescription](../../aspose.imaging.imageoptions/tiffoptions/imagedescription) { get; set; } | Görüntü açıklamasını alır veya ayarlar. |
| [ImageLength](../../aspose.imaging.imageoptions/tiffoptions/imagelength) { get; set; } | Görüntü uzunluğunu alır veya ayarlar. |
| [ImageWidth](../../aspose.imaging.imageoptions/tiffoptions/imagewidth) { get; set; } | Görüntü genişliğini alır veya ayarlar. |
| [InkNames](../../aspose.imaging.imageoptions/tiffoptions/inknames) { get; set; } | Mürekkep adlarını alır veya ayarlar. |
| [IsExtraSamplesPresent](../../aspose.imaging.imageoptions/tiffoptions/isextrasamplespresent) { get; } | Fazladan örneklerin mevcut olup olmadığını gösteren bir değer alır. |
| [IsTiled](../../aspose.imaging.imageoptions/tiffoptions/istiled) { get; } | Resmin döşenip döşenmediğini gösteren bir değer alır. |
| [IsValid](../../aspose.imaging.imageoptions/tiffoptions/isvalid) { get; } | olup olmadığını gösteren bir değer alır.[`TiffOptions`](../tiffoptions) uygun şekilde yapılandırılmıştır. Hata nedenini bulmak için Validate yöntemini kullanın. |
| [MaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/maxsamplevalue) { get; set; } | Maksimum örnek değerini alır veya ayarlar. |
| [MinSampleValue](../../aspose.imaging.imageoptions/tiffoptions/minsamplevalue) { get; set; } | Minimum örnek değerini alır veya ayarlar. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Çoklu sayfa seçenekleri |
| [Orientation](../../aspose.imaging.imageoptions/tiffoptions/orientation) { get; set; } | Yönü alır veya ayarlar. |
| [PageName](../../aspose.imaging.imageoptions/tiffoptions/pagename) { get; set; } | Sayfa adını alır veya ayarlar. |
| [PageNumber](../../aspose.imaging.imageoptions/tiffoptions/pagenumber) { get; set; } | Sayfa numarası etiketini alır veya ayarlar. |
| override [Palette](../../aspose.imaging.imageoptions/tiffoptions/palette) { get; set; } | Renk paletini alır veya ayarlar. |
| [Photometric](../../aspose.imaging.imageoptions/tiffoptions/photometric) { get; set; } | Fotometriyi alır veya ayarlar. |
| [PlanarConfiguration](../../aspose.imaging.imageoptions/tiffoptions/planarconfiguration) { get; set; } | Düzlemsel yapılandırmayı alır veya ayarlar. |
| [Predictor](../../aspose.imaging.imageoptions/tiffoptions/predictor) { get; set; } | LZW sıkıştırması için tahmin ediciyi alır veya ayarlar. |
| [PremultiplyComponents](../../aspose.imaging.imageoptions/tiffoptions/premultiplycomponents) { get; set; } | Bileşenlerin önceden çoğaltılmasının gerekip gerekmediğini belirten bir değer alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | İlerleme olayı işleyicisini alır veya ayarlar. |
| override [ResolutionSettings](../../aspose.imaging.imageoptions/tiffoptions/resolutionsettings) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [ResolutionUnit](../../aspose.imaging.imageoptions/tiffoptions/resolutionunit) { get; set; } | Çözünürlük birimini alır veya ayarlar. |
| [RowsPerStrip](../../aspose.imaging.imageoptions/tiffoptions/rowsperstrip) { get; set; } | Şerit başına satırları alır veya ayarlar. |
| [SampleFormat](../../aspose.imaging.imageoptions/tiffoptions/sampleformat) { get; set; } | Örnek biçimi alır veya ayarlar. |
| [SamplesPerPixel](../../aspose.imaging.imageoptions/tiffoptions/samplesperpixel) { get; } | Piksel başına örnekleri alır. Bu özellik değerini değiştirmek için[`BitsPerSample`](./bitspersample) özellik ayarlayıcı. |
| [ScannerManufacturer](../../aspose.imaging.imageoptions/tiffoptions/scannermanufacturer) { get; set; } | Tarayıcı üreticisini alır veya ayarlar. |
| [ScannerModel](../../aspose.imaging.imageoptions/tiffoptions/scannermodel) { get; set; } | Tarayıcı modelini alır veya ayarlar. |
| [SmaxSampleValue](../../aspose.imaging.imageoptions/tiffoptions/smaxsamplevalue) { get; set; } | Maksimum örnek değerini alır veya ayarlar. Değer, örnek verilerle en iyi eşleşen alan türüne sahiptir (Byte, Short veya Long type). |
| [SminSampleValue](../../aspose.imaging.imageoptions/tiffoptions/sminsamplevalue) { get; set; } | Minimum örnek değerini alır veya ayarlar. Değer, örnek verilerle en iyi eşleşen alan türüne sahiptir (Byte, Short veya Long type). |
| [SoftwareType](../../aspose.imaging.imageoptions/tiffoptions/softwaretype) { get; set; } | Yazılım türünü alır veya ayarlar. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Görüntü oluşturmak için kaynağı alır veya ayarlar. |
| [StripByteCounts](../../aspose.imaging.imageoptions/tiffoptions/stripbytecounts) { get; set; } | Şerit bayt sayılarını alır veya ayarlar. |
| [StripOffsets](../../aspose.imaging.imageoptions/tiffoptions/stripoffsets) { get; set; } | Şerit ofsetlerini alır veya ayarlar. |
| [SubFileType](../../aspose.imaging.imageoptions/tiffoptions/subfiletype) { get; set; } | Bu alt dosyada bulunan veri türünün genel bir göstergesini alır veya ayarlar. |
| [Tags](../../aspose.imaging.imageoptions/tiffoptions/tags) { get; set; } | Etiketleri alır veya ayarlar. |
| [TargetPrinter](../../aspose.imaging.imageoptions/tiffoptions/targetprinter) { get; set; } | Hedef yazıcıyı alır veya ayarlar. |
| [Threshholding](../../aspose.imaging.imageoptions/tiffoptions/threshholding) { get; set; } | Eşik değerini alır veya ayarlar. |
| [TileByteCounts](../../aspose.imaging.imageoptions/tiffoptions/tilebytecounts) { get; set; } | Döşeme bayt sayılarını alır veya ayarlar. |
| [TileLength](../../aspose.imaging.imageoptions/tiffoptions/tilelength) { get; set; } | Döşeme uzunluğunu ayarlar. |
| [TileOffsets](../../aspose.imaging.imageoptions/tiffoptions/tileoffsets) { get; set; } | Döşeme ofsetlerini alır veya ayarlar. |
| [TileWidth](../../aspose.imaging.imageoptions/tiffoptions/tilewidth) { get; set; } | Döşeme genişliğini ayarlar. |
| [TotalPages](../../aspose.imaging.imageoptions/tiffoptions/totalpages) { get; } | Toplam sayfaları alır. |
| [ValidTagCount](../../aspose.imaging.imageoptions/tiffoptions/validtagcount) { get; } | Geçerli etiket sayısını alır. Bu, toplam etiket sayısı değil, korunabilecek etiket sayısıdır. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| override [XmpData](../../aspose.imaging.imageoptions/tiffoptions/xmpdata) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |
| [XPAuthor](../../aspose.imaging.imageoptions/tiffoptions/xpauthor) { get; set; } | Windows Gezgini tarafından kullanılan görüntü yazarını alır veya ayarlar. |
| [XPComment](../../aspose.imaging.imageoptions/tiffoptions/xpcomment) { get; set; } | Windows Gezgini tarafından kullanılan resim üzerinde yorum alır veya ayarlar. |
| [XPKeywords](../../aspose.imaging.imageoptions/tiffoptions/xpkeywords) { get; set; } | Windows Gezgini tarafından kullanılan konu görüntüsünü alır veya ayarlar. |
| [Xposition](../../aspose.imaging.imageoptions/tiffoptions/xposition) { get; set; } | x konumunu alır veya ayarlar. |
| [XPSubject](../../aspose.imaging.imageoptions/tiffoptions/xpsubject) { get; set; } | Windows Gezgini tarafından kullanılan görüntü hakkında bilgi alır veya ayarlar. |
| [XPTitle](../../aspose.imaging.imageoptions/tiffoptions/xptitle) { get; set; } | Windows Gezgini tarafından kullanılan görüntü hakkında bilgi alır veya ayarlar. |
| [Xresolution](../../aspose.imaging.imageoptions/tiffoptions/xresolution) { get; set; } | x çözünürlüğünü alır veya ayarlar. |
| [YCbCrCoefficients](../../aspose.imaging.imageoptions/tiffoptions/ycbcrcoefficients) { get; set; } | YCbCrCoectives'i alır veya ayarlar. |
| [YCbCrSubsampling](../../aspose.imaging.imageoptions/tiffoptions/ycbcrsubsampling) { get; set; } | YCbCr fotometrik için alt örnekleme faktörlerini alır veya ayarlar. |
| [Yposition](../../aspose.imaging.imageoptions/tiffoptions/yposition) { get; set; } | Y konumunu alır veya ayarlar. |
| [Yresolution](../../aspose.imaging.imageoptions/tiffoptions/yresolution) { get; set; } | Y çözünürlüğünü alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddTag](../../aspose.imaging.imageoptions/tiffoptions/addtag)(TiffDataType) | Yeni bir etiket ekler. |
| [AddTags](../../aspose.imaging.imageoptions/tiffoptions/addtags)(TiffDataType[]) | Etiketleri ekler. |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Bu örneği klonlar. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |
| [GetTagByType](../../aspose.imaging.imageoptions/tiffoptions/gettagbytype)(TiffTags) | Türe göre etiketin örneğini alır. |
| [IsTagPresent](../../aspose.imaging.imageoptions/tiffoptions/istagpresent)(TiffTags) | Seçeneklerde etiketin bulunup bulunmadığını belirler. |
| [RemoveTag](../../aspose.imaging.imageoptions/tiffoptions/removetag)(TiffTags) | Etiketi kaldırır. |
| [Validate](../../aspose.imaging.imageoptions/tiffoptions/validate)() | Seçeneklerin geçerli etiket kombinasyonuna sahip olup olmadığını doğrular |
| static [GetValidTagsCount](../../aspose.imaging.imageoptions/tiffoptions/getvalidtagscount)(TiffDataType[]) | Geçerli etiket sayısını alır. |

### Örnekler

Bu örnek, dışa aktarma amacıyla SaveOptions Ad Alanından farklı sınıfların kullanımını gösterir. Gif türünde bir görüntü, bir Görüntü örneğine yüklenir ve ardından çeşitli biçimlere dışa aktarılır.

```csharp
[C#]

string dir = "c:\\temp\\";

//Mevcut bir görüntüyü (Gif türünde) bir Image sınıfı örneğine yükleyin
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(dir + "sample.gif"))
{
    //Varsayılan seçenekleri kullanarak BMP dosya formatına aktar
    image.Save(dir + "output.bmp", new Aspose.Imaging.ImageOptions.BmpOptions());

    //Varsayılan seçenekleri kullanarak JPEG dosya formatına aktar
    image.Save(dir + "output.jpg", new Aspose.Imaging.ImageOptions.JpegOptions());

    //Varsayılan seçenekleri kullanarak PNG dosya formatına aktar
    image.Save(dir + "output.png", new Aspose.Imaging.ImageOptions.PngOptions());

    //Varsayılan seçenekleri kullanarak TIFF dosya formatına aktar
    image.Save(dir + "output.tif", new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default));
}
```

Aşağıdaki örnek, çok sayfalı bir vektör görüntüsünün, belirli bir görüntü türüne başvurmadan genel olarak TIFF biçimine nasıl dönüştürüleceğini gösterir.

```csharp
[C#]

string dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548";
string inputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr");
string outputFilePath = System.IO.Path.Combine(dir, "Multipage.cdr.tiff");

Aspose.Imaging.ImageOptionsBase exportOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Aspose.Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFilePath))
{
    exportOptions.MultiPageOptions = null;

    // Yalnızca ilk iki sayfayı dışa aktar. Bu sayfalar TIFF çıktısında çerçeveler olarak sunulacaktır.
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

Bu örnekler, bir Görüntü yüzeyinde Şekiller oluşturmak ve işlemek için GraphicsPath ve Graphics sınıfını kullanır. Örnek, yeni bir Görüntü (Tiff tipinde) oluşturur, yüzeyi temizler ve GraphicsPath sınıfının yardımıyla yollar çizer. Sonunda, yolları yüzeyde işlemek için Graphics sınıfı tarafından sunulan DrawPath yöntemi çağrılır.

```csharp
[C#]

//FileStream örneğini oluştur
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\output.tiff", System.IO.FileMode.Create))
{
    // Bir TiffOptions örneği oluşturun ve çeşitli özelliklerini ayarlayın
    Aspose.Imaging.ImageOptions.TiffOptions tiffOptions = new Aspose.Imaging.ImageOptions.TiffOptions(Imaging.FileFormats.Tiff.Enums.TiffExpectedFormat.Default);

    // ImageOptions örneğinin kaynağını ayarlayın
    tiffOptions.Source = new Aspose.Imaging.Sources.StreamSource(stream);

    //Görüntü örneğini oluştur 
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(tiffOptions, 500, 500))
    {
        // Graphics sınıfının bir örneğini oluştur ve başlat
        Aspose.Imaging.Graphics graphics = new Aspose.Imaging.Graphics(image);

        //Grafik yüzeyini temizle
        graphics.Clear(Color.Wheat);

        // GraphicsPath sınıfının bir örneğini oluştur
        Aspose.Imaging.GraphicsPath graphicspath = new Aspose.Imaging.GraphicsPath();

        // Figure sınıfının bir örneğini oluşturun
        Aspose.Imaging.Figure figure = new Aspose.Imaging.Figure();

        // Figure nesnesine Şekiller Ekle
        figure.AddShape(new Aspose.Imaging.Shapes.RectangleShape(new Aspose.Imaging.RectangleF(10f, 10f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.EllipseShape(new Aspose.Imaging.RectangleF(50f, 50f, 300f, 300f)));
        figure.AddShape(new Aspose.Imaging.Shapes.PieShape(new Aspose.Imaging.RectangleF(new Aspose.Imaging.PointF(250f, 250f), new Aspose.Imaging.SizeF(200f, 200f)), 0f, 45f));

        // Figure nesnesini GraphicsPath'e ekle
        graphicspath.AddFigure(figure);

        // Siyah renkli Pen nesnesiyle yol çiz
        graphics.DrawPath(new Aspose.Imaging.Pen(Aspose.Imaging.Color.Black, 2), graphicspath);

        // tüm değişiklikleri kaydet.
        image.Save();
    }
}
```

### Ayrıca bakınız

* class [ImageOptionsBase](../../aspose.imaging/imageoptionsbase)
* ad alanı [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
