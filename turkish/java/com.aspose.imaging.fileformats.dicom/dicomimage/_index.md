---
title: "DicomImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bu Sınıf, Digital Imaging and Communications in Medicine DICOM raster görüntü formatı desteğini uygular ve DICOM görüntülerini hassasiyet ve esneklikle işlemek için kapsamlı bir çözüm sunar."
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.fileformats.dicom/dicomimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public final class DicomImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

Bu Sınıf, Digital Imaging and Communications in Medicine (DICOM) raster görüntü formatı desteğini uygular ve DICOM görüntülerini hassasiyet ve esneklikle işlemek için kapsamlı bir çözüm sunar. Görüntü sayfalarını sorunsuz bir şekilde yönetebilirsiniz; sayfaları alma, ekleme veya kaldırma işlemleri ve varsayılan ve etkin sayfaları kontrol etme dahil. Alfa kanallarıyla çalışma, XMP meta verilerini gömme, yeniden boyutlandırma, döndürme, kırpma, ikilileştirme, ayarlama, filtre uygulama ve diğer raster formatlarına dönüştürme yeteneklerine sahiptir. Bu API, geliştiricilerin DICOM görüntülerini etkili bir şekilde ele almasını sağlar ve tıbbi görüntüleme bağlamlarında çeşitli uygulama gereksinimlerini karşılar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DicomImage(DicomOptions dicomOptions, int width, int height)](#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-) | Bu yapıcıyı kullanarak DicomImage sınıfının yeni bir örneğini sorunsuz bir şekilde başlatın, dicomOptions parametrelerini kullanarak. |
| [DicomImage(InputStream stream, LoadOptions loadOptions)](#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Bu yapıcıda bir akış ve loadOptions parametrelerini kullanarak DicomImage sınıfının yeni bir örneğini sorunsuz bir şekilde başlatın. |
| [DicomImage(InputStream stream)](#DicomImage-java.io.InputStream-) | Bu yapıcıda bir akış parametresi kullanarak DicomImage sınıfının yeni bir örneğini oluşturun. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPageCount()](#getPageCount--) | Bu sezgisel özellik sayesinde görüntünün toplam sayfa sayısını alın. |
| [getPages()](#getPages--) | Bu sezgisel özellik ile görüntünün sayfalarına erişin. |
| [getFileInfo()](#getFileInfo--) | Bu sezgisel özellik ile DICOM dosyasından değerli başlık bilgilerini zahmetsizce alın. |
| [getDicomPages()](#getDicomPages--) | Bu sezgisel özellik ile görüntünün sayfalarına erişin. |
| [getActivePage()](#getActivePage--) | Bu sezgisel özellik ile görüntünün aktif sayfasına erişin. |
| [setActivePage(DicomPage value)](#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-) | Bu sezgisel özellik ile görüntünün aktif sayfasını yönetin. |
| [getActivePageIndex()](#getActivePageIndex--) | Bu sezgisel özellik ile aktif sayfanın dizinini zahmetsizce alın. |
| [getFileFormat()](#getFileFormat--) | Bu sezgisel özellik ile dosya formatı değerini zahmetsizce alın. |
| [hasAlpha()](#hasAlpha--) | Bu sezgisel özellik ile görüntünün alfa kanalı olup olmadığını zahmetsizce öğrenin. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Bu sezgisel yöntemle yeni bir sayfa ekleyerek görüntü koleksiyonunuzu genişletin. |
| [saveAll(String filePath, ImageOptionsBase options)](#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-) | Nesnenin verilerini, belirtilen dosya formatı ve seçeneklerle birlikte belirlenen dosya (indeksleyici + dosya adı) konumuna kaydederek koruyun. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Bu [RasterImage](../../com.aspose.imaging/rasterimage) çözünürlüğünü bu basit yöntemi kullanarak hassas bir şekilde ayarlayın. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Bu kullanışlı yöntemle görüntünün en‑boy oranını koruyarak yeniden boyutlandırın. |
| [addPage()](#addPage--) | Bu basit yöntemle görüntünün sayfa listesine yeni bir sayfayı sona ekleyin. |
| [insertPage(int pageIndex)](#insertPage-int-) | Bu sezgisel yöntemle görüntünün sayfa listesine belirtilen bir indekste yeni bir sayfa ekleyin. |
| [removePage(int pageIndex)](#removePage-int-) | Bu kullanışlı yöntemle sayfa listesinden belirtilen indeksteki sayfayı kaldırın. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Bu kullanışlı yöntemle görüntüyü merkez etrafında döndürün. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Bu basit yöntemle görüntünün boyutunu ayarlayın. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Bu kullanışlı yöntemle görüntünün enini, en‑boy oranını koruyarak ayarlayın. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Bu kullanıcı dostu yöntemle görüntünün yüksekliğini, en‑boy oranını koruyarak ayarlayın. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Bu basit yöntemle aktif çerçeveyi döndürerek, çevirerek veya her iki işlemi aynı anda yaparak kolayca manipüle edin. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Bu basit yöntemle mevcut görüntüyü dithering efektleri uygulayarak geliştirin. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Bu basit yöntemle istenmeyen alanları kırparak ve temel içeriğe odaklanarak görüntüyü kırpın. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Bu çok yönlü yöntemle kaydırmalar uygulayarak görüntünün kırpma alanını ayarlayın. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Bu basit yöntemle önceden tanımlı bir eşik kullanarak görüntüyü kolayca ikili formata dönüştürün. |
| [binarizeOtsu()](#binarizeOtsu--) | Görüntüyü ikili hale getirmek için Otsu eşikleme uygula, görüntünün histogramına dayanarak optimal eşik değerini otomatik olarak belirler. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Bradley'nin uyarlamalı eşikleme algoritmasıyla görüntüleri ikili hale getir, geliştirilmiş performans için integral görüntü eşiklemeyi kullan. |
| [grayscale()](#grayscale--) | Görüntüleri kolayca gri tonlamalı temsiline dönüştür, görsel analiz ve işleme görevlerini basitleştir. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Görüntü kalitesini artır ve görsel görünümü ince ayarlamak için güçlü bir teknik olan gama düzeltmesiyle ayarla. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Bir görüntünün kırmızı, yeşil ve mavi bileşenlerine gama düzeltmesini bağımsız olarak uygulayarak hassas renk ayarlamaları elde et. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | `brightness` ayarıyla görüntü parlaklığını artır, geliştiricilerin görüntülerin ışık seviyesini ince ayarlamasına olanak tanıyan parametreli bir yöntem. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Bu kullanıcı dostu yöntemle [Image](../../com.aspose.imaging/image) kontrastını artır, ışık ve karanlık alanlar arasındaki farkı ayarlar. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Belirlenmiş dikdörtgenlere filtre uygulayarak görüntünüzün belirli bölgelerini zahmetsizce iyileştirin. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Bu basit yeniden boyutlandırma yöntemiyle görüntünüzün boyutunu ayarlayın. |
| [cacheData()](#cacheData--) | Bu yöntem verileri verimli bir şekilde önbelleğe alır, performansı optimize eder ve gerektiğinde hızlı erişim sağlar. |

## Example: This example demonstrates the loading and exporting of dicom file.

``` java

String dir = "c:\\temp\\";

// Bir görüntü yükle
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load("sample.dicom");
try {
    image.adjustBrightness(50);
    image.save(dir + "sample.dicom.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```


## Example: Create a multi-page Dicom image.

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Vektör grafikleri kullanarak bir şey çizin
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Çizilen görüntünün piksellerini kaydedin. Artık Dicom görüntüsünün ilk sayfasındalar.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Sonra birkaç sayfa ekleyin, onları daha karanlık hale getirerek
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Ana sayfanın önüne birkaç sayfa ekleyin, onları daha parlak yaparak
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Oluşturulan çok sayfalı görüntüyü çıktı dosyasına kaydedin
        image.save("MultiPage.dcm");
    }
}
```


## Example: Use JPEG compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg);
    JpegOptions jpegOptions = new JpegOptions();
    jpegOptions.setCompressionType(JpegCompressionMode.Baseline);
    jpegOptions.setSampleRoundingMode(SampleRoundingMode.Truncate);
    jpegOptions.setQuality(50);
    compression.setJpeg(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG.dcm", options);
}
```


## Example: Use JPEG 2000 compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Jpeg2000);
    Jpeg2000Options jpegOptions = new Jpeg2000Options();
    jpegOptions.setCodec(Jpeg2000Codec.Jp2);
    jpegOptions.setIrreversible(false);
    compression.setJpeg2000(jpegOptions);

    options.setCompression(compression);

    inputImage.save("original_JPEG2000.dcm", options);
}
```


## Example: Use RLE compression in DICOM image.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Rgb24Bit);

    Compression compression = new Compression();
    compression.setType(CompressionType.Rle);
    options.setCompression(compression);

    inputImage.save("original_RLE.dcm", options);
}
```


## Example: Change Color Type in DICOM compression.

``` java
try (Image inputImage = Image.load("original.jpg"))
{
    DicomOptions options = new DicomOptions();
    options.setColorType(ColorType.Grayscale8Bit);

    inputImage.save("original_8Bit.dcm", options);
}
```

### DicomImage(DicomOptions dicomOptions, int width, int height) {#DicomImage-com.aspose.imaging.imageoptions.DicomOptions-int-int-}
```
public DicomImage(DicomOptions dicomOptions, int width, int height)
```


Bu yapıcıyı kullanarak DicomImage sınıfının yeni bir örneğini zahmetsizce başlat, dicomOptions parametrelerini kullan. Projelerinde [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) nesnelerine hızlı ve verimli bir şekilde dalmak isteyen geliştiriciler için mükemmeldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dicomOptions | [DicomOptions](../../com.aspose.imaging.imageoptions/dicomoptions) | Dicom seçenekleri (şimdilik yok sayılıyor). |
| genişlik | int | Genişlik. |
| yükseklik | int | Yükseklik. |

### DicomImage(InputStream stream, LoadOptions loadOptions) {#DicomImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DicomImage(InputStream stream, LoadOptions loadOptions)
```


Bu yapıcıda bir akış ve loadOptions parametrelerini kullanarak DicomImage sınıfının yeni bir örneğini sorunsuz bir şekilde başlat. Projelerinde [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) nesneleriyle hızlı ve etkili bir şekilde çalışmaya hevesli geliştiriciler için idealdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

### DicomImage(InputStream stream) {#DicomImage-java.io.InputStream-}
```
public DicomImage(InputStream stream)
```


Bu yapıcıda bir akış parametresi kullanarak DicomImage sınıfının yeni bir örneğini oluştur. Mevcut veri akışlarından [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) nesnelerini başlatmak isteyen geliştiriciler için mükemmeldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Bu sezgisel özellik ile görüntünün toplam sayfa sayısını al. Görüntü içindeki sayfa sayısına hızlı erişim arayan geliştiriciler için idealdir, verimli gezinme ve yönetim sağlar.

**Returns:**
int - sayfa sayısı.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Bu sezgisel özellik ile görüntünün sayfalarına eriş. Görüntü içindeki tek tek sayfalarla etkileşime girmek isteyen geliştiriciler için idealdir, sorunsuz gezinme ve manipülasyon sağlar.

**Returns:**
com.aspose.imaging.Image[] - sayfalar.
### getFileInfo() {#getFileInfo--}
```
public DicomImageInfo getFileInfo()
```


Bu sezgisel özellik ile DICOM dosyasından değerli başlık bilgilerini zahmetsizce al. DICOM dosyasında kapsüllenmiş temel detaylara hızlı erişim arayan geliştiriciler için idealdir, verimli veri çıkarma ve analiz sağlar.

**Returns:**
[DicomImageInfo](../../com.aspose.imaging.fileformats.dicom/dicomimageinfo) - a value, which contains info header the DICOM file
### getDicomPages() {#getDicomPages--}
```
public DicomPage[] getDicomPages()
```


Bu sezgisel özellik ile görüntünün sayfalarına eriş. Görüntü içindeki tek tek sayfalarla etkileşime girmek isteyen geliştiriciler için idealdir, sorunsuz gezinme ve manipülasyon sağlar.

**Returns:**
com.aspose.imaging.fileformats.dicom.DicomPage[] - sayfalar.
### getActivePage() {#getActivePage--}
```
public DicomPage getActivePage()
```


Bu sezgisel özellik ile görüntünün aktif sayfasına eriş. Çok sayfalı görüntülerde sayfalar arasında dinamik olarak geçiş yapmak isteyen geliştiriciler için idealdir, verimli gezinme ve işleme sağlar.

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - the active page.
### setActivePage(DicomPage value) {#setActivePage-com.aspose.imaging.fileformats.dicom.DicomPage-}
```
public void setActivePage(DicomPage value)
```


Bu sezgisel özellik ile görüntünün aktif sayfasını yönet. Çok sayfalı görüntülerde sayfalar arasında dinamik geçiş yapmak isteyen geliştiriciler için idealdir, verimli gezinme ve işleme sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) | aktif sayfa. |

### getActivePageIndex() {#getActivePageIndex--}
```
public int getActivePageIndex()
```


Bu sezgisel özellik ile aktif sayfanın indeksini zahmetsizce al. Çok sayfalı görüntülerde mevcut sayfa indeksine hızlı erişim arayan geliştiriciler için idealdir, verimli gezinme ve işleme sağlar.

**Returns:**
int - aktif sayfanın indeksi.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Bu sezgisel özellik ile dosya formatı değerini zahmetsizce al. Görüntü dosyasının formatına hızlı erişim arayan geliştiriciler için idealdir, dosya türüne göre verimli işleme ve yönetim sağlar.

**Returns:**
long - dosya formatı değeri [FileFormat](../../com.aspose.imaging/fileformat).
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Resmin alfa kanalına sahip olup olmadığını bu sezgisel özellik ile zahmetsizce alın. Görüntünün şeffaflık bilgisi içerip içermediğini belirlemek isteyen geliştiriciler için idealdir ve alfa kanal verilerinin görüntü işleme görevlerinde hassas bir şekilde ele alınmasını sağlar.

**Returns:**
boolean - resim alfa kanalı içeriyorsa true.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Bu sezgisel yöntemle yeni bir sayfa ekleyerek görüntü koleksiyonunuzu genişletin. Çok sayfalı görüntülere dinamik olarak sayfa eklemek isteyen geliştiriciler için idealdir ve görüntü içeriğinin sorunsuz bir şekilde genişlemesi ve düzenlenmesini sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Eklenecek sayfa. |

### saveAll(String filePath, ImageOptionsBase options) {#saveAll-java.lang.String-com.aspose.imaging.ImageOptionsBase-}
```
public void saveAll(String filePath, ImageOptionsBase options)
```


Nesnenin verilerini, belirtilen dosya (indeks + dosya adı) konumuna, seçilen dosya formatı ve seçeneklerle kaydederek koruyun. Çeşitli formatlarda verileri güvenli bir şekilde depolamak ve kaydetme parametreleri üzerinde esneklik ve kontrol sağlamak isteyen geliştiriciler için idealdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya yolu. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Seçenekler. |

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Bu doğrudan yöntemle bu [RasterImage](../../com.aspose.imaging/rasterimage) çözünürlüğünü hassas bir şekilde ayarlayın. Görüntü çözünürlüğünü belirli gereksinimlere göre özelleştirmek isteyen geliştiriciler için idealdir ve optimal görüntü kalitesi ve dosya boyutu yönetimini sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dpiX | double | The horizontal resolution, in dots per inch, of the [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | The vertical resolution, in dots per inch, of the [RasterImage](../../com.aspose.imaging/rasterimage). |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Bu kullanışlı yöntemle görüntüyü en boy oranını koruyarak yeniden boyutlandırın. Görüntü boyutlarını orantılı olarak ayarlamak isteyen geliştiriciler için idealdir, tutarlılığı sağlar ve orijinal içeriğin oranlarını korur. Orantılı yeniden boyutlandırma, her çerçeveyi `newWidth`/width ve `newHeight`/height oranına göre yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |

### addPage() {#addPage--}
```
public DicomPage addPage()
```


Bu doğrudan yöntemle görüntünün sayfa listesine yeni bir sayfa ekleyin. Çok sayfalı görüntüleri dinamik olarak genişletmek isteyen geliştiriciler için idealdir ve görüntü içeriğinin sorunsuz entegrasyonu ve düzenlenmesini sağlar.

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).
### insertPage(int pageIndex) {#insertPage-int-}
```
public DicomPage insertPage(int pageIndex)
```


Bu sezgisel yöntemle görüntünün sayfa listesine belirtilen bir indeks'te yeni bir sayfa ekleyin. Çok sayfalı görüntülerde sayfa düzeni üzerinde hassas kontrol sağlamak isteyen geliştiriciler için idealdir ve görüntü içeriğinin sorunsuz düzenlenmesi ve özelleştirilmesini sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageIndex | int | Sayfanın indeksi. |

**Returns:**
[DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage) - The newly created [DicomPage](../../com.aspose.imaging.fileformats.dicom/dicompage).

**Example: Create a multi-page Dicom image.**

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Vektör grafikleri kullanarak bir şey çizin
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Çizilen görüntünün piksellerini kaydedin. Artık Dicom görüntüsünün ilk sayfasındalar.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Sonra birkaç sayfa ekleyin, onları daha karanlık hale getirerek
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Ana sayfanın önüne birkaç sayfa ekleyin, onları daha parlak yaparak
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Oluşturulan çok sayfalı görüntüyü çıktı dosyasına kaydedin
        image.save("MultiPage.dcm");
    }
}
```

### removePage(int pageIndex) {#removePage-int-}
```
public void removePage(int pageIndex)
```


Bu kullanışlı yöntemle belirtilen indeksteki sayfayı sayfa listesinden kaldırın. Çok sayfalı görüntülerin yönetimi üzerinde hassas kontrol sağlamak isteyen geliştiriciler için idealdir ve görüntü içeriğinin sorunsuz düzenlenmesi ve özelleştirilmesini sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pageIndex | int | Sayfanın indeksi. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Bu kullanışlı yöntemle görüntüyü merkez etrafında döndürün. Görüntü yönünü dinamik olarak ayarlamak isteyen geliştiriciler için idealdir ve uygulamalarında optimal sunum ve hizalama sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Dönme açısı derece cinsindendir. Pozitif değerler saat yönünde döndürür. |
| resizeProportionally | boolean | eğer `true` olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgenin (köşe noktaları) izdüşümlerine göre değişir; diğer durumda boyutlar dokunulmaz kalır ve sadece `` görüntü içeriği döndürülür. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Arka planın rengi. |


**Example: This example shows how to rotate all pages of a DICOM image and save them all to a multi-frame TIFF image.**

``` java
String dir = "c:\\temp\\";

// Bir dosya akışından DICOM görüntüsü yükleyin.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "multiframe.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = new com.aspose.imaging.fileformats.dicom.DicomImage(stream);
    try {
        // Görüntüyü merkez etrafında saat yönünde 60 derece döndürün.
        // Arka plan rengi olarak gri kullanın.
        dicomImage.rotate(60, true, com.aspose.imaging.Color.getGray());

        com.aspose.imaging.imageoptions.TiffOptions createOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
        createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Deflate);

        // Görüntü renkliyse, aşağıdaki seçeneklere göre otomatik olarak gri tonlamalı formata dönüştürüleceğini unutmayın.
        createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
        createOptions.setBitsPerSample(new int[]{8});

        // TIFF çerçevelerinden bir dizi oluşturun.
        // Çerçeve sayısı DJVU sayfa sayısına eşittir.
        com.aspose.imaging.fileformats.dicom.DicomPage[] pages = dicomImage.getDicomPages();
        com.aspose.imaging.fileformats.tiff.TiffFrame[] tiffFrames = new com.aspose.imaging.fileformats.tiff.TiffFrame[pages.length];

        // Her sayfayı ayrı bir TIFF çerçevesi olarak kaydedin.
        for (com.aspose.imaging.fileformats.dicom.DicomPage dicomPage : pages) {
            // DICOM sayfasına dayalı bir TIFF çerçevesi oluşturun.
            tiffFrames[dicomPage.getIndex()] = new com.aspose.imaging.fileformats.tiff.TiffFrame(dicomPage, createOptions);
        }

        // Çerçevelerden bir TIFF görüntüsü oluşturun.
        com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(tiffFrames);
        try {
            // Bir dosyaya kaydet.
            tiffImage.save(dir + "multiframe.tif");
        } finally {
            tiffImage.dispose();
        }
    } finally {
        dicomImage.dispose();
    }
} finally {
    stream.close();
}
```

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Bu doğrudan yöntemle görüntünün boyutunu ayarlayın. Görüntüleri dinamik olarak yeniden boyutlandırmak isteyen geliştiriciler için idealdir ve uygulamalarındaki çeşitli bağlam ve düzenlere sorunsuz bir şekilde uyum sağlamasını garantiler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |


**Example: This example loads a DICOM image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Bu kullanışlı yöntemle görüntünün genişliğini en boy oranını koruyarak ayarlayın. Görüntüleri orantılı olarak yeniden boyutlandırmak isteyen geliştiriciler için idealdir ve farklı görüntü ortamlarında tutarlı ve görsel olarak çekici sonuçlar sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| resizeType | int | Yeniden boyutlandırma türü. |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
Bu örnek bir DICOM görüntüsü yükler ve çeşitli yeniden boyutlandırma yöntemleri kullanarak orantılı olarak yeniden boyutlandırır. Yalnızca genişlik belirtilir, yükseklik otomatik olarak hesaplanır.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat küçült.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Bu kullanıcı dostu yöntemle görüntünün yüksekliğini, en boy oranını koruyarak ayarlayın. Görüntülerin dinamik olarak yeniden boyutlandırılmasını ve oranlarının korunmasını isteyen geliştiriciler için mükemmeldir; uygulamalarında optimal görüntüleme ve kullanılabilirlik sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |


**Example: This example loads a DICOM image and resizes it proportionally using various resizing methods.**
Bu örnek bir DICOM görüntüsü yükler ve çeşitli yeniden boyutlandırma yöntemleri kullanarak orantılı olarak yeniden boyutlandırır. Yalnızca yükseklik belirtilir, genişlik otomatik olarak hesaplanır.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat küçült.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydedin.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Bu basit yöntemle aktif çerçeveyi döndürerek, çevirerek veya her iki işlemi aynı anda gerçekleştirerek kolayca manipüle edin. Görüntü dizilerindeki belirli çerçevelerin yönünü dinamik olarak ayarlamaları gereken geliştiriciler için idealdir; optimal sunum ve hizalama sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateFlipType | int | Döndürme çevirme türü. |


**Example: This example loads a DICOM image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Döndür, çevir ve çıktıyı dosyaya kaydet.
    com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + rotateFlipType + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Bu basit yöntemle mevcut görüntüyü dithering efektleri uygulayarak geliştirin. Görüntülere doku ve derinlik eklemeyi hedefleyen geliştiriciler için mükemmeldir; görsel kaliteyi ve genel çekiciliği artırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ditheringMethod | int | Dithering yöntemi. |
| bitsCount | int | Dithering için son bit sayısı. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Dithering için özel palet. |


**Example: The following example loads a DICOM image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // 16 renk içeren 4-bit renk paleti kullanarak eşik dithering uygulayın.
    // Daha fazla bit belirtildiğinde çıktı görüntüsünün kalitesi daha yüksek ve boyutu daha büyük olur.
    // Şu anda yalnızca 1-bit, 4-bit ve 8-bit paletlerin desteklendiğini unutmayın.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Sadece 2 renk (siyah ve beyaz) içeren 1-bit renk paleti kullanarak Floyd dithering uygulayın.
    // Daha fazla bit belirtildiğinde çıktı görüntüsünün kalitesi daha yüksek ve boyutu daha büyük olur.
    // Şu anda yalnızca 1-bit, 4-bit ve 8-bit paletlerin desteklendiğini unutmayın.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Bu basit yöntemle görüntüyü kırparak istenmeyen alanları kaldırın ve temel içeriğe odaklanın. Görüntülerin görsel kompozisyonunu özelleştirmek isteyen geliştiriciler için idealdir; istenen mesajı etkili bir şekilde iletmelerini sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |


**Example: The following example crops a DICOM image.**
Aşağıdaki örnek bir DICOM görüntüsünü kırpar. Kırpma alanı Aspose.Imaging.Rectangle aracılığıyla belirtilir.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Görüntüyü kırp. Kırpma alanı, görüntünün dikdörtgen merkezi alanıdır.
    com.aspose.imaging.Rectangle area =
            new com.aspose.imaging.Rectangle(
                    dicomImage.getWidth() / 4, dicomImage.getHeight() / 4, dicomImage.getWidth() / 2, dicomImage.getHeight() / 2);
    dicomImage.crop(area);

    // Kırpılmış görüntüyü PNG olarak kaydet.
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Bu çok yönlü yöntemle kaydırmalar uygulayarak görüntünün kırpma alanını ayarlayın. Kırpma sürecinde hassas kontrol ihtiyacı duyan geliştiriciler için mükemmeldir; önemli detayların korunmasını sağlarken gereksiz öğeleri ortadan kaldırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| leftShift | int | Sol kaydırma. |
| rightShift | int | Sağ kaydırma. |
| topShift | int | Üst kaydırma. |
| bottomShift | int | Alt kaydırma. |


**Example: The following example crops a DICOM image.**
Aşağıdaki örnek bir DICOM görüntüsünü kırpar. Kırpma alanı Sol, Üst, Sağ, Alt kenar boşluklarıyla belirtilir.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Tekrar kırpın. Görüntü boyutunun %10'u kadar bir kenar boşluğu ayarlayın.
    int horizontalMargin = dicomImage.getWidth() / 10;
    int verticalMargin = dicomImage.getHeight() / 10;
    dicomImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Kırpılmış görüntüyü PNG olarak kaydedin.
    dicomImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Bu basit yöntemle önceden tanımlı bir eşik kullanarak görüntüyü ikili formata kolayca dönüştürün. Belirtilen yoğunluk seviyelerine göre görüntüyü ön plan ve arka plan bileşenlerine ayırarak görüntü işleme görevlerini basitleştirmek isteyen geliştiriciler için idealdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | byte | Eşik değeri. Bir pikselin ilgili gri değeri eşiğin üzerindeyse, ona 255 değeri atanır, aksi takdirde 0 atanır. |


**Example: The following example binarizes a DICOM image with the predefined threshold.**
Aşağıdaki örnek önceden tanımlı eşik ile bir DICOM görüntüsünü ikili hale getirir. İkili görüntüler yalnızca 2 renkten oluşur - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Görüntüyü 127 eşik değeriyle ikilileştirin.
    // Bir pikselin ilgili gri değeri 127'den büyükse, ona 255 değeri atanır, aksi takdirde 0.
    dicomImage.binarizeFixed((byte) 127);
    dicomImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Görüntüyü ikili hale getirmek için Otsu eşikleme uygulayın; görüntünün histogramına dayanarak optimal eşik değerini otomatik olarak belirler. Görüntüleri ön plan ve arka plan bölgelerine minimum manuel müdahale ile bölmek isteyen geliştiriciler için mükemmeldir.


**Example: The following example binarizes a DICOM image with Otsu thresholding.**
Aşağıdaki örnek Otsu eşikleme ile bir DICOM görüntüsünü ikili hale getirir. İkili görüntüler yalnızca 2 renkten oluşur - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Görüntüyü Otsu eşikleme ile ikilileştirin.
    dicomImage.binarizeOtsu();
    dicomImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Bradley'in adaptif eşikleme algoritmasıyla görüntüleri ikili hale getirin; geliştirilmiş performans için integral görüntü eşiklemeyi kullanır. Parlaklıkta yerel değişikliklere dayalı olarak görüntüleri otomatik olarak bölmek isteyen geliştiriciler için idealdir; değişken aydınlatma koşullarında doğru nesne tespiti ve çıkarımı sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightnessDifference | double | Bu pikselin etrafında merkezlenmiş s x s piksellik bir pencerenin ortalaması ile piksel arasındaki parlaklık farkı. |
| windowSize | int | Bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin boyutu |


**Example: The following example binarizes a DICOM image with Bradley's adaptive thresholding algorithm with the specified window size.**
Aşağıdaki örnek belirtilen pencere boyutuyla Bradley'in adaptif eşikleme algoritması kullanarak bir DICOM görüntüsünü ikili hale getirir. İkili görüntüler yalnızca 2 renkten oluşur - siyah ve beyaz.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Görüntüyü 5 parlaklık farkı ile ikili hale getirin. Parlaklık, bir piksel ile bu pikselin etrafındaki 10 x 10 pencere ortalaması arasındaki farktır.
    dicomImage.binarizeBradley(5, 10);
    dicomImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Görüntüleri kolayca gri tonlamalı temsiline dönüştürün; görsel analiz ve işleme görevlerini basitleştirir. Görüntü netliğini artırmak, karmaşıklığı azaltmak ve çeşitli uygulamalar için verimli gri tonlamalı algoritmaları kolaylaştırmak isteyen geliştiriciler için mükemmeldir.


**Example: The following example transforms a colored DICOM image to its grayscale representation.**
Aşağıdaki örnek renkli bir DICOM görüntüsünü gri tonlamalı temsiline dönüştürür. Gri tonlamalı görüntüler yalnızca gri tonlardan oluşur ve sadece yoğunluk bilgisi taşır.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    dicomImage.grayscale();
    dicomImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Görüntü kalitesini artırın ve gamma düzeltmesiyle ayarlayın; görsel görünümü ince ayarlamak için güçlü bir tekniktir. Görüntü sunumunu optimize etmeyi, renk dengesini ayarlamayı ve farklı cihaz ve ortamlar arasında tutarlı render almayı hedefleyen geliştiriciler için mükemmeldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gamma | float | Kırmızı, yeşil ve mavi kanallar için gamma katsayısı |


**Example: The following example performs gamma-correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Kırmızı, yeşil ve mavi kanallar için gamma katsayısını ayarlayın.
    dicomImage.adjustGamma(2.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Bir görüntünün kırmızı, yeşil ve mavi bileşenlerine gamma düzeltmesini bağımsız olarak uygulayarak hassas renk ayarlamaları elde edin. Bu yöntem doğru renk dengesini ve optimal görsel çıktıyı sağlar; görüntü renderı ve renk doğruluğu üzerinde ayrıntılı kontrol isteyen geliştiricilere hitap eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gammaRed | float | Kırmızı kanal katsayısı için gama |
| gammaGreen | float | Yeşil kanal katsayısı için gama |
| gammaBlue | float | Mavi kanal katsayısı için gamma |


**Example: The following example performs gamma-correction of a DICOM image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Kırmızı, yeşil ve mavi kanallar için ayrı ayrı gamma katsayılarını ayarlayın.
    dicomImage.adjustGamma(1.5f, 2.5f, 3.5f);
    dicomImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Görüntü parlaklığını `brightness` ayarıyla artırın; geliştiricilerin görüntülerin ışıklılığını hassas bir şekilde ayarlamasına olanak tanıyan parametreli bir yöntemdir. Bu kullanıcı dostu fonksiyon, geliştiricilerin görüntü parlaklığını sorunsuz bir şekilde manipüle etmelerini sağlar; görsel estetik üzerinde esneklik ve kontrol sunar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightness | int | Parlaklık değeri. |


**Example: The following example performs brightness correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Parlaklık değerini ayarlayın. Kabul edilen parlaklık değerleri [-255, 255] aralığındadır.
    dicomImage.adjustBrightness(50);
    dicomImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Bu kullanıcı dostu yöntemle [Image](../../com.aspose.imaging/image) kontrastını artırın; ışık ve karanlık alanlar arasındaki farkı ayarlar. Görsel netliği ve tanımlamayı zahmetsizce iyileştirin; geliştiricilere optimal render için görüntü kontrastı üzerinde sezgisel kontrol sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| contrast | float | Kontrast değeri ([-100; 100] aralığında) |


**Example: The following example performs contrast correction of a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Kontrast değerini ayarlayın. Kabul edilen kontrast değerleri [-100f, 100f] aralığındadır.
    dicomImage.adjustContrast(50f);
    dicomImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Belirlenmiş dikdörtgenlere filtreler uygulayarak görüntünüzün belirli alanlarını zahmetsizce geliştirin. Bu yöntem, geliştiricilere görüntü manipülasyonu üzerinde hassas kontrol sağlar; istenen görsel efektleri kolayca elde etmek için hedeflenmiş ayarlamalara izin verir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Seçenekler. |


**Example: The following example applies various types of filters to a DICOM image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Tüm görüntüye, dikdörtgen boyutu 5 olan bir medyan filtresi uygula.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    dicomImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Tüm görüntüye, çekirdek boyutu 5 olan çift taraflı yumuşatma filtresi uygula.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    dicomImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Tüm görüntüye, yarıçapı 5 ve sigma değeri 4.0 olan bir Gaussian bulanıklaştırma filtresi uygula.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Tüm görüntüye, yarıçapı 5 ve pürüzsüzlük değeri 4.0 olan bir Gauss-Wiener filtresi uygula.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Tüm görüntüye, uzunluğu 5, pürüzsüzlük değeri 4.0 ve açısı 90.0 derece olan bir hareket Wiener filtresi uygula.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    dicomImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Tüm görüntüye, çekirdek boyutu 5 ve sigma değeri 4.0 olan bir keskinleştirme filtresi uygula.
    dicomImage.filter(dicomImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    dicomImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Bu basit yeniden boyutlandırma yöntemiyle görüntünüzün boyutunu ayarlayın. Görüntünüzü küçültmeniz veya büyütmeniz gerektiğinde, bu fonksiyon yeniden boyutlandırma ihtiyaçlarınızı verimli ve doğru bir şekilde karşılar; hızlı ve kolay görüntü boyutu ayarlamaları isteyen geliştiriciler için mükemmeldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Yeniden boyutlandırma ayarları. |


**Example: This example loads a DICOM image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// Ağırlıklı ve karıştırılmış rasyonel fonksiyon ve lanczos3 enterpolasyonu üzerine kurulu uyarlamalı algoritma.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Küçük dikdörtgen filtre
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Palet içindeki renk sayısı.
resizeSettings.setEntriesCount(256);

// Renk kantitatizasyonu kullanılmaz
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// Euclidian yöntemi
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.dicom");
{
    com.aspose.imaging.fileformats.dicom.DicomImage dicomImage = (com.aspose.imaging.fileformats.dicom.DicomImage) image;

    // Uyarlanabilir yeniden örnekleme kullanarak 2 kat küçült.
    dicomImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // PNG'ye kaydet
    dicomImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Bu yöntem verileri verimli bir şekilde önbelleğe alır, performansı optimize eder ve gerektiğinde hızlı erişim sağlar. Veri kaynaklarını akıllıca yöneterek uygulamalarının hızını ve verimliliğini artırmak isteyen geliştiriciler için idealdir.


**Example: The following example shows how to cache all pages of a DICOM image.**

``` java
String dir = "c:\\temp\\";

// Bir DICOM dosyasından görüntü yükleyin.
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "sample.dicom");
try {
    // Bu çağrı, tüm sayfaları önbelleğe alır, böylece temel veri akışından ek veri yüklemesi yapılmaz.
    image.cacheData();

    // Veya sayfaları tek tek önbelleğe alabilirsiniz.
    for (com.aspose.imaging.fileformats.dicom.DicomPage page : image.getDicomPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

