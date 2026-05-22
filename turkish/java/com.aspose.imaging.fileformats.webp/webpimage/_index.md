---
title: "WebPImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "WebP raster görüntülerini API'mizle, kayıpsız ve kayıplı sıkıştırma için modern özelliklerini kullanarak, optimal görüntü kalitesini sağlarken dosya boyutlarını azaltın."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.webp/webpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public final class WebPImage extends RasterCachedMultipageImage implements IMultipageImageExt, IMetadataContainer
```

WebP raster görüntülerini API'mizle, kayıpsız ve kayıplı sıkıştırma için modern özelliklerini kullanarak, optimal görüntü kalitesini sağlarken dosya boyutlarını azaltın. Genişletilmiş dosya formatlarını, animasyonları ve alfa kanallarını sorunsuz bir şekilde yönetin, aynı zamanda boyutları kolayca güncelleyerek, orantılı yeniden boyutlandırma, kırpma, döndürme, filtre uygulama, görüntü parametrelerini ayarlama ve diğer görüntü formatlarına dönüştürme işlemlerini yaparak çok yönlü web görüntüsü optimizasyonu sağlayın.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WebPImage(InputStream stream)](#WebPImage-java.io.InputStream-) | Sağlanan bir akış kaynağından başlatılan [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) sınıfının yeni bir örneğini oluşturun. |
| [WebPImage(InputStream stream, LoadOptions loadOptions)](#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Bir akış ve belirtilen yükleme seçeneklerini kullanarak [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) sınıfının yeni bir örneğini oluşturun, WebP görüntü verilerinin çok yönlü işlenmesini kolaylaştırın. |
| [WebPImage(String path)](#WebPImage-java.lang.String-) | Sağlanan bir dosya kaynağından başlatılan [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) sınıfının yeni bir örneğini oluşturun. |
| [WebPImage(String path, LoadOptions loadOptions)](#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-) | Bir dosya ve belirtilen yükleme seçeneklerini kullanarak [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) sınıfının yeni bir örneğini oluşturun, WebP görüntü verilerinin esnek işlenmesini sağlayın. |
| [WebPImage(RasterImage rasterImage)](#WebPImage-com.aspose.imaging.RasterImage-) | Sağlanan bir rasterImage nesnesinden başlatılan [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) sınıfının yeni bir örneğini oluşturun. |
| [WebPImage(RasterImage rasterImage, LoadOptions loadOptions)](#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-) | Bir rasterImage nesnesi ve belirtilen yükleme seçeneklerini kullanarak [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) sınıfının yeni bir örneğini oluşturun, görüntü verilerinin esnek işlenmesini sağlayın. |
| [WebPImage(int width, int height, WebPOptions options)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-) | Belirtilen genişlik ve yükseklik boyutlarına sahip boş bir görüntü ile [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) sınıfının yeni bir örneğini oluşturun. |
| [WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)](#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-) | Boş bir görüntü ve belirtilen yükleme seçenekleriyle [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) sınıfının yeni bir örneğini oluşturun. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getOptions()](#getOptions--) | Belirtilen özellik ile ilişkili seçenekleri alabilir veya değiştirebilir, davranış ve ayarların ince ayarlı özelleştirilmesini sağlayabilirsiniz. |
| [getPages()](#getPages--) | Görüntü içindeki WebP bloklarına erişin, temel blok yapısının ayrıntılı incelenmesini veya manipülasyonunu mümkün kılar. |
| [getPageCount()](#getPageCount--) | Belirtilen belgede bulunan sayfaların toplam sayısını alın, çok sayfalı içeriğin verimli gezinmesi ve yönetimini kolaylaştırarak. |
| [getFileFormat()](#getFileFormat--) | Görüntüyle ilişkili dosya formatı değerine erişin, görüntünün depolandığı format hakkında bilgi sağlar. |
| [hasAlpha()](#hasAlpha--) | Görüntünün bir alfa kanalı içerip içermediğini alın, bu sayede şeffaflık bilgisinin varlığını gösterir. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Görüntüye yeni bir sayfa ekleyin, içeriğini genişletin ve ek görsel öğeleri barındırmasını sağlayın. |
| [addBlock(IFrame block)](#addBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Görüntüye yeni bir WebP bloğu ekleyin, içeriğini zenginleştirin ve gelişmiş görüntü manipülasyonunu kolaylaştırın. |
| [clearBlocks()](#clearBlocks--) | Görüntüdeki mevcut tüm WebP bloklarını temizleyin, sonraki değişiklikler veya eklemeler için temiz bir başlangıç sağlayın. |
| [insertBlock(int index, IFrame block)](#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-) | Görüntü içinde belirtilen indeksde yeni bir WebP bloğu ekleyin, blok sırasının hassas kontrolünü mümkün kılın. |
| [removeBlock(IFrame block)](#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-) | Görüntüden belirtilen WebP bloğunu kaldırın, görüntü veri yapısının verimli yönetimini sağlayın. |
| [getOriginalOptions()](#getOriginalOptions--) | Orijinal dosya ayarlarına dayalı seçenekleri alır. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Görüntüyü merkez etrafında belirtilen bir açıyla döndürün, aynı zamanda orantılı olarak yeniden boyutlandırın ve belirtilen arka plan rengi parametrelerini uygulayın. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Görüntüyü yeniden boyutlandırın, boyutlarını ayarlarken en boy oranını koruyun. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Görüntünün genişliğini orantılı olarak ayarlayın, en boy oranını koruyarak. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Görüntünün yüksekliğini orantılı olarak ayarlayın, tutarlı yeniden boyutlandırma için en boy oranını koruyarak. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Görüntüdeki aktif çerçeveye yalnızca döndürme, çevirme veya her iki işlemi de uygulayın. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Mevcut görüntüde renk bandlamasını azaltmak ve görsel kaliteyi artırmak için dithering uygulayın. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Belirtilen dikdörtgen bölgeyi kullanarak görüntüyü kırpın, istenmeyen kısımları kaldırırken istediğiniz içeriği koruyun. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Görüntüyü sola, sağa, yukarı ve aşağı kaydırmalar uygulayarak kırpın, böylece görüntü içinde bir ilgi bölgesi seçmiş olursunuz. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Görüntüyü önceden tanımlanmış bir eşik değeri kullanarak ikilileştirin, böylece pikseller eşik değerine göre ön plan veya arka plan olarak sınıflandırılan ikili bir görüntüye dönüştürülür. |
| [binarizeOtsu()](#binarizeOtsu--) | Görüntüyü Otsu'nun eşikleme yöntemiyle ikilileştirin, görüntünün histogramına göre otomatik olarak optimal eşik değerini belirler. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Bradley'in bütünsel görüntü eşikleme algoritmasıyla uyarlamalı eşikleme kullanarak görüntüyü ikilileştirin. |
| [grayscale()](#grayscale--) | Bradley'in bütünsel görüntü eşikleme algoritmasıyla uyarlamalı eşikleme kullanarak görüntüyü ikilileştirin. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Görüntüye gama düzeltmesi uygulayın, piksel yoğunluklarını ayarlayarak istenen parlaklık ve renk dengesini elde edin. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Görüntüye kırmızı, yeşil ve mavi kanallar için ayrı katsayılar kullanarak gama düzeltmesi uygulayın, böylece renk dengesi ve kontrast üzerinde ince ayarlamalar yapabilirsiniz. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Görüntü için `brightness` ayarını uygulayın, genel parlaklık seviyelerinin değiştirilmesine izin verir. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | [Image](../../com.aspose.imaging/image) kontrastını artırın, aydınlık ve karanlık bölgeler arasındaki farkları güçlendirin. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Belirtilen dikdörtgen içindeki içeriği filtreleyin, seçilen bölgeyi geliştirmek veya değiştirmek için belirlenmiş bir görüntü işleme filtresi uygulayın. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Görüntüyü belirtilen ayarlara göre yeniden boyutlandırın, boyutlar, en‑boy oranı ve ölçekleme davranışı üzerinde hassas kontrol sağlayın. |

## Example: This example shows how to load a WebP image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// Bir dosyadan WebP görüntüsü yükleyin.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(dir + "test.webp");
try {
    // PNG'ye kaydet
    // PNG çok sayfalı bir format olmadığından yalnızca aktif çerçevenin PNG'ye kaydedileceğini unutmayın.
    webPImage.save(dir + "test.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    webPImage.dispose();
}
```

