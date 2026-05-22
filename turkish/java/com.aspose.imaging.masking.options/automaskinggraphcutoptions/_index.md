---
title: "AutoMaskingGraphCutOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "GraphCut otomatik maskeleme seçenekleri."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.masking.options/automaskinggraphcutoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.masking.options.MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions), [com.aspose.imaging.masking.options.GraphCutMaskingOptions](../../com.aspose.imaging.masking.options/graphcutmaskingoptions)
```
public class AutoMaskingGraphCutOptions extends GraphCutMaskingOptions
```

GraphCut otomatik maskeleme seçenekleri.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AutoMaskingGraphCutOptions()](#AutoMaskingGraphCutOptions--) | Yeni bir [AutoMaskingGraphCutOptions](../../com.aspose.imaging.masking.options/automaskinggraphcutoptions) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDefaultForegroundStrokes()](#getDefaultForegroundStrokes--) | Önceden hesaplanmış varsayılan ön plan darbelerini alır. |
| [getDefaultBackgroundStrokes()](#getDefaultBackgroundStrokes--) | Varsayılan arka plan darbelerini alır. |
| [getDefaultObjectsRectangles()](#getDefaultObjectsRectangles--) | Varsayılan nesne dikdörtgenlerini alır. |
| [getAssumedObjects()](#getAssumedObjects--) | Varsayılan nesneleri alır. |
| [setAssumedObjects(List<AssumedObjectData> value)](#setAssumedObjects-java.util.List-com.aspose.imaging.masking.options.AssumedObjectData--) | Varsayılan nesneleri ayarlar. |
| [getCalculateDefaultStrokes()](#getCalculateDefaultStrokes--) | Varsayılan darbelerin hesaplanıp hesaplanmayacağını gösteren bir değeri alır. |
| [setCalculateDefaultStrokes(boolean value)](#setCalculateDefaultStrokes-boolean-) | Varsayılan darbelerin hesaplanıp hesaplanmayacağını gösteren bir değeri ayarlar. |
| [getPrecalculationProgressEventHandler()](#getPrecalculationProgressEventHandler--) | Varsayılan noktaların ön hesaplama süreci ilerleme olay işleyicisini alır. |
| [setPrecalculationProgressEventHandler(ProgressEventHandler value)](#setPrecalculationProgressEventHandler-com.aspose.imaging.ProgressEventHandler-) | Varsayılan noktaların ön hesaplama süreci ilerleme olay işleyicisini ayarlar. |

## Example: Saving image masking result with feathering based on image size.
Görüntü boyutuna göre yumuşatma ile görüntü maskeleme sonucu kaydediliyor. Görüntü maskelemesi otomatik hesaplanan varsayılan darbeler kullanılarak gerçekleştirilir. AutoMaskingGraphCutOptions sınıfının Args özelliği, varsayılan darbeler sonunda oraya yerleştirildiği için atlanabilir. MaskingResult[] results;
``` java

MaskingResult[] results; 
            
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius((Math.max(image.getWidth(), image.getHeight()) / 500) + 1);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}
            
```


## Example: Saving image masking result with feathering based on image size.
Görüntü boyutuna göre yumuşatma ile görüntü maskeleme sonucu kaydediliyor. Görüntü maskelemesi otomatik hesaplanan varsayılan darbeler kullanılarak gerçekleştirilir. Ayrıca iki assumed objects'in verileri de AutoMaskingGraphCutOptions sınıfının AssumedObjects özelliğinde belirtilir.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius((Math.max(image.getWidth(), image.getHeight()) / 500) + 1);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}
            
```


## Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.
Görüntü boyutuna göre yumuşatma ile görüntü maskeleme sonucu kaydediliyor ve yeni maskeleme yinelemesi için maskeleme seçenekleri yeniden kullanılıyor. Görüntü maskelemesi otomatik hesaplanan varsayılan darbeler kullanılarak gerçekleştirilir. Ayrıca iki assumed objects'in verileri de AutoMaskingGraphCutOptions sınıfının AssumedObjects özelliğinde belirtilir. İlk maskeleme sonucu alındıktan sonra uygulanan arka plan/ön plan darbeleri değiştirilir ve başka bir maskeleme yinelemesi yapılır.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// Bu noktada uygulanan ön plan/arka plan darbeleri analiz edilebilir ve buna dayanarak ek
// ön plan/arka plan darbeleri manuel olarak sağlanabilir.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // AutoMaskingGraphCutOptions yeniden kullanıldığında varsayılan darbelerin hesaplamasını ikinci kez yapmaya gerek yoktur.
    options.setCalculateDefaultStrokes(false);
    // AutoMaskingArgs sınıfının Args özelliğinde hem varsayılan darbeler hem de ObjectsPoints sağlandığında, Point dizileri birleştirilir.
    // İlk ObjectsPoints dizisi bir arka plan nokta dizisi olarak kabul edilir ve
    // İkinci ObjectsPoints dizisi ön plan noktaları dizisi olarak kabul edilir.
    // AutoMaskingArgs'in Args özelliğinde hem DefaultObjectsRectangles hem de ObjectsRectangles sağlandığında,
    // yalnızca Args'tan gelen dizi kullanılmaktadır.
    AutoMaskingArgs args = new AutoMaskingArgs();
    args.setObjectsPoints(new Point[][]
            {
                    new Point[] { new Point(100, 100), new Point(150, 100) },
                    new Point[] { new Point(500, 200) },
            });

    args.setObjectsRectangles( new Rectangle[] { new Rectangle(100, 100, 300, 300) });
    options.setArgs(args);
    results = new ImageMasking(image).decompose(options);
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}

```


## Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.
Resim boyutuna göre feathering uygulanarak görüntü maskeleme sonucu kaydediliyor, elde edilen varsayılan darbeler değiştiriliyor ve yeni maskeleme yinelemesi için kullanılıyor. Görüntü maskelemesi otomatik hesaplanan varsayılan darbeler kullanılarak gerçekleştirilir. Ayrıca iki varsayılan nesnenin verileri AutoMaskingGraphCutOptions'ın AssumedObjects özelliğinde belirtilir. İlk maskeleme sonucu alındıktan sonra uygulanan arka plan/ön plan darbeleri değiştirilir ve yeni bir GraphCutMaskingOptions örneği kullanılarak başka bir maskeleme yinelemesi yapılır.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// Bu noktada uygulanan ön plan/arka plan darbeleri analiz edilebilir ve buna dayanarak ek
// ön plan/arka plan darbeleri manuel olarak sağlanabilir.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingArgs args = new AutoMaskingArgs();
        args.setObjectsPoints(new Point[][]
                {
                        appliedBackgroundStrokes,
                        appliedForegroundStrokes
                });

        args.setObjectsRectangles(appliedObjectRectangles);
                    
        GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions();
        graphCutOptions.setFeatheringRadius(3);
        graphCutOptions.setMethod(SegmentationMethod.GraphCut);
        graphCutOptions.setDecompose(false);
        graphCutOptions.setExportOptions(pngOptions);
        graphCutOptions.setBackgroundReplacementColor(Color.getTransparent());
        graphCutOptions.setArgs(args);
                    
        results = new ImageMasking(image).decompose(graphCutOptions);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}
```

### AutoMaskingGraphCutOptions() {#AutoMaskingGraphCutOptions--}
```
public AutoMaskingGraphCutOptions()
```


Yeni bir [AutoMaskingGraphCutOptions](../../com.aspose.imaging.masking.options/automaskinggraphcutoptions) sınıfı örneği başlatır.

### getDefaultForegroundStrokes() {#getDefaultForegroundStrokes--}
```
public final Point[] getDefaultForegroundStrokes()
```


Önceden hesaplanmış varsayılan ön plan darbelerini alır.

**Returns:**
com.aspose.imaging.Point[] - önceden hesaplanmış varsayılan ön plan darbeleri.

**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
Görüntü boyutuna göre yumuşatma ile görüntü maskeleme sonucu kaydediliyor ve yeni maskeleme yinelemesi için maskeleme seçenekleri yeniden kullanılıyor. Görüntü maskelemesi otomatik hesaplanan varsayılan darbeler kullanılarak gerçekleştirilir. Ayrıca iki assumed objects'in verileri de AutoMaskingGraphCutOptions sınıfının AssumedObjects özelliğinde belirtilir. İlk maskeleme sonucu alındıktan sonra uygulanan arka plan/ön plan darbeleri değiştirilir ve başka bir maskeleme yinelemesi yapılır.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// Bu noktada uygulanan ön plan/arka plan darbeleri analiz edilebilir ve buna dayanarak ek
// ön plan/arka plan darbeleri manuel olarak sağlanabilir.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // AutoMaskingGraphCutOptions yeniden kullanıldığında varsayılan darbelerin hesaplamasını ikinci kez yapmaya gerek yoktur.
    options.setCalculateDefaultStrokes(false);
    // AutoMaskingArgs sınıfının Args özelliğinde hem varsayılan darbeler hem de ObjectsPoints sağlandığında, Point dizileri birleştirilir.
    // İlk ObjectsPoints dizisi bir arka plan nokta dizisi olarak kabul edilir ve
    // İkinci ObjectsPoints dizisi ön plan noktaları dizisi olarak kabul edilir.
    // AutoMaskingArgs'in Args özelliğinde hem DefaultObjectsRectangles hem de ObjectsRectangles sağlandığında,
    // yalnızca Args'tan gelen dizi kullanılmaktadır.
    AutoMaskingArgs args = new AutoMaskingArgs();
    args.setObjectsPoints(new Point[][]
            {
                    new Point[] { new Point(100, 100), new Point(150, 100) },
                    new Point[] { new Point(500, 200) },
            });

    args.setObjectsRectangles( new Rectangle[] { new Rectangle(100, 100, 300, 300) });
    options.setArgs(args);
    results = new ImageMasking(image).decompose(options);
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}

```


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
Resim boyutuna göre feathering uygulanarak görüntü maskeleme sonucu kaydediliyor, elde edilen varsayılan darbeler değiştiriliyor ve yeni maskeleme yinelemesi için kullanılıyor. Görüntü maskelemesi otomatik hesaplanan varsayılan darbeler kullanılarak gerçekleştirilir. Ayrıca iki varsayılan nesnenin verileri AutoMaskingGraphCutOptions'ın AssumedObjects özelliğinde belirtilir. İlk maskeleme sonucu alındıktan sonra uygulanan arka plan/ön plan darbeleri değiştirilir ve yeni bir GraphCutMaskingOptions örneği kullanılarak başka bir maskeleme yinelemesi yapılır.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// Bu noktada uygulanan ön plan/arka plan darbeleri analiz edilebilir ve buna dayanarak ek
// ön plan/arka plan darbeleri manuel olarak sağlanabilir.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingArgs args = new AutoMaskingArgs();
        args.setObjectsPoints(new Point[][]
                {
                        appliedBackgroundStrokes,
                        appliedForegroundStrokes
                });

        args.setObjectsRectangles(appliedObjectRectangles);
                    
        GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions();
        graphCutOptions.setFeatheringRadius(3);
        graphCutOptions.setMethod(SegmentationMethod.GraphCut);
        graphCutOptions.setDecompose(false);
        graphCutOptions.setExportOptions(pngOptions);
        graphCutOptions.setBackgroundReplacementColor(Color.getTransparent());
        graphCutOptions.setArgs(args);
                    
        results = new ImageMasking(image).decompose(graphCutOptions);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}
```

### getDefaultBackgroundStrokes() {#getDefaultBackgroundStrokes--}
```
public final Point[] getDefaultBackgroundStrokes()
```


Varsayılan arka plan darbelerini alır.

**Returns:**
com.aspose.imaging.Point[] - varsayılan arka plan darbeleri.

**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
Görüntü boyutuna göre yumuşatma ile görüntü maskeleme sonucu kaydediliyor ve yeni maskeleme yinelemesi için maskeleme seçenekleri yeniden kullanılıyor. Görüntü maskelemesi otomatik hesaplanan varsayılan darbeler kullanılarak gerçekleştirilir. Ayrıca iki assumed objects'in verileri de AutoMaskingGraphCutOptions sınıfının AssumedObjects özelliğinde belirtilir. İlk maskeleme sonucu alındıktan sonra uygulanan arka plan/ön plan darbeleri değiştirilir ve başka bir maskeleme yinelemesi yapılır.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// Bu noktada uygulanan ön plan/arka plan darbeleri analiz edilebilir ve buna dayanarak ek
// ön plan/arka plan darbeleri manuel olarak sağlanabilir.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // AutoMaskingGraphCutOptions yeniden kullanıldığında varsayılan darbelerin hesaplamasını ikinci kez yapmaya gerek yoktur.
    options.setCalculateDefaultStrokes(false);
    // AutoMaskingArgs sınıfının Args özelliğinde hem varsayılan darbeler hem de ObjectsPoints sağlandığında, Point dizileri birleştirilir.
    // İlk ObjectsPoints dizisi bir arka plan nokta dizisi olarak kabul edilir ve
    // İkinci ObjectsPoints dizisi ön plan noktaları dizisi olarak kabul edilir.
    // AutoMaskingArgs'in Args özelliğinde hem DefaultObjectsRectangles hem de ObjectsRectangles sağlandığında,
    // yalnızca Args'tan gelen dizi kullanılmaktadır.
    AutoMaskingArgs args = new AutoMaskingArgs();
    args.setObjectsPoints(new Point[][]
            {
                    new Point[] { new Point(100, 100), new Point(150, 100) },
                    new Point[] { new Point(500, 200) },
            });

    args.setObjectsRectangles( new Rectangle[] { new Rectangle(100, 100, 300, 300) });
    options.setArgs(args);
    results = new ImageMasking(image).decompose(options);
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}

```


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
Resim boyutuna göre feathering uygulanarak görüntü maskeleme sonucu kaydediliyor, elde edilen varsayılan darbeler değiştiriliyor ve yeni maskeleme yinelemesi için kullanılıyor. Görüntü maskelemesi otomatik hesaplanan varsayılan darbeler kullanılarak gerçekleştirilir. Ayrıca iki varsayılan nesnenin verileri AutoMaskingGraphCutOptions'ın AssumedObjects özelliğinde belirtilir. İlk maskeleme sonucu alındıktan sonra uygulanan arka plan/ön plan darbeleri değiştirilir ve yeni bir GraphCutMaskingOptions örneği kullanılarak başka bir maskeleme yinelemesi yapılır.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// Bu noktada uygulanan ön plan/arka plan darbeleri analiz edilebilir ve buna dayanarak ek
// ön plan/arka plan darbeleri manuel olarak sağlanabilir.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingArgs args = new AutoMaskingArgs();
        args.setObjectsPoints(new Point[][]
                {
                        appliedBackgroundStrokes,
                        appliedForegroundStrokes
                });

        args.setObjectsRectangles(appliedObjectRectangles);
                    
        GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions();
        graphCutOptions.setFeatheringRadius(3);
        graphCutOptions.setMethod(SegmentationMethod.GraphCut);
        graphCutOptions.setDecompose(false);
        graphCutOptions.setExportOptions(pngOptions);
        graphCutOptions.setBackgroundReplacementColor(Color.getTransparent());
        graphCutOptions.setArgs(args);
                    
        results = new ImageMasking(image).decompose(graphCutOptions);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}
```

### getDefaultObjectsRectangles() {#getDefaultObjectsRectangles--}
```
public final Rectangle[] getDefaultObjectsRectangles()
```


Varsayılan nesne dikdörtgenlerini alır.

**Returns:**
com.aspose.imaging.Rectangle[] - varsayılan nesne dikdörtgenleri.

**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
Görüntü boyutuna göre yumuşatma ile görüntü maskeleme sonucu kaydediliyor ve yeni maskeleme yinelemesi için maskeleme seçenekleri yeniden kullanılıyor. Görüntü maskelemesi otomatik hesaplanan varsayılan darbeler kullanılarak gerçekleştirilir. Ayrıca iki assumed objects'in verileri de AutoMaskingGraphCutOptions sınıfının AssumedObjects özelliğinde belirtilir. İlk maskeleme sonucu alındıktan sonra uygulanan arka plan/ön plan darbeleri değiştirilir ve başka bir maskeleme yinelemesi yapılır.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// Bu noktada uygulanan ön plan/arka plan darbeleri analiz edilebilir ve buna dayanarak ek
// ön plan/arka plan darbeleri manuel olarak sağlanabilir.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // AutoMaskingGraphCutOptions yeniden kullanıldığında varsayılan darbelerin hesaplamasını ikinci kez yapmaya gerek yoktur.
    options.setCalculateDefaultStrokes(false);
    // AutoMaskingArgs sınıfının Args özelliğinde hem varsayılan darbeler hem de ObjectsPoints sağlandığında, Point dizileri birleştirilir.
    // İlk ObjectsPoints dizisi bir arka plan nokta dizisi olarak kabul edilir ve
    // İkinci ObjectsPoints dizisi ön plan noktaları dizisi olarak kabul edilir.
    // AutoMaskingArgs'in Args özelliğinde hem DefaultObjectsRectangles hem de ObjectsRectangles sağlandığında,
    // yalnızca Args'tan gelen dizi kullanılmaktadır.
    AutoMaskingArgs args = new AutoMaskingArgs();
    args.setObjectsPoints(new Point[][]
            {
                    new Point[] { new Point(100, 100), new Point(150, 100) },
                    new Point[] { new Point(500, 200) },
            });

    args.setObjectsRectangles( new Rectangle[] { new Rectangle(100, 100, 300, 300) });
    options.setArgs(args);
    results = new ImageMasking(image).decompose(options);
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}

```


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
Resim boyutuna göre feathering uygulanarak görüntü maskeleme sonucu kaydediliyor, elde edilen varsayılan darbeler değiştiriliyor ve yeni maskeleme yinelemesi için kullanılıyor. Görüntü maskelemesi otomatik hesaplanan varsayılan darbeler kullanılarak gerçekleştirilir. Ayrıca iki varsayılan nesnenin verileri AutoMaskingGraphCutOptions'ın AssumedObjects özelliğinde belirtilir. İlk maskeleme sonucu alındıktan sonra uygulanan arka plan/ön plan darbeleri değiştirilir ve yeni bir GraphCutMaskingOptions örneği kullanılarak başka bir maskeleme yinelemesi yapılır.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// Bu noktada uygulanan ön plan/arka plan darbeleri analiz edilebilir ve buna dayanarak ek
// ön plan/arka plan darbeleri manuel olarak sağlanabilir.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingArgs args = new AutoMaskingArgs();
        args.setObjectsPoints(new Point[][]
                {
                        appliedBackgroundStrokes,
                        appliedForegroundStrokes
                });

        args.setObjectsRectangles(appliedObjectRectangles);
                    
        GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions();
        graphCutOptions.setFeatheringRadius(3);
        graphCutOptions.setMethod(SegmentationMethod.GraphCut);
        graphCutOptions.setDecompose(false);
        graphCutOptions.setExportOptions(pngOptions);
        graphCutOptions.setBackgroundReplacementColor(Color.getTransparent());
        graphCutOptions.setArgs(args);
                    
        results = new ImageMasking(image).decompose(graphCutOptions);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}
```

### getAssumedObjects() {#getAssumedObjects--}
```
public final List<AssumedObjectData> getAssumedObjects()
```


Varsayılan nesneleri alır.

**Returns:**
java.util.List<com.aspose.imaging.masking.options.AssumedObjectData> - varsayılan nesneler.
### setAssumedObjects(List<AssumedObjectData> value) {#setAssumedObjects-java.util.List-com.aspose.imaging.masking.options.AssumedObjectData--}
```
public final void setAssumedObjects(List<AssumedObjectData> value)
```


Varsayılan nesneleri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<com.aspose.imaging.masking.options.AssumedObjectData> | varsayılan nesneler. |

### getCalculateDefaultStrokes() {#getCalculateDefaultStrokes--}
```
public final boolean getCalculateDefaultStrokes()
```


Varsayılan darbelerin hesaplanıp hesaplanmayacağını gösteren bir değeri alır.

**Returns:**
boolean - varsayılan darbelerin hesaplanıp hesaplanmayacağını gösteren bir değer.
### setCalculateDefaultStrokes(boolean value) {#setCalculateDefaultStrokes-boolean-}
```
public final void setCalculateDefaultStrokes(boolean value)
```


Varsayılan darbelerin hesaplanıp hesaplanmayacağını gösteren bir değeri ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean | varsayılan darbelerin hesaplanıp hesaplanmayacağını gösteren bir değer. |


**Example: Saving image masking result with feathering based on image size.**
Görüntü boyutuna göre yumuşatma ile görüntü maskeleme sonucu kaydediliyor. Görüntü maskelemesi otomatik hesaplanan varsayılan darbeler kullanılarak gerçekleştirilir. AutoMaskingGraphCutOptions sınıfının Args özelliği, varsayılan darbeler sonunda oraya yerleştirildiği için atlanabilir. MaskingResult[] results;
``` java

MaskingResult[] results; 
            
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius((Math.max(image.getWidth(), image.getHeight()) / 500) + 1);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}
            
```


**Example: Saving image masking result with feathering based on image size.**
Görüntü boyutuna göre yumuşatma ile görüntü maskeleme sonucu kaydediliyor. Görüntü maskelemesi otomatik hesaplanan varsayılan darbeler kullanılarak gerçekleştirilir. Ayrıca iki assumed objects'in verileri de AutoMaskingGraphCutOptions sınıfının AssumedObjects özelliğinde belirtilir.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius((Math.max(image.getWidth(), image.getHeight()) / 500) + 1);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}
            
```


**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
Görüntü boyutuna göre yumuşatma ile görüntü maskeleme sonucu kaydediliyor ve yeni maskeleme yinelemesi için maskeleme seçenekleri yeniden kullanılıyor. Görüntü maskelemesi otomatik hesaplanan varsayılan darbeler kullanılarak gerçekleştirilir. Ayrıca iki assumed objects'in verileri de AutoMaskingGraphCutOptions sınıfının AssumedObjects özelliğinde belirtilir. İlk maskeleme sonucu alındıktan sonra uygulanan arka plan/ön plan darbeleri değiştirilir ve başka bir maskeleme yinelemesi yapılır.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// Bu noktada uygulanan ön plan/arka plan darbeleri analiz edilebilir ve buna dayanarak ek
// ön plan/arka plan darbeleri manuel olarak sağlanabilir.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // AutoMaskingGraphCutOptions yeniden kullanıldığında varsayılan darbelerin hesaplamasını ikinci kez yapmaya gerek yoktur.
    options.setCalculateDefaultStrokes(false);
    // AutoMaskingArgs sınıfının Args özelliğinde hem varsayılan darbeler hem de ObjectsPoints sağlandığında, Point dizileri birleştirilir.
    // İlk ObjectsPoints dizisi bir arka plan nokta dizisi olarak kabul edilir ve
    // İkinci ObjectsPoints dizisi ön plan noktaları dizisi olarak kabul edilir.
    // AutoMaskingArgs'in Args özelliğinde hem DefaultObjectsRectangles hem de ObjectsRectangles sağlandığında,
    // yalnızca Args'tan gelen dizi kullanılmaktadır.
    AutoMaskingArgs args = new AutoMaskingArgs();
    args.setObjectsPoints(new Point[][]
            {
                    new Point[] { new Point(100, 100), new Point(150, 100) },
                    new Point[] { new Point(500, 200) },
            });

    args.setObjectsRectangles( new Rectangle[] { new Rectangle(100, 100, 300, 300) });
    options.setArgs(args);
    results = new ImageMasking(image).decompose(options);
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}

```


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
Resim boyutuna göre feathering uygulanarak görüntü maskeleme sonucu kaydediliyor, elde edilen varsayılan darbeler değiştiriliyor ve yeni maskeleme yinelemesi için kullanılıyor. Görüntü maskelemesi otomatik hesaplanan varsayılan darbeler kullanılarak gerçekleştirilir. Ayrıca iki varsayılan nesnenin verileri AutoMaskingGraphCutOptions'ın AssumedObjects özelliğinde belirtilir. İlk maskeleme sonucu alındıktan sonra uygulanan arka plan/ön plan darbeleri değiştirilir ve yeni bir GraphCutMaskingOptions örneği kullanılarak başka bir maskeleme yinelemesi yapılır.
``` java
List<AssumedObjectData> assumedObjects = new LinkedList<AssumedObjectData>();
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Human, new Rectangle(100, 100, 150, 300)));
assumedObjects.add(new AssumedObjectData(DetectedObjectType.Dog, new Rectangle(300, 100, 50, 30)));

MaskingResult[] results;
AutoMaskingGraphCutOptions options = new AutoMaskingGraphCutOptions();
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        options.setAssumedObjects(assumedObjects);
        options.setCalculateDefaultStrokes(true);
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());

        results = new ImageMasking(image).decompose(options);
    }
}

