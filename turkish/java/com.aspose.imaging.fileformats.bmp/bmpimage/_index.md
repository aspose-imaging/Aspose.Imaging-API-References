---
title: "BmpImage"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bitmap BMP ve Device Independent Bitmap DIB dosyalarını sorunsuz bir şekilde işleyebilir, raster görüntülerin verimli manipülasyonu ve işlenmesini kolaylaştırabilirsiniz."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging.fileformats.bmp/bmpimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class BmpImage extends RasterCachedImage
```

Bitmap (BMP) ve Device Independent Bitmap (DIB) dosyalarını sorunsuz bir şekilde işleyebilir, raster görüntülerin verimli manipülasyonu ve işlenmesini kolaylaştırabilirsiniz. Görüntüler üzerinde çeşitli işlemler gerçekleştirerek, bu API iş akışını basitleştirir ve geliştiricilere BMP ve DIB formatlarıyla çalışmak için güvenilir bir araç seti sunar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BmpImage(String path)](#BmpImage-java.lang.String-) | BmpImage sınıfını sorunsuz bir şekilde kullanmaya başlayın; bu yapıcı yeni bir örnek başlatır. |
| [BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.lang.String-int-long-double-double-) | Bu yapıcıyı kullanarak, yol, bitsPerPixel ve sıkıştırma gibi belirtilen parametreleri kullanarak, [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sınıfının yeni bir örneğini sorunsuz bir şekilde oluşturun. |
| [BmpImage(InputStream stream)](#BmpImage-java.io.InputStream-) | Bu yapıcıyı kullanarak bir akışı girdi olarak vererek, [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sınıfını sorunsuz bir şekilde kullanmaya başlayın; yeni bir örnek başlatın. |
| [BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-java.io.InputStream-int-long-double-double-) | Bir akış ve bitsPerPixel ile sıkıştırma gibi belirtilen parametreleri kullanarak yeni bir örnek oluşturarak, [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sınıfı ile sorunsuz bir şekilde çalışmaya başlayın. |
| [BmpImage(RasterImage rasterImage)](#BmpImage-com.aspose.imaging.RasterImage-) | Bir RasterImage nesnesiyle başlatarak, [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sınıfının yeni bir örneğini sorunsuz bir şekilde oluşturun. |
| [BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-) | Bir rasterImage ve bitsPerPixel ile sıkıştırma gibi belirtilen parametreleri kullanarak yeni bir örnek oluşturarak, [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sınıfı ile sorunsuz bir şekilde çalışmaya başlayın. |
| [BmpImage(int width, int height)](#BmpImage-int-int-) | Belirtilen genişlik ve yükseklik parametreleriyle yeni bir örnek oluşturarak, [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sınıfını sorunsuz bir şekilde kullanmaya başlayın. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-) | Genişlik, yükseklik, bit derinliği ve palet gibi parametrelerle yeni bir örnek başlatarak, [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sınıfını sorunsuz bir şekilde kullanmaya başlayın. |
| [BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)](#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-) | Bu yapıcıyı kullanarak [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sınıfının yeni bir örneğini zahmetsizce oluşturun, genişlik, yükseklik, bitsPerPixel ve palet gibi parametreleri belirterek. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBitmapInfoHeader()](#getBitmapInfoHeader--) | Bu basit işlevle bitmap görüntünüz hakkında temel ayrıntılara hızlıca erişin. |
| [getFileFormat()](#getFileFormat--) | Bu kullanıcı dostu özellik sayesinde dosya formatı değerini kolayca alabilirsiniz. |
| [getRawDataFormat()](#getRawDataFormat--) | Bu kullanıcı dostu işlevle ham verinizin biçimini kolayca elde edin. |
| [getRawLineSize()](#getRawLineSize--) | Bu basit özellik sayesinde her ham satırın bayt cinsinden boyutuna hızlıca erişin. |
| [getCompression()](#getCompression--) | Bu özellik sayesinde görüntü için kullanılan sıkıştırma türünü zahmetsizce alın. |
| [getWidth()](#getWidth--) | Bu özellik sayesinde görüntünün genişliğine kolayca erişin. |
| [getHeight()](#getHeight--) | Bu özellik sayesinde görüntünün yüksekliğini zahmetsizce alın. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Bu özellik sayesinde görüntünün piksel başına bit sayısına kolayca erişin. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Bu özellik, [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin inç başına piksel cinsinden ölçülen yatay çözünürlüğünü kolayca alıp ayarlamanıza olanak tanır. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Bu özellik, [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin inç başına piksel cinsinden ölçülen yatay çözünürlüğünü kolayca alıp ayarlamanıza olanak tanır. |
| [getVerticalResolution()](#getVerticalResolution--) | Bu özellik sayesinde bu [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin inç başına piksel cinsinden ölçülen dikey çözünürlüğünü kolayca alıp ayarlayabilirsiniz. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Bu özellik sayesinde bu [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin inç başına piksel cinsinden ölçülen dikey çözünürlüğünü kolayca alıp ayarlayabilirsiniz. |
| [hasAlpha()](#hasAlpha--) | Bu örneğin alfa içerip içermediğini gösteren bir değer alır. |
| [setResolution(double dpiX, double dpiY)](#setResolution-double-double-) | [RasterImage](../../com.aspose.imaging/rasterimage) çözünürlüğünüzü bu kullanıcı dostu yöntemle zahmetsizce ayarlayın. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Bu basit yöntemle varsayılan seçenekleri zahmetsizce alın. |

## Example: The following example shows how to create a BMP image of the specified size.

``` java
String dir = "c:\\temp\\";

