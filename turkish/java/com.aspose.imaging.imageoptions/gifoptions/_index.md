---
title: "GifOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Grafik Değişim Formatı (GIF) raster görüntü dosyası oluşturma API'si, geliştiricilere GIF görüntülerini hassas kontrolle oluşturmak için kapsamlı seçenekler sunar."
type: docs
weight: 22
url: /tr/java/com.aspose.imaging.imageoptions/gifoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class GifOptions extends ImageOptionsBase
```

Grafik Değişim Formatı (GIF) raster görüntü dosyası oluşturma API'si, geliştiricilere GIF görüntülerini hassas kontrolle oluşturmak için kapsamlı seçenekler sunar. Arka plan rengini, renk paletini, çözünürlüğü, taramalı tipi, şeffaf rengi, XMP meta veri konteynerini ve görüntü sıkıştırmasını ayarlama özellikleriyle, bu API belirli uygulama gereksinimlerine göre optimize edilmiş ve görsel olarak çekici GIF'ler oluştururken esneklik ve verimlilik sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [GifOptions()](#GifOptions--) | `GifOptions` sınıfının yeni bir örneğini başlatır. |
| [GifOptions(GifOptions gifOptions)](#GifOptions-com.aspose.imaging.imageoptions.GifOptions-) | `GifOptions` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDoPaletteCorrection()](#getDoPaletteCorrection--) | Palet düzeltmesinin uygulanıp uygulanmadığını gösteren bir değeri alır veya ayarlar. |
| [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | Palet düzeltmesinin uygulanıp uygulanmadığını gösteren bir değeri alır veya ayarlar. |
| [getLoopsCount()](#getLoopsCount--) | Döngü sayısını alır (Varsayılan 1 döngü) |
| [setLoopsCount(int value)](#setLoopsCount-int-) | Döngü sayısını ayarlar (Varsayılan 1 döngü) |
| [getColorResolution()](#getColorResolution--) | GIF renk çözünürlüğünü alır veya ayarlar. |
| [setColorResolution(byte value)](#setColorResolution-byte-) | GIF renk çözünürlüğünü alır veya ayarlar. |
| [isPaletteSorted()](#isPaletteSorted--) | Palet girişlerinin sıralanıp sıralanmadığını gösteren bir değeri alır veya ayarlar. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Palet girişlerinin sıralanıp sıralanmadığını gösteren bir değeri alır veya ayarlar. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | GIF piksel en-boy oranını alır veya ayarlar. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | GIF piksel en-boy oranını alır veya ayarlar. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | GIF arka plan renk indeksini alır veya ayarlar. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | GIF arka plan renk indeksini alır veya ayarlar. |
| [hasTrailer()](#hasTrailer--) | GIF'in trailer (son ek) içerip içermediğini gösteren bir değeri alır veya ayarlar. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | GIF'in trailer (son ek) içerip içermediğini gösteren bir değeri alır veya ayarlar. |
| [getInterlaced()](#getInterlaced--) | Görüntünün taramalı olması durumunda doğru. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Görüntünün taramalı olması durumunda doğru. |
| [getMaxDiff()](#getMaxDiff--) | İzin verilen maksimum piksel farkını alır veya ayarlar. |
| [setMaxDiff(int value)](#setMaxDiff-int-) | İzin verilen maksimum piksel farkını alır veya ayarlar. |
| [getBackgroundColor()](#getBackgroundColor--) | Arka plan rengini alır. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Arka plan rengini ayarlar. |
| [hasTransparentColor()](#hasTransparentColor--) | Bir GIF görüntüsünün şeffaf renge sahip olup olmadığını gösteren bir değer alır. |
| [setTransparentColor(Boolean value)](#setTransparentColor-java.lang.Boolean-) | Bir GIF görüntüsünün şeffaf renge sahip olup olmadığını gösteren bir değeri ayarlar. |

## Example: This example demonstrates the use of different classes from SaveOptions Namespace for export purposes.
Bu örnek, dışa aktarma amaçları için SaveOptions ad alanındaki farklı sınıfların kullanımını gösterir. Gif türünde bir görüntü, Image sınıfının bir örneğine yüklenir ve ardından çeşitli formatlara dışa aktarılır.
``` java
String dir = "c:\\temp\\";

