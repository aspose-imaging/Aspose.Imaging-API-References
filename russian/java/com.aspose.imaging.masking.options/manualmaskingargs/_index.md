---
title: "ManualMaskingArgs"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет аргументы, указанные для ручного метода маскирования"
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.masking.options/manualmaskingargs/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.masking.options.IMaskingArgs](../../com.aspose.imaging.masking.options/imaskingargs)
```
public class ManualMaskingArgs implements IMaskingArgs
```

Представляет аргументы, указанные для ручного метода маскирования
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ManualMaskingArgs()](#ManualMaskingArgs--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getMask()](#getMask--) | Получает набор графических фигур, образующих маску. |
| [setMask(GraphicsPath value)](#setMask-com.aspose.imaging.GraphicsPath-) | Устанавливает набор графических фигур, образующих маску. |

## Example: This example shows how to decompose a raster image into multiple images using image masking and a manual mask.
В этом примере показано, как разбить растровое изображение на несколько изображений с помощью маскирования изображения и ручной маски. Маскирование изображения — это техника обработки изображений, используемая для разделения фона и объектов переднего плана.
``` java
String dir = "c:\\temp\\";

// Определите ручную маску.
com.aspose.imaging.GraphicsPath manualMask = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();
figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 40, 40)));
figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 20, 50, 30)));
manualMask.addFigure(figure);

// Установите ручную маску.
com.aspose.imaging.masking.options.ManualMaskingArgs args = new com.aspose.imaging.masking.options.ManualMaskingArgs();
args.setMask(manualMask);

com.aspose.imaging.RasterImage image = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "Blue hills.png");
try {
    com.aspose.imaging.masking.options.MaskingOptions maskingOptions = new com.aspose.imaging.masking.options.MaskingOptions();

    // Используйте алгоритм ручного кластеризации.
    maskingOptions.setMethod(com.aspose.imaging.masking.options.SegmentationMethod.Manual);

    // Все фигуры, составляющие маску, будут объединены в одну.
    maskingOptions.setDecompose(false);
    maskingOptions.setArgs(args);

    // Максимальный ожидаемый размер PNG‑изображения TrueColor с альфа‑каналом.
    int estimatedMaxImageSize = image.getWidth() * image.getHeight() * 4;

    // Каждый кластер (сегмент) будет сохранён в отдельный PNG‑файл.
    com.aspose.imaging.imageoptions.PngOptions exportOptions = new com.aspose.imaging.imageoptions.PngOptions();
    exportOptions.setColorType(com.aspose.imaging.fileformats.png.PngColorType.TruecolorWithAlpha);
    exportOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[estimatedMaxImageSize])));

    // Цвет фона будет оранжевым.
    maskingOptions.setBackgroundReplacementColor(com.aspose.imaging.Color.getOrange());
    maskingOptions.setExportOptions(exportOptions);

    // Область исходного изображения, к которой будет применено маскирование.
    maskingOptions.setMaskingArea(new com.aspose.imaging.Rectangle(50, 50, 120, 120));

    // Создайте экземпляр класса ImageMasking.
    com.aspose.imaging.masking.ImageMasking masking = new com.aspose.imaging.masking.ImageMasking(image);

    // Разделите исходное изображение на несколько кластеров (сегментов).
    com.aspose.imaging.masking.result.MaskingResult maskingResults = masking.decompose(maskingOptions);

    try
    {
        // Получите изображения из результата маскирования и сохраните их в PNG.
        for (int i = 0; i < maskingResults.getLength(); i++) {
            String outputFileName = String.format("Blue hills.Segment%s.png", maskingResults.get_Item(i).getObjectNumber());
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

### ManualMaskingArgs() {#ManualMaskingArgs--}
```
public ManualMaskingArgs()
```


### getMask() {#getMask--}
```
public final GraphicsPath getMask()
```


Получает набор графических фигур, образующих маску.

Значение: Маска.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - the set of graphic shapes that form mask.
### setMask(GraphicsPath value) {#setMask-com.aspose.imaging.GraphicsPath-}
```
public final void setMask(GraphicsPath value)
```


Устанавливает набор графических фигур, образующих маску.

Значение: Маска.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | набор графических фигур, образующих маску. |