// 100 x 100 piksel bir BMP görüntüsü oluştur.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100);
try {
    // Görüntüyü basit bir lineer kırmızı-siyah degrade ile doldurun.
    int width = bmpImage.getWidth();
    int height = bmpImage.getHeight();
    for (int y = 0; y < height; y++) {
        for (int x = 0; x < width; x++) {
            int hue = (255 * x) / width;
            bmpImage.setPixel(x, y, com.aspose.imaging.Color.fromArgb(255, hue, 0, 0));
        }
    }

    java.io.OutputStream stream = new java.io.FileOutputStream(dir + "output.bmp");
    try {
        bmpImage.save(stream);
    } finally {
        stream.close();
    }
} finally {
    bmpImage.dispose();
}
```


## Example: Compress BMP image using DXT1 compression algorithm.

``` java
try (Image image = Image.load("Tiger.bmp"))
{
    BmpOptions options = new BmpOptions();
    options.setCompression(BitmapCompression.Dxt1);
    image.save("CompressedTiger.bmp", options);
}
```


## Example: Decompress BMP image which was previously compressed using DXT1 compression algorithm.

``` java
    try (Image image = Image.load("CompressedTiger.bmp"))
    {
        image.save("DecompressedTiger.bmp", new BmpOptions());
    }
}

