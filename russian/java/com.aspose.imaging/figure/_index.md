---
title: "Figure"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Фигура."
type: docs
weight: 44
url: /ru/java/com.aspose.imaging/figure/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public class Figure extends ObjectWithBounds
```

Фигура. Контейнер для фигур.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Figure()](#Figure--) | Инициализирует новый экземпляр [Figure](../../com.aspose.imaging/figure). |
## Методы

| Метод | Описание |
| --- | --- |
| [getShapes()](#getShapes--) | Получает формы фигуры. |
| [getBounds()](#getBounds--) | Получает или задает границы объекта. |
| [isClosed()](#isClosed--) | Получает значение, указывающее, закрыта ли эта фигура. |
| [setClosed(boolean value)](#setClosed-boolean-) | Устанавливает значение, указывающее, закрыта ли эта фигура. |
| [getSegments()](#getSegments--) | Получает все сегменты фигуры. |
| [addShape(Shape shape)](#addShape-com.aspose.imaging.Shape-) | Добавляет форму к фигуре. |
| [addShapes(Shape[] shapes)](#addShapes-com.aspose.imaging.Shape---) | Добавляет диапазон форм к фигуре. |
| [removeShape(Shape shape)](#removeShape-com.aspose.imaging.Shape-) | Удаляет форму из фигуры. |
| [removeShapes(Shape[] shapes)](#removeShapes-com.aspose.imaging.Shape---) | Удаляет диапазон форм из фигуры. |
| [reverse()](#reverse--) | Изменяет порядок форм этой фигуры и порядок точек форм на обратный. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Получает границы объекта. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Получает границы объекта. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Применяет указанное преобразование к форме. |
| [equals(Object obj)](#equals-java.lang.Object-) | Определяет, равен ли указанный объект текущему объекту. |
| [hashCode()](#hashCode--) | Служит функцией хеширования по умолчанию. |

## Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.
Эти примеры используют классы GraphicsPath и Graphics для создания и манипулирования фигурами на поверхности Image. Пример создает новое изображение (типа Tiff) и рисует пути с помощью класса GraphicsPath. В конце вызывается метод DrawPath, предоставляемый классом Graphics, чтобы отрисовать пути на поверхности.
``` java
// Создать экземпляр FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Создать экземпляр TiffOptions и установить его различные свойства
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // Установить источник для экземпляра ImageOptions
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Создать экземпляр Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // Создать и инициализировать экземпляр класса Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Очистить поверхность Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Создать экземпляр класса GraphicsPath
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // Создать экземпляр класса Figure
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // Добавить формы в объект Figure
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // Добавить объект Figure в GraphicsPath
        graphicspath.addFigure(figure);

        // Нарисовать путь объектом Pen цвета Black
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // Сохранить все изменения.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### Figure() {#Figure--}
```
public Figure()
```


Инициализирует новый экземпляр [Figure](../../com.aspose.imaging/figure). Конструктор, необходимый для десериализации JSON.

### getShapes() {#getShapes--}
```
public Shape[] getShapes()
```


Получает формы фигуры.

**Returns:**
com.aspose.imaging.Shape[] - Фигурные формы.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Получает или задает границы объекта.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### isClosed() {#isClosed--}
```
public boolean isClosed()
```


Получает значение, указывающее, замкнута ли эта фигура. Замкнутая фигура имеет значение только в случае, когда первая и последняя формы фигуры являются непрерывными формами. В таком случае первая точка первой формы будет соединена прямой линией с последней точкой последней формы.

**Returns:**
boolean - `True` если эта фигура замкнута; иначе `false`.
### setClosed(boolean value) {#setClosed-boolean-}
```
public void setClosed(boolean value)
```


Устанавливает значение, указывающее, замкнута ли эта фигура. Замкнутая фигура имеет значение только в случае, когда первая и последняя формы фигуры являются непрерывными формами. В таком случае первая точка первой формы будет соединена прямой линией с последней точкой последней формы.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `True` если эта фигура замкнута; иначе `false`. |

### getSegments() {#getSegments--}
```
public ShapeSegment[] getSegments()
```


Получает все сегменты фигуры.

**Returns:**
com.aspose.imaging.ShapeSegment[] - Сегменты фигуры.
### addShape(Shape shape) {#addShape-com.aspose.imaging.Shape-}
```
public void addShape(Shape shape)
```


Добавляет форму к фигуре.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | Форма для добавления. |


**Example: This examples make use of GraphicsPath and Graphics class to create and manipulate Figures on an Image surface.**
Эти примеры используют классы GraphicsPath и Graphics для создания и манипулирования фигурами на поверхности Image. Пример создает новое изображение (типа Tiff) и рисует пути с помощью класса GraphicsPath. В конце вызывается метод DrawPath, предоставляемый классом Graphics, чтобы отрисовать пути на поверхности.
``` java
// Создать экземпляр FileStream
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.tif", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Создать экземпляр TiffOptions и установить его различные свойства
    com.aspose.imaging.imageoptions.TiffOptions tiffOptions = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);

    // Установить источник для экземпляра ImageOptions
    tiffOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Создать экземпляр Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(tiffOptions, 500, 500);
    try {
        // Создать и инициализировать экземпляр класса Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Очистить поверхность Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Создать экземпляр класса GraphicsPath
        com.aspose.imaging.GraphicsPath graphicspath = new com.aspose.imaging.GraphicsPath();

        // Создать экземпляр класса Figure
        com.aspose.imaging.Figure figure = new com.aspose.imaging.Figure();

        // Добавить формы в объект Figure
        figure.addShape(new com.aspose.imaging.shapes.RectangleShape(new com.aspose.imaging.RectangleF(10, 10, 300, 300)));
        figure.addShape(new com.aspose.imaging.shapes.EllipseShape(new com.aspose.imaging.RectangleF(50, 50, 300, 300)));
        figure.addShape(
                new com.aspose.imaging.shapes.PieShape(new com.aspose.imaging.RectangleF(
                        new com.aspose.imaging.PointF(250, 250),
                        new com.aspose.imaging.SizeF(200, 200)),
                        0, 45));

        // Добавить объект Figure в GraphicsPath
        graphicspath.addFigure(figure);

        // Нарисовать путь объектом Pen цвета Black
        graphics.drawPath(new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2), graphicspath);

        // Сохранить все изменения.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### addShapes(Shape[] shapes) {#addShapes-com.aspose.imaging.Shape---}
```
public void addShapes(Shape[] shapes)
```


Добавляет диапазон форм к фигуре.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | Формы для добавления. |

### removeShape(Shape shape) {#removeShape-com.aspose.imaging.Shape-}
```
public void removeShape(Shape shape)
```


Удаляет форму из фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shape | [Shape](../../com.aspose.imaging/shape) | Форма для удаления. |

### removeShapes(Shape[] shapes) {#removeShapes-com.aspose.imaging.Shape---}
```
public void removeShapes(Shape[] shapes)
```


Удаляет диапазон форм из фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| shapes | [Shape\[\]](../../com.aspose.imaging/shape) | Диапазон форм для удаления. |

### reverse() {#reverse--}
```
public void reverse()
```


Изменяет порядок форм этой фигуры и порядок точек форм на обратный.

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
