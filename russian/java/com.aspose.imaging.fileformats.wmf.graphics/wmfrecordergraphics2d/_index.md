---
title: "WmfRecorderGraphics2D"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Записыватель Wmf."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.graphics.MetafileRecorderGraphics2D](../../com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d)
```
public final class WmfRecorderGraphics2D extends MetafileRecorderGraphics2D
```

Записыватель Wmf.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WmfRecorderGraphics2D(Rectangle frame, int inch)](#WmfRecorderGraphics2D-com.aspose.imaging.Rectangle-int-) | Инициализирует новый экземпляр класса `WmfRecorderGraphics2D`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBackgroundMode()](#getBackgroundMode--) | Получает или задаёт режим фона. |
| [setBackgroundMode(int value)](#setBackgroundMode-int-) | Получает или задаёт режим фона. |
| [endRecording()](#endRecording--) | Останавливает запись. |
| [fromWmfImage(WmfImage wmfImage)](#fromWmfImage-com.aspose.imaging.fileformats.wmf.WmfImage-) | Получает экземпляр рекордера Wmf для существующего изображения Wmf. |

## Example: This example shows how to create a WMF image and draw some geometric shapes using WmfRecorderGraphics2D.

``` java
String dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;

// Это разрешение экрана по умолчанию.
int dpi = 96;

com.aspose.imaging.Rectangle frame = new com.aspose.imaging.Rectangle(0, 0, imageWidth, imageHeight);

// Создать изображение WMF.
com.aspose.imaging.fileformats.wmf.graphics.WmfRecorderGraphics2D graphics =
        new com.aspose.imaging.fileformats.wmf.graphics.WmfRecorderGraphics2D(frame, dpi);

// Нарисовать черный прямоугольник вдоль границ изображения, используя черное перо шириной 1 пиксель.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, imageWidth, imageHeight);

// Заполнить прямоугольник цветом white-smoke.
graphics.fillRectangle(
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()),
        new com.aspose.imaging.Rectangle(10, 10, 580, 380));

// Нарисовать две диагональные линии, используя темно-зеленое перо шириной 1 пиксель.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, imageWidth, imageHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, imageHeight, imageWidth, 0);

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
{
    graphics.drawImage(imageToDraw,
            new com.aspose.imaging.Rectangle(400, 200, 100, 50),
            new com.aspose.imaging.Rectangle(0, 0, imageWidth, imageHeight),
            com.aspose.imaging.GraphicsUnit.Pixel);
}

// Нарисовать строку текста
graphics.drawString("Hello World!", new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular), com.aspose.imaging.Color.getDarkRed(), 200, 300);

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
com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = graphics.endRecording();
try {
    wmfImage.save(dir + "test.output.wmf");
} finally {
    wmfImage.dispose();
}
```

### WmfRecorderGraphics2D(Rectangle frame, int inch) {#WmfRecorderGraphics2D-com.aspose.imaging.Rectangle-int-}
```
public WmfRecorderGraphics2D(Rectangle frame, int inch)
```


Инициализирует новый экземпляр класса `WmfRecorderGraphics2D`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| frame | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник назначения, измеряемый в twips, для отображения метафайла. |
| дюйм | int | Количество пикселей на дюйм. |

### getBackgroundMode() {#getBackgroundMode--}
```
public int getBackgroundMode()
```


Получает или задаёт режим фона.

Значение: режим фона.

**Returns:**
int
### setBackgroundMode(int value) {#setBackgroundMode-int-}
```
public void setBackgroundMode(int value)
```


Получает или задаёт режим фона.

Значение: режим фона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### endRecording() {#endRecording--}
```
public WmfImage endRecording()
```


Останавливает запись.

**Returns:**
[WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) - The result image.
### fromWmfImage(WmfImage wmfImage) {#fromWmfImage-com.aspose.imaging.fileformats.wmf.WmfImage-}
```
public static WmfRecorderGraphics2D fromWmfImage(WmfImage wmfImage)
```


Получает экземпляр рекордера Wmf для существующего изображения Wmf.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| wmfImage | [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) | Изображение Wmf, для которого требуется получить рекордер. |

**Returns:**
[WmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d) - An instance of the [WmfRecorderGraphics2D](../../com.aspose.imaging.fileformats.wmf.graphics/wmfrecordergraphics2d) class.
