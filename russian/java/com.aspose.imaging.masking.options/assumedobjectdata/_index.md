---
title: "AssumedObjectData"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Данные предполагаемых объектов."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.masking.options/assumedobjectdata/
---
**Inheritance:**
java.lang.Object
```
public class AssumedObjectData
```

Данные предполагаемого объекта. Включает тип объекта и площадь.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [AssumedObjectData()](#AssumedObjectData--) | Инициализирует новый экземпляр класса [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata). |
| [AssumedObjectData(int type, Rectangle bounds)](#AssumedObjectData-int-com.aspose.imaging.Rectangle-) | Инициализирует новый экземпляр класса [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata). |
| [AssumedObjectData(String type, Rectangle bounds)](#AssumedObjectData-java.lang.String-com.aspose.imaging.Rectangle-) | Инициализирует новый экземпляр класса [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata). |
## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Получает тип объекта. |
| [setType(int value)](#setType-int-) | Устанавливает тип объекта. |
| [getBounds()](#getBounds--) | Получает границы объекта. |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Устанавливает границы объекта. |

## Example: Saving image masking result with feathering based on image size.
Сохранение результата маскирования изображения с растушевкой в зависимости от размера изображения. Маскирование изображения выполняется с использованием автоматически рассчитанных стандартных штрихов. Кроме того, данные двух предполагаемых объектов также указываются в свойстве AssumedObjects класса AutoMaskingGraphCutOptions.
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

// освободить ресурсы
for (MaskingResult res : results)
{
    res.close();
}
            
```


## Example: Saving image masking result with feathering based on image size and re-using masking options for the new masking iteration.
Сохранение результата маскирования изображения с растушевкой в зависимости от размера изображения и повторное использование параметров маскирования для новой итерации маскирования. Маскирование изображения выполняется с использованием автоматически рассчитанных стандартных штрихов. Кроме того, данные двух предполагаемых объектов также указываются в свойстве AssumedObjects класса AutoMaskingGraphCutOptions. После получения начального результата маскирования применённые штрихи фона/переднего плана изменяются, и выполняется ещё одна итерация маскирования.
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

// На данном этапе применённые штрихи переднего/фонового плана могут быть проанализированы, и на их основе дополнительные
// штрихи переднего/фонового плана могут быть предоставлены вручную.
Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// освободить ресурсы
for (MaskingResult res : results)
{
    res.close();
}

try (RasterImage image = (RasterImage)Image.load("input.jpg"))
{
    // При повторном использовании AutoMaskingGraphCutOptions нет необходимости выполнять расчёт стандартных штрихов второй раз.
    options.setCalculateDefaultStrokes(false);
    // Когда в свойстве Args класса AutoMaskingArgs предоставлены как стандартные штрихи, так и ObjectsPoints, массивы точек в итоге объединяются.
    // Первый массив ObjectsPoints считается массивом точек фона и
    // второй массив ObjectsPoints считается массивом точек переднего плана.
    // Когда оба свойства DefaultObjectsRectangles и ObjectsRectangles в свойстве Args класса AutoMaskingArgs предоставлены,
    // используется только массив из Args.
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

// освободить ресурсы
for (MaskingResult res : results)
{
    res.close();
}

```


## Example: Saving image masking result with feathering based on image size, modifying obtained default strokes and using it for the new masking iteration.
Сохранение результата маскирования изображения с растушевкой, основанной на размере изображения, модификация полученных стандартных штрихов и их использование для новой итерации маскирования. Маскирование изображения выполняется с использованием автоматически вычисленных стандартных штрихов. Кроме того, данные двух предполагаемых объектов также указаны в свойстве AssumedObjects класса AutoMaskingGraphCutOptions. После получения начального результата маскирования применённые штрихи фона/переднего плана модифицируются, и выполняется ещё одна итерация маскирования с использованием нового экземпляра GraphCutMaskingOptions.
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

// На данном этапе применённые штрихи переднего/фонового плана могут быть проанализированы, и на их основе дополнительные
// штрихи переднего/фонового плана могут быть предоставлены вручную.

Point[] appliedBackgroundStrokes = options.getDefaultBackgroundStrokes();
Point[] appliedForegroundStrokes = options.getDefaultForegroundStrokes();
Rectangle[] appliedObjectRectangles = options.getDefaultObjectsRectangles();
try (RasterImage resultImage = (RasterImage)results[1].getImage())
{
    PngOptions pngOptions = new PngOptions();
    pngOptions.setColorType(PngColorType.TruecolorWithAlpha);
    resultImage.save("output.png", pngOptions);
}

// освободить ресурсы
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

// освободить ресурсы
for (MaskingResult res : results)
{
    res.close();
}
```

### AssumedObjectData() {#AssumedObjectData--}
```
public AssumedObjectData()
```


Инициализирует новый экземпляр класса [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata).

### AssumedObjectData(int type, Rectangle bounds) {#AssumedObjectData-int-com.aspose.imaging.Rectangle-}
```
public AssumedObjectData(int type, Rectangle bounds)
```


Инициализирует новый экземпляр класса [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | int | Тип объекта. |
| bounds | [Rectangle](../../com.aspose.imaging/rectangle) | Границы объекта. |

### AssumedObjectData(String type, Rectangle bounds) {#AssumedObjectData-java.lang.String-com.aspose.imaging.Rectangle-}
```
public AssumedObjectData(String type, Rectangle bounds)
```


Инициализирует новый экземпляр класса [AssumedObjectData](../../com.aspose.imaging.masking.options/assumedobjectdata).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | java.lang.String | Тип объекта. |
| bounds | [Rectangle](../../com.aspose.imaging/rectangle) | Границы объекта. |

### getType() {#getType--}
```
public final int getType()
```


Получает тип объекта.

**Returns:**
int - тип объекта.
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Устанавливает тип объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | тип объекта. |

### getBounds() {#getBounds--}
```
public final Rectangle getBounds()
```


Получает границы объекта.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the object's bounds.
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public final void setBounds(Rectangle value)
```


Устанавливает границы объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) | границы объекта. |