### WebPImage(InputStream stream) {#WebPImage-java.io.InputStream-}
```
public WebPImage(InputStream stream)
```


[WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) sınıfının yeni bir örneğini, sağlanan bir akış kaynağından başlatarak oluşturun. Bu yapıcıyı, WebP görüntü nesnelerini akışlardan doğrudan sorunsuz bir şekilde oluşturmak için kullanın; böylece uygulamanız içinde WebP görüntü verilerinin verimli bir şekilde işlenmesi ve manipüle edilmesi sağlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış WebP görüntüsü. |

### WebPImage(InputStream stream, LoadOptions loadOptions) {#WebPImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public WebPImage(InputStream stream, LoadOptions loadOptions)
```


Bir akış ve belirtilen yükleme seçeneklerini kullanarak [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) sınıfının yeni bir örneğini oluşturun, WebP görüntü verilerinin çok yönlü işlenmesini kolaylaştırın. Bu yapıcıyı, uygulamanız içinde gerektiği gibi yükleme parametrelerini özelleştirerek akışlardan WebP görüntü nesnelerini sorunsuz bir şekilde başlatmak için ekleyin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış WebP görüntüsü. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

### WebPImage(String path) {#WebPImage-java.lang.String-}
```
public WebPImage(String path)
```


[WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) sınıfının yeni bir örneğini, sağlanan bir dosya kaynağından başlatarak oluşturun. Bu yapıcıyı, WebP görüntü nesnelerini dosyalardan doğrudan sorunsuz bir şekilde oluşturmak için kullanın; böylece uygulamanız içinde WebP görüntü verilerinin yüklenmesi ve manipüle edilmesi sürecini hızlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | WebP görüntüsü dosyasının yolu |

### WebPImage(String path, LoadOptions loadOptions) {#WebPImage-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public WebPImage(String path, LoadOptions loadOptions)
```


