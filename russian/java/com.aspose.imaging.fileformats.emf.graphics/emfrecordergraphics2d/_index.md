---
title: "EmfRecorderGraphics2D"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Графика рекордера Emf"
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.graphics.MetafileRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d)
```
public final class EmfRecorderGraphics2D extends MetafileRecorderGraphics2D
```

Графика рекордера Emf
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfRecorderGraphics2D(Rectangle frame, Size deviceSize, Size deviceSizeMm)](#EmfRecorderGraphics2D-com.aspose.imaging.Rectangle-com.aspose.imaging.Size-com.aspose.imaging.Size-) | Инициализирует новый экземпляр класса `EmfRecorderGraphics2D`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | Получает или задаёт режим фона. |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Получает или задаёт режим фона. |
| [endRecording()](#endRecording--) | Останавливает запись. |
| [fromEmfImage(EmfImage emfImage)](#fromEmfImage-com.aspose.imaging.fileformats.emf.EmfImage-) | Получает экземпляр [EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d), содержащий все записи из изображения Emf. |

## Example: This example shows how to create a EMF image and draw some geometric shapes on it using EmfRecorderGraphics2D.

``` java
String dir = "c:\\temp\\";

// Размер изображения в пикселях
int deviceWidth = 600;
int deviceHeight = 400;

// Размер изображения в миллиметрах
int deviceWidthMm = (int) (deviceWidth / 100f);
int deviceHeightMm = (int) (deviceHeight / 100f);

com.aspose.imaging.Rectangle frame = new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight);

// Создать изображение EMF.
com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
        new com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D(
                frame,
                new com.aspose.imaging.Size(deviceWidth, deviceHeight),
                new com.aspose.imaging.Size(deviceWidthMm, deviceHeightMm));

// Нарисовать черный прямоугольник вдоль границ изображения, используя черное перо шириной 1 пиксель.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, deviceWidth, deviceHeight);

// Заполнить прямоугольник цветом white-smoke.
graphics.fillRectangle(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()),
        new com.aspose.imaging.Rectangle(10, 10, 580, 380));

// Нарисовать две диагональные линии, используя темно-зеленое перо шириной 1 пиксель.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, deviceWidth, deviceHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, deviceHeight, deviceWidth, 0);

// Нарисовать дугу внутри прямоугольника {0, 0, 200, 200}, используя синее перо шириной 2 пикселя.
graphics.drawArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2), new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Заполнить дугу
graphics.fillPie(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Нарисовать кубический безье, используя красное перо шириной 2 пикселя.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.Point(0, 0),
        new com.aspose.imaging.Point(200, 133),
        new com.aspose.imaging.Point(400, 166),
        new com.aspose.imaging.Point(600, 400));

// Нарисовать растровое изображение указанного размера в указанном месте.
// Изображение масштабируется, чтобы вписаться в требуемый прямоугольник.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw,
            new com.aspose.imaging.Rectangle(400, 200, 100, 50),
            new com.aspose.imaging.Rectangle(0, 0, deviceWidth, deviceHeight),
            com.aspose.imaging.GraphicsUnit.Pixel);
} finally {
    imageToDraw.dispose();
}

// Нарисовать строку текста
graphics.drawString("Hello World!",
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        com.aspose.imaging.Color.getDarkRed(), 200, 300);

// Создать путь для заполнения
com.aspose.imaging.Figure figureToFill = new com.aspose.imaging.Figure();
figureToFill.setClosed(true);

com.aspose.imaging.GraphicsPath pathToFill = new com.aspose.imaging.GraphicsPath();
pathToFill.addFigure(figureToFill);

figureToFill.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(400, 0, 200, 100), 45, 300),
                new com.aspose.imaging.shapes.BezierShape(
                        new com.aspose.imaging.PointF[]
                                {
                                        new com.aspose.imaging.PointF(300, 200),
                                        new com.aspose.imaging.PointF(400, 200),
                                        new com.aspose.imaging.PointF(500, 100),
                                        new com.aspose.imaging.PointF(600, 200),
                                }),
                new com.aspose.imaging.shapes.PolygonShape(
                        new com.aspose.imaging.PointF[]
                                {
                                        new com.aspose.imaging.PointF(300, 100),
                                }),
                new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(0, 100, 200, 200)),
        });

// Заполнить путь, используя желтую кисть и зеленое перо для обводки.
graphics.fillPath(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getYellow()), pathToFill);

// Создать путь для рисования
com.aspose.imaging.GraphicsPath pathToDraw = new com.aspose.imaging.GraphicsPath();
com.aspose.imaging.Figure figureToDraw = new com.aspose.imaging.Figure();
pathToDraw.addFigure(figureToDraw);

figureToDraw.addShapes(new com.aspose.imaging.Shape[]
        {
                new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(200, 200, 200, 200), 0, 360),
        });

// Нарисовать путь, используя оранжевое перо шириной 5 пикселей.
graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 5), pathToDraw);

// Для растеризации SVG необходимо указать параметры растеризации.
com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();
com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
saveOptions.setVectorRasterizationOptions(rasterizationOptions);

// Получить окончательное изображение WMF, включающее все команды рисования.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = graphics.endRecording();
try {
    emfImage.save(dir + "test.output.emf");
} finally {
    emfImage.dispose();
}
```

### EmfRecorderGraphics2D(Rectangle frame, Size deviceSize, Size deviceSizeMm) {#EmfRecorderGraphics2D-com.aspose.imaging.Rectangle-com.aspose.imaging.Size-com.aspose.imaging.Size-}
```
public EmfRecorderGraphics2D(Rectangle frame, Size deviceSize, Size deviceSizeMm)
```


Инициализирует новый экземпляр класса `EmfRecorderGraphics2D`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| frame | [Rectangle](../../com.aspose.imaging/rectangle) | Кадр. |
| deviceSize | [Size](../../com.aspose.imaging/size) | Размер устройства. |
| deviceSizeMm | [Size](../../com.aspose.imaging/size) | Размер устройства в мм. |

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


Получает или задаёт режим фона.

**Returns:**
int - режим фона.
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Получает или задаёт режим фона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Режим фона. |

### endRecording() {#endRecording--}
```
public EmfImage endRecording()
```


Останавливает запись.

**Returns:**
[EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) - The result image.
### fromEmfImage(EmfImage emfImage) {#fromEmfImage-com.aspose.imaging.fileformats.emf.EmfImage-}
```
public static EmfRecorderGraphics2D fromEmfImage(EmfImage emfImage)
```


Получает экземпляр [EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d), содержащий все записи из изображения Emf.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| emfImage | [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) | Изображение Emf, из которого читаются записи. |

**Returns:**
[EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d) - An instance of the [EmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/emfrecordergraphics2d)

**Example: This example shows how to load a EMF image from a file and draw a text string over it.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D graphics =
            com.aspose.imaging.fileformats.emf.graphics.EmfRecorderGraphics2D.fromEmfImage(emfImage);

    // Сначала получите размер изображения
    int width = emfImage.getWidth();
    int height = emfImage.getHeight();

    // Во-вторых, вычислите преобразование, чтобы разместить текстовую строку вдоль главной диагонали изображения -
    // от верхнего левого до нижнего правого угла.
    float emFontSize = 96f;
    float d = (float) java.lang.Math.sqrt(width * width + height * height);
    float scaleFactor = d / (emFontSize * 5f);

    float tan = ((float) height) / width;
    double radians = java.lang.Math.atan(tan);
    double degrees = (180 * radians) / java.lang.Math.PI;

    com.aspose.imaging.Matrix transform = new com.aspose.imaging.Matrix();
    transform.rotate((float) degrees);
    transform.scale(scaleFactor, scaleFactor);

    // Затем установите преобразование.
    graphics.setTransform(transform);

    // Наконец, разместите водяной знак (текстовая строка розового цвета) вдоль главной диагонали.
    graphics.drawString("WATERMARK", new com.aspose.imaging.Font(
                    "Courier New", emFontSize),
            com.aspose.imaging.Color.getLightPink(), 0, 0/*, (float)degrees*/);

    // Сохраните изображение с водяным знаком в другой файл EMF.
    com.aspose.imaging.fileformats.emf.EmfImage scaledEmfImage = graphics.endRecording();
    try {
        scaledEmfImage.save(dir + "test.scaled.emf");
    } finally {
        scaledEmfImage.dispose();
    }
} finally {
    emfImage.dispose();
}
```

