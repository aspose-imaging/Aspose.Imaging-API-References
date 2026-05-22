---
title: "EpsImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Encapsulated PostScript EPS görüntü dosya formatı desteği için API, metin, grafik ve görüntülerden oluşan kompozisyonları manipüle etmek için güçlü yetenekler sunar."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.eps/epsimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)
```
public final class EpsImage extends VectorImage
```

Encapsulated PostScript (EPS) görüntü dosya formatı desteği için API, metin, grafik ve görüntülerden oluşan kompozisyonları manipüle etmek için güçlü yetenekler sunar. Bitmap önizleme görüntüsü işleme, yön çevirme, illüstrasyon sınırları için sınırlama kutusu alma, yeniden boyutlandırma, görüntü döndürme ve önizleme görüntüleri ekleme gibi özelliklerle. Bu API, EPS dosyalarının çeşitli uygulamalara hassasiyet ve çok yönlülükle sorunsuz işlenmesini ve entegrasyonunu sağlar.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPreviewImageCount()](#getPreviewImageCount--) | Mevcut önizleme görüntülerinin sayısına kolayca erişin. |
| [getPreviewImages()](#getPreviewImages--) | Dosyanızla ilişkili önizleme görüntülerini alın. |
| [getFileFormat()](#getFileFormat--) | Bu özellik ile görüntünüzün dosya formatına erişin. |
| [getEpsType()](#getEpsType--) | EPS görüntünüzün alt tip değerine erişin ve yorumlayın, iş akışınızı kolaylaştırın ve platformlar arası uyumluluğu artırın. |
| [hasRasterPreview()](#hasRasterPreview--) | Bu özellik sayesinde raster önizlemenin varlığını zahmetsizce keşfedin. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Bu özellik ile görüntünün kesin bit derinliğine zahmetsizce erişin. |
| [getWidthF()](#getWidthF--) | Bu kullanışlı özellik ile görüntünün genişliğini alın. |
| [getHeightF()](#getHeightF--) | Bu özelliği kullanarak görüntünün yüksekliğine erişin. |
| [isCached()](#isCached--) | Bu özellik, nesnenin verisinin şu anda önbellekte olup olmadığını kontrol etmenin pratik bir yolunu sunar, ek veri okuma ihtiyacını ortadan kaldırır. |
| [getPsStream()](#getPsStream--) | Yürütülecek PostScript'i içeren akışı alır. |
| [getPostScriptVersion()](#getPostScriptVersion--) | Bu özellik, [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) örneğiyle ilişkili PostScript sürümünü alır. |
| [getTitle()](#getTitle--) | Bu özellik, EPS dosyasına gömülü EPS Document Structuring Conventions (DSC) yorumlarından çıkarılan başlığı alır. |
| [getCreator()](#getCreator--) | Bu özellik, EPS dosyasında bulunan EPS Document Structuring Conventions (DSC) yorumlarından elde edilen oluşturucu bilgisine erişim sağlar. |
| [getCreationDate()](#getCreationDate--) | EPS Document Structuring Conventions (DSC) yorumlarından oluşturulma tarihini alarak, bu özellik EPS dosyasının başlangıcını gösteren temel meta verileri sağlar. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | EPS Document Structuring Conventions (DSC) yorumlarından oluşturulma tarihini alarak, bu özellik EPS dosyasının başlangıcını gösteren temel meta verileri sağlar. |
| [getBoundingBox()](#getBoundingBox--) | Cihaz bağımsız puanlarda orijinal sınırlama kutusuna erişerek, bu özellik [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) boyutları hakkında kritik geometrik bilgiler sunar. |
| [getBoundingBoxPx()](#getBoundingBoxPx--) | Bu özellik, [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) örneğinin orijinal sınırlama kutusunu piksel cinsinden döndürür, doğru renderleme ve manipülasyon için gerekli geometrik verileri sağlar. |
| [cacheData()](#cacheData--) | Bu özellik, [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) örneğinin orijinal sınırlama kutusunu piksel cinsinden döndürür, doğru renderleme ve manipülasyon için gerekli geometrik verileri sağlar. |
| [getPreviewImagesIter()](#getPreviewImagesIter--) | Bu özellik, [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) örneğine bağlı önizleme görüntülerine erişir, uygulamalarda inceleme veya kullanım için sorunsuz alım sağlar. |
| [getPreviewImage()](#getPreviewImage--) | Belirtilen `format` içinde mevcut önizleme görüntüsünü alır veya bulunamazsa `` döndürür. |
| [getPreviewImage(long format)](#getPreviewImage-long-) | Belirtilen `format` içinde mevcut önizleme görüntüsünü alır veya bulunamazsa `` döndürür. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Benzersiz renk şemaları elde etmek ve görsel çekiciliği artırmak için görüntü paletlerini özelleştirin. |

## Example: Convert EPS image to PNG using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PngOptions options = new PngOptions();
    EpsRasterizationOptions epsRasterizationOptions = new EpsRasterizationOptions();
    epsRasterizationOptions.setPageWidth(500);  // Image width
    epsRasterizationOptions.setPageHeight(500); // Image height
    epsRasterizationOptions.setPreviewToExport(EpsPreviewFormat.PostScriptRendering); // Render raster image using the PostScript
    options.setVectorRasterizationOptions(epsRasterizationOptions);

    image.save("Sample.png", options);
}
```


## Example: Convert EPS image to PDF using PostScript rendering.

``` java
try (EpsImage image = (EpsImage)Image.load("Sample.eps"))
{
    PdfOptions options = new PdfOptions();
    PdfCoreOptions coreOptions = new PdfCoreOptions();
    coreOptions.setPdfCompliance(PdfComplianceVersion.PdfA1b); // Set required PDF compliance
    options.setPdfCoreOptions(coreOptions);

    image.save("Sample.pdf", options);
}
```


## Example: Resize EPS image and export it to PNG format.

``` java
// EPS görüntüsü yükle
try (Image image = Image.load("AstrixObelix.eps"))
{
    // Görüntüyü Mitchell kübik enterpolasyon yöntemiyle yeniden boyutlandır
    image.resize(400, 400, ResizeType.Mitchell);

    // Görüntüyü PNG formatına dışa aktar
    image.save("ExportResult.png", new PngOptions());
}
```


## Example: Resize EPS image using advanced settings.

``` java
// EPS görüntüsü yükle
try (Image image = Image.load("AstrixObelix.eps"))
{
    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    // Enterpolasyon modunu ayarla
    resizeSettings.setMode(ResizeType.LanczosResample);
    // Filtre tipini ayarla
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);
    // Renk karşılaştırma yöntemini ayarlar
    resizeSettings.setColorCompareMethod(ColorCompareMethod.Euclidian);
    // Renk kantizasyon yöntemini ayarla
    resizeSettings.setColorQuantizationMethod(ColorQuantizationMethod.Popularity);

    // Görüntüyü gelişmiş yeniden boyutlandırma ayarlarıyla yeniden boyutlandır
    image.resize(400, 400, resizeSettings);

    // Görüntüyü PNG formatına dışa aktar
    image.save("ExportResult.png", new PngOptions());
}
```

### getPreviewImageCount() {#getPreviewImageCount--}
```
public int getPreviewImageCount()
```


Mevcut önizleme görüntülerinin sayısına kolayca erişin. Bu özellik, dosyanızla ilişkili önizleme görüntülerinin sayısını zahmetsizce almanızı sağlar, görüntü önizlemelerinizin verimli yönetimi ve gezinmesini mümkün kılar. İş akışınızı optimize etmek ve görüntü varlıklarınızı etkili bir şekilde düzenlemek için idealdir.

**Returns:**
int
### getPreviewImages() {#getPreviewImages--}
```
public Image[] getPreviewImages()
```


Dosyanızla ilişkili önizleme görüntülerini alın. Bu özellik, önizleme görüntüleri koleksiyonuna sorunsuz erişim sağlar, ihtiyaç duyulduğunda bunları verimli bir şekilde göz atıp yönetmenize olanak tanır. Projeniz için doğru görüntüyü hızlıca önizlemek ve seçmek için idealdir.

**Returns:**
com.aspose.imaging.Image[]
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Bu özellik ile görüntünüzün dosya formatına erişin. Görüntü dosyanızın formatı hakkında temel bilgileri alarak uyumluluğu ve verimli işleme kolaylaştırır. Projelerinize sorunsuz entegrasyon için görüntü dosyalarınızın formatını belirlemede idealdir.

**Returns:**
long
### getEpsType() {#getEpsType--}
```
public short getEpsType()
```


EPS görüntünüzün alt tür değerine erişin ve yorumlayın, iş akışınızı kolaylaştırın ve platformlar arasında uyumluluğu artırın. Projelerinizde EPS alt türünün alınmasını hassasiyet ve verimlilikle optimize etmek için idealdir.

**Returns:**
short
### hasRasterPreview() {#hasRasterPreview--}
```
public boolean hasRasterPreview()
```


Bu özellik sayesinde raster önizlemenin varlığını zahmetsizce keşfedin. [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) örneğinin raster önizleme içerip içermediğini gösteren boolean değere erişin, görüntü işleme görevlerinizi netlik ve verimlilikle güçlendirin. EPS görüntülerinde raster önizlemelerin varlığına veya yokluğuna göre iş akışı kararlarını kolaylaştırmak için idealdir.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Bu özellik ile görüntünün kesin bit derinliğine zahmetsizce erişin. Piksel başına bit sayısını alın, görüntünün renk derinliği hakkında kritik bilgiler sağlayın ve işleme görevlerini optimize etmeye yardımcı olun. Görüntü manipülasyonu ve analizinde ayrıntılı kontrol gerektiren uygulamalar için idealdir.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Bu kullanışlı özellik sayesinde görüntünün genişliğini alın. Görüntünün genişliğine zahmetsizce ulaşın, kesin yerleşim hesaplamalarını, ölçekleme işlemlerini ve boyutla ilgili görevleri uygulamanız içinde kolaylaştırın. Çeşitli platform ve cihazlarda görüntülerin doğru render edilmesini ve gösterilmesini sağlamak için idealdir.

**Returns:**
float - Görüntünün piksel cinsinden genişliği.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Bu özelliği kullanarak görüntünün yüksekliğine erişin. Görüntünün yüksekliğini kolayca alın, sorunsuz yerleşim ayarlamaları, en‑boy oranı hesaplamaları ve farklı ekran çözünürlükleri ve görüntü ortamlarında kesin renderlamayı mümkün kılın.

**Returns:**
float - Görüntünün piksel cinsinden yüksekliği.
### isCached() {#isCached--}
```
public boolean isCached()
```


Bu özellik, nesnenin verisinin şu anda önbellekte olup olmadığını kontrol etmenin pratik bir yolunu sunar, ek veri okuma ihtiyacını ortadan kaldırır. Gerekli bilginin hazır olup olmadığını hızlı ve verimli bir şekilde belirlemenizi sağlar, performansı optimize eder ve veri yoğun işlemlerde kaynak yükünü azaltır.

**Returns:**
boolean
### getPsStream() {#getPsStream--}
```
public InputStream getPsStream()
```


Yürütülecek PostScript'i içeren akışı alır.

**Returns:**
java.io.InputStream - yürütülecek PostScript'i içeren akış.
### getPostScriptVersion() {#getPostScriptVersion--}
```
public String getPostScriptVersion()
```


Bu özellik, [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) örneğiyle ilişkili PostScript sürümünü alır. EPS dosyasında kullanılan belirli PostScript dil sürümü hakkında bilgi sağlar, uyumluluk değerlendirmesine yardımcı olur ve PostScript uyumlu ortamlarla sorunsuz entegrasyonu kolaylaştırır.

**Returns:**
java.lang.String
### getTitle() {#getTitle--}
```
public String getTitle()
```


Bu özellik, EPS dosyasına gömülü EPS Document Structuring Conventions (DSC) yorumlarından çıkarılan başlığı alır. EPS dosyasının içeriği hakkında değerli meta veriler sağlar, belge organizasyonu ve uyumlu yazılım uygulamaları içinde tanımlamaya yardımcı olur.

**Returns:**
java.lang.String
### getCreator() {#getCreator--}
```
public String getCreator()
```


Bu özellik, EPS dosyasında bulunan EPS Document Structuring Conventions (DSC) yorumlarından alınan oluşturucu bilgisine erişim sunar. Oluşturucu detaylarını anlamak, EPS dosyasını oluşturan yazılım veya aracı gösterir ve çeşitli platform ve uygulamalarda uyumluluk değerlendirmesini kolaylaştırır.

**Returns:**
java.lang.String
### getCreationDate() {#getCreationDate--}
```
public Date getCreationDate()
```


EPS Document Structuring Conventions (DSC) yorumlarından oluşturulma tarihini alarak, bu özellik EPS dosyasının başlangıcını gösteren temel meta verileri sağlar. Bu bilgiye erişen kullanıcılar, dosyanın kökeni ve zaman çizelgesi hakkında içgörü kazanır, dosya yönetimi ve organizasyonunu geliştirir.

**Returns:**
java.util.Date
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public void setCreationDate(Date value)
```


EPS Document Structuring Conventions (DSC) yorumlarından oluşturulma tarihini alarak, bu özellik EPS dosyasının başlangıcını gösteren temel meta verileri sağlar. Bu bilgiye erişen kullanıcılar, dosyanın kökeni ve zaman çizelgesi hakkında içgörü kazanır, dosya yönetimi ve organizasyonunu geliştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date |  |

### getBoundingBox() {#getBoundingBox--}
```
public RectangleF getBoundingBox()
```


Cihaz bağımsız puanlarda orijinal sınırlama kutusuna erişerek, bu özellik [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) boyutları hakkında kritik geometrik bilgiler sunar. Bu verileri alarak, kullanıcılar görüntünün boyutunu ve en‑boy oranını doğru bir şekilde değerlendirebilir, çeşitli uygulamalarda kesin yerleşim ve konumlandırmayı kolaylaştırır.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getBoundingBoxPx() {#getBoundingBoxPx--}
```
public Rectangle getBoundingBoxPx()
```


Bu özellik, [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) örneğinin orijinal sınırlama kutusunu piksel cinsinden döndürür, doğru renderleme ve manipülasyon için temel geometrik veriler sağlar. Bu bilgilerle, kullanıcılar EPS görüntülerinin projelerinde kesin konumlandırma ve boyutlandırmasını sağlayabilir, genel görsel sunumu ve kaliteyi artırır.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### cacheData() {#cacheData--}
```
public void cacheData()
```


Bu özellik, [EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) örneğinin orijinal sınırlama kutusunu piksel cinsinden döndürür, doğru renderleme ve manipülasyon için temel geometrik veriler sağlar. Bu bilgilerle, kullanıcılar EPS görüntülerinin projelerinde kesin konumlandırma ve boyutlandırmasını sağlayabilir, genel görsel sunumu ve kaliteyi artırır.

### getPreviewImagesIter() {#getPreviewImagesIter--}
```
public Iterable<Image> getPreviewImagesIter()
```


[EpsImage](../../com.aspose.imaging.fileformats.eps/epsimage) örneğine bağlı önizleme görüntülerine erişir, uygulamalarda inceleme veya kullanım için sorunsuz alım sağlar. Bu yöntem, önizleme görüntülerine pratik erişim sunar, kullanıcı etkileşimini görüntü verisiyle artırır.

**Returns:**
java.lang.Iterable<com.aspose.imaging.Image> - Önizleme görüntüleri.
### getPreviewImage() {#getPreviewImage--}
```
public Image getPreviewImage()
```


Belirtilen `format` içinde mevcut önizleme görüntüsünü alır veya bulunamazsa `` döndürür. Bu yöntem, belirli formatlara göre özelleştirilmiş önizleme görüntülerine erişimde esneklik sağlar, uygulamalarda uyumluluğu ve kaynak yönetimini optimize eder.

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### getPreviewImage(long format) {#getPreviewImage-long-}
```
public Image getPreviewImage(long format)
```


Belirtilen `format` içinde mevcut önizleme görüntüsünü alır veya bulunamazsa `` döndürür. Bu yöntem, belirli formatlara göre özelleştirilmiş önizleme görüntülerine erişimde esneklik sağlar, uygulamalarda uyumluluğu ve kaynak yönetimini optimize eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| format | long | EPS önizleme görüntü formatı. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The existing preview image or `null`.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Benzersiz renk şemaları elde etmek ve görsel çekiciliği artırmak için görüntü paletlerini özelleştirin. Belirli etkiler için renkleri ayarlayın ve farklı platform ve cihazlarda görüntü kalitesini kolayca optimize edin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Ayarlanacak palet. |
| updateColors | boolean | `true` olarak ayarlanırsa renkler yeni palete göre güncellenecek; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri olmaması durumunda görüntünün yüklenirken çökmesine neden olabileceğini unutmayın. |