Bir dosya ve belirtilen yükleme seçeneklerini kullanarak [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) sınıfının yeni bir örneğini oluşturun, WebP görüntü verilerinin esnek bir şekilde işlenmesini sağlayın. Bu yapıcıyı, uygulamanızın gereksinimlerine göre yükleme parametrelerini özelleştirerek dosyalardan WebP görüntü nesnelerini sorunsuz bir şekilde başlatmak için kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | WebP görüntüsü dosyasının yolu |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

### WebPImage(RasterImage rasterImage) {#WebPImage-com.aspose.imaging.RasterImage-}
```
public WebPImage(RasterImage rasterImage)
```


[WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) sınıfının yeni bir örneğini, sağlanan bir rasterImage nesnesinden başlatarak oluşturun. Bu yapıcı, raster görüntülerin WebP formatına sorunsuz bir şekilde dönüştürülmesini sağlar; böylece uygulamanız içinde görüntü verilerinin verimli bir şekilde işlenmesi ve manipüle edilmesi mümkün olur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Raster görüntü. |

### WebPImage(RasterImage rasterImage, LoadOptions loadOptions) {#WebPImage-com.aspose.imaging.RasterImage-com.aspose.imaging.LoadOptions-}
```
public WebPImage(RasterImage rasterImage, LoadOptions loadOptions)
```


Bir rasterImage nesnesi ve belirtilen yükleme seçeneklerini kullanarak [WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) sınıfının yeni bir örneğini oluşturun, görüntü verilerinin esnek bir şekilde işlenmesini sağlayın. Bu yapıcıyı, uygulamanızın gereksinimlerine göre yükleme parametrelerini özelleştirerek raster görüntülerden WebP görüntü nesnelerini sorunsuz bir şekilde başlatmak için kullanın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Raster görüntü. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

### WebPImage(int width, int height, WebPOptions options) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-}
```
public WebPImage(int width, int height, WebPOptions options)
```


[WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) sınıfının yeni bir örneğini, belirtilen genişlik ve yükseklik boyutlarında boş bir görüntü ile oluşturun. Bu yapıcı, boş WebP görüntüleri oluşturmanıza olanak tanır ve uygulamanız içinde sonraki görüntü manipülasyonu ve içerik üretimi için bir temel sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Görüntünün genişliği |
| yükseklik | int | Görüntü yüksekliği. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | Seçenekler. |

### WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions) {#WebPImage-int-int-com.aspose.imaging.imageoptions.WebPOptions-com.aspose.imaging.LoadOptions-}
```
public WebPImage(int width, int height, WebPOptions options, LoadOptions loadOptions)
```