{
```


## Example: The example shows how to export a BmpImage from a Png file while keeping the alpha channel, save a Bmp file with transparency.

``` java
String sourcePath = "input.png";
String outputPathPng = "output.png";
String outputPathBmp = "output.bmp";
// Bir dosyadan PNG görüntüsü yükle.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP görüntüsü varsayılan olarak şeffaflık desteğiyle kaydedilir.
    // Bu modu açıkça belirtmek istiyorsanız, BmpOptions'ın Compression özelliği BitmapCompression.Bitfields olarak ayarlanmalıdır.
    // BitmapCompression.Bitfields sıkıştırma yöntemi BmpOptions içinde varsayılan sıkıştırma yöntemidir.
    // Bu nedenle, şeffaflıkla bir Bmp görüntüsü dışa aktarmanın aynı sonucu aşağıdaki yöntemlerden biriyle elde edilebilir.
    // Örtük bir varsayılan seçenekle:
    pngImage.save(outputPathPng);
    // Açık bir varsayılan seçenekle:
    pngImage.save(outputPathBmp, new BmpOptions());
    // BitmapCompression.Bitfields sıkıştırma yöntemini belirterek:
    pngImage.save(outputPathBmp, new BmpOptions() {{ setCompression(BitmapCompression.Bitfields); }});
}
```


## Example: The example shows how to export a BmpImage with the Rgb compression type.

``` java
String sourcePath = "input.png";
String outputPath = "output.bmp";
// Bir dosyadan PNG görüntüsü yükle.
try (Image pngImage = Image.load(sourcePath))
{
    // BMP görüntüsü varsayılan olarak şeffaflık desteğiyle kaydedilir, bu BitmapCompression.Bitfields sıkıştırma yöntemi kullanılarak sağlanır.
    // RGB sıkıştırma yöntemiyle bir BMP görüntüsü kaydetmek için, Compression özelliği BitmapCompression.Rgb olarak ayarlanmış BmpOptions belirtilmelidir.
    pngImage.save(outputPath, new BmpOptions()
    {{
        setCompression(BitmapCompression.Rgb);
    }});
}
```


## Example: The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm.

``` java
String imageFilePath = "ball.png"; 
try (Image image = Image.load(imageFilePath))
{
    PngImage pngImage = (PngImage)image;

    GraphicsPath mask = new GraphicsPath();
    Figure firstFigure = new Figure();
    firstFigure.addShape(new EllipseShape(new RectangleF(350, 170, 570 - 350, 400 - 170)));
    mask.addFigure(firstFigure);

    ContentAwareFillWatermarkOptions options = new ContentAwareFillWatermarkOptions(mask);
    options.setMaxPaintingAttempts(4);
    try (Image result = WatermarkRemover.paintOver(pngImage, options))
    {
        result.Save(outputPath);
    }
}
```

### BmpImage(String path) {#BmpImage-java.lang.String-}
```
public BmpImage(String path)
```


Bu yapıcıyı kullanarak BmpImage sınıfını zahmetsizce kullanmaya başlayın; yeni bir örnek başlatır. [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) nesneleriyle hızlı ve verimli bir şekilde çalışmak isteyen geliştiriciler için mükemmeldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Görüntüyü yüklemek ve piksel ile palet verilerini başlatmak için yol. |

### BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.lang.String-int-long-double-double-}
```
public BmpImage(String path, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Bu yapıcıyı kullanarak [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sınıfının yeni bir örneğini zahmetsizce oluşturun; yol, bitsPerPixel ve compression gibi belirtilen parametreleri kullanarak. BmpImage nesnelerini hızlı ve verimli bir şekilde başlatmak ve görüntü özellikleri üzerinde hassas kontrol sağlamak isteyen geliştiriciler için idealdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Görüntüyü yüklemek ve piksel ile palet verilerini başlatmak için yol. |
| bitsPerPixel | int | Piksel başına bit. |
| sıkıştırma | long | Kullanılacak sıkıştırma. |
| horizontalResolution | double | Yatay çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |
| verticalResolution | double | Dikey çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |

### BmpImage(InputStream stream) {#BmpImage-java.io.InputStream-}
```
public BmpImage(InputStream stream)
```


Bu yapıcıyı kullanarak yeni bir örnek başlatarak [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sınıfını zahmetsizce kullanmaya başlayın; girdi olarak bir akış kullanır. Çeşitli veri kaynaklarından BmpImage nesneleriyle çalışmak için uygun bir yol arayan geliştiriciler için esneklik ve entegrasyon kolaylığı sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Görüntüyü yüklemek ve piksel ile palet verilerini başlatmak için akış. |

### BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-java.io.InputStream-int-long-double-double-}
```
public BmpImage(InputStream stream, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Bu akışı kullanarak bir örnek oluşturarak ve bitsPerPixel ve compression gibi belirtilen parametrelerle [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sınıfı ile sorunsuz bir şekilde çalışmaya başlayın. BmpImage nesnelerini yönetmek için doğrudan bir yol arayan geliştiriciler için projelerinde esneklik ve verimlilik sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Görüntüyü yüklemek ve piksel ile palet verilerini başlatmak için akış. |
| bitsPerPixel | int | Piksel başına bit. |
| sıkıştırma | long | Kullanılacak sıkıştırma. |
| horizontalResolution | double | Yatay çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |
| verticalResolution | double | Dikey çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |

### BmpImage(RasterImage rasterImage) {#BmpImage-com.aspose.imaging.RasterImage-}
```
public BmpImage(RasterImage rasterImage)
```


Bu yapıcıyı kullanarak bir RasterImage nesnesiyle başlatarak [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sınıfının yeni bir örneğini zahmetsizce oluşturun. Mevcut raster görüntüleri BmpImage formatına sorunsuz bir şekilde dönüştürmek ve projelerinde uyumluluk ve entegrasyon kolaylığı sağlamak isteyen geliştiriciler için mükemmeldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Piksel ve palet verilerini başlatmak için kullanılacak görüntü. |

### BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-com.aspose.imaging.RasterImage-int-long-double-double-}
```
public BmpImage(RasterImage rasterImage, int bitsPerPixel, long compression, double horizontalResolution, double verticalResolution)
```


Bu rasterImage'i kullanarak ve bitsPerPixel ve compression gibi belirtilen parametrelerle yeni bir örnek oluşturarak [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sınıfı ile sorunsuz bir şekilde çalışmaya başlayın. BmpImage nesnelerini yönetmek için doğrudan bir yol arayan geliştiriciler için projelerinde esneklik ve verimlilik sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Piksel ve palet verilerini başlatmak için kullanılacak görüntü. |
| bitsPerPixel | int | Piksel başına bit. |
| sıkıştırma | long | Kullanılacak sıkıştırma. |
| horizontalResolution | double | Yatay çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |
| verticalResolution | double | Dikey çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |

### BmpImage(int width, int height) {#BmpImage-int-int-}
```
public BmpImage(int width, int height)
```


Bu yapıcıyı kullanarak belirli genişlik ve yükseklik parametreleriyle yeni bir örnek oluşturarak [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sınıfını zahmetsizce kullanmaya başlayın. Özel boyutlarda BmpImage nesneleri oluşturmak için uygun bir yol arayan geliştiriciler için esneklik ve entegrasyon kolaylığı sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Görüntünün genişliği. |
| yükseklik | int | Görüntü yüksekliği. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette)
```


Yeni bir örnek başlatarak genişlik, yükseklik, bit derinliği ve palet gibi parametrelerle [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sınıfını sorunsuz bir şekilde kullanmaya başlayın. Özelleştirilmiş boyutlar ve renk yapılandırmalarıyla BmpImage nesneleri oluşturmanın basit bir yolunu arayan geliştiriciler için mükemmeldir, projelerinde esneklik ve verimlilik sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Görüntünün genişliği. |
| yükseklik | int | Görüntü yüksekliği. |
| bitsPerPixel | int | Piksel başına bit. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Renk paleti. |

### BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution) {#BmpImage-int-int-int-com.aspose.imaging.IColorPalette-long-double-double-}
```
public BmpImage(int width, int height, int bitsPerPixel, IColorPalette palette, long compression, double horizontalResolution, double verticalResolution)
```


Bu yapıcıyı kullanarak genişlik, yükseklik, bitsPerPixel ve palet gibi parametreleri belirterek [BmpImage](../../com.aspose.imaging.fileformats.bmp/bmpimage) sınıfının yeni bir örneğini zahmetsizce oluşturun. Özelleştirilmiş boyutlar ve renk yapılandırmalarıyla BmpImage nesneleri üretmenin pratik bir yolunu arayan geliştiriciler için mükemmeldir, projelerine entegrasyonu kolaylaştırır ve esneklik sağlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Görüntünün genişliği. |
| yükseklik | int | Görüntü yüksekliği. |
| bitsPerPixel | int | Piksel başına bit. |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Renk paleti. |
| sıkıştırma | long | Kullanılacak sıkıştırma. |
| horizontalResolution | double | Yatay çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |
| verticalResolution | double | Dikey çözünürlük. Not: yuvarlamadan dolayı elde edilen çözünürlük, verilen değerden biraz farklı olabilir. |

### getBitmapInfoHeader() {#getBitmapInfoHeader--}
```
public BitmapInfoHeader getBitmapInfoHeader()
```


Bu basit işlevle bitmap görüntünüzle ilgili temel ayrıntılara hızlıca erişin. Görüntülerinin başlık bilgilerini almak zorunda olan geliştiriciler için mükemmeldir.

**Returns:**
[BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader) - The bitmap information header.

**Example: The following example gets the information from the BMP header and prints it to the console.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;
    com.aspose.imaging.fileformats.bmp.BitmapInfoHeader header = bmpImage.getBitmapInfoHeader();

    System.out.println("The number of palette colors that are required for displaying the bitmap: " + header.getBitmapColorsImportant());
    System.out.println("The number of palette colors used in the bitmap: " + header.getBitmapColorsUsed());
    System.out.println("The bitmap compression: " + header.getBitmapCompression());
    System.out.println("The bitmap height: " + header.getBitmapHeight());
    System.out.println("The bitmap width: " + header.getBitmapWidth());
    System.out.println("The bitmap raw data size in bytes: " + header.getBitmapImageSize());
    System.out.println("The number of planes: " + header.getBitmapPlanes());
    System.out.println("The horizontal resolution of the bitmap, in pixels-per-meter: " + header.getBitmapXPelsPerMeter());
    System.out.println("The vertical resolution of the bitmap, in pixels-per-meter: " + header.getBitmapYPelsPerMeter());
    System.out.println("The number of bits per pixel: " + header.getBitsPerPixel());
    System.out.println("The extra bits masks: " + header.getExtraBitMasks());
    System.out.println("The header size in bytes: " + header.getHeaderSize());
} finally {
    image.dispose();
}

//Çıktı şöyle görünebilir:
//Bitmap'i görüntülemek için gereken palet renk sayısı: 0
//Bitmap'te kullanılan palet renk sayısı: 0
//Bitmap sıkıştırması: 0
//Bitmap yüksekliği: 100
//Bitmap genişliği: 100
//Bitmap ham veri boyutu (bayt cinsinden): 40000
//Düzlem sayısı: 1
//Bitmap'in yatay çözünürlüğü, piksel/metre cinsinden: 0
//Bitmap'in dikey çözünürlüğü, piksel/metre cinsinden: 0
//Piksel başına bit sayısı: 32
//Ek bit maskeleri: null
//Başlık boyutu (bayt cinsinden): 40
```

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Bu kullanıcı dostu özellik ile dosya formatı değerini kolayca alın. Dosya formatı hakkında bilgiye hızlı erişim isteyen geliştiriciler için idealdir.

**Returns:**
long

**Example: The following example shows how to extract information about raw data format and alpha channel from a BMP image.**

``` java

// Aşağıdaki ana örnekte kullanılan yardımcı sınıf.
class Utils {
    // Dosya formatının dize temsili almayı sağlayan yardımcı metod.
    public String getFileFormatString(long fileFormat) {
        if (fileFormat == com.aspose.imaging.FileFormat.Bmp) {
            return "BMP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Gif) {
            return "GIF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dicom) {
            return "DICOM";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Djvu) {
            return "DJVU";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Dng) {
            return "DNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Png) {
            return "PNG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg) {
            return "JPEG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Jpeg2000) {
            return "JPEG2000";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Psd) {
            return "PSD";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Tiff) {
            return "Tiff";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Webp) {
            return "WEBP";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cdr) {
            return "CDR";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Cmx) {
            return "CMX";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Emf) {
            return "EMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Wmf) {
            return "WMF";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Svg) {
            return "SVG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Odg) {
            return "ODG";
        } else if (fileFormat == com.aspose.imaging.FileFormat.Eps) {
            return "EPS";
        } else {
            return "UNDEFINED";
        }
    }
}

// İşte ana örnek.
Utils utils = new Utils();

// 100 x 100 piksel boyutunda 32-bpp BMP görüntüsü oluştur.
com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 32, null);
try {
    System.out.printf("FileFormat=%s, RawDataFormat=%s, HasAlpha=%s",
            utils.getFileFormatString(bmpImage.getFileFormat()),
            bmpImage.getRawDataFormat(),
            bmpImage.hasAlpha());
    System.out.println();
} finally {
    bmpImage.dispose();
}

// 100 x 100 piksel boyutunda 24-bpp BMP görüntüsü oluştur.
bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 24, null);
try {
    System.out.printf("FileFormat=%s, RawDataFormat=%s, HasAlpha=%s",
            utils.getFileFormatString(bmpImage.getFileFormat()),
            bmpImage.getRawDataFormat(),
            bmpImage.hasAlpha());
    System.out.println();
} finally {
    bmpImage.dispose();
}

// Çoğu durumda BMP alfa kanalını desteklemez, bu yüzden çıktı muhtemelen şöyle görünecektir:
// FileFormat=BMP, RawDataFormat=Rgb32Bpp, used channels: 8,8,8,8, HasAlpha=false
// FileFormat=BMP, RawDataFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=false
```

### getRawDataFormat() {#getRawDataFormat--}
```
public PixelDataFormat getRawDataFormat()
```


Bu kullanıcı dostu işlevle ham verinizin formatını kolayca elde edin. Veri formatlarıyla ilgili kritik bilgilere hızlıca erişmek isteyen geliştiriciler için mükemmeldir.

**Returns:**
[PixelDataFormat](../../com.aspose.imaging/pixeldataformat) - The raw data format.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Çıktı şöyle görünebilir:
//Piksel formatı: Rgb24Bpp, kullanılan kanallar: 8,8,8
//Ham satır boyutu (bayt cinsinden): 1500
//Bitmap sıkıştırması: 0
//Bitmap genişliği: 500
//Bitmap yüksekliği: 500
//Piksel başına bit sayısı: 24
//Yatay çözünürlük, inç başına piksel olarak: 96.012
//Dikey çözünürlük, inç başına piksel olarak: 96.012
//Çözünürlük değerlerini 96 dpi olarak ayarlayın
//Yatay çözünürlük, inç başına piksel olarak: 96.012
//Dikey çözünürlük, inç başına piksel olarak: 96.012
```

### getRawLineSize() {#getRawLineSize--}
```
public int getRawLineSize()
```


Bu basit özellik ile her ham satırın bayt cinsinden boyutuna hızlıca erişin. Ham görüntü verisini verimli bir şekilde işlemek isteyen geliştiriciler için idealdir.

**Returns:**
int - Ham satır boyutu bayt cinsinden.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Çıktı şöyle görünebilir:
//Piksel formatı: Rgb24Bpp, kullanılan kanallar: 8,8,8
//Ham satır boyutu (bayt cinsinden): 1500
//Bitmap sıkıştırması: 0
//Bitmap genişliği: 500
//Bitmap yüksekliği: 500
//Piksel başına bit sayısı: 24
//Yatay çözünürlük, inç başına piksel olarak: 96.012
//Dikey çözünürlük, inç başına piksel olarak: 96.012
//Çözünürlük değerlerini 96 dpi olarak ayarlayın
//Yatay çözünürlük, inç başına piksel olarak: 96.012
//Dikey çözünürlük, inç başına piksel olarak: 96.012
```

### getCompression() {#getCompression--}
```
public long getCompression()
```


Bu özellik ile görüntüde kullanılan sıkıştırma türünü zahmetsizce alın. Görüntü sıkıştırması hakkında hızlıca bilgiye ihtiyaç duyan geliştiriciler için mükemmeldir.

**Returns:**
long - Görüntü sıkıştırması [BitmapCompression](../../com.aspose.imaging.fileformats.bmp/bitmapcompression).

**Example: The following example shows how the bitmap compression affects the output image size.**

``` java

// Aşağıdaki ana örnekte kullanılan yardımcı sınıf.
class Utils {
    // Dosya formatının dize temsili almayı sağlayan yardımcı metod.
    public String getBitmapCompressionString(long bitmapCompression) {
        if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb) {
            return "RGB";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle8) {
            return "RLE8";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle4) {
            return "RLE4";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Bitfields) {
            return "BITFIELDS";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Jpeg) {
            return "JPEG";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.Png) {
            return "PNG";
        } else if (bitmapCompression == com.aspose.imaging.fileformats.bmp.BitmapCompression.AlphaBitfields) {
            return "ALPHA_BITFIELDS";
        } else {
            return "UNDEFINED";
        }
    }
}

