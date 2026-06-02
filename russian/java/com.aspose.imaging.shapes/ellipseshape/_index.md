---
title: "EllipseShape"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет форму эллипса."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging.shapes/ellipseshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape), [com.aspose.imaging.shapes.RectangleShape](../../com.aspose.imaging/shapes/rectangleshape)
```
public class EllipseShape extends RectangleShape
```

Представляет форму эллипса.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EllipseShape()](#EllipseShape--) | Инициализирует новый экземпляр класса `EllipseShape`. |
| [EllipseShape(RectangleF rectangle)](#EllipseShape-com.aspose.imaging.RectangleF-) | Инициализирует новый экземпляр класса `EllipseShape`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getSegments()](#getSegments--) | Получает сегменты фигуры. |

## Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...
В этом примере создаётся новое изображение и рисуются различные формы с использованием Figures и GraphicsPath на поверхности изображения.
``` java
//Создаёт экземпляр BmpOptions и задаёт его различные свойства.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Создайте экземпляр FileCreateSource и назначьте его в качестве Source для экземпляра BmpOptions
//Второй логический параметр определяет, является ли создаваемый файл временным (IsTemporal) или нет
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\output.bmp", false));

//Создать экземпляр Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Создать и инициализировать экземпляр класса Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Очистить поверхность Graphics
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Создать экземпляр класса GraphicsPath
    com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

    //Создать экземпляр класса Figure
    com.aspose.imaging.Figure figure1 = new com.aspose.imaging.Figure();

    //Добавить Shape к объекту Figure.
    figure1.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
    figure1.addShape(new com.aspose.imaging.shapes.PieShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(110, 110),
                    new com.aspose.imaging.SizeF(200, 200)), 0, 90));

    //Создать экземпляр класса Figure
    com.aspose.imaging.Figure figure2 = new com.aspose.imaging.Figure();

    //Добавить Shape к объекту Figure.
    figure2.addShape(new com.aspose.imaging.shapes.ArcShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300), 0, 45));
    figure2.addShape(new com.aspose.imaging.shapes.PolygonShape(
            new com.aspose.imaging.PointF[]
                    {
                            new com.aspose.imaging.PointF(150, 10),
                            new com.aspose.imaging.PointF(150, 200),
                            new com.aspose.imaging.PointF(250, 300),
                            new com.aspose.imaging.PointF(350, 400)}, true));
    figure2.addShape(new com.aspose.imaging.shapes.RectangleShape(
            new com.aspose.imaging.RectangleF(
                    new com.aspose.imaging.PointF(250, 250),
                    new com.aspose.imaging.SizeF(200, 200))));

    //Добавить объект Figure в GraphicsPath
    graphicspath.addFigures(new com.aspose.imaging.Figure[]{figure1, figure2});

    //Нарисовать путь объектом Pen цвета Black
    graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

    // Сохранить все изменения.
    image.save();
} finally {
    image.dispose();
}
```

### EllipseShape() {#EllipseShape--}
```
public EllipseShape()
```


Инициализирует новый экземпляр класса `EllipseShape`.

### EllipseShape(RectangleF rectangle) {#EllipseShape-com.aspose.imaging.RectangleF-}
```
public EllipseShape(RectangleF rectangle)
```


Инициализирует новый экземпляр класса `EllipseShape`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Прямоугольник. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Получает сегменты фигуры.

Значение: Сегменты фигуры.

**Returns:**
com.aspose.imaging.ShapeSegment[]