[WebPImage](../../com.aspose.imaging.fileformats.webp/webpimage) sınıfının yeni bir örneğini, boş bir görüntü ve belirtilen yükleme seçenekleriyle oluşturun. Bu yapıcı, WebP görüntülerini özelleştirilebilir yükleme parametreleriyle başlatmanıza olanak tanır; böylece uygulamanız içinde görüntü oluşturma ve manipülasyonunda esneklik sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Görüntünün genişliği |
| yükseklik | int | Görüntü yüksekliği. |
| options | [WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) | Seçenekler. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

### getOptions() {#getOptions--}
```
public WebPOptions getOptions()
```


Belirtilen özellik ile ilişkili seçenekleri alın veya değiştirin, davranış ve ayarların ince ayarlı özelleştirilmesini sağlayın. Bu özelliği, yapılandırılabilir parametrelere sorunsuz bir şekilde erişmek ve bunları manipüle etmek için kullanın; böylece uygulamanızın işlevselliği içinde çok yönlü kontrol ve optimizasyon sağlanır.

**Returns:**
[WebPOptions](../../com.aspose.imaging.imageoptions/webpoptions) - the options.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Görüntü içindeki WebP bloklarına erişin, temel blok yapısının ayrıntılı incelenmesine veya manipülasyonuna izin verin. Bu özelliği, WebP görüntü verileri içindeki bireysel blokları analiz etmek veya değiştirmek için kullanın; böylece uygulamanız içinde gelişmiş görüntü işleme tekniklerini kolaylaştırır.

**Returns:**
com.aspose.imaging.Image[]
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Belirtilen belgedeki sayfa toplam sayısını alın, çok sayfalı içeriğin verimli gezinmesi ve yönetimini kolaylaştırın. Kullanıcı deneyimini artırmak için bu işlevi ekleyin, kapsamlı belge yapılarının sorunsuz erişimini sağlayın.

**Returns:**
int - sayfa sayısı.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Görüntüyle ilişkili dosya formatı değerine erişin; bu, görüntünün depolandığı format hakkında bilgi verir. Bu özelliği, görüntünün dosya formatını belirlemek ve uygulamanızda uyumluluk kontrolleri ile format‑özel işlemleri kolaylaştırmak için kullanın.

**Returns:**
long - dosya formatı değeri
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Görüntünün alfa kanalı içerip içermediğini alın, bu sayede şeffaflık bilgisinin varlığını gösterir. Bu özelliği, görüntünün şeffaflık içerip içermediğini belirlemek için kullanın; böylece uygulamanız içinde alfa ile ilgili işlemlerin uygun şekilde işlenmesi ve yönetilmesi sağlanır.

**Returns:**
boolean - alfa kanalı varsa `true`.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Aktif TIFF çerçevesi alfa kanalına sahipse, tüm TIFF görüntüsü alfa kanalı olduğu kabul edilir.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, webpImage.getRawDataFormat(), webpImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.webp.IFrame frame : webpImage.getBlocks()) {
        if (frame instanceof com.aspose.imaging.fileformats.webp.WebPFrameBlock) {
            com.aspose.imaging.fileformats.webp.WebPFrameBlock frameBlock = (com.aspose.imaging.fileformats.webp.WebPFrameBlock) frame;
            System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", i++, frameBlock.getRawDataFormat(), frameBlock.hasAlpha());
        }
    }
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, kullanılan kanallar: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, kullanılan kanallar: 1, HasAlpha=False
```

### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Görüntüye yeni bir sayfa ekleyin, içeriğini genişletin ve ek görsel öğeleri barındırın. Bu yöntemi, uygulamanız içinde dinamik sayfa yönetimini kolaylaştırmak için entegre edin; böylece çok sayfalı belgelerin veya görüntülerin sorunsuz bir şekilde oluşturulması ve artırılması sağlanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Eklenecek sayfa. |

### addBlock(IFrame block) {#addBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void addBlock(IFrame block)
```


Görüntüye yeni bir WebP bloğu ekleyerek içeriğini zenginleştirin ve gelişmiş görüntü işleme imkanı sağlayın. Bu yöntemi uygulayarak WebP görüntü verisinin yapısını ve karmaşıklığını dinamik olarak artırın, böylece görüntü renderlamasını hassas bir şekilde kontrol edip optimize edebilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Eklenecek Webp bloğu. |


