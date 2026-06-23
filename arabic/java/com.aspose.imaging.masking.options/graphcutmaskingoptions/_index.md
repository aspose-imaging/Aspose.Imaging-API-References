---
title: "GraphCutMaskingOptions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "خيارات القناع التلقائي GraphCut."
type: docs
weight: 14
url: /ar/java/com.aspose.imaging.masking.options/graphcutmaskingoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.masking.options.MaskingOptions](../../com.aspose.imaging.masking.options/maskingoptions)
```
public class GraphCutMaskingOptions extends MaskingOptions
```

خيارات القناع التلقائي GraphCut.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [GraphCutMaskingOptions()](#GraphCutMaskingOptions--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFeatheringRadius()](#getFeatheringRadius--) | يحصل على نصف قطر التمويه. |
| [setFeatheringRadius(int value)](#setFeatheringRadius-int-) | يضبط نصف قطر التمويه. |

## Example: Saving image masking result with feathering based on image size.
حفظ نتيجة قناع الصورة مع تمويه بناءً على حجم الصورة. يتم تنفيذ قناع الصورة باستخدام الضربات الافتراضية المحسوبة تلقائيًا. يمكن حذف خاصية Args من AutoMaskingGraphCutOptions لأن الضربات الافتراضية توضع هناك في النهاية.MaskingResult[] results;
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

// تحرير الموارد
for (MaskingResult res : results)
{
    res.close();
}
            
```


## Example: Saving Graph Cut image masking result with feathering set to 3.
حفظ نتيجة تمويه صورة Graph Cut مع ضبط التمويه إلى 3. يتم تنفيذ تمويه الصورة باستخدام مصفوفة Point المحددة.
``` java
MaskingResult[] results;
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingArgs args = new AutoMaskingArgs();
        args.setObjectsPoints(new Point[][] {
                                    new Point[]
                                            {
                                                    new Point(100, 100),
                                            },
                            });

        GraphCutMaskingOptions options = new GraphCutMaskingOptions();
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());
        options.setArgs(args);

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


## Example: Saving image masking result with feathering based on image size.
حفظ نتيجة قناع الصورة مع تمويه بناءً على حجم الصورة. يتم تنفيذ قناع الصورة باستخدام الضربات الافتراضية المحسوبة تلقائيًا. بالإضافة إلى ذلك، يتم تحديد بيانات الكائنين المفترضين أيضًا في خاصية AssumedObjects من AutoMaskingGraphCutOptions.
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
حفظ نتيجة قناع الصورة مع تمويه بناءً على حجم الصورة وإعادة استخدام خيارات القناع للتكرار الجديد للقناع. يتم تنفيذ قناع الصورة باستخدام الضربات الافتراضية المحسوبة تلقائيًا. بالإضافة إلى ذلك، يتم تحديد بيانات الكائنين المفترضين أيضًا في خاصية AssumedObjects من AutoMaskingGraphCutOptions. بعد الحصول على نتيجة القناع الأولية، يتم تعديل الضربات الخلفية/الأمامية المطبقة ويتم إجراء تكرار قناع آخر.
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

// في هذه المرحلة يمكن تحليل الضربات الأمامية/الخلفية المطبقة وبناءً عليها إضافية
// يمكن توفير الضربات الأمامية/الخلفية يدويًا.
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
    // باستخدام AutoMaskingGraphCutOptions مرة أخرى لا حاجة لإجراء حسابات الضربات الافتراضية مرة ثانية.
    options.setCalculateDefaultStrokes(false);
    // عند توفير كل من الضربات الافتراضية وObjectsPoints في خاصية Args من AutoMaskingArgs، يتم دمج مصفوفات النقاط في النهاية.
    // يُعتبر مصفوفة ObjectsPoints الأولى مصفوفة نقاط خلفية و
    // المصفوفة الثانية من ObjectsPoints تُعتبر مصفوفة نقاط أمامية.
    // عند توفير كل من DefaultObjectsRectangles وObjectsRectangles في خاصية Args من AutoMaskingArgs،
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
حفظ نتيجة قناع الصورة مع تمويه بناءً على حجم الصورة، تعديل الضربات الافتراضية المستلمة واستخدامها للتكرار الجديد للقناع. يتم تنفيذ قناع الصورة باستخدام الضربات الافتراضية المحسوبة تلقائيًا. بالإضافة إلى ذلك، يتم تحديد بيانات الكائنين المفترضين أيضًا في خاصية AssumedObjects من AutoMaskingGraphCutOptions. بعد الحصول على نتيجة القناع الأولية، يتم تعديل الضربات الخلفية/الأمامية المطبقة ويتم إجراء تكرار قناع آخر باستخدام نسخة جديدة من GraphCutMaskingOptions.
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

// في هذه المرحلة يمكن تحليل الضربات الأمامية/الخلفية المطبقة وبناءً عليها إضافية
// يمكن توفير الضربات الأمامية/الخلفية يدويًا.

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

### GraphCutMaskingOptions() {#GraphCutMaskingOptions--}
```
public GraphCutMaskingOptions()
```


### getFeatheringRadius() {#getFeatheringRadius--}
```
public final int getFeatheringRadius()
```


يحصل على نصف قطر التمويه.

**Returns:**
int - نصف قطر التمويه.
### setFeatheringRadius(int value) {#setFeatheringRadius-int-}
```
public final void setFeatheringRadius(int value)
```


يضبط نصف قطر التمويه.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | int | نصف قطر التمويه. |


**Example: Saving image masking result with feathering based on image size.**
حفظ نتيجة قناع الصورة مع تمويه بناءً على حجم الصورة. يتم تنفيذ قناع الصورة باستخدام الضربات الافتراضية المحسوبة تلقائيًا. يمكن حذف خاصية Args من AutoMaskingGraphCutOptions لأن الضربات الافتراضية توضع هناك في النهاية.MaskingResult[] results;
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

// تحرير الموارد
for (MaskingResult res : results)
{
    res.close();
}
            
```


**Example: Saving Graph Cut image masking result with feathering set to 3.**
حفظ نتيجة تمويه صورة Graph Cut مع ضبط التمويه إلى 3. يتم تنفيذ تمويه الصورة باستخدام مصفوفة Point المحددة.
``` java
MaskingResult[] results;
try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    try (PngOptions pngOptions = new PngOptions())
    {
        pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
        pngOptions.setSource(new FileCreateSource("tempFile"));

        AutoMaskingArgs args = new AutoMaskingArgs();
        args.setObjectsPoints(new Point[][] {
                                    new Point[]
                                            {
                                                    new Point(100, 100),
                                            },
                            });

        GraphCutMaskingOptions options = new GraphCutMaskingOptions();
        options.setFeatheringRadius(3);
        options.setMethod(SegmentationMethod.GraphCut);
        options.setDecompose(false);
        options.setExportOptions(pngOptions);
        options.setBackgroundReplacementColor(Color.getTransparent());
        options.setArgs(args);

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


**Example: Saving image masking result with feathering based on image size.**
حفظ نتيجة قناع الصورة مع تمويه بناءً على حجم الصورة. يتم تنفيذ قناع الصورة باستخدام الضربات الافتراضية المحسوبة تلقائيًا. بالإضافة إلى ذلك، يتم تحديد بيانات الكائنين المفترضين أيضًا في خاصية AssumedObjects من AutoMaskingGraphCutOptions.
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


**Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.**
حفظ نتيجة قناع الصورة مع تمويه بناءً على حجم الصورة وإعادة استخدام خيارات القناع للتكرار الجديد للقناع. يتم تنفيذ قناع الصورة باستخدام الضربات الافتراضية المحسوبة تلقائيًا. بالإضافة إلى ذلك، يتم تحديد بيانات الكائنين المفترضين أيضًا في خاصية AssumedObjects من AutoMaskingGraphCutOptions. بعد الحصول على نتيجة القناع الأولية، يتم تعديل الضربات الخلفية/الأمامية المطبقة ويتم إجراء تكرار قناع آخر.
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

// في هذه المرحلة يمكن تحليل الضربات الأمامية/الخلفية المطبقة وبناءً عليها إضافية
// يمكن توفير الضربات الأمامية/الخلفية يدويًا.
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
    // باستخدام AutoMaskingGraphCutOptions مرة أخرى لا حاجة لإجراء حسابات الضربات الافتراضية مرة ثانية.
    options.setCalculateDefaultStrokes(false);
    // عند توفير كل من الضربات الافتراضية وObjectsPoints في خاصية Args من AutoMaskingArgs، يتم دمج مصفوفات النقاط في النهاية.
    // يُعتبر مصفوفة ObjectsPoints الأولى مصفوفة نقاط خلفية و
    // المصفوفة الثانية من ObjectsPoints تُعتبر مصفوفة نقاط أمامية.
    // عند توفير كل من DefaultObjectsRectangles وObjectsRectangles في خاصية Args من AutoMaskingArgs،
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


**Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.**
حفظ نتيجة قناع الصورة مع تمويه بناءً على حجم الصورة، تعديل الضربات الافتراضية المستلمة واستخدامها للتكرار الجديد للقناع. يتم تنفيذ قناع الصورة باستخدام الضربات الافتراضية المحسوبة تلقائيًا. بالإضافة إلى ذلك، يتم تحديد بيانات الكائنين المفترضين أيضًا في خاصية AssumedObjects من AutoMaskingGraphCutOptions. بعد الحصول على نتيجة القناع الأولية، يتم تعديل الضربات الخلفية/الأمامية المطبقة ويتم إجراء تكرار قناع آخر باستخدام نسخة جديدة من GraphCutMaskingOptions.
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

// في هذه المرحلة يمكن تحليل الضربات الأمامية/الخلفية المطبقة وبناءً عليها إضافية
// يمكن توفير الضربات الأمامية/الخلفية يدويًا.

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

