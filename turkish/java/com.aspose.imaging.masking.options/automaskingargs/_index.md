---
title: "AutoMaskingArgs"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Otomatik maskeleme yöntemleri için belirtilen argümanları temsil eder."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.masking.options/automaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class AutoMaskingArgs implements IMaskingArgs
```

Otomatik maskeleme yöntemleri için belirtilen argümanları temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AutoMaskingArgs()](#AutoMaskingArgs--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getNumberOfObjects()](#getNumberOfObjects--) | İlk görüntüyü ayırmak için nesne sayısını alır (isteğe bağlı), varsayılan değer 2'dir (nesne ve arka plan). |
| [setNumberOfObjects(int value)](#setNumberOfObjects-int-) | İlk görüntüyü ayırmak için nesne sayısını ayarlar (isteğe bağlı), varsayılan değer 2'dir (nesne ve arka plan). |
| [getObjectsRectangles()](#getObjectsRectangles--) | Ayrılmış nesnelere ait nesne dikdörtgenlerini alır (isteğe bağlı). |
| [setObjectsRectangles(Rectangle[] value)](#setObjectsRectangles-com.aspose.imaging.Rectangle---) | Ayrılmış nesnelere ait nesne dikdörtgenlerini ayarlar (isteğe bağlı). |
| [getObjectsPoints()](#getObjectsPoints--) | Ayrılmış nesnelere ait noktaları alır (isteğe bağlı) NumberOfObjects koordinatları, ilk görüntünün NumberOfObjects nesnesine aittir. |
| [setObjectsPoints(Point[][] value)](#setObjectsPoints-com.aspose.imaging.Point-----) | Ayrılmış nesnelere ait noktaları ayarlar (isteğe bağlı) NumberOfObjects koordinatları, ilk görüntünün NumberOfObjects nesnesine aittir. |
| [getOrphanedPoints()](#getOrphanedPoints--) | Artık herhangi bir nesneye ait olmayan noktaları alır (isteğe bağlı). |
| [setOrphanedPoints(Point[] value)](#setOrphanedPoints-com.aspose.imaging.Point---) | Artık herhangi bir nesneye ait olmayan noktaları ayarlar (isteğe bağlı). |
| [getPrecision()](#getPrecision--) | Segmentasyon yönteminin hassasiyetini alır (isteğe bağlı). |
| [setPrecision(double value)](#setPrecision-double-) | Segmentasyon yönteminin hassasiyetini ayarlar (isteğe bağlı). |
| [getMaxIterationNumber()](#getMaxIterationNumber--) | Maksimum yineleme sayısını alır. |
| [setMaxIterationNumber(int value)](#setMaxIterationNumber-int-) | Maksimum yineleme sayısını ayarlar. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and the K-means segmentation algorithm.
Bu örnek, görüntü maskesi ve K-means segmentasyon algoritması kullanarak bir raster görüntüyü birden fazla görüntüye nasıl ayıracağınızı gösterir. Görüntü maskesi, arka planı ön plan görüntü nesnelerinden ayırmak için kullanılan bir görüntü işleme tekniğidir.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Küme sayısını (ayrı nesneler) ayarlayın. Varsayılan değer 2'dir, ön plan nesnesi ve arka plan.
    args.setNumberOfObjects(3);

    // Maksimum yineleme sayısını ayarlayın.
    args.setMaxIterationNumber(50);

    // Segmentasyon yönteminin hassasiyetini ayarlayın (isteğe bağlı).
    args.setPrecision(1);

    // Her küme (segment) ayrı bir PNG dosyasına kaydedilecektir.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // K-means kümeleme kullanın.
    // K-means kümeleme, görüntüyü birkaç bağımsız kümeye (segmentlere) ayırmaya olanak tanır.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.KMeans);
    maskingOptions.setDecompose(true);
    maskingOptions.setArgs(args);

    // Arka plan rengi turuncu olacaktır.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // ImageMasking sınıfının bir örneğini oluşturun.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Kaynak görüntüyü birkaç küme (segment) içine bölün.
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);
    try
    {
        // Maskleme sonucundan görüntüleri elde edin ve PNG olarak kaydedin.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            final IMaskingLayer resultsItem = maskingResults.get_Item(i);
            String outputFileName = String.format("Blue hills.Segment%s.png", resultsItem.getObjectNumber());
            Image resultImage = resultsItem.getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```


## Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.
Bu örnek, segmentasyon (kümeleme) yönteminin hassasiyetini artırmak için görüntü maskesi algoritmasına öneriler nasıl belirtileceğini gösterir. Görüntü maskesi, arka planı ön plan görüntü nesnelerinden ayırmak için kullanılan bir görüntü işleme tekniğidir.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try {
    com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

    // Öneri #1.
    // Görüntüyü görsel olarak analiz edin ve ilgi alanını ayarlayın. Segmentasyon sonucu, yalnızca bu alan içinde tamamen konumlanmış nesneleri içerecektir.
    args.setObjectsRectangles(new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(86, 6, 270, 364),
            });

    // Öneri #2.
    // Görüntüyü görsel olarak analiz edin ve ayrı nesnelere ait noktaları ayarlayın.
    args.setObjectsPoints(new com.aspose.imaging.Point[][]
            {
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(103, 326)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(280, 43)},
                    new com.aspose.imaging.Point[]{new com.aspose.imaging.Point(319, 86)},
            });

    // Her küme (segment) ayrı bir PNG dosyasına kaydedilecektir.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // GraphCut kümeleme kullanın.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // Arka plan rengi turuncu olacaktır.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // ImageMasking sınıfının bir örneğini oluşturun.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Kaynak görüntüyü birkaç küme (segment) içine bölün.
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Maskleme sonucundan görüntüleri elde edin ve PNG olarak kaydedin.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Gorilla.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
            Image resultImage = maskingResults.get_Item(i).getImage();
            try {
                resultImage.save(dir + outputFileName);
            } finally {
                resultImage.close();
            }
        }
    }
    finally
    {
        maskingResults.close();
    }
} finally {
    image.close();
}
```


## Example: Using a segment mask to speed up the segmentation process

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


## Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.

``` java
String dir = "c:\\temp\\";
String sessionBackupFile = dir + "session.bak";

// Maskeleme dışa aktarma seçenekleri
com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
exportOptions.setSource(new com.aspose.imaging.sources.StreamSource());

com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

// GraphCut kümeleme kullanın.
maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.GraphCut);
maskingOptions.setDecompose(false);
maskingOptions.setArgs(new com.aspose.imaging.masking.options.AutoMaskingArgs());

// Arka plan rengi turuncu olacaktır.
maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
maskingOptions.setExportOptions(exportOptions);

// İlk kez bir oturum başlatılıyor ve dosyaya kaydediliyor
com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // ImageMasking sınıfının bir örneğini oluşturun.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    com.aspose.imaging.masking.IMaskingSession session = masking.createSession(maskingOptions);
    try
    {
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.decompose();
        try
        {
            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step1.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }

        session.save(sessionBackupFile);
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image.close();
}