// İşte ana örnek.
Utils utils = new Utils();

long[] compressions = new long[]
        {
                com.aspose.imaging.fileformats.bmp.BitmapCompression.Rgb,
                com.aspose.imaging.fileformats.bmp.BitmapCompression.Rle8,
        };

com.aspose.imaging.Color[] paletterColors = new com.aspose.imaging.Color[]
        {
                com.aspose.imaging.Color.getRed(),
                com.aspose.imaging.Color.getGreen(),
        };

// Sadece kırmızı ve yeşil renkleri içeren bir monokrom palet oluşturun.
com.aspose.imaging.IColorPalette palette = new com.aspose.imaging.ColorPalette(paletterColors);

for (long compression : compressions) {
    // 100 x 100 piksel boyutunda 8 bpp BMP görüntüsü oluşturun.
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = new com.aspose.imaging.fileformats.bmp.BmpImage(100, 100, 8, palette, compression, 0.0, 0.0);
    try {
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(bmpImage);

        // Tüm görüntüyü kırmızıyla doldurun.
        com.aspose.imaging.brushes.SolidBrush redBrush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
        gr.fillRectangle(redBrush, bmpImage.getBounds());

        // Çıktı görüntü boyutunu elde etmek için görüntüyü bir akışa kaydedin.
        java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
        try {
            bmpImage.save(stream);

            System.out.printf("---------------------------------------------\r\n");
            System.out.printf("The compression=%s\r\n", utils.getBitmapCompressionString(bmpImage.getCompression()));
            System.out.printf("The number of bits per pixel=%s\r\n", bmpImage.getBitsPerPixel());
            System.out.printf("The image dimensions=%s x %s\r\n", bmpImage.getWidth(), bmpImage.getHeight());
            System.out.printf("The raw line size=%s\r\n", bmpImage.getRawLineSize());
            System.out.printf("The output size in bytes=%s\r\n", stream.size());
        } finally {
            stream.close();
        }
    } finally {
        bmpImage.dispose();
    }
}