//Image sınıfının bir örneğine mevcut bir görüntüyü (Gif türünde) yükleyin
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    //Varsayılan seçenekleri kullanarak BMP dosya formatına dışa aktar
    image.save(dir + "output.bmp", new com.aspose.imaging.imageoptions.BmpOptions());

    //Varsayılan seçenekleri kullanarak JPEG dosya formatına dışa aktar
    image.save(dir + "output.jpeg", new com.aspose.imaging.imageoptions.JpegOptions());

    //Varsayılan seçenekleri kullanarak PNG dosya formatına dışa aktar
    image.save(dir + "output.png", new com.aspose.imaging.imageoptions.PngOptions());

    //Varsayılan seçenekleri kullanarak TIFF dosya formatına dışa aktar
    image.save(dir + "output.tif", new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default));
} finally {
    image.dispose();
}
```


## Example: The following example shows how to convert a multipage vector image to GIF format in general way without referencing to a particular image type.

``` java
String dir = "C:\\aspose.imaging\\net\\misc\\ImagingReleaseQATester\\Tests\\testdata\\2548\\";
String inputFilePath = dir + "Multipage.cdr";
String outputFilePath = dir + "Multipage.cdr.gif";

com.aspose.imaging.ImageOptionsBase exportOptions = new com.aspose.imaging.imageoptions.GifOptions();

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFilePath))
{
    exportOptions.setMultiPageOptions(null);

    // Yalnızca ilk iki sayfayı dışa aktar. Bu sayfalar çıktı GIF'inde hareketli kareler olarak sunulacak.
    com.aspose.imaging.IMultipageImage multipageImage = (image instanceof com.aspose.imaging.IMultipageImage) ? (com.aspose.imaging.IMultipageImage) image : null;
    if (multipageImage != null && (multipageImage.getPages() != null && multipageImage.getPageCount() > 2))
    {
        exportOptions.setMultiPageOptions(new com.aspose.imaging.imageoptions.MultiPageOptions(new com.aspose.imaging.IntRange(0, 2)));
    }

    if (image instanceof com.aspose.imaging.VectorImage)
    {
        com.aspose.imaging.imageoptions.VectorRasterizationOptions defaultOptions = (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        exportOptions.setVectorRasterizationOptions(defaultOptions);
        defaultOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.SingleBitPerPixel);
        defaultOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.None);
    }

    image.save(outputFilePath, exportOptions);
}
```

### GifOptions() {#GifOptions--}
```
public GifOptions()
```


`GifOptions` sınıfının yeni bir örneğini başlatır.

### GifOptions(GifOptions gifOptions) {#GifOptions-com.aspose.imaging.imageoptions.GifOptions-}
```
public GifOptions(GifOptions gifOptions)
```


`GifOptions` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| gifOptions | [GifOptions](../../com.aspose.imaging.imageoptions/gifoptions) | GIF Seçenekleri. |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


Palet düzeltmesinin uygulanıp uygulanmadığını gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean - palet düzeltmesi uygulanıyorsa `true`; aksi takdirde `false`.

Palet düzeltmesi, bir görüntü GIF olarak dışa aktarıldığında kaynak görüntünün renklerinin en uygun paleti oluşturmak üzere analiz edileceği anlamına gelir (görüntünün Paleti mevcut değilse veya seçeneklerde belirtilmemişse). Analiz süreci biraz zaman alır, ancak çıktı görüntüsü en uygun renk paletine sahip olur ve sonuç görsel olarak daha iyidir.
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


Palet düzeltmesinin uygulanıp uygulanmadığını gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | boolean | `true` eğer palet düzeltmesi uygulanıyorsa; aksi takdirde `false`. |

Palet düzeltmesi, bir görüntü GIF olarak dışa aktarıldığında kaynak görüntünün renklerinin en uygun paleti oluşturmak üzere analiz edileceği anlamına gelir (görüntünün Paleti mevcut değilse veya seçeneklerde belirtilmemişse). Analiz süreci biraz zaman alır, ancak çıktı görüntüsü en uygun renk paletine sahip olur ve sonuç görsel olarak daha iyidir. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Tüm görüntüyü mavi-sarı degrade ile doldur.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Bir rengi depolamak için gereken bit sayısı, 1 eksik.
    saveOptions.setColorResolution((byte) 7);

    // Palet düzeltmesi, bir görüntü GIF olarak dışa aktarıldığında kaynak görüntünün renklerinin analiz edileceği anlamına gelir
    // en uygun paleti oluşturmak için (görüntünün Paleti mevcut değilse veya seçeneklerde belirtilmemişse)
    saveOptions.setDoPaletteCorrection(true);

    // Bir GIF görüntüsünü aşamalı bir şekilde yükle.
    // Aralıklı bir GIF, tarama çizgilerini üstten alta doğrusal olarak göstermez, bunun yerine yeniden sıralar
    // bu sayede GIF'in içeriği, yükleme tamamlanmadan bile netleşir.
    saveOptions.setInterlaced(true);

    // Kayıpsız bir GIF olarak kaydet.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // İzin verilen maksimum piksel farkını ayarla. Sıfırdan büyükse, kayıplı sıkıştırma kullanılacak.
    // Optimum kayıplı sıkıştırma için önerilen değer 80'dir. 30 çok hafif sıkıştırma, 200 ise ağırdır.
    saveOptions.setMaxDiff(80);

    // Kayıplı bir GIF olarak kaydet.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//Çıktı şöyle görünebilir:
//Kayıpsız GIF'in boyutu: 212816 bayt.
//Kayıplı GIF'in boyutu: 89726 bayt.
```

