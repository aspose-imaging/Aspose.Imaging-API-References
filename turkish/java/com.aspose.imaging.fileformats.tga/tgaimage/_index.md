---
title: "TgaImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "TARGA Truevision Advanced Raster Adapter formatı için özelleştirilmiş API'mizle TGA raster görüntü dosyalarını işleyin, sorunsuz yükleme ve özelleştirme sağlayın."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.tga/tgaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class TgaImage extends RasterCachedImage
```

TARGA (Truevision Advanced Raster Adapter) formatı için özelleştirilmiş API'mizle TGA raster görüntü dosyalarını işleyin, sorunsuz yükleme ve özelleştirme sağlayın. Yazar, zaman damgası, görüntü kimliği ve yazılım sürümü gibi genel özellikleri kolayca güncelleyebilir, piksel başına çeşitli bit ayarları, alfa kanalı ve renk şeffaflığını kullanabilirsiniz. Ayrıca, TGA görüntülerini diğer popüler raster formatlarına dışa aktararak projeleriniz için uyumluluğu garantileyebilirsiniz.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TgaImage(String path)](#TgaImage-java.lang.String-) | Sağlanan dosya yolunu kullanarak görüntü içeriğini yüklemek için yeni bir [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) nesnesi başlatır. |
| [TgaImage(RasterImage rasterImage)](#TgaImage-com.aspose.imaging.RasterImage-) | Bir raster görüntü nesnesi sağlayarak [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) sınıfının yeni bir örneğini oluşturur. |
| [TgaImage(InputStream stream)](#TgaImage-java.io.InputStream-) | Görüntüyü yüklemek için bir akış kullanarak [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Piksel başına bit değerini alır, görüntünün renk derinliği hakkında temel bilgi sağlar. |
| [getBytesPerPixel()](#getBytesPerPixel--) | Piksel başına bayt değerini elde eder; bu, görüntüdeki her pikselin kapladığı bellek miktarını gösterir. |
| [hasAlpha()](#hasAlpha--) | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) içinde alfa kanalı olup olmadığını gösteren bir boolean değer alır, şeffaflık etkilerini kolaylaştırır. |
| [isGrayScale()](#isGrayScale--) | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) bir gri tonlamalı görüntüyü temsil edip etmediğini gösteren bir boolean değer elde eder. |
| [getWidth()](#getWidth--) | Bu [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) örneği tarafından temsil edilen görüntünün genişliğini alır. |
| [getHeight()](#getHeight--) | Bu [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) örneği tarafından kapsanan görüntünün yüksekliğini elde eder. |
| [getFileFormat()](#getFileFormat--) | Bu [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) örneği tarafından temsil edilen görüntünün dosya formatı hakkında önemli bilgileri al. |
| [hasColorMap()](#hasColorMap--) | Bu [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) örneğinin bir renk haritası içerip içermediğini al. |
| [getGammaValueNumerator()](#getGammaValueNumerator--) | Görüntülerde doğru renk temsili için gerekli olan gama değerinin pay kısmını alır. |
| [getGammaValueDenominator()](#getGammaValueDenominator--) | Gama değerinin payda kısmını alır; bu, görüntülerde renk temsili belirlemede bütünleyici bir faktördür. |
| [getPixelAspectRatioNumerator()](#getPixelAspectRatioNumerator--) | Piksel En Boy Oranı'nın pay bileşenini alır; bu, görüntüdeki piksellerin görsel görünümünü etkiler. |
| [getPixelAspectRatioDenominator()](#getPixelAspectRatioDenominator--) | Piksel En Boy Oranı'nın payda kısmını alır; bu, görüntüdeki piksellerin görsel görünümünü belirlemede kritik bir faktördür. |
| [getXOrigin()](#getXOrigin--) | Ekranın sol alt köşesinde bir orijine sahip bir görüntü aygıtında (ör. TARGA serisi) konumlandırılmış görüntünün sol alt köşesi için mutlak yatay koordinatı alır. |
| [setXOrigin(int value)](#setXOrigin-int-) | Ekranın sol alt köşesinde bir orijine sahip bir görüntü aygıtında (ör. TARGA serisi) konumlandırılmış görüntünün sol alt köşesi için mutlak yatay koordinatı ayarlar. |
| [getYOrigin()](#getYOrigin--) | Ekranın sol alt köşesinde bir orijine sahip bir görüntü aygıtında (ör. TARGA serisi) konumlandırılmış görüntünün sol alt köşesi için mutlak dikey koordinatı alır. |
| [setYOrigin(int value)](#setYOrigin-int-) | Ekranın sol alt köşesinde bir orijine sahip bir görüntü aygıtında (ör. TARGA serisi) konumlandırılmış görüntünün sol alt köşesi için mutlak dikey koordinatı ayarlar. |
| [getImageId()](#getImageId--) | Görüntüyle ilişkili benzersiz tanımlayıcıyı alır. |
| [setImageId(String value)](#setImageId-java.lang.String-) | Görüntüyle ilişkili benzersiz tanımlayıcıyı ayarlar. |
| [getAuthorComments()](#getAuthorComments--) | Görüntünün yazarının sağladığı yorumları alır veya ayarlar. |
| [setAuthorComments(String value)](#setAuthorComments-java.lang.String-) | Görüntünün yazarının sağladığı yorumları alır veya ayarlar. |
| [getAuthorName()](#getAuthorName--) | Görüntüyle ilişkili yazarın adını alır veya ayarlar. |
| [setAuthorName(String value)](#setAuthorName-java.lang.String-) | Görüntüyle ilişkili yazarın adını alır veya ayarlar. |
| [getDateTimeStamp()](#getDateTimeStamp--) | Tarih/Saat damgasını alır. |
| [setDateTimeStamp(Date value)](#setDateTimeStamp-java.util.Date-) | Tarih/Saat damgasını ayarlar. |
| [getJobNameOrId()](#getJobNameOrId--) | Görüntüyle ilişkili iş adını veya kimliğini alır veya ayarlar. |
| [setJobNameOrId(String value)](#setJobNameOrId-java.lang.String-) | Görüntüyle ilişkili iş adını veya kimliğini alır veya ayarlar. |
| [getJobTime()](#getJobTime--) | Görüntüyle ilişkili iş zamanını gösteren zaman damgasını alır veya ayarlar. |
| [setJobTime(Date value)](#setJobTime-java.util.Date-) | Görüntüyle ilişkili iş zamanını gösteren zaman damgasını alır veya ayarlar. |
| [getTransparentColor()](#getTransparentColor--) | Görüntüyle ilişkili ana rengi alır veya ayarlar. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Görüntüyle ilişkili ana rengi alır veya ayarlar. |
| [hasTransparentColor()](#hasTransparentColor--) | Görüntünün şeffaf renk içerip içermediğini gösteren bir boolean değeri alır veya ayarlar. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Görüntünün şeffaf renk içerip içermediğini gösteren bir boolean değeri alır veya ayarlar. |
| [getBackgroundColor()](#getBackgroundColor--) | Görüntünün arka plan rengini alır veya ayarlar. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Görüntünün arka plan rengini alır veya ayarlar. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Görüntünün arka plan rengi içerip içermediğini gösteren bir değeri alır veya ayarlar. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Görüntünün arka plan rengi içerip içermediğini gösteren bir değeri alır veya ayarlar. |
| [getSoftwareVersion()](#getSoftwareVersion--) | Görüntüyle ilişkili yazılım sürümünü alır veya ayarlar. |
| [setSoftwareVersion(String value)](#setSoftwareVersion-java.lang.String-) | Görüntüyle ilişkili yazılım sürümünü alır veya ayarlar. |
| [getSoftwareVersionLetter()](#getSoftwareVersionLetter--) | Görüntüyle ilişkili yazılım sürümünün harf bileşenini alır veya ayarlar. |
| [setSoftwareVersionLetter(char value)](#setSoftwareVersionLetter-char-) | Görüntüyle ilişkili yazılım sürümünün harf bileşenini alır veya ayarlar. |
| [getSoftwareVersionNumber()](#getSoftwareVersionNumber--) | Görüntüyle ilişkili yazılım sürümünün sayısal bileşenini alır veya ayarlar. |
| [setSoftwareVersionNumber(int value)](#setSoftwareVersionNumber-int-) | Görüntüyle ilişkili yazılım sürümünün sayısal bileşenini alır veya ayarlar. |
| [getSoftwareId()](#getSoftwareId--) | Görüntüyle ilişkili yazılım kimliğini (ID) yönetir, en fazla 40 ASCII karaktere izin verir. |
| [setSoftwareId(String value)](#setSoftwareId-java.lang.String-) | Görüntüyle ilişkili yazılım kimliğini (ID) yönetir, en fazla 40 ASCII karaktere izin verir. |
| [op_Equality(TgaImage first, TgaImage second)](#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Karşılaştırma sürecinde yer alan ilk ve ikinci görüntüyü dikkate alarak iki TGA görüntüsü arasında eşitlik karşılaştırması yapar. |
| [op_Inequality(TgaImage first, TgaImage second)](#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Karşılaştırma sürecinde yer alan ilk ve ikinci görüntüyü değerlendirerek iki TGA görüntüsü arasında eşit olmayan bir karşılaştırma gerçekleştirir. |
| [deepClone()](#deepClone--) | Mevcut örneğin bir kopyasını üretir, orijinalin tüm özniteliklerini ve özelliklerini klonlayan yeni bir nesne oluşturur. |
| [deepClone(TgaImage tgaImage)](#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-) | Başka bir [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) nesnesinin özelliklerini kopyalar, aynı özniteliklere sahip yeni bir örnek oluşturur. |
| [equals(TgaImage other)](#equals-com.aspose.imaging.fileformats.tga.TgaImage-) | Bir eşitlik karşılaştırmasında, yöntem mevcut [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) örneğinin parametre olarak verilen ikinci görüntüye eşit olup olmadığını değerlendirir. |
| [equals(Object other)](#equals-java.lang.Object-) | Yöntem, mevcut [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) örneği ile parametre olarak verilen başka bir nesne arasında eşitlik karşılaştırması yapar. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | \"rotateFlip\" yöntemi, görüntü üzerinde döndürme ve çevirme işlemlerini etkinleştirir. |
| [hashCode()](#hashCode--) | Mevcut örneğin hash kodunu alır. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Görüntüyü belirtilen bölgeye kırp. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Görüntüyü sol, sağ, üst ve alt sınırlar için kaydırmalar belirterek kırpar. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | İstenen boyutları ve en-boy oranını korumak için belirli ayarları uygulayarak görüntüyü yeniden boyutlandır. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Yeniden boyutlandırma işleminin nasıl gerçekleştirileceğini belirleyen belirtilen bir yeniden boyutlandırma türü kullanarak görüntünün boyutunu ayarlar. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Belirtilen bir açıyla, yeniden boyutlandırma oranını koruyarak ve arka plan rengini muhafaza ederek görüntüyü merkez etrafında döndürür. |

## Example: Saving of the JPG image as a TGA image.

``` java
try (Image image = Image.load("test.jpg"))
{
    image.save("test.tga", new TgaOptions());
}
```


## Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```