// Çıktı şöyle görünebilir:
// Sıkıştırma=RGB
// Piksel başına bit sayısı=8
// Görüntü boyutları=100 x 100
// Ham satır boyutu=100
// Çıktı boyutu bayt olarak=11078
// ---------------------------------------------
// Sıkıştırma=RLE8
// Piksel başına bit sayısı=8
// Görüntü boyutları=100 x 100
// Ham satır boyutu=100
// Çıktı boyutu bayt olarak=856
```

### getWidth() {#getWidth--}
```
public int getWidth()
```


Bu özellik ile görüntünün genişliğine kolayca erişin. Görüntü boyutları hakkında hızlı bilgi arayan geliştiriciler için idealdir.

**Returns:**
int - Görüntü genişliği piksel cinsinden.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Çıktı şöyle görünebilir:
//Piksel formatı: Rgb24Bpp, kullanılan kanallar: 8,8,8
//Ham satır boyutu (bayt cinsinden): 1500
//Bitmap sıkıştırması: 0
//Bitmap genişliği: 500
//Bitmap yüksekliği: 500
//Piksel başına bit sayısı: 24
//Yatay çözünürlük, inç başına piksel olarak: 96.012
//Dikey çözünürlük, inç başına piksel olarak: 96.012
//Çözünürlük değerlerini 96 dpi olarak ayarlayın
//Yatay çözünürlük, inç başına piksel olarak: 96.012
//Dikey çözünürlük, inç başına piksel olarak: 96.012
```

