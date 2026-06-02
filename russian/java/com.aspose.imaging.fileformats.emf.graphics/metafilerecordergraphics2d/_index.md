---
title: "MetafileRecorderGraphics2D"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Графика рекордера метафайлов"
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.emf.graphics/metafilerecordergraphics2d/
---
**Inheritance:**
java.lang.Object
```
public abstract class MetafileRecorderGraphics2D
```

Графика рекордера метафайлов
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MetafileRecorderGraphics2D()](#MetafileRecorderGraphics2D--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getClip()](#getClip--) | Получает или задает Region, ограничивающий область рисования этого Graphics |
| [setClip(Region value)](#setClip-com.aspose.imaging.Region-) | Получает или задает Region, ограничивающий область рисования этого Graphics |
| [getClipBounds()](#getClipBounds--) | Получает границы обрезки. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает цвет фона. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Устанавливает цвет фона. |
| [clear()](#clear--) | Очищает состояние графического объекта |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Рисует дугу, представляющую часть эллипса, заданную структурой Rectangle. |
| [drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Рисует кубический безье. |
| [drawPolyCubicBezier(Pen pen, Point[] points)](#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Рисует поликубический безье. |
| [drawEllipse(Pen pen, Rectangle rect)](#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Рисует эллипс. |
| [fillEllipse(Brush brush, Rectangle rect)](#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Заполняет эллипс. |
| [drawImage(RasterImage image, Point location)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте. |
| [drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)](#drawImage-byte---com.aspose.imaging.Rectangle-int-) | Рисует изображение. |
| [drawImage(InputStream stream, Rectangle destRect, int srcUnit)](#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-) | Рисует изображение. |
| [drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-) | Рисует указанную часть указанного изображения в заданном месте и с заданным размером. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Рисует линию. |
| [drawLine(Pen pen, Point pt1, Point pt2)](#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-) | Рисует линию. |
| [drawPolyline(Pen pen, Point[] points)](#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Рисует полилинию. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Рисует путь. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Заполняет путь. |
| [drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)](#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Рисует сектор. |
| [fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)](#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Заполняет сектор. |
| [drawPolygon(Pen pen, Point[] points)](#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---) | Рисует многоугольник. |
| [fillPolygon(Brush brush, Point[] points)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---) | Заполняет многоугольник. |
| [fillPolygon(Brush brush, Point[] points, int fillMode)](#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-) | Заполняет многоугольник. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Рисует прямоугольник. |
| [drawRectangle(Pen pen, Rectangle rectangle)](#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-) | Рисует прямоугольник. |
| [fillRectangle(Brush brush, Rectangle rectangle)](#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-) | Заполняет прямоугольник. |
| [drawString(String string, Font font, Color color, int x, int y)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-) | Рисует строку. |
| [drawString(String string, Font font, Color color, int x, int y, float angle)](#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-float-) | Рисует строку. |
| [excludeClip(Rectangle rect)](#excludeClip-com.aspose.imaging.Rectangle-) | Обновляет область обрезки этого Graphics, исключая область, указанную структурой Rectangle. |
| [excludeClip(Region region)](#excludeClip-com.aspose.imaging.Region-) | Обновляет область обрезки этого Graphics, исключая область, указанную объектом Region. |
| [intersectClip(RectangleF rect)](#intersectClip-com.aspose.imaging.RectangleF-) | Обновляет область обрезки этого Graphics до пересечения текущей области обрезки и указанной структуры Rectangle. |
| [intersectClip(Region region)](#intersectClip-com.aspose.imaging.Region-) | Обновляет область обрезки этого Graphics до пересечения текущей области обрезки и указанного объекта Region. |
| [resetClip()](#resetClip--) | Сбрасывает обрезку. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Умножает мировое преобразование этого Graphics на указанный Matrix. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Умножает мировое преобразование этого Graphics на указанный Matrix в заданном порядке. |
| [translateTransform(float x, float y)](#translateTransform-float-float-) | Изменяет начало системы координат, предварительно добавляя указанное смещение к матрице преобразования этого Graphics. |
| [translateTransform(float x, float y, int order)](#translateTransform-float-float-int-) | Изменяет начало системы координат, применяя указанное смещение к матрице преобразования этого Graphics в заданном порядке. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Применяет указанное вращение к матрице преобразования этого Graphics. |
| [rotateTransform(float angle, PointF center, int order)](#rotateTransform-float-com.aspose.imaging.PointF-int-) | Применяет указанное вращение к матрице преобразования этого Graphics в заданном порядке. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Применяет указанную операцию масштабирования к матрице преобразования этого Graphics, предварительно добавляя её к матрице преобразования объекта. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Применяет указанную операцию масштабирования к матрице преобразования этого Graphics в заданном порядке. |
| [getTransform()](#getTransform--) | Получает мировое преобразование. |
| [setTransform(Matrix transform)](#setTransform-com.aspose.imaging.Matrix-) | Устанавливает преобразование. |

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

### MetafileRecorderGraphics2D() {#MetafileRecorderGraphics2D--}
```
public MetafileRecorderGraphics2D()
```


### getClip() {#getClip--}
```
public Region getClip()
```


Получает или задает Region, ограничивающий область рисования этого Graphics

**Returns:**
[Region](../../com.aspose.imaging/region) - The clip region.
### setClip(Region value) {#setClip-com.aspose.imaging.Region-}
```
public void setClip(Region value)
```


Получает или задает Region, ограничивающий область рисования этого Graphics

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Region](../../com.aspose.imaging/region) | Область обрезки. |

### getClipBounds() {#getClipBounds--}
```
public RectangleF getClipBounds()
```


Получает границы обрезки.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The clip bounds.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Получает цвет фона.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of the background.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Устанавливает цвет фона.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Цвет фона. |

### clear() {#clear--}
```
public void clear()
```


Очищает состояние графического объекта

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


Рисует дугу, представляющую часть эллипса, заданную структурой Rectangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо, определяющее цвет, ширину и стиль фигуры. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Границы эллипса. |
| startAngle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до начальной точки дуги. |
| arcAngle | float | Угол в градусах, измеряемый по часовой стрелке от параметра startAngle до конечной точки дуги. |

### drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawCubicBezier(Pen pen, Point pt1, Point pt2, Point pt3, Point pt4)
```


Рисует кубический безье.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо, определяющее цвет, ширину и стиль фигуры. |
| pt1 | [Point](../../com.aspose.imaging/point) | Начальная точка кривой. |
| pt2 | [Point](../../com.aspose.imaging/point) | Первая контрольная точка кривой. |
| pt3 | [Point](../../com.aspose.imaging/point) | Вторая контрольная точка кривой. |
| pt4 | [Point](../../com.aspose.imaging/point) | Конечная точка кривой. |

### drawPolyCubicBezier(Pen pen, Point[] points) {#drawPolyCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyCubicBezier(Pen pen, Point[] points)
```


Рисует поликубический безье.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо, определяющее цвет, ширину и стиль фигуры. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Точки. |

### drawEllipse(Pen pen, Rectangle rect) {#drawEllipse-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawEllipse(Pen pen, Rectangle rect)
```


Рисует эллипс.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо, определяющее цвет, ширину и стиль фигуры. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Границы эллипса. |

### fillEllipse(Brush brush, Rectangle rect) {#fillEllipse-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillEllipse(Brush brush, Rectangle rect)
```


Заполняет эллипс.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Кисть, определяющая характеристики заливки. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Границы эллипса. |

### drawImage(RasterImage image, Point location) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public void drawImage(RasterImage image, Point location)
```


Рисует указанное изображение, используя его оригинальный физический размер, в указанном месте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение для отрисовки. |
| location | [Point](../../com.aspose.imaging/point) | Расположение верхнего левого угла отрисованного изображения. |

### drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit) {#drawImage-byte---com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(byte[] imageBytes, Rectangle destRect, int srcUnit)
```


Рисует изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| imageBytes | byte[] | Байты изображения. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник назначения. |
| srcUnit | int | Исходная единица измерения. |

### drawImage(InputStream stream, Rectangle destRect, int srcUnit) {#drawImage-java.io.InputStream-com.aspose.imaging.Rectangle-int-}
```
public final void drawImage(InputStream stream, Rectangle destRect, int srcUnit)
```


Рисует изображение.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник назначения. |
| srcUnit | int | Исходная единица измерения. |

### drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-int-}
```
public void drawImage(RasterImage image, Rectangle destRect, Rectangle srcRect, int srcUnit)
```


Рисует указанную часть указанного изображения в заданном месте и с заданным размером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение для отрисовки. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Структура Rectangle, указывающая расположение и размер отрисованного изображения. Изображение масштабируется, чтобы соответствовать прямоугольнику. |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | Структура Rectangle, указывающая часть объекта изображения для отрисовки. |
| srcUnit | int | Единицы измерения, используемые параметром srcRect. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Рисует линию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо, определяющее цвет, ширину и стиль фигуры. |
| x1 | int | Координата x первой точки. |
| y1 | int | Координата y первой точки. |
| x2 | int | Координата x второй точки. |
| y2 | int | Координата y второй точки. |

### drawLine(Pen pen, Point pt1, Point pt2) {#drawLine-com.aspose.imaging.Pen-com.aspose.imaging.Point-com.aspose.imaging.Point-}
```
public void drawLine(Pen pen, Point pt1, Point pt2)
```


Рисует линию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо, определяющее цвет, ширину и стиль фигуры. |
| pt1 | [Point](../../com.aspose.imaging/point) | Первая точка. |
| pt2 | [Point](../../com.aspose.imaging/point) | Вторая точка. |

### drawPolyline(Pen pen, Point[] points) {#drawPolyline-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolyline(Pen pen, Point[] points)
```


Рисует полилинию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо, определяющее цвет, ширину и стиль фигуры. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Точки. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public void drawPath(Pen pen, GraphicsPath path)
```


Рисует путь.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо, определяющее цвет, ширину и стиль фигуры. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Путь для рисования. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


Заполняет путь.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо, определяющее цвет, ширину и стиль фигуры. |
| brush | [Brush](../../com.aspose.imaging/brush) | Кисть, определяющая характеристики заливки. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Путь для заливки. |

### drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle) {#drawPie-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public void drawPie(Pen pen, Rectangle rect, float startAngle, float sweepAngle)
```


Рисует сектор.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо, определяющее цвет, ширину и стиль фигуры. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Границы эллипса. |
| startAngle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до начальной точки дуги. |
| sweepAngle | float | Угол в градусах, измеряемый по часовой стрелке от параметра startAngle до конечной точки дуги. |

### fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle) {#fillPie-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public void fillPie(Brush brush, Rectangle rect, float startAngle, float sweepAngle)
```


Заполняет сектор.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Кисть, определяющая характеристики заливки. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Границы эллипса. |
| startAngle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до начальной точки дуги. |
| sweepAngle | float | Угол в градусах, измеряемый по часовой стрелке от параметра startAngle до конечной точки дуги. |

### drawPolygon(Pen pen, Point[] points) {#drawPolygon-com.aspose.imaging.Pen-com.aspose.imaging.Point---}
```
public void drawPolygon(Pen pen, Point[] points)
```


Рисует многоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо, определяющее цвет, ширину и стиль фигуры. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Точки. |

### fillPolygon(Brush brush, Point[] points) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---}
```
public void fillPolygon(Brush brush, Point[] points)
```


Заполняет многоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Кисть, определяющая характеристики заливки. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Точки. |

### fillPolygon(Brush brush, Point[] points, int fillMode) {#fillPolygon-com.aspose.imaging.Brush-com.aspose.imaging.Point---int-}
```
public void fillPolygon(Brush brush, Point[] points, int fillMode)
```


Заполняет многоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Кисть, определяющая характеристики заливки. |
| points | [Point\[\]](../../com.aspose.imaging/point) | Точки. |
| fillMode | int | Режим заливки. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Рисует прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо, определяющее цвет, ширину и стиль фигуры. |
| x | int | Координата x верхнего левого угла прямоугольника для рисования. |
| y | int | Координата y верхнего левого угла прямоугольника для рисования. |
| width | int | Ширина прямоугольника для рисования. |
| height | int | Высота прямоугольника для рисования. |

### drawRectangle(Pen pen, Rectangle rectangle) {#drawRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-}
```
public void drawRectangle(Pen pen, Rectangle rectangle)
```


Рисует прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо, определяющее цвет, ширину и стиль фигуры. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник для рисования. |

### fillRectangle(Brush brush, Rectangle rectangle) {#fillRectangle-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-}
```
public void fillRectangle(Brush brush, Rectangle rectangle)
```


Заполняет прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | Кисть, определяющая характеристики заливки. |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Прямоугольник для заливки. |

### drawString(String string, Font font, Color color, int x, int y) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-}
```
public void drawString(String string, Font font, Color color, int x, int y)
```


Рисует строку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| строка | java.lang.String | Строка. |
| font | [Font](../../com.aspose.imaging/font) | Шрифт, определяющий формат текста строки. |
| color | [Color](../../com.aspose.imaging/color) | Цвет текста. |
| x | int | Координата x верхнего левого угла нарисованного текста. |
| y | int | Координата y верхнего левого угла нарисованного текста. |


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

### drawString(String string, Font font, Color color, int x, int y, float angle) {#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Color-int-int-float-}
```
public void drawString(String string, Font font, Color color, int x, int y, float angle)
```


Рисует строку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| строка | java.lang.String | Строка. |
| font | [Font](../../com.aspose.imaging/font) | Шрифт, определяющий формат текста строки. |
| color | [Color](../../com.aspose.imaging/color) | Цвет текста. |
| x | int | Координата x верхнего левого угла нарисованного текста. |
| y | int | Координата y верхнего левого угла нарисованного текста. |
| angle | float | Угол в градусах между вектором эксапмента и осью x устройства. Вектор эксапмента параллелен базовой линии строки текста. |

### excludeClip(Rectangle rect) {#excludeClip-com.aspose.imaging.Rectangle-}
```
public void excludeClip(Rectangle rect)
```


Обновляет область обрезки этого Graphics, исключая область, указанную структурой Rectangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Структура прямоугольника, указывающая прямоугольник, исключаемый из области отсечения. |

### excludeClip(Region region) {#excludeClip-com.aspose.imaging.Region-}
```
public void excludeClip(Region region)
```


Обновляет область обрезки этого Graphics, исключая область, указанную объектом Region.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Область, указывающая область, исключаемую из области отсечения. |

### intersectClip(RectangleF rect) {#intersectClip-com.aspose.imaging.RectangleF-}
```
public void intersectClip(RectangleF rect)
```


Обновляет область обрезки этого Graphics до пересечения текущей области обрезки и указанной структуры Rectangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rect | [RectangleF](../../com.aspose.imaging/rectanglef) | Структура прямоугольника для пересечения с текущей областью отсечения. |

### intersectClip(Region region) {#intersectClip-com.aspose.imaging.Region-}
```
public void intersectClip(Region region)
```


Обновляет область обрезки этого Graphics до пересечения текущей области обрезки и указанного объекта Region.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| region | [Region](../../com.aspose.imaging/region) | Область для пересечения с текущей областью. |

### resetClip() {#resetClip--}
```
public void resetClip()
```


Сбрасывает обрезку.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Умножает мировое преобразование этого Graphics на указанный Matrix.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Матрица, умножающая мировое преобразование. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Умножает мировое преобразование этого Graphics на указанный Matrix в заданном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Матрица, умножающая мировое преобразование. |
| order | int | Порядок умножения. |

### translateTransform(float x, float y) {#translateTransform-float-float-}
```
public void translateTransform(float x, float y)
```


Изменяет начало системы координат, предварительно добавляя указанное смещение к матрице преобразования этого Graphics.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x трансляции. |
| y | float | Координата y трансляции. |

### translateTransform(float x, float y, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float x, float y, int order)
```


Изменяет начало системы координат, применяя указанное смещение к матрице преобразования этого Graphics в заданном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x трансляции. |
| y | float | Координата y трансляции. |
| order | int | Указывает, добавляется ли трансляция в начало или в конец матрицы преобразования. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Применяет указанное вращение к матрице преобразования этого Graphics.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения в градусах. |

### rotateTransform(float angle, PointF center, int order) {#rotateTransform-float-com.aspose.imaging.PointF-int-}
```
public void rotateTransform(float angle, PointF center, int order)
```


Применяет указанное вращение к матрице преобразования этого Graphics в заданном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения в градусах. |
| center | [PointF](../../com.aspose.imaging/pointf) | Центр вращения. |
| order | int | Указывает, добавляется ли вращение в конец или в начало преобразования матрицы. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Применяет указанную операцию масштабирования к матрице преобразования этого Graphics, предварительно добавляя её к матрице преобразования объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Коэффициент масштабирования по оси X. |
| sy | float | Коэффициент масштабирования по оси Y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Применяет указанную операцию масштабирования к матрице преобразования этого Graphics в заданном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Коэффициент масштабирования по оси X. |
| sy | float | Коэффициент масштабирования по оси Y. |
| order | int | Указывает, добавляется ли операция масштабирования в начало или в конец матрицы преобразования. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Получает мировое преобразование.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - The transform matrix.
### setTransform(Matrix transform) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix transform)
```


Устанавливает преобразование.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Новая матрица преобразования. |


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

