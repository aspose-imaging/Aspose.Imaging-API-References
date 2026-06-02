---
title: "Jpeg2000Image"
second_title: "Aspose.Imaging for Java API Referansı"
description: "API'mizle JPEG2000 JP2 görüntü dosyalarını verimli bir şekilde işleyin; piksel başına bit derinlikleri aralığını destekler ve temel görüntü bilgilerini içeren XMP meta verilerinin sorunsuz işlenmesini sağlar."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.fileformats.jpeg2000/jpeg2000image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class Jpeg2000Image extends RasterCachedImage
```

API'mizle JPEG2000 (JP2) görüntü dosyalarını verimli bir şekilde işleyin; piksel başına bit derinlikleri aralığını destekler ve temel görüntü bilgilerini içeren XMP meta verilerinin sorunsuz işlenmesini sağlar. Kayıpsız sıkıştırma yetenekleriyle, dosya bütünlüğünü korurken optimal görüntü kalitesini garanti eder ve JP2 görüntülerini tam olarak istediğiniz özelliklere kolayca uyarlamanızı sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [Jpeg2000Image(String path)](#Jpeg2000Image-java.lang.String-) | Yüklemek istediğiniz görüntünün yolunu belirterek yeni bir örnek başlatarak [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) sınıfı ile çalışmaya başlayın. |
| [Jpeg2000Image(String path, int bitsPerPixel)](#Jpeg2000Image-java.lang.String-int-) | [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) sınıfını, dosya yolu ve istenen piksel başına bit parametresini belirterek yeni bir örnek oluşturarak kolayca başlatın. |
| [Jpeg2000Image(InputStream stream)](#Jpeg2000Image-java.io.InputStream-) | Bir akış nesnesi sağlayarak [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) sınıfının yeni bir örneğini kolayca başlatın. |
| [Jpeg2000Image(InputStream stream, int bitsPerPixel)](#Jpeg2000Image-java.io.InputStream-int-) | Görüntüyü yüklemek için bir akış ve piksel başına bit parametreleriyle [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) sınıfının yeni bir örneğini başlatın. |
| [Jpeg2000Image(int width, int height)](#Jpeg2000Image-int-int-) | Genişlik ve yükseklik parametrelerini belirterek [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) sınıfının yeni bir örneğini oluşturun. |
| [Jpeg2000Image(int width, int height, Jpeg2000Options options)](#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-) | Genişlik, yükseklik ve görüntü seçenekleri parametrelerini sağlayarak yeni bir [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) nesnesi oluşturun. |
| [Jpeg2000Image(int width, int height, int bitsCount)](#Jpeg2000Image-int-int-int-) | Genişlik, yükseklik ve bit sayısı parametreleriyle [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) sınıfının yeni bir örneğini oluşturun. |
| [Jpeg2000Image(RasterImage image)](#Jpeg2000Image-com.aspose.imaging.RasterImage-) | Bir raster görüntü ile yeni bir [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) sınıfı örneği oluşturun. |
| [Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)](#Jpeg2000Image-com.aspose.imaging.RasterImage-int-) | Bir raster görüntü ve piksel başına bit parametreleriyle yeni bir [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) örneği başlatın. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Görüntü dosyasının formatını alın. |
| [getRawDataFormat()](#getRawDataFormat--) | Bu özellik, görüntünün ham veri formatını alır. |
| [getRawLineSize()](#getRawLineSize--) | Bu özellik, ham görüntü verisinin tek bir satırının boyutunu bayt cinsinden alır. |
| [getWidth()](#getWidth--) | Bu özellik, görüntünün genişliğini piksel cinsinden döndürür. |
| [getHeight()](#getHeight--) | Bu özellik, görüntünün yüksekliğini piksel cinsinden alır. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Bu özellik, görüntünün derinliğini piksel başına bit (bpp) cinsinden döndürür. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Bu özellik, [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin yatay çözünürlüğünü piksel başına inç (PPI) cinsinden almanıza veya değiştirmenize olanak tanır. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Bu özellik, [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin yatay çözünürlüğünü piksel başına inç (PPI) cinsinden almanıza veya değiştirmenize olanak tanır. |
| [getVerticalResolution()](#getVerticalResolution--) | Bu özellik, [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin dikey çözünürlüğüne piksel başına inç (PPI) cinsinden erişim sağlar. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Bu özellik, [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin dikey çözünürlüğüne piksel başına inç (PPI) cinsinden erişim sağlar. |
| [getComments()](#getComments--) | Bu özellik, görüntüyle ilişkili yorumları almanıza veya güncellemenize olanak tanır. |
| [setComments(String[] value)](#setComments-java.lang.String---) | Bu özellik, görüntüyle ilişkili yorumları almanıza veya güncellemenize olanak tanır. |
| [getCodec()](#getCodec--) | Bu özellik, görüntüyle ilişkili JPEG2000 kod çözücüyü alır. |
| [getOriginalOptions()](#getOriginalOptions--) | Görüntü seçeneklerini orijinal dosya ayarlarına göre alın. |

## Example: This example shows how to load a JPEG2000 image from a file and save it to PNG.

``` java
String dir = "c:\\temp\\";