## Example: Getting values of the public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    Date dateTimeStamp = image.getDateTimeStamp();
    String authorName = image.getAuthorName();
    String authorComments = image.getAuthorComments();
    String imageId = image.getImageId();
    String jobNameOrId = image.getJobNameOrId();
    Date jobTime = image.getJobTime();
    Color keyColor = image.getTransparentColor();
    String softwareId = image.getSoftwareId();
    String softwareVersion = image.getSoftwareVersion();
    char softwareVersionLetter = image.getSoftwareVersionLetter();
    int softwareVersionNumber = image.getSoftwareVersionNumber();
    int xOrigin = image.getXOrigin();
    int yOrigin = image.getYOrigin();
    int gammaValueDenominator = image.getGammaValueDenominator();
    int gammaValueNumerator = image.getGammaValueNumerator();
    boolean hasAlphaChannel = image.hasAlpha();
    boolean hasColorMap = image.hasColorMap();
    int height = image.getHeight();
    boolean isGrayScale = image.isGrayScale();
    int pixelAspectRatioDenominator = image.getPixelAspectRatioDenominator();
    int pixelAspectRatioNumerator = image.getPixelAspectRatioNumerator();
    Size size = image.getSize();
    int width = image.getWidth();
}
```


## Example: Updating public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### TgaImage(String path) {#TgaImage-java.lang.String-}
```
public TgaImage(String path)
```


Sağlanan dosya yolunu kullanarak görüntü içeriğini yüklemek için yeni bir [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) nesnesi başlatır. Bu yapıcı, görüntü örneğini verimli bir şekilde başlatarak TGA görüntü dosyalarına sorunsuz erişim sağlar ve uygulama iş akışınıza entegrasyonu basitleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Görüntüyü yüklemek için yol. |

### TgaImage(RasterImage rasterImage) {#TgaImage-com.aspose.imaging.RasterImage-}
```
public TgaImage(RasterImage rasterImage)
```


Bir raster görüntü nesnesi sağlayarak [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) sınıfının yeni bir örneğini oluşturun. Bu yapıcı, mevcut raster görüntülerin TGA görüntü formatına doğrudan entegrasyonunu kolaylaştırır ve yazılım sistemlerinizde uyumluluğu artırmak için dönüşüm sürecini sadeleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Raster görüntü. |


**Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.**

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```