### getHeight() {#getHeight--}
```
public int getHeight()
```


Bu özellik ile görüntünün yüksekliğini zahmetsizce alın. Görüntü boyutları hakkında hızlı bilgiye ihtiyaç duyan geliştiriciler için idealdir.

**Returns:**
int - Görüntü yüksekliği piksel cinsinden.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Çıktı şöyle görünebilir:
//Piksel formatı: Rgb24Bpp, kullanılan kanallar: 8,8,8
//Ham satır boyutu (bayt cinsinden): 1500
//Bitmap sıkıştırması: 0
//Bitmap genişliği: 500
//Bitmap yüksekliği: 500
//Piksel başına bit sayısı: 24
//Yatay çözünürlük, inç başına piksel olarak: 96.012
//Dikey çözünürlük, inç başına piksel olarak: 96.012
//Çözünürlük değerlerini 96 dpi olarak ayarlayın
//Yatay çözünürlük, inç başına piksel olarak: 96.012
//Dikey çözünürlük, inç başına piksel olarak: 96.012
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Bu özellik ile görüntünün piksel başına bit sayısına kolayca erişin. Görüntü kalitesi ve derinliği hakkında hızlı bilgi arayan geliştiriciler için mükemmeldir.

**Returns:**
int - Görüntünün piksel başına bit sayısı.

