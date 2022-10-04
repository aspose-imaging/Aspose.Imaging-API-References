---
title: OdgRasterizationOptions
second_title: Aspose.Imaging for .NET API Referansı
description: Odg rasterleştirme seçenekleri
type: docs
weight: 10080
url: /tr/net/aspose.imaging.imageoptions/odgrasterizationoptions/
---
## OdgRasterizationOptions class

Odg rasterleştirme seçenekleri

```csharp
public class OdgRasterizationOptions : OdRasterizationOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [OdgRasterizationOptions](odgrasterizationoptions)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [BackgroundColor](../../aspose.imaging.imageoptions/vectorrasterizationoptions/backgroundcolor) { get; set; } | Bir arka plan rengi alır veya ayarlar. |
| [BorderX](../../aspose.imaging.imageoptions/vectorrasterizationoptions/borderx) { get; set; } | X. sınırını alır veya ayarlar |
| [BorderY](../../aspose.imaging.imageoptions/vectorrasterizationoptions/bordery) { get; set; } | Y. sınırını alır veya ayarlar |
| [BufferSizeHint](../../aspose.imaging/imageoptionsbase/buffersizehint) { get; set; } | Tüm dahili arabellekler için izin verilen maksimum boyut olarak tanımlanan arabellek boyutu ipucunu alır veya ayarlar. |
| [CenterDrawing](../../aspose.imaging.imageoptions/vectorrasterizationoptions/centerdrawing) { get; set; } | Merkez çizimi olup olmadığını gösteren bir değer alır veya ayarlar. |
| [Disposed](../../aspose.imaging/disposableobject/disposed) { get; } | Bu örneğin atılıp atılmadığını gösteren bir değer alır. |
| [DrawColor](../../aspose.imaging.imageoptions/vectorrasterizationoptions/drawcolor) { get; set; } | Bir ön plan rengi alır veya ayarlar. |
| [FullFrame](../../aspose.imaging/imageoptionsbase/fullframe) { get; set; } | [tam kare]. olup olmadığını belirten bir değer alır veya ayarlar. |
| [MultiPageOptions](../../aspose.imaging/imageoptionsbase/multipageoptions) { get; set; } | Çoklu sayfa seçenekleri |
| [PageHeight](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pageheight) { get; set; } | Sayfa yüksekliğini alır veya ayarlar. |
| [PageSize](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pagesize) { get; set; } | Sayfa boyutunu alır veya ayarlar. |
| [PageWidth](../../aspose.imaging.imageoptions/vectorrasterizationoptions/pagewidth) { get; set; } | Sayfa genişliğini alır veya ayarlar. |
| virtual [Palette](../../aspose.imaging/imageoptionsbase/palette) { get; set; } | Renk paletini alır veya ayarlar. |
| [Positioning](../../aspose.imaging.imageoptions/vectorrasterizationoptions/positioning) { get; set; } | Konumlandırmayı alır veya ayarlar. |
| [ProgressEventHandler](../../aspose.imaging/imageoptionsbase/progresseventhandler) { get; set; } | İlerleme olayı işleyicisini alır veya ayarlar. |
| virtual [ResolutionSettings](../../aspose.imaging/imageoptionsbase/resolutionsettings) { get; set; } | Çözünürlük ayarlarını alır veya ayarlar. |
| [SmoothingMode](../../aspose.imaging.imageoptions/vectorrasterizationoptions/smoothingmode) { get; set; } | Düzgünleştirme modunu alır veya ayarlar. |
| [Source](../../aspose.imaging/imageoptionsbase/source) { get; set; } | Görüntü oluşturmak için kaynağı alır veya ayarlar. |
| [TextRenderingHint](../../aspose.imaging.imageoptions/vectorrasterizationoptions/textrenderinghint) { get; set; } | Metin oluşturma ipucunu alır veya ayarlar. |
| [VectorRasterizationOptions](../../aspose.imaging/imageoptionsbase/vectorrasterizationoptions) { get; set; } | Vektör rasterleştirme seçeneklerini alır veya ayarlar. |
| virtual [XmpData](../../aspose.imaging/imageoptionsbase/xmpdata) { get; set; } | XMP meta veri kapsayıcısını alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Clone](../../aspose.imaging/imageoptionsbase/clone)() | Bu örneği klonlar. |
| [CopyTo](../../aspose.imaging.imageoptions/vectorrasterizationoptions/copyto)(VectorRasterizationOptions) | Kopyalar. |
| [Dispose](../../aspose.imaging/disposableobject/dispose)() | Geçerli örneği atar. |

### Örnekler

Aşağıdaki örnek, bir FODG (Düz XML ODF Şablonu) görüntüsünün PDF formatına nasıl dışa aktarılacağını gösterir.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3635";

string inputFileName = System.IO.Path.Combine(dir, "VariousObjectsMultiPage.fodg");
string outputFileName = inputFileName + ".pdf";

using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(inputFileName))
{
    Aspose.Imaging.ImageOptions.OdgRasterizationOptions rasterizationOptions = new Aspose.Imaging.ImageOptions.OdgRasterizationOptions();
    rasterizationOptions.BackgroundColor = Aspose.Imaging.Color.White;
    rasterizationOptions.PageSize = image.Size;

    Aspose.Imaging.ImageOptions.PdfOptions saveOptions = new Aspose.Imaging.ImageOptions.PdfOptions();
    saveOptions.VectorRasterizationOptions = rasterizationOptions;

    image.Save(outputFileName, saveOptions);
}
```

### Ayrıca bakınız

* class [OdRasterizationOptions](../odrasterizationoptions)
* ad alanı [Aspose.Imaging.ImageOptions](../../aspose.imaging.imageoptions)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->