// Bir JPEG2000 görüntüsü yükleyin.
com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = new com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image(dir + "sample.jp2");
try {
    // PNG'ye kaydet
    jpeg2000Image.save(dir + "sample.output.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    jpeg2000Image.dispose();
}
```

### Jpeg2000Image(String path) {#Jpeg2000Image-java.lang.String-}
```
public Jpeg2000Image(String path)
```


Yüklemek istediğiniz görüntünün yolunu belirterek yeni bir örnek başlatarak [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) sınıfı ile çalışmaya başlayın. Bu yapıcı, JPEG2000 görüntülerine kolay erişim sağlar ve görüntü dosyalarını yükleme ve işleme sürecini basitleştirir. Dosya yolunu sağlayarak uygulamanızda JPEG2000 görüntülerini hızlı bir şekilde işlemeye ve manipüle etmeye başlayabilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Görüntüyü yüklemek ve piksel ile palet verilerini başlatmak için yol. |

### Jpeg2000Image(String path, int bitsPerPixel) {#Jpeg2000Image-java.lang.String-int-}
```
public Jpeg2000Image(String path, int bitsPerPixel)
```


Hem dosya yolu hem de istenen piksel başına bit parametresiyle yeni bir örnek oluşturarak [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) sınıfına kolayca başlayın. Bu yapıcı, görüntü yükleme sürecini ince ayar yapmanıza olanak tanır ve çeşitli görüntü formatları ve kalite ayarlarıyla uyumluluğu sağlar. Bu esneklik sayesinde JPEG2000 görüntülerini belirli gereksinimlerinize göre verimli bir şekilde yönetebilir ve manipüle edebilirsiniz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Görüntüyü yüklemek ve piksel ile palet verilerini başlatmak için yol |
| bitsPerPixel | int | Piksel başına bit. |

### Jpeg2000Image(InputStream stream) {#Jpeg2000Image-java.io.InputStream-}
```
public Jpeg2000Image(InputStream stream)
```


Bir akış nesnesi sağlayarak [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) sınıfının yeni bir örneğini kolayca başlatın. Bu yapıcı, JPEG2000 görüntülerini akışlardan doğrudan yükleme sürecini basitleştirir ve çeşitli kaynaklardan gelen görüntü verilerini işlemek için esneklik ve kolaylık sunar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Görüntüyü yüklemek ve piksel ile palet verilerini başlatmak için akış. |

### Jpeg2000Image(InputStream stream, int bitsPerPixel) {#Jpeg2000Image-java.io.InputStream-int-}
```
public Jpeg2000Image(InputStream stream, int bitsPerPixel)
```


[Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) sınıfının yeni bir örneğini, görüntüyü yüklemek için bir akış ve piksel başına bit parametreleriyle başlatın. Bu yapıcı, hem görüntü veri kaynağını hem de istenen piksel başına bit değerini belirlemenize olanak tanıyarak görüntü yükleme sürecinde daha hassas kontrol sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Görüntüyü yüklemek ve piksel ile palet verilerini başlatmak için akış. |
| bitsPerPixel | int | Piksel başına bit. |

### Jpeg2000Image(int width, int height) {#Jpeg2000Image-int-int-}
```
public Jpeg2000Image(int width, int height)
```


[Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) sınıfının yeni bir örneğini oluşturun ve genişlik ile yükseklik parametrelerini belirtin. Bu yapıcı, belirli boyutlarda bir JPEG2000 görüntüsü başlatmanıza olanak tanır; bu, programlı olarak belirli bir boyutta görüntü oluşturmanız gerektiğinde faydalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Görüntünün genişliği |
| yükseklik | int | Görüntünün yüksekliği |

### Jpeg2000Image(int width, int height, Jpeg2000Options options) {#Jpeg2000Image-int-int-com.aspose.imaging.imageoptions.Jpeg2000Options-}
```
public Jpeg2000Image(int width, int height, Jpeg2000Options options)
```


Genişlik, yükseklik ve görüntü seçenekleri parametrelerini sağlayarak yeni bir [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) nesnesi oluşturun. Bu yapıcı, belirli boyutlarda ve ek seçeneklerle JPEG2000 görüntüleri oluşturmanıza olanak tanır ve görüntü üretiminde esneklik sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Görüntünün genişliği |
| yükseklik | int | Görüntünün yüksekliği |
| options | [Jpeg2000Options](../../com.aspose.imaging.imageoptions/jpeg2000options) | Seçenekler. |

### Jpeg2000Image(int width, int height, int bitsCount) {#Jpeg2000Image-int-int-int-}
```
public Jpeg2000Image(int width, int height, int bitsCount)
```


Genişlik, yükseklik ve bit sayısı parametreleriyle [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) sınıfının yeni bir örneğini oluşturun. Bu yapıcı, belirli boyutlarda ve bit derinliklerinde JPEG2000 görüntüleri oluşturmanıza olanak tanır ve çeşitli görüntüleme ihtiyaçları için esneklik sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Görüntünün genişliği |
| yükseklik | int | Görüntünün yüksekliği |
| bitsCount | int | Bit sayısı. |

### Jpeg2000Image(RasterImage image) {#Jpeg2000Image-com.aspose.imaging.RasterImage-}
```
public Jpeg2000Image(RasterImage image)
```


Bir raster görüntü ile yeni bir [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) sınıfı örneği oluşturun. Bu yapıcı, mevcut bir raster görüntüden JPEG2000 görüntüsü oluşturmayı kolaylaştırır ve farklı görüntü formatları arasında sorunsuz entegrasyon ve dönüşüm sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Görüntü. |

### Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel) {#Jpeg2000Image-com.aspose.imaging.RasterImage-int-}
```
public Jpeg2000Image(RasterImage rasterImage, int bitsPerPixel)
```


Yeni bir [Jpeg2000Image](../../com.aspose.imaging.fileformats.jpeg2000/jpeg2000image) örneğini raster görüntü ve piksel başına bit parametreleriyle başlatın. Bu yapıcı, ortaya çıkan JPEG2000 görüntüsünün kalitesi ve boyutu üzerinde hassas kontrol sağlar ve özelleştirmenin kritik olduğu senaryolar için idealdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Piksel ve palet verilerini başlatmak için kullanılacak görüntü. |
| bitsPerPixel | int | Piksel başına bit. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Görüntü dosyasının formatını alın. Bu özellik, görüntünün dosya formatı hakkında bilgi sağlar. Bu özelliği programlı olarak görüntü dosyasının formatını belirlemek için kullanın; böylece dosyanın formatına göre uygun işleme ve işlemeye olanak tanır.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Bu özellik, görüntünün ham veri formatını alır. Piksel verilerinin bellekte nasıl saklandığı hakkında bilgi verir. Bu özelliği, renk dönüşümü, sıkıştırma veya sıkıştırma açma gibi çeşitli görüntü işleme işlemleri için kritik olabilecek görüntünün temel veri formatını anlamak amacıyla kullanın.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.
### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Bu özellik, ham görüntü verisinin tek bir satırının bayt cinsinden boyutunu alır. Görüntünün ham veri formatında tek bir piksel satırının kapladığı bellek miktarını gösterir. Ham satır boyutunu anlamak, bellek tahsisi, veri manipülasyonu ve tek tek görüntü satırları üzerinde çalışan görüntü işleme algoritmaları gibi görevler için gereklidir.

**Returns:**
int - Ham satır boyutu bayt cinsinden.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Bu özellik, görüntünün genişliğini piksel olarak döndürür. Görüntünün boyutları hakkında temel bir bilgi sağlar; yeniden boyutlandırma, kırpma ve render gibi çeşitli görüntü işleme görevleri için kritiktir.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Bu özellik, görüntünün yüksekliğini piksel olarak alır. Görüntünün dikey boyutlarını anlamak için temel bilgi sağlar; yeniden boyutlandırma, kırpma ve render gibi çeşitli görüntü manipülasyon görevlerine yardımcı olur. Bu özelliğe erişmek, kullanıcıların görüntünün dikey boyutunu belirlemesini sağlar ve uygulamalarda hassas yerleşim ve görüntüleme imkanı verir.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Bu özellik, görüntünün derinliğini piksel başına bit (bpp) cinsinden döndürür. Görüntünün her pikselinde depolanan renk bilgisinin miktarını gösterir. Görüntü derinliğini anlamak, renk doğruluğu ve görüntü kalitesini belirlemek için kritiktir. Bu bilgi sayesinde kullanıcılar, görüntüdeki detay ve renk zenginliği seviyesini ölçebilir.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Bu özellik, [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin yatay çözünürlüğünü piksel başına inç (PPI) cinsinden almanıza veya değiştirmenize olanak tanır. Bu çözünürlüğün ayarlanması, görüntünün yazdırıldığında veya gösterildiğinde boyut ve kalitesini etkileyebilir. Yatay çözünürlüğü ayarlayarak, kullanıcılar görüntüyü belirli çıktı cihazları veya uygulamalar için optimize edebilir ve mümkün olan en iyi görsel sonuçları elde edebilir.

**Returns:**
double - Yatay çözünürlük.

Not: varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // Jpeg2000Image'in yatay ve dikey çözünürlüğünü alın.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// Yatay çözünürlük, piksel başına inç: 72.0
// Dikey çözünürlük, piksel başına inç: 72.0
// Çözünürlük değerlerini 96 dpi olarak ayarlayın
// Yatay çözünürlük, piksel başına inç: 72.0
// Dikey çözünürlük, piksel başına inç: 72.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Bu özellik, [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin yatay çözünürlüğünü piksel başına inç (PPI) cinsinden almanıza veya değiştirmenize olanak tanır. Bu çözünürlüğün ayarlanması, görüntünün yazdırıldığında veya gösterildiğinde boyut ve kalitesini etkileyebilir. Yatay çözünürlüğü ayarlayarak, kullanıcılar görüntüyü belirli çıktı cihazları veya uygulamalar için optimize edebilir ve mümkün olan en iyi görsel sonuçları elde edebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Yatay çözünürlük. |

Not: varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Bu özellik, [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin dikey çözünürlüğüne piksel başına inç (PPI) cinsinden erişim sağlar. Bu çözünürlüğün değiştirilmesi, görüntünün yazdırıldığında veya gösterildiğinde kalite ve boyutunu etkileyebilir. Dikey çözünürlüğü ayarlayarak, kullanıcılar görüntüyü farklı çıktı cihazları veya uygulamalar için optimize edebilir ve optimal görsel render elde edebilir.

**Returns:**
double - Dikey çözünürlük.

Not: varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.

**Example: The following example shows how to set horizontal/vertical resolution of a JPEG2000 image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.jp2");
try {
    com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image jpeg2000Image = (com.aspose.imaging.fileformats.jpeg2000.Jpeg2000Image) image;

    // Jpeg2000Image'in yatay ve dikey çözünürlüğünü alın.
    double horizontalResolution = jpeg2000Image.getHorizontalResolution();
    double verticalResolution = jpeg2000Image.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
        System.out.println("Set resolution values to 96 dpi");
        jpeg2000Image.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + jpeg2000Image.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + jpeg2000Image.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// Yatay çözünürlük, piksel başına inç: 72.0
// Dikey çözünürlük, piksel başına inç: 72.0
// Çözünürlük değerlerini 96 dpi olarak ayarlayın
// Yatay çözünürlük, piksel başına inç: 72.0
// Dikey çözünürlük, piksel başına inç: 72.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Bu özellik, [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin dikey çözünürlüğüne piksel başına inç (PPI) cinsinden erişim sağlar. Bu çözünürlüğün değiştirilmesi, görüntünün yazdırıldığında veya gösterildiğinde kalite ve boyutunu etkileyebilir. Dikey çözünürlüğü ayarlayarak, kullanıcılar görüntüyü farklı çıktı cihazları veya uygulamalar için optimize edebilir ve optimal görsel render elde edebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Dikey çözünürlük. |

Not: varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz. |

### getComments() {#getComments--}
```
public String[] getComments()
```


Bu özellik, görüntüyle ilişkili yorumları almanıza veya güncellemenize olanak tanır. Yorumlar, görüntü içeriği hakkında ek bilgiler sağlar; örneğin açıklamalar, tanımlar veya meta veriler. Bu yorumları değiştirmek, görüntüleri düzenlemek ve sınıflandırmak, ayrıca izleyicilere veya kullanıcılara önemli detayları iletmek için faydalı olabilir.

**Returns:**
java.lang.String[] - Yorumlar.
### setComments(String[] value) {#setComments-java.lang.String---}
```
public void setComments(String[] value)
```


Bu özellik, görüntüyle ilişkili yorumları almanıza veya güncellemenize olanak tanır. Yorumlar, görüntü içeriği hakkında ek bilgiler sağlar; örneğin açıklamalar, tanımlar veya meta veriler. Bu yorumları değiştirmek, görüntüleri düzenlemek ve sınıflandırmak, ayrıca izleyicilere veya kullanıcılara önemli detayları iletmek için faydalı olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String[] | Yorumlar. |

### getCodec() {#getCodec--}
```
public int getCodec()
```


Bu özellik, görüntüyle ilişkili JPEG2000 codec'ini alır. JPEG2000 codec'i, görüntü verilerini JPEG2000 formatında kodlamak ve kod çözmekten sorumludur; yüksek görüntü kalitesini korurken verimli sıkıştırma sağlar. Bu codec'e erişmek, gelişmiş görüntü işleme işlemleri gerçekleştirmek veya belirli gereksinimlere göre özelleştirilmiş görüntü sıkıştırma ayarlarını optimize etmek için faydalı olabilir.

**Returns:**
int - Codec.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Orijinal dosya ayarlarına dayalı görüntü seçeneklerini alın. Bu yöntem, orijinal görüntünün bit derinliğini ve diğer parametrelerini korumak, tutarlılığı sağlamak ve görüntü verisinin bütünlüğünü korumak için faydalıdır. Bu seçeneklere erişmek, görüntünün orijinal özelliklerini korurken sorunsuz bir şekilde işlenmesini ve işlenmesini kolaylaştırır. Örneğin, 1 bit/piksel bir siyah-beyaz PNG görüntüsü yüklerseniz ve ardından [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) yöntemiyle kaydederseniz, 8 bit/piksel bir çıktı PNG görüntüsü oluşur. Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için, bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve ikinci parametre olarak [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) yöntemine geçirin.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
