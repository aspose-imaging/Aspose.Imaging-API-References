---
title: "PolygonShape"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет форму многоугольника."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.shapes/polygonshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape)

**All Implemented Interfaces:**
[com.aspose.imaging.IOrderedShape](../../com.aspose.imaging/iorderedshape)
```
public class PolygonShape extends Shape implements IOrderedShape
```

Представляет форму многоугольника.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PolygonShape()](#PolygonShape--) | Инициализирует новый экземпляр класса `PolygonShape`. |
| [PolygonShape(PointF[] points)](#PolygonShape-com.aspose.imaging.PointF---) | Инициализирует новый экземпляр класса `PolygonShape`. |
| [PolygonShape(PointF[] points, boolean isClosed)](#PolygonShape-com.aspose.imaging.PointF---boolean-) | Инициализирует новый экземпляр класса `PolygonShape`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPoints()](#getPoints--) | Получает или задаёт точки кривой. |
| [setPoints(PointF[] value)](#setPoints-com.aspose.imaging.PointF---) | Получает или задаёт точки кривой. |
| [isClosed()](#isClosed--) | Получает или задаёт значение, указывающее, замкнута ли форма. |
| [setClosed(boolean value)](#setClosed-boolean-) | Получает или задаёт значение, указывающее, замкнута ли форма. |
| [getBounds()](#getBounds--) | Получает границы объекта. |
| [getCenter()](#getCenter--) | Получает центр фигуры. |
| [getSegments()](#getSegments--) | Получает сегменты фигуры. |
| [hasSegments()](#hasSegments--) | Получает значение, указывающее, есть ли у фигуры сегменты. |
| [getStartPoint()](#getStartPoint--) | Получает начальную точку формы. |
| [getEndPoint()](#getEndPoint--) | Получает конечную точку формы. |
| [reverse()](#reverse--) | Обращает порядок точек этой формы. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Получает границы объекта. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Получает границы объекта. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Применяет указанное преобразование к форме. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный объект текущему объекту. |
| [hashCode()](#hashCode--) | Служит функцией хеширования по умолчанию. |

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

### PolygonShape() {#PolygonShape--}
```
public PolygonShape()
```


Инициализирует новый экземпляр класса `PolygonShape`.

### PolygonShape(PointF[] points) {#PolygonShape-com.aspose.imaging.PointF---}
```
public PolygonShape(PointF[] points)
```


Инициализирует новый экземпляр класса `PolygonShape`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Массив точек. |

### PolygonShape(PointF[] points, boolean isClosed) {#PolygonShape-com.aspose.imaging.PointF---boolean-}
```
public PolygonShape(PointF[] points, boolean isClosed)
```


Инициализирует новый экземпляр класса `PolygonShape`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| points | [PointF\[\]](../../com.aspose.imaging/pointf) | Массив точек. |
| isClosed | boolean | Если установить `true`, полигон будет закрыт. |

### getPoints() {#getPoints--}
```
public PointF[] getPoints()
```


Получает или задаёт точки кривой.

Значение: Точки кривой.

**Returns:**
com.aspose.imaging.PointF[]
### setPoints(PointF[] value) {#setPoints-com.aspose.imaging.PointF---}
```
public void setPoints(PointF[] value)
```


Получает или задаёт точки кривой.

Значение: Точки кривой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Получает или задаёт значение, указывающее, замкнута ли форма.

Значение: `true`, если фигура закрыта; иначе `false`.

**Returns:**
boolean
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Получает или задаёт значение, указывающее, замкнута ли форма.

Значение: `true`, если фигура закрыта; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Получает границы объекта.

Значение: Границы объекта.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Получает центр фигуры.

Значение: Центр формы.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Получает сегменты фигуры.

Значение: Сегменты фигуры.

**Returns:**
com.aspose.imaging.ShapeSegment[]
### hasSegments() {#hasSegments--}
```
public boolean hasSegments()
```


Получает значение, указывающее, есть ли у фигуры сегменты.

Значение: `True`, если у формы есть сегменты; иначе `false`.

**Returns:**
boolean
### getStartPoint() {#getStartPoint--}
```
public PointF getStartPoint()
```


Получает начальную точку формы.

Значение: Начальная точка фигуры.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getEndPoint() {#getEndPoint--}
```
public PointF getEndPoint()
```


Получает конечную точку формы.

Значение: Конечная точка фигуры.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### reverse() {#reverse--}
```
public void reverse()
```


Обращает порядок точек этой формы.

### getBounds(Matrix matrix) {#getBounds-com.aspose.imaging.Matrix-}
```
public RectangleF getBounds(Matrix matrix)
```


Получает границы объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Матрица, применяемая перед вычислением границ. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### getBounds(Matrix matrix, Pen pen) {#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-}
```
public RectangleF getBounds(Matrix matrix, Pen pen)
```


Получает границы объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Матрица, применяемая перед вычислением границ. |
| pen | [Pen](../../com.aspose.imaging/pen) | Карандаш, используемый для объекта. Это может влиять на размер границ объекта. |

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The estimated object's bounds.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Применяет указанное преобразование к форме.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Преобразование, которое следует применить. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Определяет, равен ли указанный объект текущему объекту.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Сравниваемый объект. |

**Returns:**
boolean - Результат сравнения на равенство
### hashCode() {#hashCode--}
```
public int hashCode()
```


Служит функцией хеширования по умолчанию.

**Returns:**
int - Хеш-код текущего объекта.