// Bu noktada uygulanan ön plan/arka plan darbeleri analiz edilebilir ve buna dayanarak ek
// ön plan/arka plan darbeleri manuel olarak sağlanabilir.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}

appliedBackgroundStrokes[5] = new Point(100, 100);
appliedBackgroundStrokes[15] = new Point(150, 100);

appliedForegroundStrokes[1] = new Point(500, 200);

appliedObjectRectangles[0] = new Rectangle(100, 100, 300, 300);

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingArgs args = new AutoMaskingArgs();
        args.setObjectsPoints(new Point[][]
                {
                        appliedBackgroundStrokes,
                        appliedForegroundStrokes
                });

        args.setObjectsRectangles(appliedObjectRectangles);
                    
        GraphCutMaskingOptions graphCutOptions = new GraphCutMaskingOptions();
        graphCutOptions.setFeatheringRadius(3);
        graphCutOptions.setMethod(SegmentationMethod.GraphCut);
        graphCutOptions.setDecompose(false);
        graphCutOptions.setExportOptions(pngOptions);
        graphCutOptions.setBackgroundReplacementColor(Color.getTransparent());
        graphCutOptions.setArgs(args);
                    
        results = new ImageMasking(image).decompose(graphCutOptions);
    }
}

try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// kaynakları serbest bırak
for (MaskingResult res : results)
{
    res.close();
}
```

### getPrecalculationProgressEventHandler() {#getPrecalculationProgressEventHandler--}
```
public final ProgressEventHandler getPrecalculationProgressEventHandler()
```


Varsayılan noktaların ön hesaplama süreci ilerleme olay işleyicisini alır.

Değer: İlerleme olay işleyicisi.

**Returns:**
[ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) - the default points pre-calculation process progress event handler.
### setPrecalculationProgressEventHandler(ProgressEventHandler value) {#setPrecalculationProgressEventHandler-com.aspose.imaging.ProgressEventHandler-}
```
public final void setPrecalculationProgressEventHandler(ProgressEventHandler value)
```


Varsayılan noktaların ön hesaplama süreci ilerleme olay işleyicisini ayarlar.

Değer: İlerleme olay işleyicisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [ProgressEventHandler](../../com.aspose.imaging/progresseventhandler) | varsayılan noktaların ön hesaplama süreci ilerleme olayı işleyicisi. |