**Example: The following example gets the general information about the image including pixel format, image size, resolution, compression etc.**

``` java
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("c:\\temp\\sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    System.out.println("The pixel format: " + bmpImage.getRawDataFormat());
    System.out.println("The raw line size in bytes: " + bmpImage.getRawLineSize());
    System.out.println("The bitmap compression: " + bmpImage.getCompression());
    System.out.println("The bitmap width: " + bmpImage.getWidth());
    System.out.println("The bitmap height: " + bmpImage.getHeight());
    System.out.println("The number of bits per pixel: " + bmpImage.getBitsPerPixel());

    double hres = bmpImage.getHorizontalResolution();
    double vres = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + hres);
    System.out.println("The vertical resolution, in pixels per inch: " + vres);

    if (hres != 96.0 || vres != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanmayı düşünebilirsiniz.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

//Çıktı şöyle görünebilir:
//Piksel formatı: Rgb24Bpp, kullanılan kanallar: 8,8,8
//Ham satır boyutu (bayt cinsinden): 1500
//Bitmap sıkıştırması: 0
//Bitmap genişliği: 500
//Bitmap yüksekliği: 500
//Piksel başına bit sayısı: 24
//Yatay çözünürlük, inç başına piksel olarak: 96.012
//Dikey çözünürlük, inç başına piksel olarak: 96.012
//Çözünürlük değerlerini 96 dpi olarak ayarlayın
//Yatay çözünürlük, inç başına piksel olarak: 96.012
//Dikey çözünürlük, inç başına piksel olarak: 96.012
```

### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Bu özellik, [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin inç başına piksel cinsinden ölçülen yatay çözünürlüğünü kolayca almanızı veya ayarlamanızı sağlar. Uygulamalarında görüntü çözünürlüğü üzerinde hassas kontrol gerektiren geliştiriciler için idealdir.

**Returns:**
double - Yatay çözünürlük.

