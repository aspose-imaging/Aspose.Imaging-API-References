---
title: "PngImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Taşınabilir Ağ Grafikleri PNG raster görüntülerini, sıkıştırma seviyeleri ve Gri Tonlama, İndeksli Renk, Gerçek Renk ve alfa kanalları dahil çeşitli renk derinliklerini destekleyen çok yönlü API'mizle işleyin."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.fileformats.png/pngimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
com.aspose.fileformats.core.interfaces.IInterlaced
```
public class PngImage extends RasterCachedImage implements IInterlaced
```

Portable Network Graphics (PNG) raster görüntülerini, sıkıştırma seviyeleri ve Gri Tonlama, İndeksli Renk, Gerçek Renk ve alfa kanalları dahil çeşitli renk derinliklerini destekleyen çok yönlü API'mizle işleyin. XMP meta verilerini sorunsuz bir şekilde işleyerek kapsamlı görüntü meta veri yönetimini mümkün kılar, PNG görüntülerini kolayca yükler, çeşitli manipülasyonlar gerçekleştirir, filtreler uygular ve görüntüleri diğer dosya formatlarına dönüştürerek optimum çok yönlülük ve özelleştirme sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [PngImage(int width, int height)](#PngImage-int-int-) | Genişlik ve yükseklik parametrelerini sağlayarak [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sınıfının yeni bir nesnesini başlatın. |
| [PngImage(String path)](#PngImage-java.lang.String-) | Yüklemek için görüntü dosyasının konumunu belirtmek üzere yol parametresini kullanarak [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sınıfının yeni bir örneğini oluşturur. |
| [PngImage(RasterImage rasterImage)](#PngImage-com.aspose.imaging.RasterImage-) | Bir raster görüntüyü parametre olarak sağlayarak [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sınıfının yeni bir örneğini oluşturur. |
| [PngImage(String path, int colorType)](#PngImage-java.lang.String-int-) | [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sınıfının yeni bir örneğini, görüntü dosyasının yolunu ve renk tipini belirterek başlatır. |
| [PngImage(RasterImage rasterImage, int colorType)](#PngImage-com.aspose.imaging.RasterImage-int-) | Bir raster görüntü ve renk tipi belirterek [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sınıfının yeni bir örneğini oluşturur. |
| [PngImage(InputStream stream)](#PngImage-java.io.InputStream-) | Bir akış ile başlatarak [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sınıfının yeni bir örneğini oluşturur. |
| [PngImage(int width, int height, int colorType)](#PngImage-int-int-int-) | İstenen genişlik, yükseklik ve renk tipi parametrelerini belirterek [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sınıfının yeni bir örneğini oluşturun. |
| [PngImage(PngOptions pngOptions, int width, int height)](#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-) | Genişlik ve yükseklik parametrelerinin yanı sıra PNG seçeneklerini de dahil ederek [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sınıfının yeni bir örneğini başlatın. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit değerini alın. |
| [getHeight()](#getHeight--) | Görüntünün yüksekliğini piksel cinsinden elde edin. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Görüntünün yatay çözünürlüğünü alın veya değiştirin. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Görüntünün yatay çözünürlüğünü alın veya değiştirin. |
| [getFileFormat()](#getFileFormat--) | Görüntü örneğiyle ilişkili dosyanın formatını alır. |
| [getRawDataFormat()](#getRawDataFormat--) | Görüntünün ham veri formatına erişir. |
| [getVerticalResolution()](#getVerticalResolution--) | Görüntünün dikey çözünürlüğüne erişim sağlar. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Görüntünün dikey çözünürlüğüne erişim sağlar. |
| [getWidth()](#getWidth--) | Görüntünün genişliğini piksel cinsinden almayı sağlar ve boyutları hakkında temel bilgi sunar. |
| [hasTransparentColor()](#hasTransparentColor--) | Görüntünün şeffaf bir renk içerip içermediğini gösteren bir boolean değer sağlar. |
| [hasAlpha()](#hasAlpha--) | Görüntünün şeffaflığını belirleyen bir alfa kanalı içerip içermediğini gösteren bir boolean değer döndürür. |
| [getTransparentColor()](#getTransparentColor--) | Varsa, görüntünün şeffaf rengini alır. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Görüntünün şeffaf bir renk içerip içermediğini gösteren bir boolean değer sağlar. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Varsa, görüntünün şeffaf rengini değiştirir. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Görüntünün bir arka plan rengine sahip olup olmadığını gösteren bir boolean değer alır. |
| [getBackgroundColor()](#getBackgroundColor--) | Belirtilmişse, görüntünün arka plan rengini alır. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Görüntünün bir arka plan rengine sahip olup olmadığını gösteren bir boolean değer alır. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Belirtilmişse, görüntünün arka plan rengini alır. |
| [getInterlaced()](#getInterlaced--) | [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) nesnesinin satır aralıklı olup olmadığını gösteren bir boolean değer alır; bu, görüntü verisinin daha hızlı yükleme veya iletim için ilerleyici bir şekilde depolanıp depolanmadığını belirler. |
| [isInterlaced()](#isInterlaced--) | Bu görüntü örneğinin satır aralıklı olup olmadığını gösteren bir değeri alır. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Varsayılan seçenekleri alır. |
| [getOriginalOptions()](#getOriginalOptions--) | Orijinal dosya ayarlarına dayalı seçenekleri alır. |

## Example: This example shows how to load a PNG image from a file.

``` java
String dir = "c:\\temp\\";

// Bir dosyadan PNG görüntüsü yükle.
com.aspose.imaging.fileformats.png.PngImage pngImage = new com.aspose.imaging.fileformats.png.PngImage(dir + "sample.png");
try {
    // Görüntüyü gri tonlamalı temsile dönüştür
    pngImage.grayscale();

    // Bir dosyaya kaydet.
    pngImage.save(dir + "sample.grayscale.png");
} finally {
    pngImage.dispose();
}
```

### PngImage(int width, int height) {#PngImage-int-int-}
```
public PngImage(int width, int height)
```


Genişlik ve yükseklik parametrelerini sağlayarak [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sınıfının yeni bir nesnesini başlatın. Bu yapıcı, geliştiricilerin boyutları doğrudan belirlemesine izin vererek PNG görüntülerinin oluşturulmasını basitleştirir ve uygulamalarında PNG görüntü verilerinin verimli yönetimini kolaylaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Genişlik. |
| yükseklik | int | Yükseklik. |

### PngImage(String path) {#PngImage-java.lang.String-}
```
public PngImage(String path)
```


[PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sınıfının yeni bir örneğini, yüklenmek istenen görüntü dosyasının konumunu belirtmek için yol parametresini kullanarak oluşturur. Bu yapıcı, geliştiricilerin bir dosyadan yükleyerek PNG görüntülerini kolayca oluşturmasını sağlar ve uygulamalarında PNG görüntüleriyle çalışmayı basitleştirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Görüntüyü yüklemek için yol. |

### PngImage(RasterImage rasterImage) {#PngImage-com.aspose.imaging.RasterImage-}
```
public PngImage(RasterImage rasterImage)
```


Bir raster görüntüyü parametre olarak sağlayarak [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sınıfının yeni bir örneğini oluşturur. Bu yapıcı, geliştiricilerin mevcut bir raster görüntüyü kullanarak doğrudan bir PNG görüntü nesnesi başlatmasına izin verir ve uygulamalarında PNG görüntüleriyle çalışmayı kolaylaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Raster görüntü. |

### PngImage(String path, int colorType) {#PngImage-java.lang.String-int-}
```
public PngImage(String path, int colorType)
```


[PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sınıfının yeni bir örneğini, görüntü dosyasının yolunu ve renk tipini belirterek başlatır. Bu yapıcı, farklı renk tiplerine sahip dosyalardan PNG görüntülerinin kolayca oluşturulmasını sağlar ve çeşitli görüntü formatlarını işleme esnekliği sunar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Görüntüyü yüklemek için yol. |
| colorType | int | Renk tipi. |

### PngImage(RasterImage rasterImage, int colorType) {#PngImage-com.aspose.imaging.RasterImage-int-}
```
public PngImage(RasterImage rasterImage, int colorType)
```


Bir raster görüntü ve renk tipi belirterek [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sınıfının yeni bir örneğini oluşturur. Bu yapıcı, geliştiricilerin istenen renk tipini belirterek raster görüntüleri doğrudan PNG formatına dönüştürmesine olanak tanır ve renk temsili konusunda esneklik sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Raster görüntü. |
| colorType | int | Renk tipi. |

### PngImage(InputStream stream) {#PngImage-java.io.InputStream-}
```
public PngImage(InputStream stream)
```


Bir akış ile başlatarak [PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sınıfının yeni bir örneğini oluşturur. Bu yapıcı, geliştiricilerin PNG görüntülerini doğrudan bir akıştan yüklemesine izin verir ve farklı kaynaklardan görüntü alımında esneklik sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Bir görüntüyü yüklemek için akış. |

### PngImage(int width, int height, int colorType) {#PngImage-int-int-int-}
```
public PngImage(int width, int height, int colorType)
```


[PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sınıfının yeni bir örneğini, istenen genişlik, yükseklik ve renk tipi parametrelerini belirterek oluşturun. Bu yapıcı, özelleştirilmiş boyut ve renk yapılandırmalarına sahip PNG görüntülerinin hızlı bir şekilde oluşturulmasını sağlar ve çeşitli uygulama ve iş akışları için sorunsuz görüntü üretimini kolaylaştırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Genişlik. |
| yükseklik | int | Yükseklik. |
| colorType | int | Renk tipi. |

### PngImage(PngOptions pngOptions, int width, int height) {#PngImage-com.aspose.imaging.imageoptions.PngOptions-int-int-}
```
public PngImage(PngOptions pngOptions, int width, int height)
```


[PngImage](../../com.aspose.imaging.fileformats.png/pngimage) sınıfının yeni bir örneğini, genişlik ve yükseklik parametreleriyle birlikte PNG seçeneklerini dahil ederek başlatın. Bu yapıcı, geliştiricilerin özelleştirilebilir ayarlar ve boyutlarla PNG görüntüleri oluşturmasını sağlar ve çeşitli kullanım senaryoları için görüntü üretiminde esneklik sunar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pngOptions | [PngOptions](../../com.aspose.imaging.imageoptions/pngoptions) | PNG seçenekleri. |
| genişlik | int | Genişlik. |
| yükseklik | int | Yükseklik. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Görüntünün piksel başına bit değerini alın. Bu özellik, görüntünün renk derinliğiyle ilgili kritik bilgiler sağlar ve geliştiricilerin görüntü verilerindeki detay seviyesi ve renk doğruluğunu anlamasına olanak tanır.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Görüntünün yüksekliğini piksel cinsinden elde edin. Bu özellik, görüntünün dikey boyutunu döndürür ve geliştiricilerin dikey eksende piksel olarak boyutunu belirlemesini sağlar.

**Returns:**
int
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Görüntünün yatay çözünürlüğünü alın veya değiştirin. Bu özellik, görüntünün yatay eksenindeki inç başına piksel sayısını temsil eder. Bu çözünürlüğün ayarlanması, görüntünün yazdırıldığında veya gösterildiğinde fiziksel boyutunu etkileyebilir.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // PngImage'in yatay ve dikey çözünürlüğünü alın.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Çıktı şöyle görünebilir:
//Yatay çözünürlük, inç başına piksel olarak: 96.0
//Dikey çözünürlük, inç başına piksel olarak: 96.0
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Görüntünün yatay çözünürlüğünü alın veya değiştirin. Bu özellik, görüntünün yatay eksenindeki inç başına piksel sayısını temsil eder. Bu çözünürlüğün ayarlanması, görüntünün yazdırıldığında veya gösterildiğinde fiziksel boyutunu etkileyebilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Görüntü örneğiyle ilişkili dosyanın formatını alır. Bu özellik, dosya türüyle ilgili temel bilgiler sağlar ve belirli format gereksinimlerine göre verimli işleme ve yönetim yapılmasını mümkün kılar.

**Returns:**
long
### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Görüntünün ham veri formatına erişir. Bu özellik, görüntü verilerinin dahili olarak nasıl yapılandırıldığını gösterir ve gelişmiş görüntü işleme görevleri veya format dönüşümü için faydalı olabilir.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat)

**Example: The following example loads PNG images and prints information about raw data format and alpha channel.**

``` java

// Yüklenecek PNG görüntüler.
String[] fileNames = new String[]
        {
                "c:\\temp\\sample.png",
                "c:\\temp\\alpha.png",
        };

for (String fileName : fileNames) {
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
        System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s", fileName, pngImage.getRawDataFormat(), pngImage.hasAlpha());
    } finally {
        image.dispose();
    }
}

// Çıktı şöyle görünebilir:
// ImageFile=c:\temp\sample.png, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
// ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True
```

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Görüntünün dikey çözünürlüğüne erişim sağlar. Geliştiriciler bu özelliği, görüntünün dikey eksenindeki inç başına piksel (PPI) sayısını gösteren çözünürlük ayarını almak veya değiştirmek için kullanabilir.

**Returns:**
double

**Example: The following example shows how to set horizontal/vertical resolution of a PNG image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png");
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

    // PngImage'in yatay ve dikey çözünürlüğünü alın.
    double horizontalResolution = pngImage.getHorizontalResolution();
    double verticalResolution = pngImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
        System.out.println("Set resolution values to 96 dpi");
        pngImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + pngImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + pngImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Çıktı şöyle görünebilir:
//Yatay çözünürlük, inç başına piksel olarak: 96.0
//Dikey çözünürlük, inç başına piksel olarak: 96.0
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Görüntünün dikey çözünürlüğüne erişim sağlar. Geliştiriciler bu özelliği, görüntünün dikey eksenindeki inç başına piksel (PPI) sayısını gösteren çözünürlük ayarını almak veya değiştirmek için kullanabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


Görüntünün genişliğini piksel cinsinden almayı sağlar ve boyutları hakkında temel bilgiler sunar. Bu özellik, geliştiricilerin görüntünün genişliğini belirlemek için sıkça kullanılır ve boyutuna göre çeşitli işlemler yapmalarına olanak tanır.

**Returns:**
int
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Görüntünün şeffaf bir renk içerip içermediğini gösteren bir boolean değer sağlar. Bu özellik, şeffaflığı yönetmesi gereken uygulamalar için kritiktir ve geliştiricilerin görüntüdeki şeffaf bölgeler için ek işleme gerekip gerekmediğini belirlemesine olanak tanır.

**Returns:**
boolean
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Görüntünün alfa kanalı olup olmadığını belirten bir boolean değer döndürür; bu, şeffaflığını belirler. Bu özellik, şeffaflığı yönetmesi gereken uygulamalar için faydalıdır ve geliştiricilerin görüntüdeki şeffaf alanları işlemek için ek işlem gerekip gerekmediğini belirlemelerine olanak tanır.

**Returns:**
boolean - bu örnek alfa içeriyorsa `true`; aksi takdirde `false`.

**Example: The following example shows how to check if a PNG image supports alpha-channel.**

``` java

// Yardımcı sınıf
class Utils {
    public String getPngColorTypeString(int colorType) {
        switch (colorType) {
            case com.aspose.imaging.fileformats.png.PngColorType.Grayscale:
                return "Grayscale";

            case com.aspose.imaging.fileformats.png.PngColorType.Truecolor:
                return "Truecolor";

            case com.aspose.imaging.fileformats.png.PngColorType.IndexedColor:
                return "IndexedColor";

            case com.aspose.imaging.fileformats.png.PngColorType.GrayscaleWithAlpha:
                return "GrayscaleWithAlpha";

            case com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha:
                return "TruecolorWithAlpha";

            default:
                throw new IllegalArgumentException("colorType");
        }
    }
}

// İşte ana örnek.
Utils utils = new Utils();

// Desteklenen tüm PNG renk türlerini alın.
java.lang.Long[] colorTypes = com.aspose.imaging.fileformats.png.PngColorType.getValues(com.aspose.imaging.fileformats.png.PngColorType.class);

for (java.lang.Long colorType : colorTypes) {
    com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
    createOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createOptions.setColorType(colorType.intValue());

    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
    try {
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;

        if (pngImage.hasAlpha()) {
            System.out.printf("A %s PNG image supports alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        } else {
            System.out.printf("A %s PNG image doesn't support alpha channel\r\n", utils.getPngColorTypeString(createOptions.getColorType()));
        }
    } finally {
        image.dispose();
    }
}

// Çıktı şu şekilde görünür:
// Gri tonlamalı bir PNG görüntüsü alfa kanalını desteklemez
// Gerçek renkli bir PNG görüntüsü alfa kanalını desteklemez
// Dizinli renkli bir PNG görüntüsü alfa kanalını desteklemez
// Alfa kanallı gri tonlamalı bir PNG görüntüsü alfa kanalını destekler
// Alfa kanallı gerçek renkli bir PNG görüntüsü alfa kanalını destekler
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Görüntünün şeffaf rengini, varsa, alır. Bu özellik, görüntülerdeki şeffaf alanların hassas bir şekilde işlenmesini gerektiren uygulamalar için değerlidir ve geliştiricilerin kullanılan belirli şeffaf renge erişip onu manipüle etmelerine olanak tanır.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Görüntünün şeffaf bir renk içerip içermediğini gösteren bir boolean değer sağlar. Bu özellik, şeffaflığı yönetmesi gereken uygulamalar için kritiktir ve geliştiricilerin görüntüdeki şeffaf bölgeler için ek işleme gerekip gerekmediğini belirlemesine olanak tanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// 100x100 piksel boyutunda bir Gerçek Renkli PNG görüntüsü oluştur.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Tüm kırmızı pikseller tamamen şeffaf olarak kabul edilecektir.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Tüm şeffaf pikseller bir arka plan rengine sahip olacaktır.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Tüm görüntüyü beyaz renk ile doldurun.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Görüntünün sol üst çeyreğini şeffaf renk ile doldurun.
    // Bu, sol üst çeyreği arka plan rengi ile renklendirir.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Görüntünün şeffaf rengini, varsa, değiştirir. Bu özellik, görüntülerdeki şeffaf alanların hassas bir şekilde işlenmesini gerektiren uygulamalar için değerlidir ve geliştiricilerin kullanılan belirli şeffaf renge erişip onu manipüle etmelerine olanak tanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// 100x100 piksel boyutunda bir Gerçek Renkli PNG görüntüsü oluştur.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Tüm kırmızı pikseller tamamen şeffaf olarak kabul edilecektir.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Tüm şeffaf pikseller bir arka plan rengine sahip olacaktır.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Tüm görüntüyü beyaz renk ile doldurun.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Görüntünün sol üst çeyreğini şeffaf renk ile doldurun.
    // Bu, sol üst çeyreği arka plan rengi ile renklendirir.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Görüntünün bir arka plan rengine sahip olup olmadığını belirten bir boolean değer alır. Bu özellik, bir görüntünün arka plan rengi içerip içermediğini belirlemesi gereken uygulamalar için faydalıdır; bu, bileşim, renderleme veya dışa aktarma gibi çeşitli işleme görevleri için önemli olabilir.

**Returns:**
boolean
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Görüntünün arka plan rengini, belirtilmişse, alır. Bu özellik, bir görüntünün arka plan rengini tanımlaması ve gerektiğinde manipüle etmesi gereken uygulamalar için yardımcıdır.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Görüntünün bir arka plan rengine sahip olup olmadığını belirten bir boolean değer alır. Bu özellik, bir görüntünün arka plan rengi içerip içermediğini belirlemesi gereken uygulamalar için faydalıdır; bu, bileşim, renderleme veya dışa aktarma gibi çeşitli işleme görevleri için önemli olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// 100x100 piksel boyutunda bir Gerçek Renkli PNG görüntüsü oluştur.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Tüm kırmızı pikseller tamamen şeffaf olarak kabul edilecektir.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Tüm şeffaf pikseller bir arka plan rengine sahip olacaktır.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Tüm görüntüyü beyaz renk ile doldurun.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Görüntünün sol üst çeyreğini şeffaf renk ile doldurun.
    // Bu, sol üst çeyreği arka plan rengi ile renklendirir.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Görüntünün arka plan rengini, belirtilmişse, alır. Bu özellik, bir görüntünün arka plan rengini tanımlaması ve gerektiğinde manipüle etmesi gereken uygulamalar için yardımcıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |


**Example: The following example shows how to set fully transparent colors for a part of a TrueColor PNG image which doesn't support alpha channel.**

``` java

com.aspose.imaging.imageoptions.PngOptions createOptions = new com.aspose.imaging.imageoptions.PngOptions();
createOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\transparent.png", false));
createOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.Truecolor);

// 100x100 piksel boyutunda bir Gerçek Renkli PNG görüntüsü oluştur.
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(createOptions, 100, 100);
try {
    com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) image;
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);

    // Tüm kırmızı pikseller tamamen şeffaf olarak kabul edilecektir.
    pngImage.setTransparentColor(com.aspose.imaging.Color.getRed());
    pngImage.setTransparentColor(true);

    // Tüm şeffaf pikseller bir arka plan rengine sahip olacaktır.
    pngImage.setBackgroundColor(com.aspose.imaging.Color.getGreen());
    pngImage.setBackgroundColor(true);

    // Tüm görüntüyü beyaz renk ile doldurun.
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite()), pngImage.getBounds());

    // Görüntünün sol üst çeyreğini şeffaf renk ile doldurun.
    // Bu, sol üst çeyreği arka plan rengi ile renklendirir.
    com.aspose.imaging.Rectangle rect = new com.aspose.imaging.Rectangle(0, 0, pngImage.getWidth() / 2, pngImage.getHeight() / 2);
    gr.fillRectangle(new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed()), rect);

    pngImage.save();
} finally {
    image.dispose();
}
```

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


[PngImage](../../com.aspose.imaging.fileformats.png/pngimage) nesnesinin satır aralıklı olup olmadığını gösteren bir boolean değer alır; bu, görüntü verisinin daha hızlı yükleme veya iletim için ilerleyici bir şekilde depolanıp depolanmadığını belirler.

**Returns:**
boolean - aralıklı ise `true`; aksi takdirde `false`.
### isInterlaced() {#isInterlaced--}
```
public final boolean isInterlaced()
```


Bu görüntü örneğinin satır aralıklı olup olmadığını gösteren bir değeri alır.

Değer: bu görüntü örneği aralıklı ise `true`; aksi takdirde `false`.

**Returns:**
boolean - bu görüntü örneğinin aralıklı olup olmadığını gösteren bir değer.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Varsayılan seçenekleri alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argümanlar | java.lang.Object[] | Argümanlar. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasını sağlamak için yararlı olabilir. Örneğin, 1 bit/piksel bir siyah-beyaz PNG görüntüsü yükleyip `DataStreamSupporter.Save(string)` yöntemiyle kaydederseniz, çıktı PNG görüntüsü 8 bit/piksel olarak üretilir. Bunu önlemek ve PNG görüntüsünü 1 bit/piksel olarak kaydetmek için bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları `Image.Save(string, ImageOptionsBase)` yöntemine ikinci parametre olarak geçirin.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
