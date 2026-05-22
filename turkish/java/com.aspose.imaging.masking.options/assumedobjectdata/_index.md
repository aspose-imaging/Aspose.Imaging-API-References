---
title: "AssumedObjectData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Varsayılan nesnelerin verileri."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.masking.options/assumedobjectdata/
---
**Inheritance:**
java.lang.Object
```
public class AssumedObjectData
```

Varsayılan nesnenin verileri. Nesnenin türünü ve alanını içerir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [AssumedObjectData()](#AssumedObjectData--) | Yeni bir [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata) sınıfı örneği başlatır. |
| [AssumedObjectData(int type, Rectangle bounds)](#AssumedObjectData-int-com.aspose.imaging.Rectangle-) | Yeni bir [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata) sınıfı örneği başlatır. |
| [AssumedObjectData(String type, Rectangle bounds)](#AssumedObjectData-java.lang.String-com.aspose.imaging.Rectangle-) | Yeni bir [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Nesnenin türünü alır. |
| [setType(int value)](#setType-int-) | Nesnenin türünü ayarlar. |
| [getBounds()](#getBounds--) | Nesnenin sınırlarını alır. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Nesnenin sınırlarını ayarlar. |

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

### AssumedObjectData() {#AssumedObjectData--}
```
public AssumedObjectData()
```


Yeni bir [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata) sınıfı örneği başlatır.

### AssumedObjectData(int type, Rectangle bounds) {#AssumedObjectData-int-com.aspose.imaging.Rectangle-}
```
public AssumedObjectData(int type, Rectangle bounds)
```


Yeni bir [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | int | Nesnenin türü. |
| bounds | [Rectangle](../../com.aspose.imaging/rectangle) | Nesnenin sınırları. |

### AssumedObjectData(String type, Rectangle bounds) {#AssumedObjectData-java.lang.String-com.aspose.imaging.Rectangle-}
```
public AssumedObjectData(String type, Rectangle bounds)
```


Yeni bir [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tür | java.lang.String | Nesnenin türü. |
| bounds | [Rectangle](../../com.aspose.imaging/rectangle) | Nesnenin sınırları. |

### getType() {#getType--}
```
public final int getType()
```


Nesnenin türünü alır.

**Returns:**
int - nesnenin türü.
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Nesnenin türünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | nesnenin türü. |

### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Nesnenin sınırlarını alır.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the object's bounds.
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Nesnenin sınırlarını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | nesnenin sınırları. |