**Example: This example shows how to create a multi-frame animated WebP image with the specified options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.WebPOptions createOptions = new com.aspose.imaging.imageoptions.WebPOptions();
createOptions.setLossless(true);
createOptions.setQuality(100f);
createOptions.setAnimBackgroundColor((long) com.aspose.imaging.Color.getGray().toArgb());

// Varsayılan çerçeve artı 36 + 36 ek çerçeve.
createOptions.setAnimLoopCount(36 + 36 + 1);

// 100x100 piksel boyutunda bir WebP görüntüsü oluşturun.
com.aspose.imaging.fileformats.webp.WebPImage webPImage = new com.aspose.imaging.fileformats.webp.WebPImage(100, 100, createOptions);
try {
    // İlk daire kırmızıdır.
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // İkinci daire siyahtır.
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Kırmızı yay şeklinin açısını kademeli olarak artırın.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush1, block.getBounds(), 0, angle);

        webPImage.addBlock(block);
    }

    // Siyah yay açısını kademeli olarak artırın ve kırmızı yay'ı silin.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.webp.WebPFrameBlock block = new com.aspose.imaging.fileformats.webp.WebPFrameBlock(100, 100);

        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(block);
        graphics.fillPie(brush2, block.getBounds(), 0, angle);
        graphics.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        webPImage.addBlock(block);
    }

    // Bir WebP dosyasına kaydedin.
    webPImage.save(dir + "output.webp");
} finally {
    webPImage.dispose();
}
```

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


Mevcut tüm WebP bloklarını görüntüden temizleyerek sonraki değişiklikler veya eklemeler için temiz bir sayfa oluşturun. Bu yöntemi kullanarak WebP görüntü verisindeki blok yapısını etkili bir şekilde sıfırlayın, uygulamanız içinde görüntü içeriğinin optimal yönetimini ve organizasyonunu sağlayın.

### insertBlock(int index, IFrame block) {#insertBlock-int-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void insertBlock(int index, IFrame block)
```


Görüntü içinde belirtilen indekste yeni bir WebP bloğu ekleyerek blok sırasını hassas bir şekilde kontrol edin. Bu yöntemi entegre ederek ek WebP bloklarını görüntü veri yapısına sorunsuz bir şekilde dahil edin, uygulamanız içinde gelişmiş görüntü işleme ve optimizasyonu kolaylaştırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Sıfır tabanlı öğe, `block`'un ekleneceği konum. |
| block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Eklenecek Webp bloğu. |

### removeBlock(IFrame block) {#removeBlock-com.aspose.imaging.fileformats.webp.IFrame-}
```
public void removeBlock(IFrame block)
```


Belirtilen WebP bloğunu görüntüden kaldırarak görüntü veri yapısının verimli yönetimini sağlayın. Bu yöntemi kullanarak uygulamanız içinde gereksiz blokları veya bileşenleri ortadan kaldırarak görüntü işleme iş akışlarını sadeleştirin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | block | [IFrame](../../com.aspose.imaging.fileformats.webp/iframe) | Kaldırılacak blok. |

--------------------

Not: `block`'u başka bir WebPImage'a eklemeyecekseniz Dispose etmeyi unutmayın. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasına yardımcı olabilir. Örneğin, 1 bit piksel başına sahip siyah-beyaz bir PNG görüntüsü yükleyip ardından [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) yöntemiyle kaydederseniz, 8 bit piksel başına çıkış PNG görüntüsü oluşur. Bunu önlemek ve PNG görüntüsünü 1 bit piksel başına kaydetmek için bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları ikinci parametre olarak [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) yöntemine geçirin.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Görüntüyü merkez etrafında belirtilen bir açıyla döndürün, aynı zamanda orantılı olarak yeniden boyutlandırın ve belirtilen arka plan renk parametrelerini uygulayın. Bu yöntemi görüntü işleme iş akışınıza dahil ederek özelleştirilebilir arka plan renkleriyle hassas dönüşümler elde edin, uygulamanız içinde optimal görsel sunumu sağlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Dönüş açısı dereceler cinsindendir. Pozitif değerler saat yönünde dönecektir. |
| resizeProportionally | boolean | eğer `true` olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgenin (köşe noktaları) izdüşümlerine göre değişir; diğer durumda boyutlar dokunulmaz kalır ve sadece `` görüntü içeriği döndürülür. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Arka planın rengi. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Görüntünün boyutlarını, en boy oranını koruyarak yeniden boyutlandırın. Bu yöntemi görüntü işleme iş akışınıza entegre ederek görüntüleri çeşitli gösterim veya depolama gereksinimlerine dinamik olarak ölçeklendirin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |


