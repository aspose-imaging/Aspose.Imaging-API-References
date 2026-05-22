---
title: "ImageMasking"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Görüntü maskeleme işlemleri sağlar"
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.masking/imagemasking/
---
**Inheritance:**
java.lang.Object
```
public class ImageMasking
```

Görüntü maskeleme işlemleri sağlar
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ImageMasking(RasterImage sourceImage)](#ImageMasking-com.aspose.imaging.RasterImage-) | Yeni bir [ImageMasking](../../com.aspose.imaging.masking/imagemasking) sınıfının örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [applyMask(RasterImage targetImage, RasterImage mask, MaskingOptions maskingOptions)](#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.RasterImage-com.aspose.imaging.masking.options.MaskingOptions-) | Maske belirtilen kaynak görüntüye uygulanır. |
| [decompose(MaskingOptions options)](#decompose-com.aspose.imaging.masking.options.MaskingOptions-) | Belirtilen maskeleme seçeneklerini kullanarak ayrıştırma işlemini gerçekleştirir |
| [decomposeAsync(MaskingOptions options)](#decomposeAsync-com.aspose.imaging.masking.options.MaskingOptions-) | Belirtilen maskeleme seçeneklerini kullanarak asenkron ayrıştırma görevini oluşturur. |
| [createSession(MaskingOptions options)](#createSession-com.aspose.imaging.masking.options.MaskingOptions-) | Yeniden eğitim ayrıştırma işlemlerini gerçekleştirebilen maskeleme oturumunu oluşturur. |
| [loadSession(InputStream stream)](#loadSession-java.io.InputStream-) | Oturumu belirtilen akıştan yükle. |
| [loadSession(System.IO.Stream stream)](#loadSession-com.aspose.ms.System.IO.Stream-) |  |
| [loadSession(String filePath)](#loadSession-java.lang.String-) | Belirtilen dosyadan oturumu yükleyin. |

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

### ImageMasking(RasterImage sourceImage) {#ImageMasking-com.aspose.imaging.RasterImage-}
```
public ImageMasking(RasterImage sourceImage)
```


Yeni bir [ImageMasking](../../com.aspose.imaging.masking/imagemasking) sınıfının örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| sourceImage | [RasterImage](../../com.aspose.imaging/rasterimage) | The source image. |


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

### applyMask(RasterImage targetImage, RasterImage mask, MaskingOptions maskingOptions) {#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.RasterImage-com.aspose.imaging.masking.options.MaskingOptions-}
```
public static void applyMask(RasterImage targetImage, RasterImage mask, MaskingOptions maskingOptions)
```


Maske belirtilen kaynak görüntüye uygulanır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| targetImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Hedef görüntü. |
| mask | [RasterImage](../../com.aspose.imaging/rasterimage) | Uygulanacak maske görüntüsü. |
| maskingOptions | [MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions) | Maskleme seçenekleri. |


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

### decompose(MaskingOptions options) {#decompose-com.aspose.imaging.masking.options.MaskingOptions-}
```
public final MaskingResult decompose(MaskingOptions options)
```


Belirtilen maskeleme seçeneklerini kullanarak ayrıştırma işlemini gerçekleştirir

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions) | Maskleme seçenekleri. |

**Returns:**
[MaskingResult](../../com.aspose.imaging.masking.result/maskingresult) - Result of masking operation as array of segment image providers.

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

### decomposeAsync(MaskingOptions options) {#decomposeAsync-com.aspose.imaging.masking.options.MaskingOptions-}
```
public final IMaskingAsyncTask decomposeAsync(MaskingOptions options)
```


Belirtilen maskeleme seçeneklerini kullanarak asenkron ayrıştırma görevini oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions) | Maskleme seçenekleri. |

**Returns:**
[IMaskingAsyncTask](../../com.aspose.imaging.masking/imaskingasynctask) - The asynchronous decompose task
### createSession(MaskingOptions options) {#createSession-com.aspose.imaging.masking.options.MaskingOptions-}
```
public final IMaskingSession createSession(MaskingOptions options)
```


Yeniden eğitim ayrıştırma işlemlerini gerçekleştirebilen maskeleme oturumunu oluşturur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions) | Seçenekler. |

**Returns:**
[IMaskingSession](../../com.aspose.imaging.masking/imaskingsession) - the masking session which can perform retraining decompose operations.

**Example: Saving the masking session to a file for long sessions, as well as for the possibility of resuming the session in another environment.**

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

### loadSession(InputStream stream) {#loadSession-java.io.InputStream-}
```
public final IMaskingSession loadSession(InputStream stream)
```


Oturumu belirtilen akıştan yükle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | java.io.InputStream | Akış. |

**Returns:**
[IMaskingSession](../../com.aspose.imaging.masking/imaskingsession) - the masking session which can perform retraining decompose operations.
### loadSession(System.IO.Stream stream) {#loadSession-com.aspose.ms.System.IO.Stream-}
```
public final IMaskingSession loadSession(System.IO.Stream stream)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | com.aspose.ms.System.IO.Stream |  |

**Returns:**
[IMaskingSession](../../com.aspose.imaging.masking/imaskingsession)
### loadSession(String filePath) {#loadSession-java.lang.String-}
```
public final IMaskingSession loadSession(String filePath)
```


Belirtilen dosyadan oturumu yükleyin.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| filePath | java.lang.String | Dosya yolu. |

**Returns:**
[IMaskingSession](../../com.aspose.imaging.masking/imaskingsession) - the masking session which can perform retraining decompose operations.
