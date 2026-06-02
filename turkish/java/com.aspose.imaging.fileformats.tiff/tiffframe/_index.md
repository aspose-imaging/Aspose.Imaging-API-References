---
title: "TiffFrame"
second_title: "Aspose.Imaging for Java API Referansı"
description: "tiff çerçevesi."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.fileformats.tiff/tiffframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public final class TiffFrame extends RasterCachedImage
```

tiff çerçevesi.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [TiffFrame(InputStream stream)](#TiffFrame-java.io.InputStream-) | Yeni bir `TiffFrame` sınıfı örneği başlatır. |
| [TiffFrame(InputStream stream, TiffOptions options)](#TiffFrame-java.io.InputStream-com.aspose.imaging.imageoptions.TiffOptions-) | Yeni bir `TiffFrame` sınıfı örneği başlatır. |
| [TiffFrame(String path)](#TiffFrame-java.lang.String-) | Yeni bir `TiffFrame` sınıfı örneği başlatır. |
| [TiffFrame(String path, TiffOptions options)](#TiffFrame-java.lang.String-com.aspose.imaging.imageoptions.TiffOptions-) | Yeni bir `TiffFrame` sınıfı örneği başlatır. |
| [TiffFrame(RasterImage image)](#TiffFrame-com.aspose.imaging.RasterImage-) | Yeni bir `TiffFrame` sınıfı örneği başlatır. |
| [TiffFrame(RasterImage image, TiffOptions options)](#TiffFrame-com.aspose.imaging.RasterImage-com.aspose.imaging.imageoptions.TiffOptions-) | Yeni bir `TiffFrame` sınıfı örneği başlatır. |
| [TiffFrame(TiffOptions options, int width, int height)](#TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-int-int-) | Yeni bir `TiffFrame` sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBackgroundColor()](#getBackgroundColor--) | Arka plan rengi için bir değer alır. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Arka plan rengi için bir değer ayarlar. |
| [hasAlpha()](#hasAlpha--) | Bu örneğin alfa içerip içermediğini gösteren bir değer alır. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit sayısını alır. |
| [getFrameOptions()](#getFrameOptions--) | Çerçeve oluşturma seçeneklerini alır. |
| [getHeight()](#getHeight--) | Görüntünün yüksekliğini alır. |
| [getWidth()](#getWidth--) | Görüntünün genişliğini alır. |
| [getHorizontalResolution()](#getHorizontalResolution--) | Bu `RasterImage`'in inç başına piksel cinsinden yatay çözünürlüğünü alır. |
| [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | Bu `RasterImage`'in inç başına piksel cinsinden yatay çözünürlüğünü ayarlar. |
| [getVerticalResolution()](#getVerticalResolution--) | Bu `RasterImage`'in inç başına piksel cinsinden dikey çözünürlüğünü alır. |
| [setVerticalResolution(double value)](#setVerticalResolution-double-) | Bu `RasterImage`'in inç başına piksel cinsinden dikey çözünürlüğünü ayarlar. |
| [getPathResources()](#getPathResources--) | Yol kaynaklarını alır. |
| [setPathResources(List<PathResource> value)](#setPathResources-java.util.List-com.aspose.imaging.fileformats.tiff.pathresources.PathResource--) | Yol kaynaklarını ayarlar. |
| [removeMetadata()](#removeMetadata--) | Bu görüntü örneğinin meta verilerini, bu IHasXmpData.XmpData ([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) ve `IHasExifData.ExifData`([IHasExifData.getExifData](../../com.aspose.imaging.exif/ihasexifdata\#getExifData)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-) IHasExifData.setExifData) değerlerini `null` olarak ayarlayarak kaldırır. |
| [getOriginalOptions()](#getOriginalOptions--) | Orijinal dosya ayarlarına dayalı seçenekleri alır. |
| [alignResolutions()](#alignResolutions--) | Yatay ve dikey çözünürlükleri eşitleyen yardımcı yöntem. |
| [copyFrame(TiffFrame tiffFrame)](#copyFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-) | Tüm çerçeveyi (kopyalarını) kopyalar. |
| [createFrameFrom(TiffFrame tiffFrame, TiffOptions options)](#createFrameFrom-com.aspose.imaging.fileformats.tiff.TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-) | Belirtilen `tiffFrame`'i, belirtilen `options` kullanarak oluşturur. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Görüntüyü yeniden boyutlandırır. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Görüntüyü döndürür, çevirir veya döndürüp çevirir. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Görüntüyü merkezin etrafında döndür. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Görüntüyü kırpar. |

## Example: This example shows how to create a TIFF image from scratch and save it to a file.

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createOptions =
        new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Her renk bileşeni için 8 bit ayarla.
createOptions.setBitsPerSample(new int[]{8, 8, 8});

// Big Endian bayt sırasını (Motorola) ayarla.
createOptions.setByteOrder(com.aspose.imaging.fileformats.tiff.enums.TiffByteOrder.BigEndian);

// LZW sıkıştırmasını ayarla.
createOptions.setCompression(com.aspose.imaging.fileformats.tiff.enums.TiffCompressions.Lzw);

// RGB renk modelini ayarla.
createOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);

// Tüm renk bileşenleri tek bir düzlemde saklanacak.
createOptions.setPlanarConfiguration(com.aspose.imaging.fileformats.tiff.enums.TiffPlanarConfigs.Contiguous);

// 100x100 piksel bir TIFF Çerçevesi oluştur.
// Bir çerçeve TiffImage içine dahil edilmişse, onu açıkça yok etmeniz gerekmediğini unutmayın.
// Konteyner yok edildiğinde tüm çerçeveler otomatik olarak yok edilecektir.
com.aspose.imaging.fileformats.tiff.TiffFrame firstFrame = new com.aspose.imaging.fileformats.tiff.TiffFrame(createOptions, 100, 100);

// Tüm çerçeveyi mavi‑sarı degrade ile doldur.
com.aspose.imaging.brushes.LinearGradientBrush gradientBrush = new com.aspose.imaging.brushes.LinearGradientBrush(
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(firstFrame.getWidth(), firstFrame.getHeight()),
        com.aspose.imaging.Color.getBlue(),
        com.aspose.imaging.Color.getYellow());

com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(firstFrame);
graphics.fillRectangle(gradientBrush, firstFrame.getBounds());

// Bir TIFF görüntüsü oluştur.
com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = new com.aspose.imaging.fileformats.tiff.TiffImage(firstFrame);
try {
    tiffImage.save(dir + "output.tif");
} finally {
    tiffImage.dispose();
}
```