### TgaImage(InputStream stream) {#TgaImage-java.io.InputStream-}
```
public TgaImage(InputStream stream)
```


Görüntüyü yüklemek için bir akış kullanarak [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) sınıfının yeni bir örneğini başlatın. Bu yapıcı, akışlardan gelen görüntü verilerinin sorunsuz entegrasyonunu sağlar ve yazılım uygulamalarınızda TGA görüntülerinin verimli işlenmesini ve işlenmesini kolaylaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Bir görüntüyü yüklemek için akış. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Piksel başına bit değerini alır, görüntünün renk derinliği hakkında temel bilgi sağlar. Bu özellik, görüntüdeki detay seviyesi ve renk zenginliğini anlamak için kritik bir ölçüt olarak hizmet eder ve geliştiricilerin işleme algoritmalarını ve kaynak tahsislerini optimize ederek verimli görüntü manipülasyonu ve renderleme görevlerini gerçekleştirmelerine yardımcı olur.

**Returns:**
int - piksel başına bit.
### getBytesPerPixel() {#getBytesPerPixel--}
```
public final int getBytesPerPixel()
```


Piksel başına bayt değerini elde edin; bu, görüntüdeki her pikselin kapladığı bellek miktarını gösterir. Bu özellik, bellek yönetimi ve optimizasyonu için kritik bir ölçüt olarak hizmet eder ve geliştiricilerin kaynakları verimli bir şekilde tahsis etmelerine ve görüntü verilerini işlemelerine yardımcı olur.

**Returns:**
int - piksel başına bayt.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Alpha kanalı içerip içermediğini gösteren bir boolean değer alır, şeffaflık efektlerini kolaylaştırır. Bu özellik, görüntü bileşimi ve renderleme işlemlerini yönetmek için temel bilgi sağlar ve geliştiricilerin çeşitli görsel efektler ve kompozisyon işlemleri uygulamasına yardımcı olur.

**Returns:**
boolean - bu [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) alpha kanalı içerip içermediğini gösteren bir değer.
### isGrayScale() {#isGrayScale--}
```
public final boolean isGrayScale()
```


Bu [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) gri tonlamalı bir görüntüyü temsil edip etmediğini gösteren bir boolean değer elde edin. Bu özellik, renkli ve gri tonlamalı görüntüleri ayırt etmek için kritiktir ve geliştiricilerin görüntünün renk özelliklerine göre uygun işleme ve renderleme tekniklerini uygulamasına yardımcı olur.

**Returns:**
boolean - bu [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) gri tonlamalı olup olmadığını gösteren bir değer.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Bu [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) örneği tarafından temsil edilen görüntünün genişliğini alın. Bu özellik, geliştiricilere görüntü boyutları hakkında temel bilgi sağlar ve yazılım uygulamalarında çeşitli görüntü manipülasyonu ve işleme görevlerini kolaylaştırır.

**Returns:**
int - bu görüntünün piksel cinsinden genişliği.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Bu [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) örneği tarafından kapsanan görüntünün yüksekliğini elde edin. Bu özellik, geliştiricilere görüntünün dikey boyutlarıyla ilgili kritik detaylar sunar ve yazılım çözümlerinde görüntülerin sorunsuz entegrasyonu ve manipülasyonunu sağlar.