### getLoopsCount() {#getLoopsCount--}
```
public final int getLoopsCount()
```


Döngü sayısını alır (Varsayılan 1 döngü)

Değer: Döngü sayısı.

**Returns:**
int - döngü sayısı (Varsayılan 1 döngü)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public final void setLoopsCount(int value)
```


Döngü sayısını ayarlar (Varsayılan 1 döngü)

Değer: Döngü sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | döngü sayısı (Varsayılan 1 döngü) |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


GIF renk çözünürlüğünü alır veya ayarlar.

**Returns:**
byte - Renk çözünürlüğü.

Renk Çözünürlüğü - Orijinal görüntüde mevcut olan birincil renk başına bit sayısı, 1 eksik. Bu değer, grafikte seçilen renklerin alındığı tüm paletin boyutunu temsil eder, grafikte gerçekte kullanılan renk sayısını değil. Örneğin, bu alandaki değer 3 ise, orijinal görüntünün paleti görüntüyü oluşturmak için birincil renk başına 4 bit içeriyordu. Bu değer, tüm paletin her renginin kaynak makinede mevcut olmasa bile orijinal paletin zenginliğini göstermek için ayarlanmalıdır.
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


GIF renk çözünürlüğünü alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | byte | Renk çözünürlüğü. |

Renk Çözünürlüğü - Orijinal görüntüde mevcut olan birincil renk başına bit sayısı, 1 eksik. Bu değer, grafikte seçilen renklerin alındığı tüm paletin boyutunu temsil eder, grafikte gerçekte kullanılan renk sayısını değil. Örneğin, bu alandaki değer 3 ise, orijinal görüntünün paleti görüntüyü oluşturmak için birincil renk başına 4 bit içeriyordu. Bu değer, tüm paletin her renginin kaynak makinede mevcut olmasa bile orijinal paletin zenginliğini göstermek için ayarlanmalıdır. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Tüm görüntüyü mavi-sarı degrade ile doldur.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Bir rengi depolamak için gereken bit sayısı, 1 eksik.
    saveOptions.setColorResolution((byte) 7);

    // Palet düzeltmesi, bir görüntü GIF olarak dışa aktarıldığında kaynak görüntünün renklerinin analiz edileceği anlamına gelir
    // en uygun paleti oluşturmak için (görüntünün Paleti mevcut değilse veya seçeneklerde belirtilmemişse)
    saveOptions.setDoPaletteCorrection(true);

    // Bir GIF görüntüsünü aşamalı bir şekilde yükle.
    // Aralıklı bir GIF, tarama çizgilerini üstten alta doğrusal olarak göstermez, bunun yerine yeniden sıralar
    // bu sayede GIF'in içeriği, yükleme tamamlanmadan bile netleşir.
    saveOptions.setInterlaced(true);

    // Kayıpsız bir GIF olarak kaydet.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // İzin verilen maksimum piksel farkını ayarla. Sıfırdan büyükse, kayıplı sıkıştırma kullanılacak.
    // Optimum kayıplı sıkıştırma için önerilen değer 80'dir. 30 çok hafif sıkıştırma, 200 ise ağırdır.
    saveOptions.setMaxDiff(80);

    // Kayıplı bir GIF olarak kaydet.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//Çıktı şöyle görünebilir:
//Kayıpsız GIF'in boyutu: 212816 bayt.
//Kayıplı GIF'in boyutu: 89726 bayt.
```

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Palet girişlerinin sıralanıp sıralanmadığını gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean - `true` ise palet girişleri sıralanmıştır; aksi takdirde `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Palet girişlerinin sıralanıp sıralanmadığını gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` ise palet girişleri sıralanmıştır; aksi takdirde `false`. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