### TiffFrame(InputStream stream) {#TiffFrame-java.io.InputStream-}
```
public TiffFrame(InputStream stream)
```


Yeni bir `TiffFrame` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Görüntüyü yüklemek ve çerçeve piksel ve palet verilerini başlatmak için akış. |

### TiffFrame(InputStream stream, TiffOptions options) {#TiffFrame-java.io.InputStream-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffFrame(InputStream stream, TiffOptions options)
```


Yeni bir `TiffFrame` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Görüntüyü yüklemek ve çerçeve piksel ve palet verilerini başlatmak için akış. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Yeni oluşturulan çerçeve için kullanılacak seçenekler. |

### TiffFrame(String path) {#TiffFrame-java.lang.String-}
```
public TiffFrame(String path)
```


Yeni bir `TiffFrame` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Görüntüyü yüklemek ve çerçeve piksel ve palet verilerini başlatmak için yol. |

### TiffFrame(String path, TiffOptions options) {#TiffFrame-java.lang.String-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffFrame(String path, TiffOptions options)
```


Yeni bir `TiffFrame` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| yol | java.lang.String | Görüntüyü yüklemek ve çerçeve piksel ve palet verilerini başlatmak için yol. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Yeni oluşturulan çerçeve için kullanılacak seçenekler. |

### TiffFrame(RasterImage image) {#TiffFrame-com.aspose.imaging.RasterImage-}
```
public TiffFrame(RasterImage image)
```


Yeni bir `TiffFrame` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Çerçeve piksel ve palet verilerini başlatmak için görüntü. |

### TiffFrame(RasterImage image, TiffOptions options) {#TiffFrame-com.aspose.imaging.RasterImage-com.aspose.imaging.imageoptions.TiffOptions-}
```
public TiffFrame(RasterImage image, TiffOptions options)
```


Yeni bir `TiffFrame` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Çerçeve piksel ve palet verilerini başlatmak için görüntü. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Yeni oluşturulan çerçeve için kullanılacak seçenekler. |