**Example: This example loads a WEBP image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.webp.WebPImage image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.webp.WebPImage) com.aspose.imaging.Image.load(dir + "sample.webp");
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


Görüntünün genişliğini, en boy oranını koruyarak orantılı şekilde ayarlayın. Bu yöntemi görüntü işleme iş akışınıza entegre ederek tutarlı oranlarla dinamik olarak yeniden boyutlandırın, uygulamanız içinde optimal gösterim veya depolama sağlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| resizeType | int | Yeniden boyutlandırma türü. |

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Görüntünün yüksekliğini orantılı olarak ayarlayın, en boy oranını koruyarak tutarlı bir yeniden boyutlandırma sağlayın. Bu yöntemi görüntü işleme iş akışınıza entegre ederek tutarlı oranlarla dinamik olarak yeniden boyutlandırın, uygulamanız içinde optimal gösterim veya depolama sağlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Döndürme, çevirme veya her iki işlemi yalnızca görüntünün aktif çerçevesine uygulayın. Bu yöntemi görüntü işleme iş akışınıza entegre ederek bireysel çerçevelerin hassas manipülasyonunu gerçekleştirin, uygulamanız içinde çerçeve dönüşümlerinde esneklik ve kontrolü artırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateFlipType | int | Döndürme çevirme türü. |

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Mevcut görüntüde renk bandlamasını azaltmak ve görsel kaliteyi artırmak için dithering uygulayın. Bu yöntemi görüntü işleme iş akışınıza entegre ederek renk geçişlerini daha yumuşak hale getirin ve görüntünün genel görünümünü iyileştirin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ditheringMethod | int | Dithering yöntemi. |
| bitsCount | int | Dithering için son bit sayısı. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Dithering için özel palet. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Belirtilen dikdörtgen bölgeyi kullanarak görüntüyü kırpın, istenmeyen kısımları kaldırırken istenen içeriği koruyun. Bu yöntemi görüntü işleme iş akışınıza entegre ederek görüntünün belirli ilgi alanlarını hassas bir şekilde çıkarın ve odaklanın, çeşitli uygulamalarda netlik ve kompozisyonu artırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Görüntüyü sol, sağ, üst ve alt kaydırmalar uygulayarak kırpın, böylece görüntü içinde bir ilgi bölgesi seçin. Bu yöntemi kullanarak uygulamanızın gereksinimlerine göre görüntünün istenen bölümlerini dinamik olarak çıkarın ve kompozisyon ile odağı ayarlayın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| leftShift | int | Sol kaydırma. |
| rightShift | int | Sağ kaydırma. |
| topShift | int | Üst kaydırma. |
| bottomShift | int | Alt kaydırma. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Önceden tanımlanmış bir eşik değeri kullanarak görüntüyü ikilileştirin, böylece pikseller eşik değerine göre ön plan veya arka plan olarak sınıflandırılan ikili bir görüntü elde edin. Bu yöntemi görüntü işleme iş akışınıza entegre ederek segmentasyon ve özellik çıkarma görevlerini kolaylaştırın, uygulamanız içinde sonraki analizlerin doğruluğunu ve verimliliğini artırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| threshold | byte | Eşik değeri. Bir pikselin karşılık gelen gri değeri eşikten büyükse (byte)255 değeri atanır, aksi takdirde 0. |

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Otsu'nun eşikleme yöntemi kullanarak görüntüyü ikiliye çevirin, görüntünün histogramına dayanarak optimal eşik değerini otomatik olarak belirleyin. Bu yöntemi görüntü işleme iş akışınıza entegre ederek etkili segmentasyon ve özellik çıkarımı sağlayın, uygulamanızdaki görüntü analizi görevlerinin doğruluğunu ve güvenilirliğini artırın.

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Bradley'ın adaptif eşikleme algoritması ve integral görüntü eşikleme kullanarak görüntüyü ikiliye çevirin. Bu yöntem, görüntünün komşuluğuna göre yerel eşikleri dinamik olarak hesaplayarak değişken aydınlatma koşullarına uyumu artırır ve uygulamanızdaki sonraki işleme görevleri için sağlam bir segmentasyon sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightnessDifference | double | Bu pikselin etrafında merkezlenmiş s x s piksellik bir pencerenin ortalaması ile piksel arasındaki parlaklık farkı. |
| windowSize | int | Bu pikselin etrafında merkezlenmiş s x s piksellik pencerenin boyutu |