GIF piksel en-boy oranını alır veya ayarlar.

Piksel En Oranı - Orijinal görüntüdeki pikselin en oranının bir yaklaşımını hesaplamak için kullanılan faktör. Alanın değeri 0 değilse, bu en oranı yaklaşımı aşağıdaki formüle göre hesaplanır: En Oranı = (Piksel En Oranı + 15) / 64. Piksel En Oranı, pikselin genişliğinin yüksekliğine bölümü olarak tanımlanır. Bu alandaki değer aralığı, en geniş piksel 4:1'den en yüksek piksel 1:4'e kadar 1/64 artışlarla belirtmeye izin verir. Değerler: 0 - En oranı bilgisi verilmez. 1..255 - Hesaplamada kullanılan değer.

**Returns:**
byte - GIF piksel en oranı.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


GIF piksel en-boy oranını alır veya ayarlar.

Piksel En Oranı - Orijinal görüntüdeki pikselin en oranının bir yaklaşımını hesaplamak için kullanılan faktör. Alanın değeri 0 değilse, bu en oranı yaklaşımı aşağıdaki formüle göre hesaplanır: En Oranı = (Piksel En Oranı + 15) / 64. Piksel En Oranı, pikselin genişliğinin yüksekliğine bölümü olarak tanımlanır. Bu alandaki değer aralığı, en geniş piksel 4:1'den en yüksek piksel 1:4'e kadar 1/64 artışlarla belirtmeye izin verir. Değerler: 0 - En oranı bilgisi verilmez. 1..255 - Hesaplamada kullanılan değer.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | GIF piksel en oranı. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


GIF arka plan renk indeksini alır veya ayarlar.

**Returns:**
byte - GIF arka plan renk indeksi.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


GIF arka plan renk indeksini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte | GIF arka plan renk indeksi. |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


GIF'in trailer (son ek) içerip içermediğini gösteren bir değeri alır veya ayarlar.

**Returns:**
boolean - `true` ise GIF'in trailer'ı vardır; aksi takdirde `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


GIF'in trailer (son ek) içerip içermediğini gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` ise GIF'in trailer'ı vardır; aksi takdirde `false`. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Görüntünün taramalı olması durumunda doğru.

**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Görüntünün taramalı olması durumunda doğru.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Tüm görüntüyü mavi-sarı degrade ile doldur.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Bir rengi depolamak için gereken bit sayısı, 1 eksik.
    saveOptions.setColorResolution((byte) 7);

    // Palet düzeltmesi, bir görüntü GIF olarak dışa aktarıldığında kaynak görüntünün renklerinin analiz edileceği anlamına gelir
    // en uygun paleti oluşturmak için (görüntünün Paleti mevcut değilse veya seçeneklerde belirtilmemişse)
    saveOptions.setDoPaletteCorrection(true);

    // Bir GIF görüntüsünü aşamalı bir şekilde yükle.
    // Aralıklı bir GIF, tarama çizgilerini üstten alta doğrusal olarak göstermez, bunun yerine yeniden sıralar
    // bu sayede GIF'in içeriği, yükleme tamamlanmadan bile netleşir.
    saveOptions.setInterlaced(true);

    // Kayıpsız bir GIF olarak kaydet.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // İzin verilen maksimum piksel farkını ayarla. Sıfırdan büyükse, kayıplı sıkıştırma kullanılacak.
    // Optimum kayıplı sıkıştırma için önerilen değer 80'dir. 30 çok hafif sıkıştırma, 200 ise ağırdır.
    saveOptions.setMaxDiff(80);

    // Kayıplı bir GIF olarak kaydet.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//Çıktı şöyle görünebilir:
//Kayıpsız GIF'in boyutu: 212816 bayt.
//Kayıplı GIF'in boyutu: 89726 bayt.
```

### getMaxDiff() {#getMaxDiff--}
```
public int getMaxDiff()
```


Maksimum izin verilen piksel farkını alır veya ayarlar. Sıfırdan büyükse kayıplı sıkıştırma kullanılacaktır. Optimum kayıplı sıkıştırma için önerilen değer 80'dir. 30 çok hafif sıkıştırma, 200 ise ağırdır. Sadece az miktarda kayıp getirildiğinde en iyi sonuç alınır ve sıkıştırma algoritmasının sınırlamaları nedeniyle çok yüksek kayıp seviyeleri fazla kazanç sağlamaz. İzin verilen değer aralığı [0, 1000]dır.

**Returns:**
int - İzin verilen değer aralığı.
### setMaxDiff(int value) {#setMaxDiff-int-}
```
public void setMaxDiff(int value)
```


Maksimum izin verilen piksel farkını alır veya ayarlar. Sıfırdan büyükse kayıplı sıkıştırma kullanılacaktır. Optimum kayıplı sıkıştırma için önerilen değer 80'dir. 30 çok hafif sıkıştırma, 200 ise ağırdır. Sadece az miktarda kayıp getirildiğinde en iyi sonuç alınır ve sıkıştırma algoritmasının sınırlamaları nedeniyle çok yüksek kayıp seviyeleri fazla kazanç sağlamaz. İzin verilen değer aralığı [0, 1000]dır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | İzin verilen değer aralığı. |


**Example: This example shows how to save a BMP image to GIF format using various options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(1000, 1000);
try {
    // Tüm görüntüyü mavi-sarı degrade ile doldur.
    com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
            new com.aspose.imaging.Point(0, 0),
            new com.aspose.imaging.Point(bmpImage.getWidth(), bmpImage.getHeight()),
            com.aspose.imaging.Color.getBlue(),
            com.aspose.imaging.Color.getYellow());

    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(bmpImage);
    graphics.fillRectangle(gradientBrush, bmpImage.getBounds());

    com.aspose.imaging.imageoptions.GifOptions saveOptions = new com.aspose.imaging.imageoptions.GifOptions();

    // Bir rengi depolamak için gereken bit sayısı, 1 eksik.
    saveOptions.setColorResolution((byte) 7);

    // Palet düzeltmesi, bir görüntü GIF olarak dışa aktarıldığında kaynak görüntünün renklerinin analiz edileceği anlamına gelir
    // en uygun paleti oluşturmak için (görüntünün Paleti mevcut değilse veya seçeneklerde belirtilmemişse)
    saveOptions.setDoPaletteCorrection(true);

    // Bir GIF görüntüsünü aşamalı bir şekilde yükle.
    // Aralıklı bir GIF, tarama çizgilerini üstten alta doğrusal olarak göstermez, bunun yerine yeniden sıralar
    // bu sayede GIF'in içeriği, yükleme tamamlanmadan bile netleşir.
    saveOptions.setInterlaced(true);

    // Kayıpsız bir GIF olarak kaydet.
    java.io.FileOutputStream stream = new java.io.FileOutputStream(dir + "output.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossless GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }

    // İzin verilen maksimum piksel farkını ayarla. Sıfırdan büyükse, kayıplı sıkıştırma kullanılacak.
    // Optimum kayıplı sıkıştırma için önerilen değer 80'dir. 30 çok hafif sıkıştırma, 200 ise ağırdır.
    saveOptions.setMaxDiff(80);

    // Kayıplı bir GIF olarak kaydet.
    stream = new java.io.FileOutputStream(dir + "output.lossy.gif");
    try {
        bmpImage.save(stream, saveOptions);
        System.out.printf("The size of the lossy GIF: %s bytes.\r\n", stream.getChannel().size());
    } finally {
        stream.close();
    }
} finally {
    bmpImage.close();
}

//Çıktı şöyle görünebilir:
//Kayıpsız GIF'in boyutu: 212816 bayt.
//Kayıplı GIF'in boyutu: 89726 bayt.
```

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


Arka plan rengini alır.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public final void setBackgroundColor(Color value)
```


Arka plan rengini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | arka plan rengi. |

### hasTransparentColor() {#hasTransparentColor--}
```
public final Boolean hasTransparentColor()
```


Bir GIF görüntüsünün şeffaf renge sahip olup olmadığını gösteren bir değer alır. Dönen değer `null` ise, bu özellik kaynak görüntü bağlamı tarafından geçersiz kılınır.

**Returns:**
java.lang.Boolean - bir GIF görüntüsünün şeffaf renge sahip olup olmadığını gösteren değer.
### setTransparentColor(Boolean value) {#setTransparentColor-java.lang.Boolean-}
```
public final void setTransparentColor(Boolean value)
```


Bir GIF görüntüsünün şeffaf renge sahip olup olmadığını gösteren bir değeri ayarlar. Dönen değer `null` ise, bu özellik kaynak görüntü bağlamı tarafından geçersiz kılınır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.Boolean | bir GIF görüntüsünün şeffaf renge sahip olup olmadığını gösteren değer. |