**Returns:**
int - bu görüntünün piksel cinsinden yüksekliği.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Bu [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) örneği tarafından temsil edilen görüntünün dosya formatı hakkında kritik bilgiler alın. Dosya formatını anlamak, uyumluluk kontrolleri ve yazılım sistemleri içinde sorunsuz entegrasyon sağlamak için gereklidir; bu, görüntülerin verimli işlenmesi ve manipülasyonu için olanak tanır.

**Returns:**
long - bu [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) örneği tarafından temsil edilen görüntünün dosya formatı hakkında kritik bilgi.
### hasColorMap() {#hasColorMap--}
```
public final boolean hasColorMap()
```


Bu [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) örneğinin bir renk haritası içerip içermediğini alın. Renk haritasının varlığını anlamak, görüntünün renk verilerinin doğru yorumlanması ve manipülasyonu için kritiktir.

**Returns:**
boolean - bu görüntünün renk haritasına sahip olup olmadığını gösteren bir değer.
### getGammaValueNumerator() {#getGammaValueNumerator--}
```
public final int getGammaValueNumerator()
```


Gama değerinin pay kısmını alır; bu, görüntülerde doğru renk temsilı için gereklidir. Gama düzeltmesi olmayan görüntülerde bu değer 1.0 olmalıdır. Bu değeri anlamak ve kullanmak, renk sadakatini korumak ve doğru görüntü işleme sağlamak için kritiktir.

**Returns:**
int - gama değerinin pay kısmı, görüntülerde doğru renk temsilı için gereklidir.
### getGammaValueDenominator() {#getGammaValueDenominator--}
```
public final int getGammaValueDenominator()
```


Gama değerinin payda kısmını alır; bu, görüntülerde renk temsilını belirlemede bütünleyici bir faktördür. Gama düzeltmesi olmayan görüntülerde bu değer 1.0 olmalıdır ve doğru renk işleme sağlanır. Bu parametreyi takdir etmek ve kullanmak, renk sadakatini korumak ve kesin görüntü görselleştirme elde etmek için temeldir.

**Returns:**
int
### getPixelAspectRatioNumerator() {#getPixelAspectRatioNumerator--}
```
public final int getPixelAspectRatioNumerator()
```


Piksel En/Boy Oranı'nın pay bileşenini alır; bu, görüntüdeki piksellerin görsel görünümünü etkiler. Bu değeri anlamak ve manipüle etmek, görüntü işleme ve renderlamada doğru piksel temsili ve en/boy oranları elde etmek için gereklidir.

**Returns:**
int
### getPixelAspectRatioDenominator() {#getPixelAspectRatioDenominator--}
```
public final int getPixelAspectRatioDenominator()
```


Piksel En/Boy Oranı'nın payda kısmını alır; bu, görüntüdeki piksellerin görsel görünümünü belirlemede kritik bir faktördür. Bu değer, çeşitli görüntü renderleme ve işleme işlemleri boyunca doğru piksel temsili ve en/boy oranlarını korumak için gereklidir ve yüksek kaliteli görsel çıktı sağlar.

**Returns:**
int
### getXOrigin() {#getXOrigin--}
```
public final int getXOrigin()
```


Ekranın sol alt köşesinde bir orijine sahip bir görüntü aygıtında (ör. TARGA serisi) konumlandırılmış görüntünün sol alt köşesi için mutlak yatay koordinatı alır.

**Returns:**
int - ekranın sol alt köşesinden başlayan bir görüntü cihazında görüntünün sol alt köşesinin mutlak yatay koordinatı.
### setXOrigin(int value) {#setXOrigin-int-}
```
public final void setXOrigin(int value)
```