// Bir dosyadan maskeleme oturumu devam ettiriliyor
com.aspose.imaging.RasterImage image2 = (com.aspose.imaging.RasterImage)com.aspose.imaging.Image.load(dir + "Gorilla.bmp");
try
{
    // ImageMasking sınıfının bir örneğini oluşturun.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image2);

    com.aspose.imaging.masking.IMaskingSession session = masking.loadSession(sessionBackupFile);
    try
    {
        com.aspose.imaging.masking.options.AutoMaskingArgs args = new com.aspose.imaging.masking.options.AutoMaskingArgs();

        // Görüntüyü görsel olarak analiz edin ve ayrı nesnelere ait noktaları ayarlayın.
        args.setObjectsPoints(new Point[][]
                {
                        new Point[]
                                {
                                        new Point(0, 0), new Point(0, 1), new Point(1, 0),
                                        new Point(1, 1), new Point(2, 0), new Point(2, 1),
                                        new Point(3, 0), new Point(3, 1)
                                },
                });
        com.aspose.imaging.masking.result.MaskingResult maskingResult = session.improveDecomposition(args);
        try
        {
            // Serileştirilemediği için dışa aktarma seçeneklerinin açık aktarımı
            maskingResult.MaskingOptions.setExportOptions(exportOptions);

            com.aspose.imaging.RasterImage segmentImage = maskingResult.get_Item(1).getImage();
            try
            {
                segmentImage.save(dir + "step2.png");
            }
            finally
            {
                segmentImage.close();
            }
        }
        finally
        {
            maskingResult.close();
        }
    }
    finally
    {
        session.dispose();
    }
}
finally
{
    image2.close();
}
```

### AutoMaskingArgs() {#AutoMaskingArgs--}
```
public AutoMaskingArgs()
```


### getNumberOfObjects() {#getNumberOfObjects--}
```
public final int getNumberOfObjects()
```


İlk görüntüyü ayırmak için nesne sayısını alır (isteğe bağlı), varsayılan değer 2'dir (nesne ve arka plan).

Değer: Nesne sayısı.

**Returns:**
int - ilk görüntüyü ayırmak için nesne sayısı (isteğe bağlı), varsayılan değer 2'dir (nesne ve arka plan).
### setNumberOfObjects(int value) {#setNumberOfObjects-int-}
```
public final void setNumberOfObjects(int value)
```


İlk görüntüyü ayırmak için nesne sayısını ayarlar (isteğe bağlı), varsayılan değer 2'dir (nesne ve arka plan).

Değer: Nesne sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | ilk görüntüyü ayırmak için nesne sayısı (isteğe bağlı), varsayılan değer 2'dir (nesne ve arka plan). |

### getObjectsRectangles() {#getObjectsRectangles--}
```
public final Rectangle[] getObjectsRectangles()
```


Ayrılmış nesnelere ait nesne dikdörtgenlerini alır (isteğe bağlı). Bu parametre, segmentasyon yönteminin hassasiyetini artırmak için kullanılır.

Değer: Nesne dikdörtgenleri.

**Returns:**
com.aspose.imaging.Rectangle[] - ayrılmış nesnelere ait nesne dikdörtgenleri (isteğe bağlı).
### setObjectsRectangles(Rectangle[] value) {#setObjectsRectangles-com.aspose.imaging.Rectangle---}
```
public final void setObjectsRectangles(Rectangle[] value)
```


Ayrılmış nesnelere ait nesne dikdörtgenlerini ayarlar (isteğe bağlı). Bu parametre, segmentasyon yönteminin hassasiyetini artırmak için kullanılır.

Değer: Nesne dikdörtgenleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle\[\]](../../com.aspose.imaging/rectangle) | ayrılmış nesnelere ait nesne dikdörtgenleri (isteğe bağlı). |

### getObjectsPoints() {#getObjectsPoints--}
```
public final Point[][] getObjectsPoints()
```


Ayrılmış nesnelere ait noktaları alır (isteğe bağlı) NumberOfObjects koordinatları, ilk görüntünün NumberOfObjects nesnesine aittir. Bu parametre, segmentasyon yönteminin hassasiyetini artırmak için kullanılır.

Değer: Nesne noktaları.

**Returns:**
com.aspose.imaging.Point[][] - ayrılmış nesnelere ait noktalar (isteğe bağlı) NumberOfObjects koordinatları, ilk görüntünün NumberOfObjects nesnesine aittir.
### setObjectsPoints(Point[][] value) {#setObjectsPoints-com.aspose.imaging.Point-----}
```
public final void setObjectsPoints(Point[][] value)
```


Ayrılmış nesnelere ait noktaları ayarlar (isteğe bağlı) NumberOfObjects koordinatları, başlangıç görüntüsündeki NumberOfObjects nesnelere aittir. Bu parametre, segmentasyon yöntemi hassasiyetini artırmak için kullanılır.

Değer: Nesne noktaları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | Ayrılmış nesnelere ait noktalar (isteğe bağlı) NumberOfObjects koordinatları, başlangıç görüntüsündeki NumberOfObjects nesnelere aittir. |

### getOrphanedPoints() {#getOrphanedPoints--}
```
public final Point[] getOrphanedPoints()
```


Artık herhangi bir nesneye ait olmayan noktaları alır (isteğe bağlı). Bu parametre yalnızca yeniden segmentasyon durumunda kullanılır.

Değer: Yalnız kalan noktalar.

**Returns:**
com.aspose.imaging.Point[] - artık herhangi bir nesneye ait olmayan noktalar (isteğe bağlı).
### setOrphanedPoints(Point[] value) {#setOrphanedPoints-com.aspose.imaging.Point---}
```
public final void setOrphanedPoints(Point[] value)
```


Artık herhangi bir nesneye ait olmayan noktaları ayarlar (isteğe bağlı). Bu parametre yalnızca yeniden segmentasyon durumunda kullanılır.

Değer: Yalnız kalan noktalar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point\[\]](../../com.aspose.imaging/point) | artık herhangi bir nesneye ait olmayan noktalar (isteğe bağlı). |

### getPrecision() {#getPrecision--}
```
public final double getPrecision()
```


Segmentasyon yönteminin hassasiyetini alır (isteğe bağlı).

Değer: Segmentasyon yöntemi hassasiyeti (isteğe bağlı).

**Returns:**
double - segmentasyon yöntemi hassasiyeti (isteğe bağlı).
### setPrecision(double value) {#setPrecision-double-}
```
public final void setPrecision(double value)
```


Segmentasyon yönteminin hassasiyetini ayarlar (isteğe bağlı).

Değer: Segmentasyon yöntemi hassasiyeti (isteğe bağlı).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | double | segmentasyon yöntemi hassasiyeti (isteğe bağlı). |

### getMaxIterationNumber() {#getMaxIterationNumber--}
```
public final int getMaxIterationNumber()
```


Maksimum yineleme sayısını alır.

Değer: En fazla yineleme sayısı.

**Returns:**
int - en fazla yineleme sayısı.
### setMaxIterationNumber(int value) {#setMaxIterationNumber-int-}
```
public final void setMaxIterationNumber(int value)
```


Maksimum yineleme sayısını ayarlar.

Değer: En fazla yineleme sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | en fazla yineleme sayısı. |

