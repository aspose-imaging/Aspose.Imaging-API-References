---
title: "DetectedObjectType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تعداد أنواع الكائنات المكتشفة."
type: docs
weight: 13
url: /ar/java/com.aspose.imaging.masking.options/detectedobjecttype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class DetectedObjectType extends System.Enum
```

تعداد أنواع الكائنات المكتشفة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [Human](#Human) | نوع الكائن البشري. |
| [Other](#Other) | نوع الكائن الآخر. |

## Example: Saving image masking result with feathering based on image size.
حفظ نتيجة قناع الصورة مع تمويه بناءً على حجم الصورة. يتم تنفيذ قناع الصورة باستخدام الخطوط الافتراضية المحسوبة تلقائياً. بالإضافة إلى ذلك، يتم تحديد بيانات الكائنين المفترضين أيضاً في خاصية AssumedObjects في AutoMaskingGraphCutOptions.
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

// تحرير الموارد
for (MaskingResult res : results)
{
    res.close();
}
            
```


## Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.
حفظ نتيجة قناع الصورة مع تمويه بناءً على حجم الصورة وإعادة استخدام خيارات القناع للتكرار الجديد. يتم تنفيذ قناع الصورة باستخدام الخطوط الافتراضية المحسوبة تلقائياً. بالإضافة إلى ذلك، يتم تحديد بيانات الكائنين المفترضين أيضاً في خاصية AssumedObjects في AutoMaskingGraphCutOptions. بعد الحصول على نتيجة القناع الأولية، يتم تعديل الخطوط الخلفية/الأمامية المطبقة ويتم إجراء تكرار قناع آخر.
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

// في هذه المرحلة يمكن تحليل الخطوط الأمامية/الخلفية المطبقة وعلى أساسها إضافية
// يمكن توفير الخطوط الأمامية/الخلفية يدوياً.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// تحرير الموارد
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // باستخدام AutoMaskingGraphCutOptions مرة أخرى لا حاجة لإجراء حسابات الخطوط الافتراضية للمرة الثانية.
    options.setCalculateDefaultStrokes(false);
    // عند توفير كل من الخطوط الافتراضية وObjectsPoints في خاصية Args في AutoMaskingArgs، يتم دمج مصفوفات النقاط في النهاية.
    // يُعتبر مصفوفة ObjectsPoints الأولى مصفوفة نقاط خلفية و
    // يُعتبر مصفوفة ObjectsPoints الثانية مصفوفة نقاط أمامية.
    // عند توفير كل من DefaultObjectsRectangles و ObjectsRectangles في خاصية Args من AutoMaskingArgs،
    // يتم استخدام المصفوفة فقط من Args.
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

// تحرير الموارد
for (MaskingResult res : results)
{
    res.close();
}

```


## Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.
حفظ نتيجة قناع الصورة مع التنعيم بناءً على حجم الصورة، وتعديل الضربات الافتراضية المستحصلة واستخدامها في تكرار القناع الجديد. يتم تنفيذ قناع الصورة باستخدام الضربات الافتراضية المحسوبة تلقائيًا. بالإضافة إلى ذلك، يتم تحديد بيانات الكائنين المفترضين أيضًا في خاصية AssumedObjects من AutoMaskingGraphCutOptions. بعد الحصول على نتيجة القناع الأولية، يتم تعديل الضربات الخلفية/الأمامية المطبقة ويتم إجراء تكرار قناع آخر باستخدام نسخة جديدة من GraphCutMaskingOptions.
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

// في هذه المرحلة يمكن تحليل الخطوط الأمامية/الخلفية المطبقة وعلى أساسها إضافية
// يمكن توفير الخطوط الأمامية/الخلفية يدوياً.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// تحرير الموارد
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

// تحرير الموارد
for (MaskingResult res : results)
{
    res.close();
}
```

### Human {#Human}
```
public static final int Human
```


نوع الكائن البشري.

### Other {#Other}
```
public static final int Other
```


نوع الكائن الآخر.

