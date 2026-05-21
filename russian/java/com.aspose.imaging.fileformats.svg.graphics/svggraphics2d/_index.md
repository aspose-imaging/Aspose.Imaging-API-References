---
title: "SvgGraphics2D"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Предоставляет команды рисования для создания Svg изображения."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.svg.graphics/svggraphics2d/
---
**Inheritance:**
java.lang.Object
```
public class SvgGraphics2D
```

Предоставляет команды рисования для создания Svg изображения.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SvgGraphics2D(int width, int height, int dpi)](#SvgGraphics2D-int-int-int-) | Инициализирует новый экземпляр класса [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |
| [SvgGraphics2D(SvgImage image)](#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-) | Инициализирует новый экземпляр класса [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |
## Методы

| Метод | Описание |
| --- | --- |
| [drawImage(RasterImage image, Point origin)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-) | Рисует указанное изображение в указанном месте. |
| [drawImage(RasterImage image, Point origin, Size size)](#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-) | Рисует указанное изображение заданного размера в указанном месте. |
| [drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)](#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-) | Рисует указанную часть указанного изображения в указанном месте и заданного размера. |
| [drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)](#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-) | Рисует дугу, представляющую часть эллипса, заданную структурой Rectangle. |
| [fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)](#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-) | Заполняет дугу, представляющую часть эллипса, заданную структурой Rectangle. |
| [drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)](#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-) | Рисует кубический безье. |
| [drawString(Font font, String text, Point origin, Color textColor)](#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-) | Рисует строку текста. |
| [drawLine(Pen pen, int x1, int y1, int x2, int y2)](#drawLine-com.aspose.imaging.Pen-int-int-int-int-) | Рисует линию. |
| [drawPath(Pen pen, GraphicsPath path)](#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-) | Рисует путь. |
| [fillPath(Pen pen, Brush brush, GraphicsPath path)](#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-) | Заполняет путь. |
| [drawRectangle(Pen pen, int x, int y, int width, int height)](#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-) | Рисует прямоугольник. |
| [fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)](#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-) | Заполняет прямоугольник. |
| [endRecording()](#endRecording--) | Получает окончательное Svg‑изображение, которое включает все команды рисования, выполненные через объект [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d). |

## Example: This example shows how to create an SVG image of the specified size and draw different shapes on it using SvgGraphics2D.

``` java
String dir = "c:\\temp\\";

int imageWidth = 600;
int imageHeight = 400;
int dpi = 96;

com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D graphics = new com.aspose.imaging.fileformats.svg.graphics.SvgGraphics2D(imageWidth, imageHeight, dpi);

// Нарисовать черный прямоугольник вдоль границ изображения, используя черное перо шириной 1 пиксель.
graphics.drawRectangle(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 1), 0, 0, imageWidth, imageHeight);

// Заполнить прямоугольник цветом white-smoke.
graphics.fillRectangle(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getWhiteSmoke(), 1),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhiteSmoke()), 10, 10, 580, 380);

// Нарисовать две диагональные линии, используя темно-зеленое перо шириной 1 пиксель.
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, 0, imageWidth, imageHeight);
graphics.drawLine(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getDarkGreen(), 1), 0, imageHeight, imageWidth, 0);

// Нарисовать дугу внутри прямоугольника {0, 0, 200, 200}, используя синее перо шириной 2 пикселя.
graphics.drawArc(
        new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
        new com.aspose.imaging.Rectangle(0, 0, 200, 200), 90, 270);

// Заполнить дугу
graphics.fillArc(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getLightCoral(), 10),
        new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getLightSkyBlue()),
        new com.aspose.imaging.Rectangle(0, 0, 150, 150), 90, 270);

// Нарисовать кубический безье, используя красное перо шириной 2 пикселя.
graphics.drawCubicBezier(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
        new com.aspose.imaging.PointF(0, 0),
        new com.aspose.imaging.PointF(200, 133),
        new com.aspose.imaging.PointF(400, 166),
        new com.aspose.imaging.PointF(600, 400));

// Нарисовать растровое изображение указанного размера в указанном месте.
// Изображение масштабируется, чтобы вписаться в требуемый прямоугольник.
com.aspose.imaging.RasterImage imageToDraw = (com.aspose.imaging.RasterImage) com.aspose.imaging.Image.load(dir + "sample.bmp");
try {
    graphics.drawImage(imageToDraw, new com.aspose.imaging.Point(400, 200), new com.aspose.imaging.Size(100, 50));
} finally {
    imageToDraw.dispose();
}

// Нарисовать строку текста
graphics.drawString(
        new com.aspose.imaging.Font("Arial", 48, com.aspose.imaging.FontStyle.Regular),
        "Hello World!",
        new com.aspose.imaging.Point(200, 300),
        com.aspose.imaging.Color.getDarkRed());

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
                new com.aspose.imaging.shapes.RectangleShape(
                        new com.aspose.imaging.RectangleF(0, 100, 200, 200)),
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

// Получить окончательное SVG‑изображение, которое включает все команды рисования
com.aspose.imaging.fileformats.svg.SvgImage svgImage = graphics.endRecording();
try {
    svgImage.save(dir + "test.output.svg");
} finally {
    svgImage.dispose();
}
```

### SvgGraphics2D(int width, int height, int dpi) {#SvgGraphics2D-int-int-int-}
```
public SvgGraphics2D(int width, int height, int dpi)
```


Инициализирует новый экземпляр класса [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина выходного Svg‑изображения. |
| height | int | Ширина выходного Svg‑изображения. |
| dpi | int | Разрешение устройства, например 96 точек на дюйм. |

### SvgGraphics2D(SvgImage image) {#SvgGraphics2D-com.aspose.imaging.fileformats.svg.SvgImage-}
```
public SvgGraphics2D(SvgImage image)
```


Инициализирует новый экземпляр класса [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) | Изображение, на котором выполняются операции рисования. |

### drawImage(RasterImage image, Point origin) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-}
```
public final void drawImage(RasterImage image, Point origin)
```


Рисует указанное изображение в указанном месте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Полученное изображение. |
| origin | [Point](../../com.aspose.imaging/point) | Расположение полученного изображения. |

### drawImage(RasterImage image, Point origin, Size size) {#drawImage-com.aspose.imaging.RasterImage-com.aspose.imaging.Point-com.aspose.imaging.Size-}
```
public final void drawImage(RasterImage image, Point origin, Size size)
```


Рисует указанное изображение заданного размера в указанном месте.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Полученное изображение. |
| origin | [Point](../../com.aspose.imaging/point) | Расположение полученного изображения. |
| size | [Size](../../com.aspose.imaging/size) | Желаемый размер полученного изображения. |

### drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image) {#drawImage-com.aspose.imaging.Rectangle-com.aspose.imaging.Rectangle-com.aspose.imaging.RasterImage-}
```
public final void drawImage(Rectangle srcRect, Rectangle destRect, RasterImage image)
```


Рисует указанную часть указанного изображения в указанном месте и заданного размера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| srcRect | [Rectangle](../../com.aspose.imaging/rectangle) | Часть объекта изображения для рисования. |
| destRect | [Rectangle](../../com.aspose.imaging/rectangle) | Расположение и размер полученного изображения. Изображение масштабируется, чтобы соответствовать прямоугольнику. |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение для отрисовки. |

### drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle) {#drawArc-com.aspose.imaging.Pen-com.aspose.imaging.Rectangle-float-float-}
```
public final void drawArc(Pen pen, Rectangle rect, float startAngle, float arcAngle)
```


Рисует дугу, представляющую часть эллипса, заданную структурой Rectangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо для рисования контура фигуры. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Границы эллипса. |
| startAngle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до начальной точки дуги. |
| arcAngle | float | Угол в градусах, измеряемый по часовой стрелке от параметра startAngle до конечной точки дуги. |

### fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle) {#fillArc-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.Rectangle-float-float-}
```
public final void fillArc(Pen pen, Brush brush, Rectangle rect, float startAngle, float arcAngle)
```


Заполняет дугу, представляющую часть эллипса, заданную структурой Rectangle.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо для рисования контура фигуры. |
| brush | [Brush](../../com.aspose.imaging/brush) | Кисть для заполнения внутренней части фигуры. |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | Границы эллипса. |
| startAngle | float | Угол в градусах, измеряемый по часовой стрелке от оси x до начальной точки дуги. |
| arcAngle | float | Угол в градусах, измеряемый по часовой стрелке от параметра startAngle до конечной точки дуги. |

### drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4) {#drawCubicBezier-com.aspose.imaging.Pen-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-com.aspose.imaging.PointF-}
```
public final void drawCubicBezier(Pen pen, PointF pt1, PointF pt2, PointF pt3, PointF pt4)
```


Рисует кубический безье.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо, определяющее цвет, толщину и стиль фигуры. |
| pt1 | [PointF](../../com.aspose.imaging/pointf) | Начальная точка кривой. |
| pt2 | [PointF](../../com.aspose.imaging/pointf) | Первая контрольная точка кривой. |
| pt3 | [PointF](../../com.aspose.imaging/pointf) | Вторая контрольная точка кривой. |
| pt4 | [PointF](../../com.aspose.imaging/pointf) | Конечная точка кривой. |

### drawString(Font font, String text, Point origin, Color textColor) {#drawString-com.aspose.imaging.Font-java.lang.String-com.aspose.imaging.Point-com.aspose.imaging.Color-}
```
public final void drawString(Font font, String text, Point origin, Color textColor)
```


Рисует строку текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| font | [Font](../../com.aspose.imaging/font) | Шрифт, используемый для отображения текста. |
| text | java.lang.String | Строка Unicode текста. |
| origin | [Point](../../com.aspose.imaging/point) | Верхний левый угол текстового блока. |
| textColor | [Color](../../com.aspose.imaging/color) | Цвет текста. |

### drawLine(Pen pen, int x1, int y1, int x2, int y2) {#drawLine-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawLine(Pen pen, int x1, int y1, int x2, int y2)
```


Рисует линию.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо, определяющее цвет, толщину и стиль фигуры. |
| x1 | int | Координата x первой точки. |
| y1 | int | Координата y первой точки. |
| x2 | int | Координата x второй точки. |
| y2 | int | Координата y второй точки. |

### drawPath(Pen pen, GraphicsPath path) {#drawPath-com.aspose.imaging.Pen-com.aspose.imaging.GraphicsPath-}
```
public final void drawPath(Pen pen, GraphicsPath path)
```


Рисует путь.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо для рисования контура фигуры. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Путь для рисования. |

### fillPath(Pen pen, Brush brush, GraphicsPath path) {#fillPath-com.aspose.imaging.Pen-com.aspose.imaging.Brush-com.aspose.imaging.GraphicsPath-}
```
public final void fillPath(Pen pen, Brush brush, GraphicsPath path)
```


Заполняет путь.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо для рисования контура фигуры. |
| brush | [Brush](../../com.aspose.imaging/brush) | Кисть для заполнения внутренней части фигуры. |
| path | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Путь для рисования. |

### drawRectangle(Pen pen, int x, int y, int width, int height) {#drawRectangle-com.aspose.imaging.Pen-int-int-int-int-}
```
public final void drawRectangle(Pen pen, int x, int y, int width, int height)
```


Рисует прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо для рисования контура фигуры. |
| x | int | Координата x верхнего левого угла прямоугольника для рисования. |
| y | int | Координата y верхнего левого угла прямоугольника для рисования. |
| width | int | Ширина прямоугольника для рисования. |
| height | int | Высота прямоугольника для рисования. |

### fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height) {#fillRectangle-com.aspose.imaging.Pen-com.aspose.imaging.Brush-int-int-int-int-}
```
public final void fillRectangle(Pen pen, Brush brush, int x, int y, int width, int height)
```


Заполняет прямоугольник.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | Перо для рисования контура фигуры. |
| brush | [Brush](../../com.aspose.imaging/brush) | Кисть для заполнения внутренней части фигуры. |
| x | int | Координата x верхнего левого угла прямоугольника для рисования. |
| y | int | Координата y верхнего левого угла прямоугольника для рисования. |
| width | int | Ширина прямоугольника для рисования. |
| height | int | Высота прямоугольника для рисования. |

### endRecording() {#endRecording--}
```
public final SvgImage endRecording()
```


Получает окончательное Svg‑изображение, которое включает все команды рисования, выполненные через объект [SvgGraphics2D](../../com.aspose.imaging.fileformats.svg.graphics/svggraphics2d).

**Returns:**
[SvgImage](../../com.aspose.imaging.fileformats.svg/svgimage) - The final Svg image.
