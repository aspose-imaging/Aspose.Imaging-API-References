---
title: "Görüntü"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Görüntü, tüm görüntü türleri için temel sınıftır."
type: docs
weight: 56
url: /tr/java/com.aspose.imaging/image/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter)

**All Implemented Interfaces:**
[com.aspose.imaging.IObjectWithBounds](../../com.aspose.imaging/iobjectwithbounds), com.aspose.internal.progressmanagement.IProgressInformer, com.aspose.internal.progressmanagement.IProgressEventHandler, [com.aspose.imaging.IMetadataContainer](../../com.aspose.imaging/imetadatacontainer)
```
public abstract class Image extends DataStreamSupporter implements IObjectWithBounds, IProgressInformer, IProgressEventHandler, IMetadataContainer
```

Görüntü, tüm görüntü türleri için temel sınıftır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [canLoad(String filePath)](#canLoad-java.lang.String-) | Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini belirler. |
| [canLoad(String filePath, LoadOptions loadOptions)](#canLoad-java.lang.String-com.aspose.imaging.LoadOptions-) | Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak belirler. |
| [canLoad(InputStream stream)](#canLoad-java.io.InputStream-) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini belirler. |
| [canLoad(InputStream stream, LoadOptions loadOptions)](#canLoad-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen `loadOptions` kullanılarak belirler. |
| [create(ImageOptionsBase imageOptions, int width, int height)](#create-com.aspose.imaging.ImageOptionsBase-int-int-) | Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur. |
| [create(ImageOptionsBase imageOptions, int width, int height, int[] pixels)](#create-com.aspose.imaging.ImageOptionsBase-int-int-int---) | Sağlanan piksel dizisinden bir [RasterImage](../../com.aspose.imaging/rasterimage) örneği oluşturur. |
| [create(Image[] images)](#create-com.aspose.imaging.Image---) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur |
| [create(MultipageCreateOptions multipageCreateOptions)](#create-com.aspose.imaging.imageoptions.MultipageCreateOptions-) | Belirtilen çok sayfalı oluşturma seçeneklerini oluşturur. |
| [create(String[] files, boolean throwExceptionOnLoadError)](#create-java.lang.String---boolean-) | Belirtilen dosyaları içeren çok sayfalı görüntüyü oluşturur. |
| [create(String[] files)](#create-java.lang.String---) | Belirtilen dosyaları içeren çok sayfalı görüntüyü oluşturur. |
| [create(Image[] images, boolean disposeImages)](#create-com.aspose.imaging.Image---boolean-) | Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur. |
| [getFileFormat(String filePath)](#getFileFormat-java.lang.String-) | Dosya biçimini alır. |
| [load(String filePath, LoadOptions loadOptions)](#load-java.lang.String-com.aspose.imaging.LoadOptions-) | Belirtilen dosya yolundan veya URL'den yeni bir görüntü yükler. |
| [load(String filePath)](#load-java.lang.String-) | Belirtilen dosya yolundan veya URL'den yeni bir görüntü yükler. |
| [load(RandomAccessFile file, LoadOptions loadOptions)](#load-java.io.RandomAccessFile-com.aspose.imaging.LoadOptions-) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(RandomAccessFile file)](#load-java.io.RandomAccessFile-) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(InputStream stream, LoadOptions loadOptions)](#load-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Belirtilen akıştan yeni bir görüntü yükler. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Belirtilen akıştan yeni bir görüntü yükler. |
| [getFileFormat(InputStream stream)](#getFileFormat-java.io.InputStream-) | Dosya biçimini alır. |
| [getFittingRectangle(Rectangle rectangle, int width, int height)](#getFittingRectangle-com.aspose.imaging.Rectangle-int-int-) | Geçerli görüntüyü saran dikdörtgeni alır. |
| [getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)](#getFittingRectangle-com.aspose.imaging.Rectangle-int---int-int-) | Geçerli görüntüyü saran dikdörtgeni alır. |
| [getProportionalWidth(int width, int height, int newHeight)](#getProportionalWidth-int-int-int-) | Orantılı bir genişlik alır. |
| [getProportionalHeight(int width, int height, int newWidth)](#getProportionalHeight-int-int-int-) | Orantılı bir yükseklik alır. |
| [removeMetadata()](#removeMetadata--) | Meta verileri kaldırır. |
| [trySetMetadata(IImageMetadataFormat metadata)](#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-) | Bu [Image](../../com.aspose.imaging/image) örneği destekliyor ve [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) türünü uyguluyorsa bir `metadata` örneği ayarlamayı dener. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Görüntünün piksel başına bit sayısını alır. |
| [getBounds()](#getBounds--) | Görüntünün sınırlarını alır. |
| [getContainer()](#getContainer--) | `Image` konteynerini alır. |
| [getPalette()](#getPalette--) | Renk paletini alır. |
| [setPalette(IColorPalette value)](#setPalette-com.aspose.imaging.IColorPalette-) | Renk paletini ayarlar. |
| [isUsePalette()](#isUsePalette--) | Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır. |
| [getSize()](#getSize--) | Görüntü boyutunu alır. |
| [getInterruptMonitor()](#getInterruptMonitor--) | Kesinti izleyicisini alır. |
| [setInterruptMonitor(InterruptMonitor value)](#setInterruptMonitor-com.aspose.imaging.multithreading.InterruptMonitor-) | Kesinti izleyicisini ayarlar. |
| [getBufferSizeHint()](#getBufferSizeHint--) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu gösteren tampon boyutu ipucunu alır. |
| [setBufferSizeHint(int value)](#setBufferSizeHint-int-) | Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu gösteren tampon boyutu ipucunu ayarlar. |
| [isAutoAdjustPalette()](#isAutoAdjustPalette--) | Otomatik palet ayarlamasının yapılıp yapılmadığını gösteren bir değeri alır. |
| [setAutoAdjustPalette(boolean value)](#setAutoAdjustPalette-boolean-) | Otomatik palet ayarlamasının yapılıp yapılmadığını gösteren bir değeri ayarlar. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değeri alır. |
| [getFileFormat()](#getFileFormat--) | Bu kullanıcı dostu özellik sayesinde dosya formatı değerini kolayca alabilirsiniz. |
| [getBackgroundColor()](#getBackgroundColor--) | Arka plan rengi için bir değeri alır veya ayarlar. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Arka plan rengi için bir değeri alır veya ayarlar. |
| [getMetadata()](#getMetadata--) | Görüntünün meta verilerini alır. |
| [getExifData()](#getExifData--) | Exif verilerini alır. |
| [setExifData(ExifData value)](#setExifData-com.aspose.imaging.exif.ExifData-) | Exif verilerini ayarlar. |
| [getXmpData()](#getXmpData--) | Xmp verilerini alır. |
| [setXmpData(XmpPacketWrapper value)](#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-) | Xmp verilerini ayarlar. |
| [getIProgressEventHandler()](#getIProgressEventHandler--) | İlerleme olayı işleyicisinin bilgilerini alır. |
| [getProgressEventHandlerInfo()](#getProgressEventHandlerInfo--) | İlerleme olayı işleyicisinin bilgilerini alır. |
| [canSave(ImageOptionsBase options)](#canSave-com.aspose.imaging.ImageOptionsBase-) | Görüntünün, verilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler. |
| [resize(int newWidth, int newHeight)](#resize-int-int-) | Görüntüyü yeniden boyutlandırır. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Görüntüyü yeniden boyutlandırır. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Görüntüyü yeniden boyutlandırır. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Varsayılan seçenekleri alır. |
| [getOriginalOptions()](#getOriginalOptions--) | Orijinal dosya ayarlarına dayalı seçenekleri alır. |
| [resizeWidthProportionally(int newWidth)](#resizeWidthProportionally-int-) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resizeHeightProportionally(int newHeight)](#resizeHeightProportionally-int-) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [resizeWidthProportionally(int newWidth, ImageResizeSettings settings)](#resizeWidthProportionally-int-com.aspose.imaging.ImageResizeSettings-) | Genişliği orantılı olarak yeniden boyutlandırır. |
| [resizeHeightProportionally(int newHeight, ImageResizeSettings settings)](#resizeHeightProportionally-int-com.aspose.imaging.ImageResizeSettings-) | Yüksekliği orantılı olarak yeniden boyutlandırır. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Görüntüyü döndürür, çevirir veya döndürüp çevirir. |
| [rotate(float angle)](#rotate-float-) | Görüntüyü merkezin etrafında döndür. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Belirtilen dikdörtgeni kırpar. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Görüntüyü kaydırmalarla kırpar. |
| [save()](#save--) | Görüntü verisini temel akışa kaydeder. |
| [save(String filePath)](#save-java.lang.String-) | Görüntüyü belirtilen dosya konumuna kaydeder. |
| [save(String filePath, ImageOptionsBase options)](#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| [save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)](#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| [save(RandomAccessFile file, ImageOptionsBase options)](#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-) | Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder. |
| [save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| [save(OutputStream stream, ImageOptionsBase optionsBase)](#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| [save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)](#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-) | Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Görüntü paletini ayarlar. |
| [getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber)](#getSerializedStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-int---) | aps formatına dönüştürür. |

## Example: This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance.
Bu örnek, BmpOptions örneğinin Source özelliğiyle belirtilen bir disk konumunda yeni bir Image dosyası oluşturur. Gerçek görüntüyü oluşturmadan önce BmpOptions örneği için birkaç özellik ayarlanır. Özellikle bu durumda gerçek disk konumuna işaret eden Source özelliği.
``` java
// BmpOptions bir örneği oluşturun ve çeşitli özelliklerini ayarlayın
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// FileCreateSource bir örneği oluşturun ve bunu BmpOptions örneği için Source olarak atayın
// İkinci Boolean parametresi, oluşturulacak dosyanın IsTemporal olup olmadığını belirler
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Image bir örneği oluşturun ve Create metodunu çağırarak BmpOptions örneğiyle başlatın
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Biraz görüntü işleme yapın

    // Tüm değişiklikleri kaydedin
    image.save();
} finally {
    image.dispose();
}
```


## Example: Resize image using specific Resize Type.

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


## Example: Determine if the palette is used by the image.

``` java
try (Image image = Image.load("Sample.bmp"))
{
    if (image.isUsePalette())
    {
        System.out.println("The palette is used by the image");
    }
}
```

### canLoad(String filePath) {#canLoad-java.lang.String-}
```
public static boolean canLoad(String filePath)
```


Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya yolu. |

**Returns:**
boolean - belirtilen dosyadan görüntü yüklenebiliyorsa `true`; aksi takdirde `false`.

**Example: This example determines whether image can be loaded from a file.**

``` java

// Dosyaya mutlak bir yol kullanın
boolean canLoad = com.aspose.imaging.Image.canLoad("c:\\temp\\sample.gif");
```

### canLoad(String filePath, LoadOptions loadOptions) {#canLoad-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public static boolean canLoad(String filePath, LoadOptions loadOptions)
```


Belirtilen dosya yolundan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen açma seçenekleri kullanılarak belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya yolu. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

**Returns:**
boolean - belirtilen dosyadan görüntü yüklenebiliyorsa `true`; aksi takdirde `false`.
### canLoad(InputStream stream) {#canLoad-java.io.InputStream-}
```
public static boolean canLoad(InputStream stream)
```


Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Yüklenecek akış. |

**Returns:**
boolean - belirtilen akıştan görüntü yüklenebiliyorsa `true`; aksi takdirde `false`.

**Example: This example determines whether image can be loaded from a file stream.**

``` java
String dir = "c:\\temp\\";

boolean canLoad;

// Bir dosya akışı kullanın
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.bmp");
try {
    canLoad = com.aspose.imaging.Image.canLoad(stream);
} finally {
    stream.close();
}

// Aşağıdaki veri geçerli bir görüntü akışı değildir, bu yüzden CanLoad `false` döndürür.
byte[] imageData = new byte[]{0, 0, 0, 0, 0, 0, 0, 0};
stream = new java.io.ByteArrayInputStream(imageData);
{
    canLoad = com.aspose.imaging.Image.canLoad(stream);
}
```

### canLoad(InputStream stream, LoadOptions loadOptions) {#canLoad-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static boolean canLoad(InputStream stream, LoadOptions loadOptions)
```


Belirtilen akıştan görüntünün yüklenip yüklenemeyeceğini ve isteğe bağlı olarak belirtilen `loadOptions` kullanılarak belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Yüklenecek akış. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

**Returns:**
boolean - belirtilen akıştan görüntü yüklenebiliyorsa `true`; aksi takdirde `false`.
### create(ImageOptionsBase imageOptions, int width, int height) {#create-com.aspose.imaging.ImageOptionsBase-int-int-}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height)
```


Belirtilen oluşturma seçeneklerini kullanarak yeni bir görüntü oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Görüntü seçenekleri. |
| genişlik | int | Genişlik. |
| yükseklik | int | Yükseklik. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The newly created image.

**Example: This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance.**
Bu örnek, BmpOptions örneğinin Source özelliğiyle belirtilen bir disk konumunda yeni bir Image dosyası oluşturur. Gerçek görüntüyü oluşturmadan önce BmpOptions örneği için birkaç özellik ayarlanır. Özellikle bu durumda gerçek disk konumuna işaret eden Source özelliği.
``` java
// BmpOptions bir örneği oluşturun ve çeşitli özelliklerini ayarlayın
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// FileCreateSource bir örneği oluşturun ve bunu BmpOptions örneği için Source olarak atayın
// İkinci Boolean parametresi, oluşturulacak dosyanın IsTemporal olup olmadığını belirler
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Image bir örneği oluşturun ve Create metodunu çağırarak BmpOptions örneğiyle başlatın
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Biraz görüntü işleme yapın

    // Tüm değişiklikleri kaydedin
    image.save();
} finally {
    image.dispose();
}
```

### create(ImageOptionsBase imageOptions, int width, int height, int[] pixels) {#create-com.aspose.imaging.ImageOptionsBase-int-int-int---}
```
public static Image create(ImageOptionsBase imageOptions, int width, int height, int[] pixels)
```


Sağlanan piksel dizisinden bir [RasterImage](../../com.aspose.imaging/rasterimage) örneği oluşturur. Belirtilen genişlik ve yüksekliğin piksel verisinin boyutlarıyla eşleştiğini doğrular. Bu yöntem yalnızca kütüphane Lisanslı modda iken kullanılabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Bir [RasterImage](../../com.aspose.imaging/rasterimage) oluşturmak için kullanılan seçenekler. |
| width | int | [RasterImage](../../com.aspose.imaging/rasterimage) genişliği. |
| height | int | [RasterImage](../../com.aspose.imaging/rasterimage) yüksekliği. |
| pikseller | int[] | Görüntüyü doldurmak için kullanılan piksel değerleri dizisi. |

**Returns:**
[Image](../../com.aspose.imaging/image) - A [RasterImage](../../com.aspose.imaging/rasterimage) populated with the provided pixel data.
### create(Image[] images) {#create-com.aspose.imaging.Image---}
```
public static Image create(Image[] images)
```


Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.imaging/image) | Görüntüler. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The Image as IMultipageImage
### create(MultipageCreateOptions multipageCreateOptions) {#create-com.aspose.imaging.imageoptions.MultipageCreateOptions-}
```
public static Image create(MultipageCreateOptions multipageCreateOptions)
```


Belirtilen çok sayfalı oluşturma seçeneklerini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| multipageCreateOptions | [MultipageCreateOptions](../../com.aspose.imaging.imageoptions/multipagecreateoptions) | Çok sayfalı oluşturma seçenekleri. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(String[] files, boolean throwExceptionOnLoadError) {#create-java.lang.String---boolean-}
```
public static Image create(String[] files, boolean throwExceptionOnLoadError)
```


Belirtilen dosyaları içeren çok sayfalı görüntüyü oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosyalar | java.lang.String[] | Dosyalar. |
| throwExceptionOnLoadError | boolean | eğer `true` olarak ayarlanırsa [yükleme hatasında istisna fırlat]. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(String[] files) {#create-java.lang.String---}
```
public static Image create(String[] files)
```


Belirtilen dosyaları içeren çok sayfalı görüntüyü oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosyalar | java.lang.String[] | Dosyalar. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The multipage image
### create(Image[] images, boolean disposeImages) {#create-com.aspose.imaging.Image---boolean-}
```
public static Image create(Image[] images, boolean disposeImages)
```


Belirtilen görüntüleri sayfa olarak kullanarak yeni bir görüntü oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| images | [Image\[\]](../../com.aspose.imaging/image) | Görüntüler. |
| disposeImages | boolean | eğer `true` olarak ayarlanırsa [görüntüleri serbest bırak]. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The Image as IMultipageImage
### getFileFormat(String filePath) {#getFileFormat-java.lang.String-}
```
public static long getFileFormat(String filePath)
```


Dosya biçimini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | filePath | java.lang.String | Dosya yolu. |

Belirlenen dosya formatı, belirtilen görüntünün yüklenebileceği anlamına gelmez. Dosyanın yüklenip yüklenemeyeceğini belirlemek için CanLoad yöntemi aşırı yüklemelerinden birini kullanın. |

**Returns:**
long - Belirlenen dosya formatı.

**Example: This example shows how to determine the image format without loading the entire image from a file.**

``` java
String dir = "c:\\temp\\";

// Dosyaya mutlak bir yol kullanın
long format = com.aspose.imaging.Image.getFileFormat(dir + "sample.gif");

// Dosya formatının bir dize temsili.
String strFormat;
if (format == com.aspose.imaging.FileFormat.Bmp) {
    strFormat = "BMP";
} else if (format == com.aspose.imaging.FileFormat.Gif) {
    strFormat = "GIF";
} else if (format == com.aspose.imaging.FileFormat.Dicom) {
    strFormat = "DICOM";
} else if (format == com.aspose.imaging.FileFormat.Djvu) {
    strFormat = "DJVU";
} else if (format == com.aspose.imaging.FileFormat.Dng) {
    strFormat = "DNG";
} else if (format == com.aspose.imaging.FileFormat.Png) {
    strFormat = "PNG";
} else if (format == com.aspose.imaging.FileFormat.Jpeg) {
    strFormat = "JPEG";
} else if (format == com.aspose.imaging.FileFormat.Jpeg2000) {
    strFormat = "JPEG2000";
} else if (format == com.aspose.imaging.FileFormat.Psd) {
    strFormat = "PSD";
} else if (format == com.aspose.imaging.FileFormat.Tiff) {
    strFormat = "Tiff";
} else if (format == com.aspose.imaging.FileFormat.Webp) {
    strFormat = "WEBP";
} else if (format == com.aspose.imaging.FileFormat.Cdr) {
    strFormat = "CDR";
} else if (format == com.aspose.imaging.FileFormat.Cmx) {
    strFormat = "CMX";
} else if (format == com.aspose.imaging.FileFormat.Emf) {
    strFormat = "EMF";
} else if (format == com.aspose.imaging.FileFormat.Wmf) {
    strFormat = "WMF";
} else if (format == com.aspose.imaging.FileFormat.Svg) {
    strFormat = "SVG";
} else if (format == com.aspose.imaging.FileFormat.Odg) {
    strFormat = "ODG";
} else if (format == com.aspose.imaging.FileFormat.Eps) {
    strFormat = "EPS";
} else {
    strFormat = "UNDEFINED";
}

System.out.println("The file format is " + strFormat);
```

### load(String filePath, LoadOptions loadOptions) {#load-java.lang.String-com.aspose.imaging.LoadOptions-}
```
public static Image load(String filePath, LoadOptions loadOptions)
```


Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler. `filePath` bir dosya yolu ise yöntem sadece dosyayı açar. `filePath` bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak depolar ve açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Görüntünün yükleneceği dosya yolu veya URL. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(String filePath) {#load-java.lang.String-}
```
public static Image load(String filePath)
```


Belirtilen dosya yolu veya URL'den yeni bir görüntü yükler. `filePath` bir dosya yolu ise yöntem sadece dosyayı açar. `filePath` bir URL ise yöntem dosyayı indirir, geçici bir dosya olarak depolar ve açar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Görüntünün yükleneceği dosya yolu veya URL. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.

**Example: This example demonstrates the loading of an existing Image file into an instance of com.**
Bu örnek, belirtilen dosya yolunu kullanarak mevcut bir Image dosyasının com.aspose.imaging.Image örneğine yüklenmesini gösterir.
``` java
// Image örneği oluşturun ve disk konumundaki mevcut bir görüntü dosyasıyla başlatın.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Bazı görüntü işleme işlemleri yapın.
} finally {
    image.dispose();
}
```

### load(RandomAccessFile file, LoadOptions loadOptions) {#load-java.io.RandomAccessFile-com.aspose.imaging.LoadOptions-}
```
public static Image load(RandomAccessFile file, LoadOptions loadOptions)
```


Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya | java.io.RandomAccessFile | Görüntünün yükleneceği dosya. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(RandomAccessFile file) {#load-java.io.RandomAccessFile-}
```
public static Image load(RandomAccessFile file)
```


Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya | java.io.RandomAccessFile | Görüntünün yükleneceği dosya. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(InputStream stream, LoadOptions loadOptions) {#load-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static Image load(InputStream stream, LoadOptions loadOptions)
```


Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Görüntünün yükleneceği akış. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Yükleme seçenekleri. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static Image load(InputStream stream)
```


Belirtilen akıştan yeni bir görüntü yükler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Görüntünün yükleneceği akış. |

**Returns:**
[Image](../../com.aspose.imaging/image) - The loaded image.

**Example: This example demonstrates the use of InputStream object to load an existing Image file**

``` java
// FileInputStream sınıfının bir örneğini oluşturun
java.io.InputStream stream = new java.io.FileInputStream("C:\\temp\\sample.bmp");
try {
    // Image sınıfının bir örneğini oluşturun ve Load metodunu çağırarak FileStream nesnesi aracılığıyla mevcut bir dosyayı yükleyin
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load(stream);
    try {
        // Bazı görüntü işleme işlemleri yapın.
    } finally {
        image.dispose();
    }
} finally {
    stream.close();
}
```

### getFileFormat(InputStream stream) {#getFileFormat-java.io.InputStream-}
```
public static long getFileFormat(InputStream stream)
```


Dosya biçimini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
|  | akış | java.io.InputStream | Akış. |

Belirlenen dosya formatı, belirtilen görüntünün yüklenebileceği anlamına gelmez. Akışın yüklenip yüklenemeyeceğini belirlemek için CanLoad metodunun bir aşırı yüklemesini kullanın. |

**Returns:**
long - Belirlenen dosya formatı.

**Example: This example shows how to determine the image format without loading the entire image from a file stream.**

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

String dir = "c:\\temp\\";

// Bir dosya akışı kullanın
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.bmp");
{
    long format = com.aspose.imaging.Image.getFileFormat(stream);
    System.out.println("The file format is " + utils.getFileFormatString(format));
}

// Aşağıdaki veri geçerli bir görüntü akışı değildir, bu yüzden GetFileFormat FileFormat.Undefined döndürür.
byte[] imageData = new byte[]{0, 0, 0, 0, 0, 0, 0, 0};
stream = new java.io.ByteArrayInputStream(imageData);
{
    long format = com.aspose.imaging.Image.getFileFormat(stream);
    System.out.println("The file format is " + utils.getFileFormatString(format));
}

// Çıktı şöyle görünebilir:
// Dosya formatı BMP'dir
// Dosya formatı TANIMSIZDIR
```

### getFittingRectangle(Rectangle rectangle, int width, int height) {#getFittingRectangle-com.aspose.imaging.Rectangle-int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int width, int height)
```


Geçerli görüntüyü saran dikdörtgeni alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Uygun dikdörtgeni elde etmek için dikdörtgen. |
| genişlik | int | Nesnenin genişliği. |
| yükseklik | int | Nesnenin yüksekliği. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height) {#getFittingRectangle-com.aspose.imaging.Rectangle-int---int-int-}
```
public static Rectangle getFittingRectangle(Rectangle rectangle, int[] pixels, int width, int height)
```


Geçerli görüntüyü saran dikdörtgeni alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Uygun dikdörtgeni elde etmek için dikdörtgen. |
| pikseller | int[] | 32-bit ARGB pikselleri. |
| genişlik | int | Nesnenin genişliği. |
| yükseklik | int | Nesnenin yüksekliği. |

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The fitting rectangle or exception if no fitting rectangle can be found.
### getProportionalWidth(int width, int height, int newHeight) {#getProportionalWidth-int-int-int-}
```
public static int getProportionalWidth(int width, int height, int newHeight)
```


Orantılı bir genişlik alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Genişlik. |
| yükseklik | int | Yükseklik. |
| newHeight | int | Yeni yükseklik. |

**Returns:**
int - Orantılı genişlik.
### getProportionalHeight(int width, int height, int newWidth) {#getProportionalHeight-int-int-int-}
```
public static int getProportionalHeight(int width, int height, int newWidth)
```


Orantılı bir yükseklik alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| genişlik | int | Genişlik. |
| yükseklik | int | Yükseklik. |
| newWidth | int | Yeni genişlik. |

**Returns:**
int - Orantılı yükseklik.
### removeMetadata() {#removeMetadata--}
```
public void removeMetadata()
```


Meta verileri kaldırır.

### trySetMetadata(IImageMetadataFormat metadata) {#trySetMetadata-com.aspose.imaging.metadata.IImageMetadataFormat-}
```
public boolean trySetMetadata(IImageMetadataFormat metadata)
```


Bu [Image](../../com.aspose.imaging/image) örneği destekliyor ve [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) türünü uyguluyorsa bir `metadata` örneği ayarlamayı dener.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| metadata | [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) | metadata. |

**Returns:**
boolean - True, eğer [Image](../../com.aspose.imaging/image) örneği [IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat) tipini destekliyor ve uyguluyorsa; aksi takdirde, false.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public abstract int getBitsPerPixel()
```


Görüntünün piksel başına bit sayısını alır.

**Returns:**
int - Görüntünün piksel başına bit sayısı.
### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Görüntünün sınırlarını alır.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - The image bounds.
### getContainer() {#getContainer--}
```
public Image getContainer()
```


`Image` konteynerini alır.

Değer: `Image` kapsayıcısı.

Bu özellik null değilse, görüntünün başka bir görüntünün içinde bulunduğunu gösterir.

**Returns:**
[Image](../../com.aspose.imaging/image)
### getPalette() {#getPalette--}
```
public IColorPalette getPalette()
```


Renk paletini alır. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz.

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### setPalette(IColorPalette value) {#setPalette-com.aspose.imaging.IColorPalette-}
```
public void setPalette(IColorPalette value)
```


Renk paletini ayarlar. Renk paleti, pikseller doğrudan temsil edildiğinde kullanılmaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Renk paleti. |

### isUsePalette() {#isUsePalette--}
```
public boolean isUsePalette()
```


Görüntü paletinin kullanılıp kullanılmadığını gösteren bir değeri alır.

Değer: `true` eğer palet görüntüde kullanılıyorsa; aksi takdirde, `false`.

**Returns:**
boolean - görüntü paletinin kullanılıp kullanılmadığını belirten bir değer.

**Example: Determine if the palette is used by the image.**

``` java
try (Image image = Image.load("Sample.bmp"))
{
    if (image.isUsePalette())
    {
        System.out.println("The palette is used by the image");
    }
}
```

### getSize() {#getSize--}
```
public Size getSize()
```


Görüntü boyutunu alır.

**Returns:**
[Size](../../com.aspose.imaging/size) - The image size.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Bir dosya akışından DJVU görüntüsü yükleyin.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//Çıktı şöyle görünebilir:
//Toplam sayfa sayısı: 2
//Etkin sayfa numarası:    1
//İlk sayfa numarası:     1
//Son sayfa numarası:      2
//--------------------------------------------------
//Sayfa numarası:     1
//Sayfa boyutu:       { Width = 2481, Height = 3508}
//Sayfa ham formatı: RgbIndexed1Bpp, kullanılan kanallar: 1
//--------------------------------------------------
//Sayfa numarası:     2
//Sayfa boyutu:       { Width = 2481, Height = 3508}
//Sayfa ham formatı: RgbIndexed1Bpp, kullanılan kanallar: 1
```

### getInterruptMonitor() {#getInterruptMonitor--}
```
public InterruptMonitor getInterruptMonitor()
```


Kesinti izleyicisini alır.

**Returns:**
[InterruptMonitor](../../com.aspose.imaging.multithreading/interruptmonitor) - the interrupt monitor.
### setInterruptMonitor(InterruptMonitor value) {#setInterruptMonitor-com.aspose.imaging.multithreading.InterruptMonitor-}
```
public void setInterruptMonitor(InterruptMonitor value)
```


Kesinti izleyicisini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [InterruptMonitor](../../com.aspose.imaging.multithreading/interruptmonitor) | kesme izleyicisi. |

### getBufferSizeHint() {#getBufferSizeHint--}
```
public final int getBufferSizeHint()
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu gösteren tampon boyutu ipucunu alır.

Değer: Bellek boyutu ipucu, megabayt cinsinden. Pozitif olmayan değer, dahili tamponlar için bellek sınırlaması olmadığı anlamına gelir

**Returns:**
int - tampon boyutu ipucu, tüm dahili tamponlar için tanımlanan maksimum izin verilen boyut.
### setBufferSizeHint(int value) {#setBufferSizeHint-int-}
```
public final void setBufferSizeHint(int value)
```


Tüm iç tamponlar için tanımlanan maksimum izin verilen boyutu gösteren tampon boyutu ipucunu ayarlar.

Değer: Bellek boyutu ipucu, megabayt cinsinden. Pozitif olmayan değer, dahili tamponlar için bellek sınırlaması olmadığı anlamına gelir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | tampon boyutu ipucu, tüm dahili tamponlar için tanımlanan maksimum izin verilen boyut. |

### isAutoAdjustPalette() {#isAutoAdjustPalette--}
```
public boolean isAutoAdjustPalette()
```


Otomatik palet ayarlamasının yapılıp yapılmadığını gösteren bir değeri alır.

**Returns:**
boolean - `true` otomatik palet ayarlamayı etkinleştirirse; aksi takdirde, `false`.
### setAutoAdjustPalette(boolean value) {#setAutoAdjustPalette-boolean-}
```
public void setAutoAdjustPalette(boolean value)
```


Otomatik palet ayarlamasının yapılıp yapılmadığını gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | `true` otomatik palet ayarlamayı etkinleştirirse; aksi takdirde, `false`. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Bu kullanıcı dostu özellik ile dosya formatı değerini kolayca alın. Dosya formatı hakkında bilgiye hızlı erişim isteyen geliştiriciler için idealdir.

**Returns:**
long
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Arka plan rengi için bir değeri alır veya ayarlar.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Görüntünün arka plan rengine sahip olup olmadığını gösteren bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Arka plan rengi için bir değeri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Görüntünün meta verilerini alır.

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - the image metadata.
### getExifData() {#getExifData--}
```
public ExifData getExifData()
```


Exif verilerini alır.

**Returns:**
[ExifData](../../com.aspose.imaging.exif/exifdata) - the Exif data.
### setExifData(ExifData value) {#setExifData-com.aspose.imaging.exif.ExifData-}
```
public void setExifData(ExifData value)
```


Exif verilerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ExifData](../../com.aspose.imaging.exif/exifdata) | Exif verileri. |

### getXmpData() {#getXmpData--}
```
public final XmpPacketWrapper getXmpData()
```


Xmp verilerini alır.

**Returns:**
[XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) - the Xmp data.
### setXmpData(XmpPacketWrapper value) {#setXmpData-com.aspose.imaging.xmp.XmpPacketWrapper-}
```
public final void setXmpData(XmpPacketWrapper value)
```


Xmp verilerini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [XmpPacketWrapper](../../com.aspose.imaging.xmp/xmppacketwrapper) | Xmp verileri. |

### getIProgressEventHandler() {#getIProgressEventHandler--}
```
public final ProgressEventHandler getIProgressEventHandler()
```


İlerleme olayı işleyicisinin bilgilerini alır.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the progress event handler information.
### getProgressEventHandlerInfo() {#getProgressEventHandlerInfo--}
```
public final ProgressEventHandlerInfo getProgressEventHandlerInfo()
```


İlerleme olayı işleyicisinin bilgilerini alır.

Değer: İlerleme olay işleyicisi bilgisi.

**Returns:**
[ProgressEventHandlerInfo](../../com.aspose.imaging.progressmanagement/progresseventhandlerinfo) - the progress event handler information.
### canSave(ImageOptionsBase options) {#canSave-com.aspose.imaging.ImageOptionsBase-}
```
public boolean canSave(ImageOptionsBase options)
```


Görüntünün, verilen kaydetme seçenekleriyle temsil edilen belirtilen dosya biçimine kaydedilip kaydedilemeyeceğini belirler.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Kullanılacak kaydetme seçenekleri. |

**Returns:**
boolean - `true` görüntü, verilen kaydetme seçenekleriyle temsil edilen belirtilen dosya formatına kaydedilebiliyorsa; aksi takdirde, `false`.

**Example: This example shows how to determine whether image can be saved to the specified file format represented by the passed save options.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.imageoptions.JpegOptions saveOptions = new com.aspose.imaging.imageoptions.JpegOptions();
    saveOptions.setQuality(50);

    // Görüntünün Jpeg formatına kaydedilip kaydedilemeyeceğini belirleyin
    boolean canSave = image.canSave(saveOptions);
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight) {#resize-int-int-}
```
public void resize(int newWidth, int newHeight)
```


Görüntüyü yeniden boyutlandırır. Varsayılan [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\#NearestNeighbourResample) kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |


**Example: The following example shows how to resize a metafile (WMF and EMF).**

``` java
String baseFolder = "c:\\temp\\";

String[] files = new String[]{"image3.emf", "image4.wmf"};
for (String fileName : files) {
    String inputFile = baseFolder + fileName;
    String outputFile = baseFolder + "Resize_" + fileName;
    com.aspose.imaging.fileformats.emf.MetaImage image = (com.aspose.imaging.fileformats.emf.MetaImage) com.aspose.imaging.Image.load(inputFile);
    try {
        image.resize(image.getWidth() / 4, image.getHeight() / 4);
        image.save(outputFile);
    } finally {
        image.close();
    }
}
```


**Example: The following example shows how to resize SVG image and save it to PNG.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1431\\";
String[] fileNames = new String[] {
                "Logotype.svg",
                "sample_car.svg",
                "rg1024_green_grapes.svg",
                "MidMarkerFigure.svg",
                "embeddedFonts.svg"
        };

com.aspose.imaging.PointF[] scales = new com.aspose.imaging.PointF[] {
                new com.aspose.imaging.PointF(0.5f, 0.5f),
                new com.aspose.imaging.PointF(1f, 1f),
                new com.aspose.imaging.PointF(2f, 2f),
                new com.aspose.imaging.PointF(3.5f, 9.2f),
        };

for (String inputFile : fileNames) {
    for (com.aspose.imaging.PointF scale : scales) {
        String outputFile = String.format("%s_%2.2f_%2.2f.png", inputFile, scale.getX(), scale.getY());
        com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + inputFile);
        try {
            image.resize((int) (image.getWidth() * scale.getX()), (int) (image.getHeight() * scale.getY()));
            image.save(dir + outputFile, new com.aspose.imaging.imageoptions.PngOptions());
        }
        finally {
            image.close();
        }
    }
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


**Example: This example loads an image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```


**Example: This example loads a raster image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
}
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
}
```


**Example: This example loads a WMF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.wmf")) {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
}
```


**Example: This example loads a multi-page ODG image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
}

try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.odg")) {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Varsayılan seçeneklerle PNG olarak kaydet.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
}
```


**Example: Using a segment mask to speed up the segmentation process**

``` java
// Maskeleme dışa aktarma seçenekleri
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// GraphCut kümeleme kullanın.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Arka plan rengi şeffaf olacaktır.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Segmentasyon sürecini hızlandırmak için görüntü boyutu küçültülüyor
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // ImageMasking sınıfının bir örneğini oluşturun.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Kaynak görüntüyü birkaç küme (segment) içine bölün.
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Ön plan maskesi alınıyor
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Maskenin boyutunu orijinal görüntünün boyutuna artırın
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Ön plan segmenti elde etmek için maskeyi orijinal görüntüye uygulama
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```


**Example: Resize image using specific Resize Type.**

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


**Example: Resize EPS image and export it to PNG format.**

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

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public abstract void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Görüntüyü yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| newHeight | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Yeniden boyutlandırma ayarları. |


**Example: This example loads an image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// Ağırlıklı ve karıştırılmış rasyonel fonksiyon ve lanczos3 enterpolasyonu üzerine kurulu uyarlamalı algoritma.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Küçük dikdörtgen filtre
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Palet içindeki renk sayısı.
resizeSettings.setEntriesCount(256);

// Renk kantitatizasyonu kullanılmaz
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// Euclidian yöntemi
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Uyarlanabilir yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.gif");
} finally {
    image.dispose();
}
```


**Example: This example loads a raster image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// Ağırlıklı ve karıştırılmış rasyonel fonksiyon ve lanczos3 enterpolasyonu üzerine kurulu uyarlamalı algoritma.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Küçük dikdörtgen filtre
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Palet içindeki renk sayısı.
resizeSettings.setEntriesCount(256);

// Renk kantitatizasyonu kullanılmaz
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// Euclidian yöntemi
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif")) {
    // Uyarlanabilir yeniden örnekleme kullanarak 2 kat küçült.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);
    image.save(dir + "downsample.adaptive.gif");
}
```


**Example: Resize image using specific Resize Type.**

``` java
try (Image image = Image.load("Photo.jpg"))
{
    image.resize(640, 480, ResizeType.CatmullRom);
    image.save("ResizedPhoto.jpg");

    image.resize(1024, 768, ResizeType.CubicConvolution);
    image.save("ResizedPhoto2.jpg");

    ImageResizeSettings resizeSettings = new ImageResizeSettings();
    resizeSettings.setMode(ResizeType.CubicBSpline);
    resizeSettings.setFilterType(ImageFilterType.SmallRectangular);

    image.resize(800, 800, resizeSettings);
    image.save("ResizedPhoto3.jpg");
}
```


**Example: Resize EPS image using advanced settings.**

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
### resizeWidthProportionally(int newWidth) {#resizeWidthProportionally-int-}
```
public void resizeWidthProportionally(int newWidth)
```


Genişliği orantılı olarak yeniden boyutlandırır. Varsayılan olarak [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\#NearestNeighbourResample) kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |

### resizeHeightProportionally(int newHeight) {#resizeHeightProportionally-int-}
```
public void resizeHeightProportionally(int newHeight)
```


Yüksekliği orantılı olarak yeniden boyutlandırır. Varsayılan olarak [ResizeType.NearestNeighbourResample](../../com.aspose.imaging/resizetype\#NearestNeighbourResample) kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newHeight | int | Yeni yükseklik. |

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| resizeType | int | Yeniden boyutlandırma türü. |


**Example: This example loads an image and resizes it proportionally using various resizing methods.**
Bu örnek bir görüntü yükler ve çeşitli yeniden boyutlandırma yöntemlerini kullanarak orantılı bir şekilde yeniden boyutlandırır. Yalnızca genişlik belirtilir, yükseklik otomatik olarak hesaplanır.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
{
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat küçült.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newHeight | int | Yeni yükseklik. |
| resizeType | int | Yeniden boyutlandırma türü. |


**Example: This example loads an image and resizes it proportionally using various resizing methods.**
Bu örnek bir görüntü yükler ve çeşitli yeniden boyutlandırma yöntemlerini kullanarak orantılı bir şekilde yeniden boyutlandırır. Yalnızca yükseklik belirtilir, genişlik otomatik olarak hesaplanır.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat büyüt.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // En Yakın Komşu yeniden örnekleme kullanarak 2 kat küçült.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat büyüt.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // İkili doğrusal yeniden örnekleme kullanarak 2 kat küçült.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```


**Example: Using a segment mask to speed up the segmentation process**

``` java
// Maskeleme dışa aktarma seçenekleri
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// GraphCut kümeleme kullanın.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Arka plan rengi şeffaf olacaktır.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getTransparent());
maskingOptions.setExportOptions(exportOptions);

String dir = "c:\\temp\\";
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
try
{
    com.aspose.imaging.Size imageSize = image.getSize();

    // Segmentasyon sürecini hızlandırmak için görüntü boyutu küçültülüyor
    image.resizeHeightProportionally(600, com.aspose.imaging.ResizeType.HighQualityResample);

    // ImageMasking sınıfının bir örneğini oluşturun.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Kaynak görüntüyü birkaç küme (segment) içine bölün.
    com.aspose.imaging.masking.result.MaskingResult maskingResult = masking.decompose(maskingOptions);
    try
    {
        // Ön plan maskesi alınıyor
        com.aspose.imaging.RasterImage foregroundMask = maskingResult.get_Item(1).getMask();
        try
        {
            // Maskenin boyutunu orijinal görüntünün boyutuna artırın
            foregroundMask.resize(imageSize.getWidth(), imageSize.getHeight(), com.aspose.imaging.ResizeType.NearestNeighbourResample);

            // Ön plan segmenti elde etmek için maskeyi orijinal görüntüye uygulama
            com.aspose.imaging.RasterImage originImage = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "BigImage.jpg");
            try
            {
                com.aspose.imaging.masking.ImageMasking.applyMask(originImage, foregroundMask, maskingOptions);
                originImage.save(dir + "BigImage_foreground.png", exportOptions);
            }
            finally
            {
                originImage.close();
            }
        }
        finally
        {
            foregroundMask.close();
        }
    }
    finally
    {
        maskingResult.close();
    }
}
finally
{
    image.close();
}
```

### resizeWidthProportionally(int newWidth, ImageResizeSettings settings) {#resizeWidthProportionally-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resizeWidthProportionally(int newWidth, ImageResizeSettings settings)
```


Genişliği orantılı olarak yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newWidth | int | Yeni genişlik. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Görüntü yeniden boyutlandırma ayarları. |

### resizeHeightProportionally(int newHeight, ImageResizeSettings settings) {#resizeHeightProportionally-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resizeHeightProportionally(int newHeight, ImageResizeSettings settings)
```


Yüksekliği orantılı olarak yeniden boyutlandırır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newHeight | int | Yeni yükseklik. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Görüntü yeniden boyutlandırma ayarları. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public abstract void rotateFlip(int rotateFlipType)
```


Görüntüyü döndürür, çevirir veya döndürüp çevirir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rotateFlipType | int | Dönüş çevirme türü. |


**Example: This example demonstrates the use of Rotate operation on an image.**
Bu örnek, bir görüntü üzerinde Rotate (Döndür) işleminin kullanımını gösterir. Örnek, bir disk konumundan mevcut bir görüntü dosyasını yükler ve görüntüyü com.aspose.imaging.RotateFlipType enum değerine göre Rotate işlemini uygular.
``` java
// Image sınıfının bir örneğini oluşturun ve dosya yolu aracılığıyla mevcut bir görüntü dosyasıyla başlatın.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Görüntüyü X ekseni etrafında 180 derece döndürün.
    image.rotateFlip(com.aspose.imaging.RotateFlipType.Rotate180FlipX);

    // Tüm değişiklikleri kaydedin.
    image.save();
} finally {
    image.dispose();
}
```

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Görüntüyü merkezin etrafında döndür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| angle | float | Derece cinsinden döndürme açısı. Pozitif değerler saat yönünde döndürür. |

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Belirtilen dikdörtgeni kırpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Dikdörtgen. |


**Example: The following example crops a raster image.**
Aşağıdaki örnek bir raster görüntüyü kırpar. Kırpma alanı com.aspose.imaging.Rectangle aracılığıyla belirtilir.
``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png")) {
    // Görüntüyü kırp. Kırpma alanı, görüntünün dikdörtgen merkezi alanıdır.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(rasterImage.getWidth() / 4, rasterImage.getHeight() / 4, rasterImage.getWidth() / 2, rasterImage.getHeight() / 2);
    image.crop(area);

    // Kırpılmış görüntüyü PNG olarak kaydet.
    image.save(dir + "sample.Crop.png");
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Görüntüyü kaydırmalarla kırpar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| leftShift | int | Sol kaydırma. |
| rightShift | int | Sağ kaydırma. |
| topShift | int | Üst kaydırma. |
| bottomShift | int | Alt kaydırma. |


**Example: The following example crops a raster image.**
Aşağıdaki örnek bir raster görüntüyü kırpar. Kırpma alanı Sol, Üst, Sağ, Alt kenar boşluklarıyla belirtilir.
``` java
String dir = "c:\\temp\\";
            
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.png")) {
    // Tekrar kırpın. Görüntü boyutunun %10'u kadar bir kenar boşluğu ayarlayın.
    int horizontalMargin = rasterImage.getWidth() / 10;
    int verticalMargin = rasterImage.getHeight() / 10;
    image.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin);

    // Kırpılmış görüntüyü PNG olarak kaydedin.
    image.save(dir + "sample.Crop.png");
}
```

### save() {#save--}
```
public final void save()
```


Görüntü verisini temel akışa kaydeder.


**Example: The following example shows how to save an entire BMP image or part of it to a file or stream.**

``` java
String dir = "c:\\temp\\";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.fileformats.bmp.BmpImage bmpImage = (com.aspose.imaging.fileformats.bmp.BmpImage) image;

    // Siyah-beyaz bir görüntüye dönüştürün
    bmpImage.binarizeOtsu();

    // Aynı konuma varsayılan seçeneklerle kaydedin.
    image.save();

    com.aspose.imaging.imageoptions.BmpOptions saveOptions = new com.aspose.imaging.imageoptions.BmpOptions();

    // Bu durumda palet yalnızca iki renk içerir: Siyah ve Beyaz.
    saveOptions.setPalette(com.aspose.imaging.ColorPaletteHelper.createMonochrome());

    // Tüm tek renkli görüntüler (siyah-beyaz olanlar dahil) için piksel başına 1 bit ayırmak yeterlidir.
    saveOptions.setBitsPerPixel(1);

    // Belirtilen seçeneklerle başka bir konuma kaydedin.
    image.save(dir + "sample.bw.palettized.bmp", saveOptions);

    // Yalnızca görüntünün merkezi kısmını kaydedin.
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(image.getWidth() / 4, image.getHeight() / 4, image.getWidth() / 2, image.getHeight() / 2);
    image.save(dir + "sample.bw.palettized.part.bmp", saveOptions, bounds);

    // Tüm görüntüyü bir bellek akışına kaydedin
    java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
    try {
        image.save(stream, saveOptions);
        System.out.println("The size of the whole image in bytes: " + stream.size());
    } finally {
        stream.close();
    }

    // Görüntünün merkezi kısmını bir bellek akışına kaydedin
    stream = new java.io.ByteArrayOutputStream();
    try {
        image.save(stream, saveOptions, bounds);
        System.out.println("The size of the central part of the image in bytes: " + stream.size());
    } finally {
        stream.close();
    }
} finally {
    image.close();
}

//Çıktı şöyle görünebilir:
//Tüm görüntünün bayt cinsinden boyutu: 1662
//Görüntünün merkezi kısmının bayt cinsinden boyutu: 462
```

### save(String filePath) {#save-java.lang.String-}
```
public void save(String filePath)
```


Görüntüyü belirtilen dosya konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Görüntünün kaydedileceği dosya yolu. |

### save(String filePath, ImageOptionsBase options) {#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-}
```
public void save(String filePath, ImageOptionsBase options)
```


Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya yolu. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Seçenekler. |


**Example: This example shows the simple steps to Save an Image.**
Bu örnek, bir görüntüyü kaydetmek için basit adımları gösterir. Bu işlemi göstermek için bir disk konumundan mevcut bir dosya yükler ve görüntüyü PSD formatında kaydeder.
``` java
// Diskten mevcut bir dosya yükleyin.
com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
try {
    // Görüntüyü PSD olarak, varsayılan PsdOptions ayarlarıyla dosya yoluna kaydedin.
    image.save("C:\\temp\\output.psd", new com.aspose.imaging.imageoptions.PsdOptions());
} finally {
    image.dispose();
}
```

### save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle) {#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(String filePath, ImageOptionsBase options, Rectangle boundsRectangle)
```


Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya yolu. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Seçenekler. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırlarını kullanmak için boş bir dikdörtgen ayarlayın. |


**Example: The following example loads a BMP image from a file, then saves a rectangular part of the image to a PNG file.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    // Görüntünün üst yarısını bir PNG dosyasına kaydedin.
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(0, 0, image.getWidth(), image.getHeight() / 2);
    image.save(dir + "output.png", saveOptions, bounds);
} finally {
    image.dispose();
}
```

### save(RandomAccessFile file, ImageOptionsBase options) {#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-}
```
public void save(RandomAccessFile file, ImageOptionsBase options)
```


Nesnenin verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen dosya konumuna kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya | java.io.RandomAccessFile | Görüntünün verilerinin kaydedileceği dosya. |
| options | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Seçenekler. |

### save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.RandomAccessFile-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(RandomAccessFile file, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| dosya | java.io.RandomAccessFile | Görüntünün verilerinin kaydedileceği dosya. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Kaydetme seçenekleri. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırlarını kullanmak için boş bir dikdörtgen ayarlayın. |

### save(OutputStream stream, ImageOptionsBase optionsBase) {#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase)
```


Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Görüntünün verilerinin kaydedileceği akış. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Kaydetme seçenekleri. |


**Example: This example shows the process of saving an Image to memory buffer.**
Bu örnek, bir Görüntünün bellek tamponuna kaydedilme sürecini gösterir. Bu işlemi göstermek için örnek, bir disk konumundan mevcut bir dosyayı yükler ve görüntüyü PSD formatında kaydeder.
``` java
java.io.ByteArrayOutputStream stream = new java.io.ByteArrayOutputStream();
try {            //Create an instance of image class and initialize it with an existing image file through File path
    com.aspose.imaging.Image image = com.aspose.imaging.Image.load("C:\\temp\\sample.bmp");
    try {
        //Görüntüyü, varsayılan PsdOptions ayarlarıyla PSD bellek akışına kaydet
        image.save(stream, new com.aspose.imaging.imageoptions.PsdOptions());
    } finally {
        image.dispose();
    }
} finally {
    stream.close();
}
```

### save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle) {#save-java.io.OutputStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-}
```
public void save(OutputStream stream, ImageOptionsBase optionsBase, Rectangle boundsRectangle)
```


Görüntünün verilerini, kaydetme seçeneklerine göre belirtilen dosya biçiminde belirtilen akışa kaydeder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.OutputStream | Görüntünün verilerinin kaydedileceği akış. |
| optionsBase | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Kaydetme seçenekleri. |
| boundsRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Hedef görüntü sınırları dikdörtgeni. Kaynak sınırlarını kullanmak için boş bir dikdörtgen ayarlayın. |


**Example: The following example loads an image from a file, then saves a rectangular part of the image to a PNG file stream.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    com.aspose.imaging.Rectangle bounds = new com.aspose.imaging.Rectangle(0, 0, image.getWidth(), image.getHeight() / 2);
    java.io.OutputStream outputStream = new java.io.FileOutputStream(dir + "sample.output.png");
    try {
        // Görüntünün üst yarısını bir dosya akışına kaydet.
        image.save(outputStream, saveOptions, bounds);
    } finally {
        outputStream.close();
    }
} finally {
    image.dispose();
}
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public abstract void setPalette(IColorPalette palette, boolean updateColors)
```


Görüntü paletini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Ayarlanacak palet. |
| updateColors | boolean | `true` olarak ayarlanırsa renkler yeni palete göre güncellenecek; aksi takdirde renk indeksleri değişmeden kalır. Değişmeyen indekslerin, bazı indekslerin karşılık gelen palet girdileri olmaması durumunda görüntünün yüklenirken çökmesine neden olabileceğini unutmayın. |

### getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber) {#getSerializedStream-com.aspose.imaging.ImageOptionsBase-com.aspose.imaging.Rectangle-int---}
```
public InputStream getSerializedStream(ImageOptionsBase imageOptions, Rectangle clippingRectangle, int[] pageNumber)
```


aps formatına dönüştürür.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageOptions | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | Görüntü seçenekleri. |
| clippingRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Kırpma dikdörtgeni. |
| pageNumber | int[] | Sayfa numarası. |

**Returns:**
java.io.InputStream - Serileştirilmiş akış