### TiffFrame(TiffOptions options, int width, int height) {#TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-int-int-}
```
public TiffFrame(TiffOptions options, int width, int height)
```


Yeni bir `TiffFrame` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Çerçeve seçenekleri. |
| genişlik | int | Genişlik. |
| yükseklik | int | Yükseklik. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Arka plan rengi için bir değer alır.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Arka plan rengi için bir değer ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Bu örneğin alfa içerip içermediğini gösteren bir değer alır.

**Returns:**
boolean - bu örnek alfa içeriyorsa `true`; aksi takdirde `false`.

**Example: The following example loads a TIFF image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";

String fileName = dir + "sample.tif";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    // Aktif TIFF çerçevesi alfa kanalına sahipse, tüm TIFF görüntüsü alfa kanalı olduğu kabul edilir.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, tiffImage.getRawDataFormat(), tiffImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", ++i, frame.getRawDataFormat(), frame.hasAlpha());
    }
} finally {
    image.dispose();
}

// Çıktı şöyle görünebilir:
// ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
// Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
```

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Görüntünün piksel başına bit sayısını alır.

**Returns:**
int - Görüntünün piksel başına bit sayısı.
### getFrameOptions() {#getFrameOptions--}
```
public TiffOptions getFrameOptions()
```


Çerçeve oluşturma seçeneklerini alır.

**Returns:**
[TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions)
### getHeight() {#getHeight--}
```
public int getHeight()
```


Görüntünün yüksekliğini alır.

**Returns:**
int - Görüntü yüksekliği.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Görüntünün genişliğini alır.

**Returns:**
int - Görüntü genişliği.
### getHorizontalResolution() {#getHorizontalResolution--}
```
public double getHorizontalResolution()
```


Bu `RasterImage`'in inç başına piksel cinsinden yatay çözünürlüğünü alır.

**Returns:**
double - Yatay çözünürlük.

**Example: The following example shows how to set horizontal/vertical resolution of a separate TIFF frame.**

``` java
String dir = "c:\\temp\\";

// Bir dosyadan TIFF görüntüsü yükle.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        // TiffFrame'in yatay ve dikey çözünürlüğünü al.
        double horizontalResolution = frame.getHorizontalResolution();
        double verticalResolution = frame.getVerticalResolution();
        System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
        System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);

        if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
            // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
            System.out.println("Set resolution values to 96 dpi");
            frame.setResolution(96.0, 96.0);

            System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
            System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);
        }

        ++i;
    }
} finally {
    image.dispose();
}
```

### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public void setHorizontalResolution(double value)
```


Bu `RasterImage`'in inç başına piksel cinsinden yatay çözünürlüğünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Yatay çözünürlük. |

### getVerticalResolution() {#getVerticalResolution--}
```
public double getVerticalResolution()
```


Bu `RasterImage`'in inç başına piksel cinsinden dikey çözünürlüğünü alır.

**Returns:**
double - Dikey çözünürlük.

**Example: The following example shows how to set horizontal/vertical resolution of a separate TIFF frame.**

``` java
String dir = "c:\\temp\\";

// Bir dosyadan TIFF görüntüsü yükle.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.tif");
try {
    com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) image;

    int i = 0;
    for (com.aspose.imaging.fileformats.tiff.TiffFrame frame : tiffImage.getFrames()) {
        // TiffFrame'in yatay ve dikey çözünürlüğünü al.
        double horizontalResolution = frame.getHorizontalResolution();
        double verticalResolution = frame.getVerticalResolution();
        System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
        System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);

        if (horizontalResolution != 96.0 || verticalResolution != 96.0) {
            // Her iki çözünürlük değerini tek bir çağrıda güncellemek için SetResolution yöntemini kullanın.
            System.out.println("Set resolution values to 96 dpi");
            frame.setResolution(96.0, 96.0);

            System.out.printf("The horizontal resolution of frame %s, pixels per inch: %s\r\n", i, horizontalResolution);
            System.out.printf("The vertical resolution, of frame %s, pixels per inch: %s\r\n", i, verticalResolution);
        }

        ++i;
    }
} finally {
    image.dispose();
}
```

### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public void setVerticalResolution(double value)
```


Bu `RasterImage`'in inç başına piksel cinsinden dikey çözünürlüğünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | Dikey çözünürlük. |

### getPathResources() {#getPathResources--}
```
public List<PathResource> getPathResources()
```


Yol kaynaklarını alır.

Değer: Yol kaynakları.

**Returns:**
java.util.List<com.aspose.imaging.fileformats.tiff.pathresources.PathResource> - yol kaynakları.

**Example: The following example shows how to retrieve paths from TIFF image and display their names in the console.**

``` java
try (TiffImage image = (TiffImage) Image.load("Sample.tif"))
{
    for (PathResource path : image.getActiveFrame().getPathResources())
    {
        System.out.println(path.getName());
    }
}
```


**Example: The following example shows how to modify already existing Clipping Paths.**
Aşağıdaki örnek, mevcut Kesme Yollarını nasıl değiştireceğinizi gösterir. Örneğin, görüntüde yalnızca bir Kesme Yolu tutabilirsiniz.
``` java
try (TiffImage image = (TiffImage) Image.load("Sample.tif"))
{
    List<PathResource> paths = image.getActiveFrame().getPathResources();
    image.getActiveFrame().setPathResources(Collections.singletonList(paths.get(0)));
    image.save();
}
```


**Example: Transfer Clipping Paths during export from TIFF to PSD image.**

``` java
try (Image image = Image.load("Sample.tif"))
{
    image.save("SampleWithPaths.psd", new PsdOptions());
}
```


**Example: Create Clipping Path manually.**

``` java
static void main()
{
    try (TiffImage image = (TiffImage)Image.load("Sample.tif"))
    {
        PathResource res = new PathResource();
        res.setBlockId((short) 2000);                                                  // Block Id according to Photoshop specification
        res.setName("My Clipping Path");                                               // Path name
        res.setRecords(createRecords(0.2f, 0.2f, 0.8f, 0.2f, 0.8f, 0.8f, 0.2f, 0.8f)); // Create path records using coordinates
                    
        image.getActiveFrame().setPathResources(Collections.singletonList(res));

        image.save("ImageWithPath.tif");
    }
}

private static List<VectorPathRecord> createRecords(float ... coordinates)
{
    List<VectorPathRecord>  records = createBezierRecords(coordinates);                                  // Create Bezier records using coordinates

    LengthRecord lr = new LengthRecord(); // LengthRecord required by Photoshop specification
    lr.setOpen(false);                    // Lets create closed path
    lr.setRecordCount(records.size());    // Record count in the path
                
    records.add(0, lr);

    return records;
}

private static List<VectorPathRecord> createBezierRecords(float[] coordinates)
{
    List<VectorPathRecord> l = new LinkedList<VectorPathRecord>();
                
    for (int index = 0; index < coordinates.length - 1; index += 2)
    {
        PointF pt = new PointF(coordinates[index], coordinates[index + 1]);
        BezierKnotRecord br = new BezierKnotRecord();
        br.setPathPoints(new PointF[] {pt, pt, pt});
        l.add(br);
    }
                    
    return l;
}