### grayscale() {#grayscale--}
```
public void grayscale()
```


Bradley'ın adaptif eşikleme algoritması ve integral görüntü eşikleme kullanarak görüntüyü ikiliye çevirin. Bu yöntem, görüntünün komşuluğuna göre yerel eşikleri dinamik olarak hesaplayarak değişken aydınlatma koşullarına uyumu artırır ve uygulamanızdaki sonraki işleme görevleri için sağlam bir segmentasyon sağlar.

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Görüntüye gama düzeltmesi uygulayın, piksel yoğunluklarını istenen parlaklık ve renk dengesine ulaşacak şekilde ayarlayın. Bu yöntemi görüntü işleme iş akışınıza dahil ederek görsel kaliteyi artırın ve uygulamanızdaki sonraki analiz veya görüntüleme görevlerinin doğruluğunu iyileştirin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gamma | float | Kırmızı, yeşil ve mavi kanallar için gamma katsayısı |

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Kırmızı, yeşil ve mavi kanallar için ayrı katsayılar kullanarak görüntüye gama düzeltmesi uygulayın; bu, renk dengesi ve kontrastın ince ayarını sağlar. Bu yöntemi görüntü işleme hattınıza entegre ederek renk render'ı üzerinde hassas kontrol elde edin ve uygulamanızdaki görsel sadakati artırın.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gammaRed | float | Kırmızı kanal katsayısı için gama |
| gammaGreen | float | Yeşil kanal katsayısı için gama |
| gammaBlue | float | Mavi kanal katsayısı için gamma |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


`brightness` ayarlamasını görüntüye uygulayın, genel parlaklık seviyelerinin değiştirilmesini sağlayın. Bu yöntemi görüntü işleme iş akışınıza dahil edin, görünürlüğü artırın ve uygulamanız içinde görüntülerin görsel kalitesini iyileştirin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| brightness | int | Parlaklık değeri. |

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


[Image](../../com.aspose.imaging/image) kontrastını artırın, aydınlık ve karanlık bölgeler arasındaki farkları büyütün. Bu yöntemi görüntü işleme iş akışınıza entegre ederek görsel netliği ve uygulamanızdaki genel görüntü kalitesini iyileştirin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| contrast | float | Kontrast değeri ([-100; 100] aralığında) |

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Belirtilen dikdörtgen içindeki içeriği filtreleyin, seçilen bölgeyi geliştirmek veya değiştirmek için belirlenmiş bir görüntü işleme filtresi uygulayın. Bu yöntemi görüntü manipülasyonu iş akışınıza entegre edin, uygulamanız içinde hedeflenmiş iyileştirmeler veya dönüşümler elde edin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Seçenekler. |


**Example: The following example applies various types of filters to a WEBP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Tüm görüntüye, dikdörtgen boyutu 5 olan bir medyan filtresi uygula.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    webpImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Tüm görüntüye, çekirdek boyutu 5 olan çift taraflı yumuşatma filtresi uygula.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    webpImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Tüm görüntüye, yarıçapı 5 ve sigma değeri 4.0 olan bir Gaussian bulanıklaştırma filtresi uygula.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Tüm görüntüye, yarıçapı 5 ve pürüzsüzlük değeri 4.0 olan bir Gauss-Wiener filtresi uygula.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Tüm görüntüye, uzunluğu 5, pürüzsüzlük değeri 4.0 ve açısı 90.0 derece olan bir hareket Wiener filtresi uygula.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    webpImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.webp");
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Tüm görüntüye, çekirdek boyutu 5 ve sigma değeri 4.0 olan bir keskinleştirme filtresi uygula.
    webpImage.filter(webpImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    webpImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Görüntüyü belirtilen ayarlara göre yeniden boyutlandırın, boyutlar, en‑boy oranı ve ölçekleme davranışı üzerinde hassas kontrol sağlayın. Bu yöntemi görüntü işleme iş akışınıza entegre ederek uygulamanızın özel gereksinimlerine göre özelleştirilmiş yeniden boyutlandırma işlemleri gerçekleştirin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Yeniden boyutlandırma ayarları. |

