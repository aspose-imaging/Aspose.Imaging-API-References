---
title: "MaskingOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Ortak görüntü maskeleme seçeneklerini temsil eder."
type: docs
weight: 16
url: /tr/java/com.aspose.imaging.masking.options/maskingoptions/
---
**Inheritance:**
java.lang.Object
```
public class MaskingOptions
```

Ortak görüntü maskeleme seçeneklerini temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [MaskingOptions()](#MaskingOptions--) |  |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [BACKGROUND_OBJECT_NUMBER](#BACKGROUND-OBJECT-NUMBER) | Arka plan nesne sayısı |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getMethod()](#getMethod--) | Segmentasyon yöntemini alır. |
| [setMethod(int value)](#setMethod-int-) | Segmentasyon yöntemini ayarlar. |
| [getArgs()](#getArgs--) | Segmentasyon algoritması için argümanları alır. |
| [setArgs(IMaskingArgs value)](#setArgs-com.aspose.imaging.masking.options.IMaskingArgs-) | Segmentasyon algoritması için argümanları ayarlar. |
| [getExportOptions()](#getExportOptions--) | Görüntü dışa aktarma seçeneklerini alır. |
| [setExportOptions(ImageOptionsBase value)](#setExportOptions-com.aspose.imaging.ImageOptionsBase-) | Görüntü dışa aktarma seçeneklerini ayarlar. |
| [getMaskingArea()](#getMaskingArea--) | Maskeleme alanını alır. |
| [setMaskingArea(Rectangle value)](#setMaskingArea-com.aspose.imaging.Rectangle-) | Maskeleme alanını ayarlar. |
| [getDecompose()](#getDecompose--) | Her bir Shape'i maskeden ayrı bir nesne olarak mı yoksa arka plandan ayrılmış maskeden birleşik bir nesne olarak mı ayırmanın gereksiz olduğunu belirten bir değeri alır. |
| [setDecompose(boolean value)](#setDecompose-boolean-) | Her bir Shape'i maskeden ayrı bir nesne olarak mı yoksa arka plandan ayrılmış maskeden birleşik bir nesne olarak mı ayırmanın gereksiz olduğunu belirten bir değeri ayarlar. |
| [getBackgroundReplacementColor()](#getBackgroundReplacementColor--) | Arka plan değiştirme rengini alır. |
| [setBackgroundReplacementColor(Color value)](#setBackgroundReplacementColor-com.aspose.imaging.Color-) | Arka plan değiştirme rengini ayarlar. |

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

### MaskingOptions() {#MaskingOptions--}
```
public MaskingOptions()
```


### BACKGROUND_OBJECT_NUMBER {#BACKGROUND-OBJECT-NUMBER}
```
public static final int BACKGROUND_OBJECT_NUMBER
```


Arka plan nesne sayısı

### getMethod() {#getMethod--}
```
public final int getMethod()
```


Segmentasyon yöntemini alır.

Değer: Segmentasyon yöntemi.

**Returns:**
int - segmentasyon yöntemi.
### setMethod(int value) {#setMethod-int-}
```
public final void setMethod(int value)
```


Segmentasyon yöntemini ayarlar.

Değer: Segmentasyon yöntemi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | segmentasyon yöntemi. |


**Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.**
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

### getArgs() {#getArgs--}
```
public final IMaskingArgs getArgs()
```


Segmentasyon algoritması için argümanları alır.

Değer: Segmentasyon algoritması için argümanlar.

**Returns:**
[IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs) - the arguments for segmentation algorithm.
### setArgs(IMaskingArgs value) {#setArgs-com.aspose.imaging.masking.options.IMaskingArgs-}
```
public final void setArgs(IMaskingArgs value)
```


Segmentasyon algoritması için argümanları ayarlar.

Değer: Segmentasyon algoritması için argümanlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs) | segmentasyon algoritması için argümanlar. |

### getExportOptions() {#getExportOptions--}
```
public final ImageOptionsBase getExportOptions()
```


Görüntü dışa aktarma seçeneklerini alır.

Değer: Oluşturulacak sonuç görüntülerinde kullanılacak görüntü dışa aktarma seçenekleri.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - the image export options.
### setExportOptions(ImageOptionsBase value) {#setExportOptions-com.aspose.imaging.ImageOptionsBase-}
```
public final void setExportOptions(ImageOptionsBase value)
```


Görüntü dışa aktarma seçeneklerini ayarlar.

Değer: Oluşturulacak sonuç görüntülerinde kullanılacak görüntü dışa aktarma seçenekleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) | görüntü dışa aktarma seçenekleri. |


**Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.**
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

### getMaskingArea() {#getMaskingArea--}
```
public final Rectangle getMaskingArea()
```


Maskeleme alanını alır.

Değer: Kaynak görüntünün bir kısmı olan maskeleme alanı. Rectangle.Empty değeri, tam kaynak görüntü alanı anlamına gelir.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the masking area.
### setMaskingArea(Rectangle value) {#setMaskingArea-com.aspose.imaging.Rectangle-}
```
public final void setMaskingArea(Rectangle value)
```


Maskeleme alanını ayarlar.

Değer: Kaynak görüntünün bir kısmı olan maskeleme alanı. Rectangle.Empty değeri, tam kaynak görüntü alanı anlamına gelir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | maskeleme alanı. |

### getDecompose() {#getDecompose--}
```
public final boolean getDecompose()
```


Her bir Shape'i maskeden ayrı bir nesne olarak mı yoksa arka plandan ayrılmış maskeden birleşik bir nesne olarak mı ayırmanın gereksiz olduğunu belirten bir değeri alır.

Değer: `true` ise ayrıştır; aksi takdirde `false`.

**Returns:**
boolean - her Shape'i maskeden ayrı nesne olarak mı yoksa maskeden arka plan ayrılmış birleşik nesne olarak mı ayırmanın gereksiz olduğunu gösteren bir değer.
### setDecompose(boolean value) {#setDecompose-boolean-}
```
public final void setDecompose(boolean value)
```


Her bir Shape'i maskeden ayrı bir nesne olarak mı yoksa arka plandan ayrılmış maskeden birleşik bir nesne olarak mı ayırmanın gereksiz olduğunu belirten bir değeri ayarlar.

Değer: `true` ise ayrıştır; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | her Shape'i maskeden ayrı nesne olarak mı yoksa maskeden arka plan ayrılmış birleşik nesne olarak mı ayırmanın gereksiz olduğunu gösteren bir değer. |

### getBackgroundReplacementColor() {#getBackgroundReplacementColor--}
```
public final Color getBackgroundReplacementColor()
```


Arka plan değiştirme rengini alır.

Değer: Arka plan değiştirme rengi. Bu renk, oluşan görüntülerde arka plan rengi olarak kullanılacak.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background replacement color.
### setBackgroundReplacementColor(Color value) {#setBackgroundReplacementColor-com.aspose.imaging.Color-}
```
public final void setBackgroundReplacementColor(Color value)
```


Arka plan değiştirme rengini ayarlar.

Değer: Arka plan değiştirme rengi. Bu renk, oluşan görüntülerde arka plan rengi olarak kullanılacak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | arka plan değiştirme rengi. |


**Example: This example shows how to specify suggestions for image masking algorithm to improve precision of segmentation (clustering) method.**
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