```

### setPathResources(List<PathResource> value) {#setPathResources-java.util.List-com.aspose.imaging.fileformats.tiff.pathresources.PathResource--}
```
public void setPathResources(List<PathResource> value)
```


Yol kaynaklarını ayarlar.

Değer: Yol kaynakları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<com.aspose.imaging.fileformats.tiff.pathresources.PathResource> | yol kaynakları. |

### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Bu görüntü örneğinin meta verilerini, bu IHasXmpData.XmpData ([IHasXmpData.getXmpData](../../com.aspose.imaging.xmp/ihasxmpdata\#getXmpData)/[IHasXmpData.setXmpData(XmpPacketWrapper)](../../com.aspose.imaging.xmp/ihasxmpdata\#setXmpData-XmpPacketWrapper-)) ve `IHasExifData.ExifData`([IHasExifData.getExifData](../../com.aspose.imaging.exif/ihasexifdata\#getExifData)/[IHasExifData.setExifData(ExifData)](../../com.aspose.imaging.exif/ihasexifdata\#setExifData-ExifData-) IHasExifData.setExifData) değerlerini `null` olarak ayarlayarak kaldırır.

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Orijinal dosya ayarlarına dayalı seçenekleri alır. Bu, orijinal görüntünün bit derinliği ve diğer parametrelerinin değişmeden kalmasına yardımcı olabilir. Örneğin, 1 bit piksel başına sahip siyah-beyaz bir PNG görüntüsü yükleyip ardından [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) yöntemiyle kaydederseniz, 8 bit piksel başına çıkış PNG görüntüsü oluşur. Bunu önlemek ve PNG görüntüsünü 1 bit piksel başına kaydetmek için bu yöntemi kullanarak ilgili kaydetme seçeneklerini alın ve bunları ikinci parametre olarak [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) yöntemine geçirin.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### alignResolutions() {#alignResolutions--}
```
public void alignResolutions()
```


Yatay ve dikey çözünürlükleri eşitleyen yardımcı yöntem.

### copyFrame(TiffFrame tiffFrame) {#copyFrame-com.aspose.imaging.fileformats.tiff.TiffFrame-}
```
public static TiffFrame copyFrame(TiffFrame tiffFrame)
```


Tüm çerçeveyi (kopyalarını) kopyalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tiffFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Kopyalanacak tiff çerçevesi. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The newly copied tiff frame.
### createFrameFrom(TiffFrame tiffFrame, TiffOptions options) {#createFrameFrom-com.aspose.imaging.fileformats.tiff.TiffFrame-com.aspose.imaging.imageoptions.TiffOptions-}
```
public static TiffFrame createFrameFrom(TiffFrame tiffFrame, TiffOptions options)
```


Belirtilen `options` kullanılarak belirtilen `tiffFrame`'den çerçeve oluşturur. Piksel verileri korunur ancak istenen formata dönüştürülür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tiffFrame | [TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) | Oluşturulacak tiff çerçevesi. |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | Kullanılacak yeni seçenekler. |

**Returns:**
[TiffFrame](../../com.aspose.imaging.fileformats.tiff/tiffframe) - The newly created frame.

**Example: The following example shows how to create a grayscale copy of an existing frame and add it to a TIFF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

// Kalıcı, geçici olmayan bir dosya kaynağı oluştur.
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource(dir + "multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Görüntünün sol üst köşesinden sağ alt köşesine doğru lineer degrade.
    com.aspose.imaging.brushes.LinearGradientBrush brush =
            new com.aspose.imaging.brushes.LinearGradientBrush(
                    new com.aspose.imaging.Point(0, 0),
                    new com.aspose.imaging.Point(tiffImage.getWidth(), tiffImage.getHeight()),
                    com.aspose.imaging.Color.getRed(),
                    com.aspose.imaging.Color.getGreen());

    // Aktif çerçeveyi lineer degrade fırçası ile doldur.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(tiffImage.getActiveFrame());
    gr.fillRectangle(brush, tiffImage.getBounds());

    // Gri tonlama seçenekleri
    com.aspose.imaging.imageoptions.TiffOptions createTiffFrameOptions
            = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
    createTiffFrameOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));
    createTiffFrameOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.MinIsBlack);
    createTiffFrameOptions.setBitsPerSample(new int[]{8});

    // Aktif çerçevenin gri tonlamalı bir kopyasını oluştur.
    // Piksel verileri korunur ancak istenen formata dönüştürülür.
    com.aspose.imaging.fileformats.tiff.TiffFrame grayscaleFrame
            = com.aspose.imaging.fileformats.tiff.TiffFrame.createFrameFrom(tiffImage.getActiveFrame(), createTiffFrameOptions);

    // Yeni oluşturulan çerçeveyi TIFF görüntüsüne ekle.
    tiffImage.addFrame(grayscaleFrame);

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Görüntüyü yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Görüntüyü döndürür, çevirir veya döndürüp çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateFlipType | int | Döndürme çevirme türü. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Görüntüyü merkezin etrafında döndür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Dönüş açısı dereceler cinsindendir. Pozitif değerler saat yönünde dönecektir. |
| resizeProportionally | boolean | Eğer `true` olarak ayarlanırsa, görüntü boyutunuz döndürülmüş dikdörtgen (köşe noktaları) projeksiyonlarına göre değişir; diğer durumda boyutlar dokunulmaz kalır ve yalnızca iç görüntü içeriği döndürülür. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Arka planın rengi. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Görüntüyü kırpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |

