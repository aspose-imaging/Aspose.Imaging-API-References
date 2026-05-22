---
title: "JpegImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "API'mizle JPEG raster görüntülerini verimli bir şekilde işleyin; RGB ve CMYK gibi çeşitli renk profillerini destekler, piksel başına özelleştirilebilir bit çözünürlüğü ve EXIF, JFIF ve XMP meta veri kapsayıcılarının işlenmesini sunar."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.fileformats.jpeg/jpegimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.exif.IHasJpegExifData](../../com.aspose.imaging.exif/ihasjpegexifdata)
```
public final class JpegImage extends RasterCachedImage implements IHasJpegExifData
```

API'mizle JPEG raster görüntülerini verimli bir şekilde işleyin; RGB ve CMYK gibi çeşitli renk profillerini destekler, piksel başına özelleştirilebilir bit çözünürlüğü ve EXIF, JFIF ve XMP meta veri kapsayıcılarının işlenmesini sağlar. Yönlendirme verilerine dayalı otomatik döndürmenin keyfini çıkarın ve kayıpsız JPEG dahil farklı sıkıştırma seviyelerinden seçim yaparak projeleriniz için optimal görüntü kalitesi ve dosya boyutu dengesini elde edin.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [JpegImage(String path)](#JpegImage-java.lang.String-) | Belirtilen yol parametresiyle yapıcıyı çağırarak [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) sınıfı sorunsuz bir şekilde başlatılır. |
| [JpegImage(InputStream stream)](#JpegImage-java.io.InputStream-) | Akış parametresi kullanarak [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) sınıfı ile bir JPEG görüntü nesnesi başlatın. |
| [JpegImage(RasterImage rasterImage)](#JpegImage-com.aspose.imaging.RasterImage-) | Raster görüntü parametresiyle [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) sınıfının yeni bir örneğini başlatın. |
| [JpegImage(int width, int height)](#JpegImage-int-int-) | Belirtilen genişlik ve yükseklik parametreleriyle [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) sınıfının yeni bir örneğini oluşturun. |
| [JpegImage(JpegOptions jpegOptions, int width, int height)](#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-) | Sağlanan JPEG seçenekleriyle yeni bir [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) nesnesi başlatın. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Bu özellik sayesinde görüntünün biçimini zahmetsizce alın. |
| [getJpegOptions()](#getJpegOptions--) | Bu [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) örneğinin oluşturulması veya yüklenmesi sırasında kullanılan JPEG seçeneklerine kolayca erişin. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Bu özellik sayesinde görüntünün piksel derinliğini zahmetsizce alın; renk ya da gri tonlamanın zenginliği hakkında bilgi sağlar. |
| [getComment()](#getComment--) | Bu özellik ile JPEG dosya yorumlarını yönetin; görüntüye ilişkin açıklayıcı notları ekleyebilir veya alabilirsiniz. |
| [setComment(String value)](#setComment-java.lang.String-) | Bu özellik ile JPEG dosya yorumlarını yönetin; görüntüye ilişkin açıklayıcı notları ekleyebilir veya alabilirsiniz. |
| [getJpegExifData()](#getJpegExifData--) | Exif örneğini alır. |
| [setJpegExifData(JpegExifData value)](#setJpegExifData-com.aspose.imaging.exif.JpegExifData-) | Bu özellik ile EXIF verilerini yönetin; görüntüye ilişkin üst verileri ekleyebilir veya alabilirsiniz. |
| [getExifData()](#getExifData--) | Exif verilerini alır; |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Exif verilerini ayarlar; |
| [getHeight()](#getHeight--) | Bu özellik sayesinde görüntünün yüksekliğini zahmetsizce alın. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Bu özellik, [RasterImage](../../com.aspose.imaging/rasterimage) öğesinin inç başına piksel cinsinden ölçülen yatay çözünürlüğüne erişmenizi sağlar. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Bu özellik, [RasterImage](../../com.aspose.imaging/rasterimage) öğesinin inç başına piksel cinsinden ölçülen yatay çözünürlüğüne erişmenizi sağlar. |
| [getJfif()](#getJfif--) | Bu özellik, JPEG görüntüsüyle ilişkili JFIF (JPEG Dosya Değişim Formatı) verilerine erişmenizi veya bunları değiştirmenizi sağlar. |
| [setJfif(JFIFData value)](#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-) | Bu özellik, JPEG görüntüsüyle ilişkili JFIF (JPEG Dosya Değişim Formatı) verilerine erişmenizi veya bunları değiştirmenizi sağlar. |
| [getRawDataFormat()](#getRawDataFormat--) | Bu özellik, görüntünün ham veri biçimini alır; bu, görüntü verilerinin nasıl yapılandırıldığını ve kodlandığını gösterir. |
| [getVerticalResolution()](#getVerticalResolution--) | Bu özellik, ilişkili [RasterImage](../../com.aspose.imaging/rasterimage) için inç başına piksel cinsinden ifade edilen dikey çözünürlüğü yönetir. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Bu özellik, ilişkili [RasterImage](../../com.aspose.imaging/rasterimage) için inç başına piksel cinsinden ifade edilen dikey çözünürlüğü yönetir. |
| [getWidth()](#getWidth--) | Bu özellik, görüntünün piksel cinsinden genişliğini alır. |
| [getRgbColorProfile()](#getRgbColorProfile--) | CMYK ve YCCK JPEG görüntüleri için RGB renk profili, doğru renk dönüşümü ve temsili sağlar. |
| [setRgbColorProfile(StreamSource value)](#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | CMYK ve YCCK JPEG görüntüleri için RGB renk profili, doğru renk dönüşümü ve temsili sağlar. |
| [getCmykColorProfile()](#getCmykColorProfile--) | CMYK ve YCCK JPEG görüntüleriyle ilişkili CMYK renk profili, kesin renk dönüşümü ve doğruluk sağlar. |
| [setCmykColorProfile(StreamSource value)](#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | CMYK ve YCCK JPEG görüntüleriyle ilişkili CMYK renk profili, kesin renk dönüşümü ve doğruluk sağlar. |
| [getDestinationRgbColorProfile()](#getDestinationRgbColorProfile--) | RGBColorProfile, kaydetme işlemi sırasında CMYK ve YCCK JPEG görüntülerinin doğru renk dönüşümü için gereklidir. |
| [setDestinationRgbColorProfile(StreamSource value)](#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-) | RGBColorProfile, kaydetme işlemi sırasında CMYK ve YCCK JPEG görüntülerinin doğru renk dönüşümü için gereklidir. |
| [getDestinationCmykColorProfile()](#getDestinationCmykColorProfile--) | CMYK renk profili, kaydetme sürecinde CMYK ve YCCK JPEG görüntülerinin doğru renk dönüşümü için hayati öneme sahiptir. |
| [setDestinationCmykColorProfile(StreamSource value)](#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-) | CMYK renk profili, kaydetme sürecinde CMYK ve YCCK JPEG görüntülerinin doğru renk dönüşümü için hayati öneme sahiptir. |
| [getIgnoreEmbeddedColorProfile()](#getIgnoreEmbeddedColorProfile--) | Gömülü renk profilinin göz ardı edilip edilmediğini belirten bayrağı alır veya değiştirir. |
| [setIgnoreEmbeddedColorProfile(boolean value)](#setIgnoreEmbeddedColorProfile-boolean-) | Gömülü renk profilinin göz ardı edilip edilmediğini belirten bayrağı alır veya değiştirir. |
| [getOriginalOptions()](#getOriginalOptions--) | Bu [Image](../../com.aspose.imaging/image) örneğinin orijinal görüntü seçeneklerini alır. |
| [removeMetadata()](#removeMetadata--) | Bu görüntü örneğinin meta verilerini, bu `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) ve `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) değerlerini `null` olarak ayarlayarak kaldırır. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | Belirtilen [RasterImage](../../com.aspose.imaging/rasterimage) için çözünürlüğü belirler; doğru ölçekleme ve baskı yeteneklerini sağlar. |

## Example: The example shows how to load a JpegImage from a file.

``` java
String dir = "c:\\temp\\";

// Bir JPEG görüntüsünü dosyadan yükleyin.
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = new com.aspose.imaging.fileformats.jpeg.JpegImage(dir + "sample.jpg");
try {
    // Bazı görüntü işleme işlemleri yapın.
    // Başka bir JPEG dosyasına kaydedin.
    jpegImage.save(dir + "sample.output.jpg");
} finally {
    jpegImage.dispose();
}
```


## Example: Access camera manufacturer maker notes in Jpeg image.

``` java
try (JpegImage image = (JpegImage)Image.load("Sample.jpg"))
{
    for (MakerNote makerNote : image.getExifData().getMakerNotes())
    {
        System.out.format("Name = %s, Value = %s", makerNote.getName(), makerNote.getValue());
    }
}
```

### JpegImage(String path) {#JpegImage-java.lang.String-}
```
public JpegImage(String path)
```


Bu [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) sınıfı, belirtilen yol parametresiyle yapıcı metodunu çağırarak zahmetsizce başlatılır. Bu yapıcı, JPEG görüntülerinin sorunsuz oluşturulmasını sağlar ve projelerinize hızlı entegrasyonu kolaylaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Görüntüyü yüklemek ve piksel ile palet verilerini başlatmak için yol. |

### JpegImage(InputStream stream) {#JpegImage-java.io.InputStream-}
```
public JpegImage(InputStream stream)
```


Bir akış parametresi kullanarak [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) sınıfı ile bir JPEG görüntü nesnesi başlatın. Bu yapıcı, JPEG görüntüleriyle çalışmayı basitleştirir ve projelerinize entegrasyonu zahmetsizce sağlayan doğrudan bir yaklaşım sunar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Görüntüyü yüklemek ve piksel ile palet verilerini başlatmak için akış. |

### JpegImage(RasterImage rasterImage) {#JpegImage-com.aspose.imaging.RasterImage-}
```
public JpegImage(RasterImage rasterImage)
```


Raster görüntü parametresi ile yeni bir [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) sınıfının bir örneğini başlatın. Bu yapıcı, JPEG görüntülerini raster görüntülerden doğrudan oluşturmanın pratik bir yolunu sunar ve uygulamalarınızda JPEG görüntülerle çalışmayı kolaylaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Piksel ve palet verilerini başlatmak için kullanılacak görüntü. |

### JpegImage(int width, int height) {#JpegImage-int-int-}
```
public JpegImage(int width, int height)
```


Belirtilen genişlik ve yükseklik parametreleriyle yeni bir [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) sınıfının örneğini oluşturun. Bu yapıcı, özel boyutlarda JPEG görüntüleri oluşturmanıza olanak tanır ve uygulamanızda görüntü boyutlarını yönetmede esneklik sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Görüntünün genişliği. |
| yükseklik | int | Görüntü yüksekliği. |

### JpegImage(JpegOptions jpegOptions, int width, int height) {#JpegImage-com.aspose.imaging.imageoptions.JpegOptions-int-int-}
```
public JpegImage(JpegOptions jpegOptions, int width, int height)
```


Sağlanan JPEG seçenekleriyle yeni bir [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) nesnesini başlatın. Bu yapıcı, sıkıştırma seviyesi, kalite ve ek parametreler gibi JPEG görüntüsü için çeşitli ayarları özelleştirmenizi sağlar ve ortaya çıkan görüntü formatı üzerinde hassas kontrol sunar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| jpegOptions | [JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) | JPEG seçenekleri. |
| genişlik | int | Görüntü genişliği. |
| yükseklik | int | Görüntü yüksekliği. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Bu özellik sayesinde görüntünün formatını zahmetsizce alın. Dosya formatı hakkında değerli bilgiler sunar, çeşitli platformlar ve uygulamalar arasında sorunsuz entegrasyon ve uyumluluk kontrollerine yardımcı olur.

**Returns:**
long
### getJpegOptions() {#getJpegOptions--}
```
public JpegOptions getJpegOptions()
```


Bu [JpegImage](../../com.aspose.imaging.fileformats.jpeg/jpegimage) örneğinin oluşturulması veya yüklenmesi sırasında kullanılan JPEG seçeneklerine kolayca erişin. Bu özellik, kullanılan belirli ayarlar hakkında değerli ayrıntılar sunar ve kullanıcıların görüntü işleme iş akışlarını etkili bir şekilde anlamalarını ve yeniden oluşturmalarını sağlar. İster sıkıştırma seviyeleri, kalite ayarları, ister diğer parametreler olsun, bu özellik sorunsuz görüntü manipülasyonu için temel içgörüler sağlar.

**Returns:**
[JpegOptions](../../com.aspose.imaging.imageoptions/jpegoptions) - The JPEG options.

**Example: The following example shows how to extract the header information from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.imageoptions.JpegOptions jpegOptions = image.getJpegOptions();

    System.out.println("The number of bits per channel: " + jpegOptions.getBitsPerChannel());
    System.out.println("The max allowed size for all internal buffers: " + jpegOptions.getBufferSizeHint());
    System.out.println("The color type: " + jpegOptions.getColorType());
    System.out.println("The compression type: " + jpegOptions.getCompressionType());
    System.out.println("The image quality: " + jpegOptions.getQuality());

    if (jpegOptions.getResolutionSettings() != null) {
        System.out.println("The horizontal resolution: " + jpegOptions.getResolutionSettings().getHorizontalResolution());
        System.out.println("The vertical resolution: " + jpegOptions.getResolutionSettings().getVerticalResolution());
    }

    for (int i = 0; i < jpegOptions.getHorizontalSampling().length; i++) {
        System.out.printf("The sampling for component %s: %sx%s\r\n", i, jpegOptions.getHorizontalSampling()[i], jpegOptions.getVerticalSampling()[i]);
    }
} finally {
    image.dispose();
}

//Çıktı şu şekilde görünür:
//Kanal başına bit sayısı: 8
//Tüm iç tamponlar için izin verilen maksimum boyut: 0
//Renk türü: YCbCr
//Sıkıştırma türü: Baseline
//Görüntü kalitesi: 75
//Bileşen 0 için örnekleme: 1x1
//Bileşen 1 için örnekleme: 1x1
//Bileşen 2 için örnekleme: 1x1
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Bu özellik sayesinde görüntünün piksel derinliğini zahmetsizce alın; renk ya da gri tonlamalı temsildeki zenginlik hakkında içgörüler sunar. Canlı bir fotoğraf ya da tek renkli bir illüstrasyon olsun, bu özellik görüntünün görsel karmaşıklığı hakkında kritik bilgiler sağlar.

**Returns:**
int - Görüntünün piksel başına bit sayısı.
### getComment() {#getComment--}
```
public String getComment()
```


Bu özellik ile JPEG dosya yorumlarını yönetin; görüntüye ilişkin açıklayıcı notları eklemenize veya almanıza olanak tanır. Görüntülere meta veri eklemek ya da ek bağlam eklemek olsun, bu özellik JPEG dosyalarınızı düzenleme ve sınıflandırmada esneklik sağlar.

**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Bu özellik ile JPEG dosya yorumlarını yönetin; görüntüye ilişkin açıklayıcı notları eklemenize veya almanıza olanak tanır. Görüntülere meta veri eklemek ya da ek bağlam eklemek olsun, bu özellik JPEG dosyalarınızı düzenleme ve sınıflandırmada esneklik sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getJpegExifData() {#getJpegExifData--}
```
public JpegExifData getJpegExifData()
```


Exif örneğini alır.

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif instance.
### setJpegExifData(JpegExifData value) {#setJpegExifData-com.aspose.imaging.exif.JpegExifData-}
```
public void setJpegExifData(JpegExifData value)
```


Bu özellik ile EXIF verilerini yönetin; görüntüyle ilişkili meta verileri eklemenize veya almanıza olanak tanır. Kamera ayarları hakkında bilgi çıkarmak ya da mevcut meta verileri değiştirmek olsun, bu özellik EXIF veri konteynerini yönetmede esneklik sunar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) |  |

### getExifData() {#getExifData--}
```
public JpegExifData getExifData()
```


Exif verilerini alır;

**Returns:**
[JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) - Exif data;

**Example: The following example shows how to extract EXIF tags from a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.jpeg.JpegImage image = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "original.jpg");
try {
    com.aspose.imaging.exif.ExifData exifData = image.getExifData();

    System.out.println("The general EXIF data");
    System.out.println("------------------------------------------");
    if (exifData != null) {
        System.out.println("The EXIF version: " + exifData.getExifVersion());
        System.out.println("The camera serial number: " + exifData.getBodySerialNumber());
        System.out.println("The color space: " + exifData.getColorSpace());
        System.out.println("The brightness: " + exifData.getBrightnessValue());
        System.out.println("The contrast: " + exifData.getContrast());
        System.out.println("The gamma: " + exifData.getGamma());
        System.out.println("The sharpness: " + exifData.getSharpness());
        System.out.println("The aperture: " + exifData.getApertureValue());
        System.out.println("The exposure mode: " + exifData.getExposureMode());
        System.out.println("The exposure bias: " + exifData.getExposureBiasValue());
        System.out.println("The exposure time: " + exifData.getExposureTime());
        System.out.println("The focal length: " + exifData.getFocalLength());
        System.out.println("The focal plane resolution unit: " + exifData.getFocalPlaneResolutionUnit());
        System.out.println("The lens model: " + exifData.getLensModel());
        System.out.println("The shutter speed: " + exifData.getShutterSpeedValue());
    }

    System.out.println("The JPEG EXIF data");
    System.out.println("------------------------------------------");
    if (exifData instanceof com.aspose.imaging.exif.JpegExifData) {
        com.aspose.imaging.exif.JpegExifData jpegExifData = (com.aspose.imaging.exif.JpegExifData) exifData;

        System.out.println("The camera manufacturer: " + jpegExifData.getMake());
        System.out.println("The camera model: " + jpegExifData.getModel());
        System.out.println("The photometric interpretation: " + jpegExifData.getPhotometricInterpretation());
        System.out.println("The artist: " + jpegExifData.getArtist());
        System.out.println("The copyright: " + jpegExifData.getCopyright());
        System.out.println("The image description: " + jpegExifData.getImageDescription());
        System.out.println("The orientation: " + jpegExifData.getOrientation());
        System.out.println("The software: " + jpegExifData.getSoftware());
    }
} finally {
    image.dispose();
}

//Çıktı şu şekilde görünür:
//Genel EXIF verileri
//------------------------------------------
//EXIF sürümü: [B@163e4e87
//Kamera seri numarası: 7100536
//Renk uzayı: SRgb
//Parlaklık:
//Kontrast: Normal
//Gama:
//Keskinlik: 0
//Diyafram: 4.64(4643856 / 1000000)
//Poz modu: Manuel
//Poz sapması: 0.67(4 / 6)
//Poz süresi: 0.01(1 / 160)
//Odak uzaklığı: 145.00(1450 / 10)
//Odak düzlemi çözünürlük birimi: Cm
//Lens modeli: 70.0 - 200.0 mm f/ 4.0
//Enstantane hızı: 7.32(7321928 / 1000000)
//JPEG EXIF verileri
//------------------------------------------
//Kamera üreticisi: NIKON CORPORATION
//Kamera modeli: NIKON D5
//Fotometrik yorum: 0
//Sanatçı:
//Telif hakkı:
//Görsel açıklaması:
//Yönelim: ÜstSol
//Yazılım: Adobe Photoshop Camera Raw 9.9(Macintosh)
```

### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Exif verilerini ayarlar;

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif verileri; |

### getHeight() {#getHeight--}
```
public int getHeight()
```


Bu özellik sayesinde görüntünün yüksekliğini zahmetsizce alın. Görüntünün dikey boyutuna hızlı erişim sağlar, karmaşık hesaplamalar veya ek yöntemler gerekmeksizin boyutunu ve en‑boy oranını verimli bir şekilde belirlemenize imkan tanır.

**Returns:**
int - Görüntü yüksekliği piksel cinsinden.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Bu özellik, [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin inç başına piksel cinsinden ölçülen yatay çözünürlüğüne erişim sağlar. Bu değeri ayarlayarak veya alarak görüntünün çözünürlüğünü hassas bir şekilde kontrol edebilir, kalite ve netlik konusundaki özel gereksinimlerinizi karşılamasını sağlayabilirsiniz.

**Returns:**
double - Yatay çözünürlük.

Not: varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // BmpImage'in yatay ve dikey çözünürlüğünü alın
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// Yatay çözünürlük, inç başına piksel olarak: 300.0
// Dikey çözünürlük, inç başına piksel olarak: 300.0
// Çözünürlük değerlerini 96 dpi olarak ayarlayın
// Yatay çözünürlük, inç başına piksel olarak: 96.0
// Dikey çözünürlük, inç başına piksel olarak: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Bu özellik, [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin inç başına piksel cinsinden ölçülen yatay çözünürlüğüne erişim sağlar. Bu değeri ayarlayarak veya alarak görüntünün çözünürlüğünü hassas bir şekilde kontrol edebilir, kalite ve netlik konusundaki özel gereksinimlerinizi karşılamasını sağlayabilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Yatay çözünürlük. |

Not: Varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Tek bir çağrıda her iki çözünürlük değerini güncellemek için `setResolution` metodunu kullanmayı düşünebilirsiniz. |

### getJfif() {#getJfif--}
```
public JFIFData getJfif()
```


Bu özellik, JPEG görüntüsüyle ilişkili JFIF (JPEG File Interchange Format) verilerine erişmenizi veya bu verileri değiştirmenizi sağlar. JFIF, bilgisayarlar ve diğer cihazlar arasında JPEG sıkıştırmalı görüntülerin değiş tokuşu için standart bir formattır. Bu özelliği alarak veya ayarlayarak JFIF verileriyle etkileşime geçebilir, bu verilerin görüntünün çözünürlüğü, en‑boy oranı ve küçük resim gibi bilgileri içerebileceğini görebilirsiniz.

**Returns:**
[JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata)
### setJfif(JFIFData value) {#setJfif-com.aspose.imaging.fileformats.jpeg.JFIFData-}
```
public void setJfif(JFIFData value)
```


Bu özellik, JPEG görüntüsüyle ilişkili JFIF (JPEG File Interchange Format) verilerine erişmenizi veya bu verileri değiştirmenizi sağlar. JFIF, bilgisayarlar ve diğer cihazlar arasında JPEG sıkıştırmalı görüntülerin değiş tokuşu için standart bir formattır. Bu özelliği alarak veya ayarlayarak JFIF verileriyle etkileşime geçebilir, bu verilerin görüntünün çözünürlüğü, en‑boy oranı ve küçük resim gibi bilgileri içerebileceğini görebilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [JFIFData](../../com.aspose.imaging.fileformats.jpeg/jfifdata) |  |

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Bu özellik, görüntünün ham veri formatını alır; bu format, görüntü verilerinin nasıl yapılandırıldığını ve kodlandığını gösterir. Ham veri formatını anlamak, görüntü verilerini etkili bir şekilde işlemek veya manipüle etmek için gereklidir. Görüntünün sıkıştırılmış olup olmadığı, belirli bir renk uzayında kodlanıp kodlanmadığı veya belirli bir dosya formatında depolanıp depolanmadığı gibi temel temsili hakkında bilgi sağlar. Bu özelliğe erişmek, görüntünün veri yapısı hakkında değerli bilgiler edinmenizi sağlar ve belirli formatına uygun çeşitli işlemler veya optimizasyonlar gerçekleştirmenize imkan tanır.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)
### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Bu özellik, ilişkili [RasterImage](../../com.aspose.imaging/rasterimage) için inç başına piksel cinsinden ifade edilen dikey çözünürlüğü yönetir. Bu çözünürlüğü ayarlamak, görüntünün sabit bir fiziksel boyutta yazdırıldığında veya gösterildiğinde boyut ve kalitesini etkiler. Bu özelliği ayarlayarak, görüntünün piksel yoğunluğunu dikey olarak ne kadar sıkı paketlediğinizi kontrol eder, bu da genel keskinlik ve netliği etkiler.

**Returns:**
double - Dikey çözünürlük.

Not: Varsayılan olarak bu değer her zaman 72'dir çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // BmpImage'in yatay ve dikey çözünürlüğünü alın
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// Yatay çözünürlük, inç başına piksel olarak: 300.0
// Dikey çözünürlük, inç başına piksel olarak: 300.0
// Çözünürlük değerlerini 96 dpi olarak ayarlayın
// Yatay çözünürlük, inç başına piksel olarak: 96.0
// Dikey çözünürlük, inç başına piksel olarak: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Bu özellik, ilişkili [RasterImage](../../com.aspose.imaging/rasterimage) için inç başına piksel cinsinden ifade edilen dikey çözünürlüğü yönetir. Bu çözünürlüğü ayarlamak, görüntünün sabit bir fiziksel boyutta yazdırıldığında veya gösterildiğinde boyut ve kalitesini etkiler. Bu özelliği ayarlayarak, görüntünün piksel yoğunluğunu dikey olarak ne kadar sıkı paketlediğinizi kontrol eder, bu da genel keskinlik ve netliği etkiler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Dikey çözünürlük. |

Not: Varsayılan olarak bu değer her zaman 72'dir çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz. |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Bu özellik, görüntünün genişliğini piksel cinsinden alır. Görüntünün boyutları hakkında temel bilgi sağlar ve görüntü verisinin doğru şekilde işlenmesi, manipüle edilmesi veya görüntülenmesini mümkün kılar.

**Returns:**
int - Görüntü genişliği piksel cinsinden.
### getRgbColorProfile() {#getRgbColorProfile--}
```
public StreamSource getRgbColorProfile()
```


CMYK ve YCCK JPEG görüntüleri için RGB renk profili, doğru renk dönüşümü ve temsili sağlar. Renk işleme tutarlılığı ve doğruluğunu korumak için CMYKColorProfile ile eşleştirilmelidir. Bu eşleşme, görüntülerin hassas renk yönetimi ve yeniden üretimini gerektiren uygulamalar için esastır ve RGB verisinin doğru şekilde yorumlanıp görüntülenmesini sağlar.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setRgbColorProfile(StreamSource value) {#setRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setRgbColorProfile(StreamSource value)
```


CMYK ve YCCK JPEG görüntüleri için RGB renk profili, doğru renk dönüşümü ve temsili sağlar. Renk işleme tutarlılığı ve doğruluğunu korumak için CMYKColorProfile ile eşleştirilmelidir. Bu eşleşme, görüntülerin hassas renk yönetimi ve yeniden üretimini gerektiren uygulamalar için esastır ve RGB verisinin doğru şekilde yorumlanıp görüntülenmesini sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
Aşağıdaki örnek, PNG'yi özel bir ICC profili kullanarak CMYK JPEG olarak yükler ve kaydeder. Ardından CMYK JPEG'i yükleyip tekrar PNG olarak kaydeder. RGB'den CMYK'ye ve CMYK'den RGB'ye renk dönüşümü, özel ICC profilleri kullanılarak gerçekleştirilir.
``` java
String dir = "c:\\temp\\";

// PNG'yi yükle ve CMYK JPEG olarak kaydet
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Özel ICC profilleri kullanın
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// CMYK JPEG'i yükle ve PNG olarak kaydet
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Özel ICC profilleri kullanın
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getCmykColorProfile() {#getCmykColorProfile--}
```
public StreamSource getCmykColorProfile()
```


CMYK ve YCCK JPEG görüntüleriyle ilişkili CMYK renk profili, kesin renk dönüşümü ve doğruluk sağlar. Çeşitli cihaz ve uygulamalarda doğru renk temsili garantilemek için RGBColorProfile ile birlikte çalışır. Bu eşleşme, renk işleme tutarlılığını korumak ve optimum görüntü kalitesine ulaşmak için kritik öneme sahiptir.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setCmykColorProfile(StreamSource value) {#setCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setCmykColorProfile(StreamSource value)
```


CMYK ve YCCK JPEG görüntüleriyle ilişkili CMYK renk profili, kesin renk dönüşümü ve doğruluk sağlar. Çeşitli cihaz ve uygulamalarda doğru renk temsili garantilemek için RGBColorProfile ile birlikte çalışır. Bu eşleşme, renk işleme tutarlılığını korumak ve optimum görüntü kalitesine ulaşmak için kritik öneme sahiptir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |


**Example: The following example loads PNG and saves it to CMYK JPEG using custom ICC profile.**
Aşağıdaki örnek, PNG'yi özel bir ICC profili kullanarak CMYK JPEG olarak yükler ve kaydeder. Ardından CMYK JPEG'i yükleyip tekrar PNG olarak kaydeder. RGB'den CMYK'ye ve CMYK'den RGB'ye renk dönüşümü, özel ICC profilleri kullanılarak gerçekleştirilir.
``` java
String dir = "c:\\temp\\";

// PNG'yi yükle ve CMYK JPEG olarak kaydet
com.aspose.imaging.fileformats.png.PngImage image = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.load(dir + "sample.png");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
        saveOptions.setColorType(com.aspose.imaging.fileformats.jpeg.JpegCompressionColorMode.Cmyk);

        // Özel ICC profilleri kullanın
        saveOptions.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        saveOptions.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        image.save(dir + "output.cmyk.jpg", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    image.dispose();
}

// CMYK JPEG'i yükle ve PNG olarak kaydet
com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) com.aspose.imaging.Image.load(dir + "output.cmyk.jpg");
try {
    java.io.InputStream rgbProfileStream = new java.io.FileInputStream(dir + "eciRGB_v2.icc");
    java.io.InputStream cmykProfileStream = new java.io.FileInputStream(dir + "ISOcoated_v2_FullGamut4.icc");
    try {
        // Özel ICC profilleri kullanın
        jpegImage.setRgbColorProfile(new com.aspose.imaging.sources.StreamSource(rgbProfileStream));
        jpegImage.setCmykColorProfile(new com.aspose.imaging.sources.StreamSource(cmykProfileStream));

        com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
        jpegImage.save(dir + "output.rgb.png", saveOptions);
    } finally {
        rgbProfileStream.close();
        cmykProfileStream.close();
    }
} finally {
    jpegImage.dispose();
}
```

### getDestinationRgbColorProfile() {#getDestinationRgbColorProfile--}
```
public StreamSource getDestinationRgbColorProfile()
```


RGBColorProfile, CMYK ve YCCK JPEG görüntülerinin kaydetme sürecindeki doğru renk dönüşümü için gereklidir. CMYKColorProfile ile eşleştirildiğinde, renklerin doğru şekilde işlenmesini sağlar ve farklı cihaz ve uygulamalarda tutarlılığı korur. Bu kombinasyon, istenen renk temsiliyi korumak ve yüksek kaliteli görüntü çıktısı elde etmek için kritik öneme sahiptir.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationRgbColorProfile(StreamSource value) {#setDestinationRgbColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationRgbColorProfile(StreamSource value)
```


RGBColorProfile, CMYK ve YCCK JPEG görüntülerinin kaydetme sürecindeki doğru renk dönüşümü için gereklidir. CMYKColorProfile ile eşleştirildiğinde, renklerin doğru şekilde işlenmesini sağlar ve farklı cihaz ve uygulamalarda tutarlılığı korur. Bu kombinasyon, istenen renk temsiliyi korumak ve yüksek kaliteli görüntü çıktısı elde etmek için kritik öneme sahiptir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getDestinationCmykColorProfile() {#getDestinationCmykColorProfile--}
```
public StreamSource getDestinationCmykColorProfile()
```


CMYK renk profili, CMYK ve YCCK JPEG görüntülerinin kaydetme sürecindeki doğru renk dönüşümü için hayati öneme sahiptir. Doğru renk temsili sağlamak ve farklı cihaz ve yazılımlarda tutarlılık ve kaliteyi korumak için RGBColorProfile ile birlikte çalışır. Bu senkronizasyon, son kaydedilen görüntülerde doğru ve güvenilir renk işleme elde etmek için kritik bir rol oynar.

**Returns:**
[StreamSource](../../com.aspose.imaging.sources/streamsource)
### setDestinationCmykColorProfile(StreamSource value) {#setDestinationCmykColorProfile-com.aspose.imaging.sources.StreamSource-}
```
public void setDestinationCmykColorProfile(StreamSource value)
```


CMYK renk profili, CMYK ve YCCK JPEG görüntülerinin kaydetme sürecindeki doğru renk dönüşümü için hayati öneme sahiptir. Doğru renk temsili sağlamak ve farklı cihaz ve yazılımlarda tutarlılık ve kaliteyi korumak için RGBColorProfile ile birlikte çalışır. Bu senkronizasyon, son kaydedilen görüntülerde doğru ve güvenilir renk işleme elde etmek için kritik bir rol oynar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [StreamSource](../../com.aspose.imaging.sources/streamsource) |  |

### getIgnoreEmbeddedColorProfile() {#getIgnoreEmbeddedColorProfile--}
```
public boolean getIgnoreEmbeddedColorProfile()
```


Gömülü renk profilinin göz ardı edilip edilmediğini belirten bayrağı alır veya değiştirir. Bu bayrak ayarlanarak, kullanıcılar gömülü profil yerine varsayılan renk profilinin kullanılmasını belirtebilir. Bu seçenek, renk yönetimi üzerinde daha fazla kontrol sağlar ve çeşitli platform ve uygulamalarda tutarlılık ve uyumluluk için ayarlamaları kolaylaştırır.

**Returns:**
boolean
### setIgnoreEmbeddedColorProfile(boolean value) {#setIgnoreEmbeddedColorProfile-boolean-}
```
public void setIgnoreEmbeddedColorProfile(boolean value)
```


Gömülü renk profilinin göz ardı edilip edilmediğini belirten bayrağı alır veya değiştirir. Bu bayrak ayarlanarak, kullanıcılar gömülü profil yerine varsayılan renk profilinin kullanılmasını belirtebilir. Bu seçenek, renk yönetimi üzerinde daha fazla kontrol sağlar ve çeşitli platform ve uygulamalarda tutarlılık ve uyumluluk için ayarlamaları kolaylaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Bu [Image](../../com.aspose.imaging/image) örneğinin orijinal görüntü seçeneklerini alır.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - A clone of original image options.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Bu görüntü örneğinin meta verilerini, bu `IHasXmpData.XmpData`([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) ve `IHasExifData.ExifData`([IHasExifData.getExifData()](../../com.aspose.imaging.exif/ihasexifdata\#getExifData--)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-)) değerlerini `null` olarak ayarlayarak kaldırır.

### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


Belirtilen [RasterImage](../../com.aspose.imaging/rasterimage) için çözünürlüğü belirler, doğru ölçekleme ve baskı yeteneklerini sağlar. Bu yöntem, kullanıcıların görüntü çözünürlüğünü dijital gösterim ya da fiziksel çoğaltma gibi özel gereksinimlerine göre uyarlamalarına olanak tanır. Çözünürlük ayarlanarak, kullanıcılar görüntü kalitesini optimize edebilir ve çeşitli çıktı cihazları ve ortamlarıyla uyumluluğu sağlayarak genel görsel deneyimi ve görüntünün kullanılabilirliğini artırabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dpiX | double | `RasterImage`'in inç başına nokta cinsinden yatay çözünürlüğü. |
| dpiY | double | `RasterImage`'in inç başına nokta cinsinden dikey çözünürlüğü. |


**Example: The following example shows how to set horizontal/vertical resolution of a JPEG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jpg");
try {
    com.aspose.imaging.fileformats.jpeg.JpegImage jpegImage = (com.aspose.imaging.fileformats.jpeg.JpegImage) image;

    // BmpImage'in yatay ve dikey çözünürlüğünü alın
    double horizontalResolution = jpegImage.getHorizontalResolution();
    double verticalResolution = jpegImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
        System.out.println("Set resolution values to 96 dpi");
        jpegImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpegImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpegImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// Yatay çözünürlük, inç başına piksel olarak: 300.0
// Dikey çözünürlük, inç başına piksel olarak: 300.0
// Çözünürlük değerlerini 96 dpi olarak ayarlayın
// Yatay çözünürlük, inç başına piksel olarak: 96.0
// Dikey çözünürlük, inç başına piksel olarak: 96.0
```

