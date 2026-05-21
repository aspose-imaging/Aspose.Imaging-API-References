---
title: "PieShape"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет форму сектора."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.shapes/pieshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape), [com.aspose.imaging.shapes.RectangleShape](../../com.aspose.imaging/shapes/rectangleshape), [com.aspose.imaging.shapes.EllipseShape](../../com.aspose.imaging/shapes/ellipseshape)
```
public class PieShape extends EllipseShape
```

Представляет форму сектора.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PieShape()](#PieShape--) | Инициализирует новый экземпляр класса `PieShape`. |
| [PieShape(RectangleF rectangle, float startAngle, float sweepAngle)](#PieShape-com.aspose.imaging.RectangleF-float-float-) | Инициализирует новый экземпляр класса `PieShape`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getStartAngle()](#getStartAngle--) | Получает или задает начальный угол. |
| [setStartAngle(float value)](#setStartAngle-float-) | Получает или задает начальный угол. |
| [getSweepAngle()](#getSweepAngle--) | Получает или задает угол разворота. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Получает или задает угол разворота. |
| [getSegments()](#getSegments--) | Получает сегменты фигуры. |
| [equals(Object o)](#equals-java.lang.Object-) | Проверяет, равны ли объекты. |
| [hashCode()](#hashCode--) | Получает хеш‑код текущего объекта. |

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

### PieShape() {#PieShape--}
```
public PieShape()
```


Инициализирует новый экземпляр класса `PieShape`.

### PieShape(RectangleF rectangle, float startAngle, float sweepAngle) {#PieShape-com.aspose.imaging.RectangleF-float-float-}
```
public PieShape(RectangleF rectangle, float startAngle, float sweepAngle)
```


Инициализирует новый экземпляр класса `PieShape`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Прямоугольник. |
| startAngle | float | Начальный угол. |
| sweepAngle | float | Угол разворота. |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Получает или задает начальный угол.

Значение: Начальный угол.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Получает или задает начальный угол.

Значение: Начальный угол.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Получает или задает угол разворота.

Значение: Угол разворота.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Получает или задает угол разворота.

Значение: Угол разворота.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Получает сегменты фигуры.

Значение: Сегменты фигуры.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Проверяет, равны ли объекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| o | java.lang.Object | Другой объект. |

**Returns:**
boolean - Результат сравнения на равенство.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш‑код текущего объекта.

**Returns:**
int - Хеш-код.