Not: Varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için \#setResolution(double, double).setResolution(double, double) yöntemini kullanmayı düşünebilirsiniz.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // BmpImage'in yatay ve dikey çözünürlüğünü alın
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// Yatay çözünürlük, inç başına piksel olarak: 0.0
// Dikey çözünürlük, inç başına piksel olarak: 0.0
// Çözünürlük değerlerini 96 dpi olarak ayarlayın
// Yatay çözünürlük, inç başına piksel olarak: 96.012
// Dikey çözünürlük, inç başına piksel olarak: 96.012
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Bu özellik, [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin inç başına piksel cinsinden ölçülen yatay çözünürlüğünü kolayca almanızı veya ayarlamanızı sağlar. Uygulamalarında görüntü çözünürlüğü üzerinde hassas kontrol gerektiren geliştiriciler için idealdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Yatay çözünürlük. |

--------------------

Not: Varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için \#setResolution(double, double).setResolution(double, double) yöntemini kullanmayı düşünebilirsiniz. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Bu özellik sayesinde bu [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin inç başına piksel cinsinden ölçülen dikey çözünürlüğünü kolayca alabilir veya ayarlayabilirsiniz. Uygulamalarında görüntü çözünürlüğü üzerinde hassas kontrol gerektiren geliştiriciler için mükemmeldir.

**Returns:**
double - Dikey çözünürlük.

--------------------

Not: Varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için \#setResolution(double, double).setResolution(double, double) yöntemini kullanmayı düşünebilirsiniz.

**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // BmpImage'in yatay ve dikey çözünürlüğünü alın
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// Yatay çözünürlük, inç başına piksel olarak: 0.0
// Dikey çözünürlük, inç başına piksel olarak: 0.0
// Çözünürlük değerlerini 96 dpi olarak ayarlayın
// Yatay çözünürlük, inç başına piksel olarak: 96.012
// Dikey çözünürlük, inç başına piksel olarak: 96.012
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Bu özellik sayesinde bu [RasterImage](../../com.aspose.imaging/rasterimage) nesnesinin inç başına piksel cinsinden ölçülen dikey çözünürlüğünü kolayca alabilir veya ayarlayabilirsiniz. Uygulamalarında görüntü çözünürlüğü üzerinde hassas kontrol gerektiren geliştiriciler için mükemmeldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | değer | double | Dikey çözünürlük. |

--------------------

Not: Varsayılan olarak bu değer her zaman 96'dır çünkü farklı platformlar ekran çözünürlüğünü döndüremez. Her iki çözünürlük değerini tek bir çağrıda güncellemek için \#setResolution(double, double).setResolution(double, double) yöntemini kullanmayı düşünebilirsiniz. |

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Bu örneğin alfa içerip içermediğini gösteren bir değer alır.

**Returns:**
boolean - bu örneğin alfa içerip içermediğini gösteren bir değer.
### setResolution(double dpiX, double dpiY) {#setResolution-double-double-}
```
public void setResolution(double dpiX, double dpiY)
```


[RasterImage](../../com.aspose.imaging/rasterimage) nesnenizin çözünürlüğünü bu kullanıcı dostu yöntemle zahmetsizce ayarlayın. Uygulamalarında görüntü çözünürlüğü üzerinde hassas kontrol arayan geliştiriciler için mükemmeldir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dpiX | double | The horizontal resolution, in dots per inch, of the [RasterImage](../../com.aspose.imaging/rasterimage). |
| dpiY | double | The vertical resolution, in dots per inch, of the [RasterImage](../../com.aspose.imaging/rasterimage). |


**Example: The following example shows how to set horizontal/vertical resolution of a BMP image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // BmpImage'in yatay ve dikey çözünürlüğünü alın
    double horizontalResolution = bmpImage.getHorizontalResolution();
    double verticalResolution = bmpImage.getVerticalResolution();
    System.out.println("The horizontal resolution, in pixels per inch: " + horizontalResolution);
    System.out.println("The vertical resolution, in pixels per inch: " + verticalResolution);

    if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
        // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
        System.out.println("Set resolution values to 96 dpi");
        bmpImage.setResolution(96.0, 96.0);

        System.out.println("The horizontal resolution, in pixels per inch: " + bmpImage.getHorizontalResolution());
        System.out.println("The vertical resolution, in pixels per inch: " + bmpImage.getVerticalResolution());
    }
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// Yatay çözünürlük, inç başına piksel olarak: 0.0
// Dikey çözünürlük, inç başına piksel olarak: 0.0
// Çözünürlük değerlerini 96 dpi olarak ayarlayın
// Yatay çözünürlük, inç başına piksel olarak: 96.012
// Dikey çözünürlük, inç başına piksel olarak: 96.012
```

### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Bu basit yöntemle varsayılan seçenekleri zahmetsizce alın. Varsayılan görüntü ayarlarına veya yapılandırmalarına hızlı erişim arayan geliştiriciler için idealdir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| argümanlar | java.lang.Object[] | Argümanlar. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