Ekranın sol alt köşesinde bir orijine sahip bir görüntü aygıtında (ör. TARGA serisi) konumlandırılmış görüntünün sol alt köşesi için mutlak yatay koordinatı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | ekranın sol alt köşesinden başlayan bir görüntü cihazında görüntünün sol alt köşesinin mutlak yatay koordinatı. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getYOrigin() {#getYOrigin--}
```
public final int getYOrigin()
```


Ekranın sol alt köşesinde bir orijine sahip bir görüntü aygıtında (ör. TARGA serisi) konumlandırılmış görüntünün sol alt köşesi için mutlak dikey koordinatı alır.

**Returns:**
int - ekranın sol alt köşesinden başlayan bir görüntü cihazında görüntünün sol alt köşesinin mutlak dikey koordinatı.
### setYOrigin(int value) {#setYOrigin-int-}
```
public final void setYOrigin(int value)
```


Ekranın sol alt köşesinde bir orijine sahip bir görüntü aygıtında (ör. TARGA serisi) konumlandırılmış görüntünün sol alt köşesi için mutlak dikey koordinatı ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | ekranın sol alt köşesinden başlayan bir görüntü cihazında görüntünün sol alt köşesinin mutlak dikey koordinatı. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getImageId() {#getImageId--}
```
public final String getImageId()
```


Görüntüyle ilişkili benzersiz tanımlayıcıyı alır. Bu kimlik, bir sistem veya uygulama içinde görüntüyü diğerlerinden tanımlamak ve ayırt etmek için bir referans noktası görevi görür. Görüntü Kimliğini ayarlayarak veya alarak görüntüleri etkili bir şekilde yönetebilir ve izleyebilir, düzenli görüntü yönetimi ve geri getirme süreçlerini kolaylaştırabilirsiniz.

Bu isteğe bağlı alan, görüntü hakkında tanımlayıcı bilgiler içerir. Bu alanın maksimum uzunluğu 255 bayttır.

**Returns:**
java.lang.String - görüntüyle ilişkili benzersiz tanımlayıcı.
### setImageId(String value) {#setImageId-java.lang.String-}
```
public final void setImageId(String value)
```


Görüntüyle ilişkili benzersiz tanımlayıcıyı ayarlar. Bu kimlik, bir sistem veya uygulama içinde görüntüyü diğerlerinden tanımlamak ve ayırt etmek için bir referans noktası görevi görür. Görüntü Kimliğini ayarlayarak veya alarak görüntüleri etkili bir şekilde yönetebilir ve izleyebilir, düzenli görüntü yönetimi ve geri getirme süreçlerini kolaylaştırabilirsiniz.

Bu isteğe bağlı alan, görüntü hakkında tanımlayıcı bilgiler içerir. Bu alanın maksimum uzunluğu 255 bayttır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | görüntüyle ilişkili benzersiz tanımlayıcı. |

### getAuthorComments() {#getAuthorComments--}
```
public final String getAuthorComments()
```


Görüntünün yazarının sağladığı yorumları alır veya ayarlar. Bu yorumlar genellikle görüntü hakkında açıklamalar, ek açıklamalar veya ek bağlam gibi değerli bilgiler içerir. Author Comments özelliğine erişerek veya değiştirerek geliştiriciler, görüntüyle ilişkili meta verileri zenginleştirebilir, kullanıcılara içeriği veya oluşturulmasıyla ilgili değerli içgörüler ve bağlam sağlayabilir. Bu, 324 bayttan oluşan bir ASCII alanıdır ve 80 karakterlik dört satır olarak düzenlenir; her satır bir null sonlandırıcı ile biter.

**Returns:**
java.lang.String
### setAuthorComments(String value) {#setAuthorComments-java.lang.String-}
```
public final void setAuthorComments(String value)
```


Görüntünün yazarının sağladığı yorumları alır veya ayarlar. Bu yorumlar genellikle görüntü hakkında açıklamalar, ek açıklamalar veya ek bağlam gibi değerli bilgiler içerir. Author Comments özelliğine erişerek veya değiştirerek geliştiriciler, görüntüyle ilişkili meta verileri zenginleştirebilir, kullanıcılara içeriği veya oluşturulmasıyla ilgili değerli içgörüler ve bağlam sağlayabilir. Bu, 324 bayttan oluşan bir ASCII alanıdır ve 80 karakterlik dört satır olarak düzenlenir; her satır bir null sonlandırıcı ile biter.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getAuthorName() {#getAuthorName--}
```
public final String getAuthorName()
```


Görüntüyle ilişkili yazarın adını alır veya ayarlar. Bu özellik, geliştiricilerin yazarın adının meta verilerine erişmesini veya değiştirmesini sağlar ve görüntünün yaratıcısı hakkında değerli bilgiler sunar. Author Name özelliğini kullanarak kullanıcılar, görüntüyü oluşturan veya katkıda bulunan kişiyi kolayca tanımlayabilir, genel meta verileri geliştirebilir ve izleyicilere değerli bağlam sağlayabilir. Bu alan, ad için toplam 40 ASCII karakter içerir. Alan kullanıldığında, görüntüyü oluşturan kişinin (yazar) adını içermelidir.

**Returns:**
java.lang.String
### setAuthorName(String value) {#setAuthorName-java.lang.String-}
```
public final void setAuthorName(String value)
```


Görüntüyle ilişkili yazarın adını alır veya ayarlar. Bu özellik, geliştiricilerin yazarın adının meta verilerine erişmesini veya değiştirmesini sağlar ve görüntünün yaratıcısı hakkında değerli bilgiler sunar. Author Name özelliğini kullanarak kullanıcılar, görüntüyü oluşturan veya katkıda bulunan kişiyi kolayca tanımlayabilir, genel meta verileri geliştirebilir ve izleyicilere değerli bağlam sağlayabilir. Bu alan, ad için toplam 40 ASCII karakter içerir. Alan kullanıldığında, görüntüyü oluşturan kişinin (yazar) adını içermelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yazar Adı. |

### getDateTimeStamp() {#getDateTimeStamp--}
```
public final Date getDateTimeStamp()
```


Date/Time Stamp değerini alır. Bu alan, görüntünün kaydedildiği tarih ve saat değerini tanımlar. İşletim sistemleri genellikle dosyaları tarih ve saat damgası ile işlese de, dosya kopyalandığında işletim sistemi bu damgayı değiştirebileceği için bu özellik sağlanır. Bu alanı kullanarak tarih ve saat kaydı için değiştirilmemiş bir bölge garantilenir.

**Returns:**
java.util.Date - Date/Time Stamp.
### setDateTimeStamp(Date value) {#setDateTimeStamp-java.util.Date-}
```
public final void setDateTimeStamp(Date value)
```


Tarih/Saat Damgasını ayarlar. Bu alan, görüntünün kaydedildiği tarih ve saat değerini tanımlar. İşletim sistemleri genellikle dosyaları tarih ve saat damgası ile işaretlese de, bu özellik işletim sisteminin dosya kopyalandığında tarih ve saat damgasını değiştirebilmesi nedeniyle sağlanır. Bu alanı kullanarak tarih ve saat kaydı için değiştirilmemiş bir bölge garantilenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date | Tarih/Saat Damgası. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getJobNameOrId() {#getJobNameOrId--}
```
public final String getJobNameOrId()
```


İmajla ilişkili iş adı veya kimliğini alır veya ayarlar. Bu özellik, imajla ilişkili belirli iş veya proje ile ilgili meta verilerine erişmenizi veya bunları değiştirmenizi sağlar. İş Adı/Kimliği özelliğini kullanarak kullanıcılar, imajın ait olduğu projeyi veya görevi kolayca tanımlayabilir, böylece daha büyük iş akışları veya projeler içinde imaj varlıklarının organizasyonu ve yönetimi kolaylaşır.

**Returns:**
java.lang.String - Job Name/ID.
### setJobNameOrId(String value) {#setJobNameOrId-java.lang.String-}
```
public final void setJobNameOrId(String value)
```


İmajla ilişkili iş adı veya kimliğini alır veya ayarlar. Bu özellik, imajla ilişkili belirli iş veya proje ile ilgili meta verilerine erişmenizi veya bunları değiştirmenizi sağlar. İş Adı/Kimliği özelliğini kullanarak kullanıcılar, imajın ait olduğu projeyi veya görevi kolayca tanımlayabilir, böylece daha büyük iş akışları veya projeler içinde imaj varlıklarının organizasyonu ve yönetimi kolaylaşır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | İş Adı/Kimliği. |

### getJobTime() {#getJobTime--}
```
public final Date getJobTime()
```


İmajla ilişkili iş zamanını gösteren zaman damgasını alır veya ayarlar. Bu özellik, geliştiricilerin imajla ilişkili belirli iş veya proje ile ilgili zaman meta verilerine erişmesini veya bunları değiştirmesini sağlar.

**Returns:**
java.util.Date - Job Time.
### setJobTime(Date value) {#setJobTime-java.util.Date-}
```
public final void setJobTime(Date value)
```


İmajla ilişkili iş zamanını gösteren zaman damgasını alır veya ayarlar. Bu özellik, geliştiricilerin imajla ilişkili belirli iş veya proje ile ilgili zaman meta verilerine erişmesini veya bunları değiştirmesini sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.Date | İş Zamanı. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


İmajla ilişkili ana rengi alır veya ayarlar. Bu özellik, belirli görüntü işleme görevleri veya efektleri için ana renk olarak belirlenen renge erişmenizi veya onu değiştirmenizi sağlar. Ana Renk özelliğini kullanmak, kullanıcıların renk tabanlı işlemler (örneğin chroma keyleme veya renk değiştirme) uygulamasına olanak tanır ve görüntü manipülasyonu yeteneklerini ve yaratıcı olasılıkları artırır.

Ana Renk, \\u2018arka plan rengi\\u2019 veya \\u2018şeffaf renk\\u2019 olarak düşünülebilir. Bu, ekranın \\u2018görüntü dışı\\u2019 alanının rengidir ve uygulamada silindiğinde ekranın temizleneceği aynı renktir.

**Returns:**
[Color](../../com.aspose.imaging/color) - Key Color.
### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


İmajla ilişkili ana rengi alır veya ayarlar. Bu özellik, belirli görüntü işleme görevleri veya efektleri için ana renk olarak belirlenen renge erişmenizi veya onu değiştirmenizi sağlar. Ana Renk özelliğini kullanmak, kullanıcıların renk tabanlı işlemler (örneğin chroma keyleme veya renk değiştirme) uygulamasına olanak tanır ve görüntü manipülasyonu yeteneklerini ve yaratıcı olasılıkları artırır.

Ana Renk, \\u2018arka plan rengi\\u2019 veya \\u2018şeffaf renk\\u2019 olarak düşünülebilir. Bu, ekranın \\u2018görüntü dışı\\u2019 alanının rengidir ve uygulamada silindiğinde ekranın temizleneceği aynı renktir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Ana Renk. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


İmajın şeffaf bir renk içerip içermediğini gösteren bir boolean değerini alır veya ayarlar. Bu özellik, imajın şeffaflığı destekleyip desteklemediğini belirlemek için esastır ve karıştırma, birleştirme veya maskeleme gibi şeffaflıkla ilgili işlemlerin uygun şekilde ele alınmasına yardımcı olur.

**Returns:**
boolean - imajın şeffaf renk içerip içermediğini gösteren bir değer.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


İmajın şeffaf bir renk içerip içermediğini gösteren bir boolean değerini alır veya ayarlar. Bu özellik, imajın şeffaflığı destekleyip desteklemediğini belirlemek için esastır ve karıştırma, birleştirme veya maskeleme gibi şeffaflıkla ilgili işlemlerin uygun şekilde ele alınmasına yardımcı olur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | imajın şeffaf renk içerip içermediğini gösteren bir değer. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


İmajın arka plan rengini alır veya ayarlar. Bu özellik, imajın arka planı için kullanılan rengi belirlemenizi sağlar, tutarlılığı sağlar ve görsel sunumu iyileştirir. Özellikle imajın farklı bir renkteki arka plan üzerinde gösterildiği veya imajın başka bir tuval üzerine render edildiği durumlarda faydalıdır.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


İmajın arka plan rengini alır veya ayarlar. Bu özellik, imajın arka planı için kullanılan rengi belirlemenizi sağlar, tutarlılığı sağlar ve görsel sunumu iyileştirir. Özellikle imajın farklı bir renkteki arka plan üzerinde gösterildiği veya imajın başka bir tuval üzerine render edildiği durumlarda faydalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | arka plan rengi. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


İmajın bir arka plan rengi içerip içermediğini gösteren bir değeri alır veya ayarlar. Bu özellik, imajın ön plan içeriğinden ayrı belirgin bir arka plan rengine sahip olup olmadığını belirlemek için kullanışlıdır. Arka plan renginin varlığına veya yokluğuna göre görüntü işleme veya renderlamayı özelleştirmenizi sağlar.

**Returns:**
boolean - imajın arka plan rengine sahip olup olmadığını gösteren bir değer.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


İmajın bir arka plan rengi içerip içermediğini gösteren bir değeri alır veya ayarlar. Bu özellik, imajın ön plan içeriğinden ayrı belirgin bir arka plan rengine sahip olup olmadığını belirlemek için kullanışlıdır. Arka plan renginin varlığına veya yokluğuna göre görüntü işleme veya renderlamayı özelleştirmenizi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | imajın arka plan rengine sahip olup olmadığını gösteren bir değer. |

### getSoftwareVersion() {#getSoftwareVersion--}
```
public final String getSoftwareVersion()
```


İmajla ilişkili yazılım sürümünü alır veya ayarlar. Sürüm dizesinin kabul edilen uzunluğu genellikle 3 ila 4 karakterdir. Bu özellik, imajı oluşturmak veya işlemek için kullanılan yazılımı izlemek için faydalıdır ve görüntü işleme ve uyumluluk kontrolleri için değerli bağlam sağlayabilir.

**Returns:**
java.lang.String - Software Version.
### setSoftwareVersion(String value) {#setSoftwareVersion-java.lang.String-}
```
public final void setSoftwareVersion(String value)
```


İmajla ilişkili yazılım sürümünü alır veya ayarlar. Sürüm dizesinin kabul edilen uzunluğu genellikle 3 ila 4 karakterdir. Bu özellik, imajı oluşturmak veya işlemek için kullanılan yazılımı izlemek için faydalıdır ve görüntü işleme ve uyumluluk kontrolleri için değerli bağlam sağlayabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yazılım Sürümü. |

### getSoftwareVersionLetter() {#getSoftwareVersionLetter--}
```
public final char getSoftwareVersionLetter()
```


İmajla ilişkili yazılım sürümünün harf bileşenini alır veya ayarlar. Bu özellik, yazılım sürüm dizesi içinde ek bir ayrıntıyı temsil eder ve daha ince sürüm ayrımı için faydalı olabilir.

**Returns:**
char - Yazılım Sürümü harf bölümü.
### setSoftwareVersionLetter(char value) {#setSoftwareVersionLetter-char-}
```
public final void setSoftwareVersionLetter(char value)
```


İmajla ilişkili yazılım sürümünün harf bileşenini alır veya ayarlar. Bu özellik, yazılım sürüm dizesi içinde ek bir ayrıntıyı temsil eder ve daha ince sürüm ayrımı için faydalı olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | char | Yazılım Sürümü harf bölümü. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareVersionNumber() {#getSoftwareVersionNumber--}
```
public final int getSoftwareVersionNumber()
```


Görüntüyle ilişkili yazılım sürümünün sayısal bileşenini alır veya ayarlar. Bu özellik, yazılım sürüm dizesinin sayısal kısmını temsil eder ve görüntüyü oluşturmak veya değiştirmek için kullanılan yazılımın sürümü hakkında önemli bilgiler sağlar.

**Returns:**
int - Yazılım Sürümü sayı bölümü.
### setSoftwareVersionNumber(int value) {#setSoftwareVersionNumber-int-}
```
public final void setSoftwareVersionNumber(int value)
```


Görüntüyle ilişkili yazılım sürümünün sayısal bileşenini alır veya ayarlar. Bu özellik, yazılım sürüm dizesinin sayısal kısmını temsil eder ve görüntüyü oluşturmak veya değiştirmek için kullanılan yazılımın sürümü hakkında önemli bilgiler sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yazılım Sürümü sayı bölümü. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareId() {#getSoftwareId--}
```
public final String getSoftwareId()
```


Görüntüyle ilişkili yazılım kimliğini (ID) yönetir ve en fazla 40 ASCII karakterine izin verir. Bu özellik, görüntünün oluşturulması veya işlenmesinde kullanılan yazılımı benzersiz şekilde tanımlamak için bir yöntem sağlar ve organizasyonel ve bilgilendirme amaçları için değerli üst veriler sunar.

**Returns:**
java.lang.String - Yazılım ID'si.
### setSoftwareId(String value) {#setSoftwareId-java.lang.String-}
```
public final void setSoftwareId(String value)
```


Görüntüyle ilişkili yazılım kimliğini (ID) yönetir ve en fazla 40 ASCII karakterine izin verir. Bu özellik, görüntünün oluşturulması veya işlenmesinde kullanılan yazılımı benzersiz şekilde tanımlamak için bir yöntem sağlar ve organizasyonel ve bilgilendirme amaçları için değerli üst veriler sunar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yazılım ID'si. |

### op_Equality(TgaImage first, TgaImage second) {#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Equality(TgaImage first, TgaImage second)
```


Karşılaştırma sürecine dahil olan ilk ve ikinci görüntüyü dikkate alarak iki TGA görüntüsü arasında eşitlik karşılaştırması yapar. Bu yöntem, görüntü eşitliğinin doğrudan değerlendirilmesini kolaylaştırır ve görüntü işleme iş akışlarında doğru analiz ve karar vermeyi sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Karşılaştırmaya katılan ilk [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Karşılaştırmaya katılan ikinci [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |

**Returns:**
boolean - Karşılaştırma sonuçları.
### op_Inequality(TgaImage first, TgaImage second) {#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Inequality(TgaImage first, TgaImage second)
```


Karşılaştırmaya dahil olan ilk ve ikinci görüntüyü değerlendirerek iki TGA görüntüsü arasında eşit olmayan bir karşılaştırma gerçekleştirir. Bu yöntem, görüntüler arasındaki tutarsızlıkları veya farkları belirlemeye yardımcı olur ve görüntü işleme görevlerinde kesin analiz ve karar vermeyi mümkün kılar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Karşılaştırmaya katılan ilk [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Karşılaştırmaya katılan ikinci [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |

**Returns:**
boolean - Karşılaştırma sonuçları.
### deepClone() {#deepClone--}
```
public final TgaImage deepClone()
```


Mevcut örneğin bir kopyasını üretir, orijinalin tüm öznitelik ve özelliklerini klonlayan yeni bir nesne oluşturur. Bu yöntem, aynı kopyaların oluşturulmasını kolaylaştırır, veri bütünlüğünü sağlar ve orijinal nesneyi etkilemeden mevcut örneğin durumunu korur.

**Returns:**
[TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) - Returns a new object that is a copy of the current instance.
### deepClone(TgaImage tgaImage) {#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final void deepClone(TgaImage tgaImage)
```


Başka bir [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) nesnesinin özelliklerini kopyalar, aynı özniteliklere sahip yeni bir örnek oluşturur. Bu işlem, veri bütünlüğünün korunmasını sağlar ve kaynak nesneyi değiştirmeden görüntü özelliklerinin çoğaltılmasını kolaylaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tgaImage | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Diğer [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) |

### equals(TgaImage other) {#equals-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final boolean equals(TgaImage other)
```


Bir eşitlik karşılaştırmasında, yöntem mevcut [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) örneğinin parametre olarak verilen ikinci görüntüye eşit olup olmadığını değerlendirir. Bu işlem, iki TGA görüntüsünün aynı olup olmadığını belirlemeyi kolaylaştırır ve görüntü işleme ve karşılaştırma görevlerine yardımcı olur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Karşılaştırmaya katılan ikinci [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |

**Returns:**
boolean - Karşılaştırma sonuçları.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Yöntem, mevcut [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) örneği ile parametre olarak verilen başka bir nesne arasında eşitlik karşılaştırması yapar. Özellikle, mevcut görüntünün özelliklerinin ikinci nesnenin özellikleriyle eşleşip eşleşmediğini değerlendirir ve görüntü işleme iş akışlarında karşılaştırma amaçlı eşdeğerliklerini belirlemeye yardımcı olur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| other | java.lang.Object | Karşılaştırmaya katılan ikinci [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage). |

**Returns:**
boolean - Karşılaştırma sonuçları.
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


The "rotateFlip" yöntemi, görüntü üzerinde döndürme ve çevirme işlemlerini etkinleştirir. Görüntü yönlendirmesini manipüle etmek için çok yönlü işlevsellik sunar, kullanıcıların gereksinimlerine göre döndürme ve çevirme yapmalarına izin verir ve yazılım uygulamalarında verimli görüntü işleme görevlerini kolaylaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateFlipType | int | Döndürme çevirme türü. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Mevcut örneğin hash kodunu alın. Ancak, bu hash kodunun özellikle TgaImage sınıfının örnekleri değiştirilebilir olduğu için bir anahtar olarak kullanılamayabileceğini unutmamak önemlidir.

**Returns:**
int - Bu örneğin hash kodu.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Görüntüyü belirli bir bölgeye kırpın. Bu yöntem, görüntü içinde tutmak istediğiniz dikdörtgen bir alanı tanımlamanıza ve geri kalanını atmanıza olanak sağlar. Bu işlem, görüntüdeki belirli içeriğe odaklanmak veya istenmeyen bölümleri kaldırmak için faydalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Görüntüyü sol, sağ, üst ve alt sınırlar için kaydırmalar belirterek kırpın. Bu yöntem, sınırları yatay ve dikey eksenlerde bağımsız olarak hareket ettirerek görüntüyü kırpmanıza olanak tanır. Bu kaydırmaları ayarlayarak, görüntünün hangi bölümlerinin korunacağını hassas bir şekilde kontrol edebilir ve istediğiniz boyutlara etkili bir şekilde kırpabilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| leftShift | int | Sol kaydırma. |
| rightShift | int | Sağ kaydırma. |
| topShift | int | Üst kaydırma. |
| bottomShift | int | Alt kaydırma. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Görüntüyü, istenen boyutları ve en-boy oranını korumak için belirli ayarları uygulayarak yeniden boyutlandırın. Görüntü ayarlarını özelleştirerek, görüntüyü etkili bir şekilde yeniden boyutlandırabilir ve optimal görsel kaliteyi ve farklı görüntüleme cihazları veya uygulamalarla uyumluluğu sağlayabilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Yeniden boyutlandırma ayarları. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Görüntünün boyutunu, yeniden boyutlandırma işleminin nasıl gerçekleştirileceğini belirleyen belirtilen bir yeniden boyutlandırma türü kullanarak ayarlar. Bu yöntem, farklı algoritmalar veya teknikler doğrultusunda görüntüleri yeniden boyutlandırmada esneklik sağlar. Uygun yeniden boyutlandırma türünü seçerek, belirli gereksinimler veya tercihler doğrultusunda görüntü kalitesi ile hesaplama verimliliği arasında istenen dengeyi elde edebilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Görüntüyü, yeniden boyutlandırma oranını koruyarak ve arka plan rengini koruyarak, belirtilen bir açıyla merkez etrafında döndürür. Bu yöntem, görüntünün döndürülmesinin görsel dengeyi ve belirtilen arka plan rengiyle tutarlılığı korumasını sağlayarak hassas görüntü manipülasyonu sağlar. Merkez etrafında doğru döndürmenin gerekli olduğu yönlendirme düzeltme veya sanatsal ayarlamalar gibi görevler için idealdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Dönüş açısı dereceler cinsindendir. Pozitif değerler saat yönünde dönecektir. |
| resizeProportionally | boolean | eğer `true` olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgenin (köşe noktaları) izdüşümlerine göre değişir; diğer durumda boyutlar dokunulmaz kalır ve sadece `` görüntü içeriği döndürülür. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Arka planın rengi. |

