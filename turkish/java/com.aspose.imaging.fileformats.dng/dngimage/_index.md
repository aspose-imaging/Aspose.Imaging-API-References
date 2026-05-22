---
title: "DngImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Dijital fotoğrafçılık ihtiyaçları için DNG Digital Negative görüntü dosya formatını işlemek amacıyla, RAW dosyaları ve meta veriler için kapsamlı destek sağlayan API."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.dng/dngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DngImage extends RasterCachedImage
```

Dijital fotoğrafçılık ihtiyaçları için DNG (Digital Negative) görüntü dosya formatını işlemek amacıyla kapsamlı ham dosya ve meta veri desteği sağlayan API. Çeşitli üreticilerin dijital kameralarıyla kullanılmak üzere tasarlanmış olup, geliştiricilerin piksel başına bit sayısı gibi öğeleri manipüle etmelerini, iç verileri çıkarmalarını ve görüntü dengesini verimli bir şekilde ayarlamalarını sağlar. Görüntü verilerini sorunsuz bir şekilde güncelleme ve kaydetme yetenekleriyle, bu API geliştiricilerin DNG dosyalarıyla çalışmasını güçlendirir, yüksek kaliteli sonuçlar ve çok yönlü işleme seçenekleri sunar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [DngImage()](#DngImage--) | Yeni bir [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) sınıfı örneğini zahmetsizce başlatın. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Bu özellik sayesinde görüntünün piksel başına bit sayısını zahmetsizce keşfedin. |
| [getHeight()](#getHeight--) | Bu özellik ile görüntünün yüksekliğini alın. |
| [getWidth()](#getWidth--) | Bu özellik ile görüntünün genişliğine erişin. |
| [getFileFormat()](#getFileFormat--) | Bu özellik ile görüntünüzün dosya formatını belirleyin. |
| [getImgData()](#getImgData--) | Bu özellik ile görüntü verilerini yönetin. |
| [setImgData(RawData value)](#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-) | Bu özellik ile görüntü verilerini yönetin. |

## Example: This example shows how to load a DNG image from a file, print its properties and save it to PNG.

``` java
String dir = "c:\\temp\\";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "test.dng");
try {
    com.aspose.imaging.fileformats.dng.DngImage dngImage = (com.aspose.imaging.fileformats.dng.DngImage) image;
    com.aspose.imaging.fileformats.dng.decoder.RawData rawData = dngImage.getImgData();
    com.aspose.imaging.fileformats.dng.decoder.ImageParameters parameters = rawData.getImageDataParameters();
    if (parameters != null) {
        System.out.println("The camera manufacturer:              " + parameters.getCameraManufacturer());
        System.out.println("The camera model:                     " + parameters.getModel());
        System.out.println("The colors count:                     " + parameters.getColorsCount());
        System.out.println("The colors description:               " + parameters.getDescription());
        System.out.println("The DNG version:                      " + parameters.getDngVersion());
        System.out.println("The number of RAW images in the file: " + parameters.getRawCount());
        System.out.println("The software:                         " + parameters.getSoftware());
        System.out.println("The order of the color pixels:        " + Long.toBinaryString(parameters.getFilters()));

        String[] translationCfaDng = parameters.getTranslationCfaDng();
        if (translationCfaDng != null) {
            System.out.printf("The translation array for CFA mosaic %s:\r\n", translationCfaDng.length);
            for (String s : translationCfaDng) {
                System.out.printf("- %s\r\n", s);
            }
        }
    }

    com.aspose.imaging.fileformats.dng.decoder.ImageOtherParameters otherParameters = rawData.getImageOtherParameters();
    if (otherParameters != null) {
        // Zaman damgasını insan tarafından okunabilir bir dizeye dönüştür.
        //java.text.SimpleDateFormat sf = new java.text.SimpleDateFormat("yyyy-MM-dd");
        java.util.Date date = new java.util.Date(otherParameters.getTimestamp());
        //System.out.println(sf.format(date));

        System.out.printf("The aperture:                         " + otherParameters.getAperture());
        System.out.printf("The description:                      " + otherParameters.getDescription());
        System.out.printf("The focal length:                     " + otherParameters.getFocalLength());
        System.out.printf("The ISO sensitivity:                  " + otherParameters.getIsoSpeed());
        System.out.printf("The serial number of the image:       " + otherParameters.getShotOrder());
        System.out.printf("The shutter speed:                    " + otherParameters.getShutterSpeed());
        System.out.printf("The date of shooting:                 " + date);
    }

    // Varsayılan seçeneklerle PNG olarak dışa aktar.
    dngImage.save(dir + "test.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

// Kamera üreticisi:              Leica
// Kamera modeli:                     M8 Digital Camera
// Renk sayısı:                     3
// Renk açıklaması:               RGBG
// DNG sürümü:                      16777216
// Dosyadaki RAW görüntü sayısı: 1
// Yazılım:                         1.107
// Renk piksel sırası:        10110100101101001011010010110100
// Diyafram:                         0
// Açıklama:
// Odak uzaklığı:                     50
// ISO hassasiyeti:                  160
// Görüntünün seri numarası:       0
// Enstantane hızı:                    12
// Çekim tarihi:                 8/3/2007 3:13:49 AM
```

### DngImage() {#DngImage--}
```
public DngImage()
```


Yeni bir [DngImage](../../com.aspose.imaging.fileformats.dng/dngimage) sınıfı örneğini zahmetsizce başlatın. Projelerinde DngImage nesnelerini hızlı ve verimli bir şekilde kullanmaya başlayan geliştiriciler için mükemmeldir.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Bu özellik sayesinde görüntünün piksel başına bit sayısını zahmetsizce keşfedin. Görüntünün piksel derinliğini hızlı ve doğru bir şekilde anlamak için idealdir.

Değer: Görüntünün piksel başına bit sayısı.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Bu özellik ile görüntünün yüksekliğini alın. Görüntünün dikey boyutunu zahmetsizce belirlemek için mükemmeldir.

Değer: Görüntünün yüksekliği.

**Returns:**
int
### getWidth() {#getWidth--}
```
public int getWidth()
```


Bu özellik ile görüntünün genişliğine erişin. Görüntünün yatay boyutunu hızlı ve verimli bir şekilde elde etmek için idealdir.

Değer: Görüntünün genişliği.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Bu özellik ile görüntünüzün dosya formatını belirleyin. Formatı anlamak için - sadece net detaylar - mükemmeldir.

**Returns:**
long
### getImgData() {#getImgData--}
```
public RawData getImgData()
```


Bu özellik ile görüntü verilerini yönetin. İster alıyor olun ister güncelliyor olun, bu özellik verimli manipülasyon için görüntü verilerine sorunsuz erişim sağlar.

**Returns:**
[RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) - The img data.
### setImgData(RawData value) {#setImgData-com.aspose.imaging.fileformats.dng.decoder.RawData-}
```
public void setImgData(RawData value)
```


Bu özellik ile görüntü verilerini yönetin. İster alıyor olun ister güncelliyor olun, bu özellik verimli manipülasyon için görüntü verilerine sorunsuz erişim sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RawData](../../com.aspose.imaging.fileformats.dng.decoder/rawdata) | Görüntü verisi. |

