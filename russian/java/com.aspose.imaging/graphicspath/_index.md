---
title: "GraphicsPath"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет серию соединённых линий и кривых."
type: docs
weight: 52
url: /ru/java/com.aspose.imaging/graphicspath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds)
```
public final class GraphicsPath extends ObjectWithBounds
```

Представляет серию соединённых линий и кривых. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GraphicsPath()](#GraphicsPath--) | Инициализирует новый экземпляр класса `GraphicsPath`. |
| [GraphicsPath(Figure[] figures)](#GraphicsPath-com.aspose.imaging.Figure---) | Инициализирует новый экземпляр класса `GraphicsPath`. |
| [GraphicsPath(Figure[] figures, int fillMode)](#GraphicsPath-com.aspose.imaging.Figure---int-) | Инициализирует новый экземпляр класса `GraphicsPath`. |
| [GraphicsPath(int fillMode)](#GraphicsPath-int-) | Инициализирует новый экземпляр класса `GraphicsPath`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFillMode()](#getFillMode--) | Получает перечисление `com.aspose.imaging.FillMode`, которое определяет, как заполняются внутренние части фигур в этом `com.aspose.imaging.GraphicsPath`. |
| [setFillMode(int value)](#setFillMode-int-) | Устанавливает перечисление `com.aspose.imaging.FillMode`, которое определяет, как заполняются внутренности фигур в этом `com.aspose.imaging.GraphicsPath`. |
| [getFigures()](#getFigures--) | Получает фигуры пути. |
| [getBounds()](#getBounds--) | Получает или задает границы объекта. |
| [reset()](#reset--) | Очищает графический путь и устанавливает `com.aspose.imaging.FillMode` в `F:com.aspose.imaging.fillMode.alternate`. |
| [reverse()](#reverse--) | Меняет порядок фигур, форм и точек в каждой форме этого `com.aspose.imaging.graphicsPath` на обратный. |
| [isVisible(float x, float y)](#isVisible-float-float-) | Определяет, находится ли указанная точка внутри этого `com.aspose.imaging.graphicsPath`. |
| [isVisible(PointF point)](#isVisible-com.aspose.imaging.PointF-) | Определяет, находится ли указанная точка внутри этого `com.aspose.imaging.graphicsPath`. |
| [isVisible(int x, int y)](#isVisible-int-int-) | Определяет, находится ли указанная точка внутри этого `com.aspose.imaging.graphicsPath`. |
| [isVisible(Point point)](#isVisible-com.aspose.imaging.Point-) | Определяет, находится ли указанная точка внутри этого `com.aspose.imaging.graphicsPath`. |
| [isVisible(float x, float y, Graphics graphics)](#isVisible-float-float-com.aspose.imaging.Graphics-) | Определяет, находится ли указанная точка внутри этого `com.aspose.imaging.GraphicsPath` в видимом клип‑регионе указанного `com.aspose.imaging.graphics`. |
| [isVisible(PointF pt, Graphics graphics)](#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-) | Определяет, находится ли указанная точка внутри этого `com.aspose.imaging.graphicsPath`. |
| [isVisible(int x, int y, Graphics graphics)](#isVisible-int-int-com.aspose.imaging.Graphics-) | Определяет, находится ли указанная точка внутри этого `com.aspose.imaging.GraphicsPath`, используя указанный `com.aspose.imaging.graphics`. |
| [isVisible(Point pt, Graphics graphics)](#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-) | Определяет, находится ли указанная точка внутри этого `com.aspose.imaging.graphicsPath`. |
| [isOutlineVisible(float x, float y, Pen pen)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-) | Определяет, находится ли указанная точка внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.pen`. |
| [isOutlineVisible(PointF point, Pen pen)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-) | Определяет, находится ли указанная точка внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.pen`. |
| [isOutlineVisible(float x, float y, Pen pen, Graphics graphics)](#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Определяет, находится ли указанная точка внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.Pen` и с использованием указанного `com.aspose.imaging.graphics`. |
| [isOutlineVisible(PointF pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Определяет, находится ли указанная точка внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.Pen` и с использованием указанного `com.aspose.imaging.graphics`. |
| [isOutlineVisible(int x, int y, Pen pen)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-) | Определяет, находится ли указанная точка внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.pen`. |
| [isOutlineVisible(Point point, Pen pen)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-) | Определяет, находится ли указанная точка внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.pen`. |
| [isOutlineVisible(int x, int y, Pen pen, Graphics graphics)](#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Определяет, находится ли указанная точка внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.Pen` и с использованием указанного `com.aspose.imaging.graphics`. |
| [isOutlineVisible(Point pt, Pen pen, Graphics graphics)](#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-) | Определяет, находится ли указанная точка внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.Pen` и с использованием указанного `com.aspose.imaging.graphics`. |
| [flatten()](#flatten--) | Преобразует каждую кривую в этом пути в последовательность соединённых отрезков. |
| [flatten(Matrix matrix)](#flatten-com.aspose.imaging.Matrix-) | Применяет указанное преобразование, а затем преобразует каждую кривую в этом `com.aspose.imaging.GraphicsPath` в последовательность соединённых отрезков. |
| [flatten(Matrix matrix, float flatness)](#flatten-com.aspose.imaging.Matrix-float-) | Преобразует каждую кривую в этом `com.aspose.imaging.GraphicsPath` в последовательность соединённых отрезков. |
| [widen(Pen pen)](#widen-com.aspose.imaging.Pen-) | Добавляет дополнительный контур к пути. |
| [widen(Pen pen, Matrix matrix)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-) | Добавляет дополнительный контур к `com.aspose.imaging.graphicsPath`. |
| [widen(Pen pen, Matrix matrix, float flatness)](#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-) | Заменяет этот `com.aspose.imaging.GraphicsPath` кривыми, которые охватывают область, заполняемую при отрисовке этого пути указанным пером. |
| [warp(PointF[] destPoints, RectangleF srcRect)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому `com.aspose.imaging.graphicsPath`. |
| [warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)](#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-) | Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому `com.aspose.imaging.graphicsPath`. |
| [addFigure(Figure figure)](#addFigure-com.aspose.imaging.Figure-) | Добавляет новую фигуру. |
| [addFigures(Figure[] figures)](#addFigures-com.aspose.imaging.Figure---) | Добавляет новые фигуры. |
| [removeFigure(Figure figure)](#removeFigure-com.aspose.imaging.Figure-) | Удаляет фигуру. |
| [removeFigures(Figure[] figures)](#removeFigures-com.aspose.imaging.Figure---) | Удаляет фигуры. |
| [addPath(GraphicsPath addingPath)](#addPath-com.aspose.imaging.GraphicsPath-) | Добавляет указанный `com.aspose.imaging.GraphicsPath` к этому пути. |
| [addPath(GraphicsPath addingPath, boolean connect)](#addPath-com.aspose.imaging.GraphicsPath-boolean-) | Добавляет указанный `com.aspose.imaging.GraphicsPath` к этому пути. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Получает границы объекта. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Получает границы объекта. |
| [deepClone()](#deepClone--) | Выполняет глубокое клонирование этого графического пути. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Применяет указанное преобразование к форме. |
| [equals(Object o)](#equals-java.lang.Object-) | Проверяет, равны ли объекты. |
| [hashCode()](#hashCode--) | Получает хеш‑код текущего объекта. |

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

### GraphicsPath() {#GraphicsPath--}
```
public GraphicsPath()
```


Инициализирует новый экземпляр класса `GraphicsPath`.

### GraphicsPath(Figure[] figures) {#GraphicsPath-com.aspose.imaging.Figure---}
```
public GraphicsPath(Figure[] figures)
```


Инициализирует новый экземпляр класса `GraphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Фигуры, из которых инициализировать. |

### GraphicsPath(Figure[] figures, int fillMode) {#GraphicsPath-com.aspose.imaging.Figure---int-}
```
public GraphicsPath(Figure[] figures, int fillMode)
```


Инициализирует новый экземпляр класса `GraphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Фигуры, из которых инициализировать. |
| fillMode | int | Режим заливки. |

### GraphicsPath(int fillMode) {#GraphicsPath-int-}
```
public GraphicsPath(int fillMode)
```


Инициализирует новый экземпляр класса `GraphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fillMode | int | Режим заливки. |

### getFillMode() {#getFillMode--}
```
public int getFillMode()
```


Получает перечисление `com.aspose.imaging.FillMode`, которое определяет, как заполняются внутренние части фигур в этом `com.aspose.imaging.GraphicsPath`.

**Returns:**
int - Режим заливки. Перечисление `com.aspose.imaging.FillMode`, которое определяет, как заполняются внутренности фигур в этом `com.aspose.imaging.GraphicsPath`.
### setFillMode(int value) {#setFillMode-int-}
```
public void setFillMode(int value)
```


Устанавливает перечисление `com.aspose.imaging.FillMode`, которое определяет, как заполняются внутренности фигур в этом `com.aspose.imaging.GraphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Режим заливки. |

### getFigures() {#getFigures--}
```
public Figure[] getFigures()
```


Получает фигуры пути.

**Returns:**
com.aspose.imaging.Figure[] - Фигуры пути.
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Получает или задает границы объекта.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - The object's bounds.
### reset() {#reset--}
```
public void reset()
```


Очищает графический путь и устанавливает `com.aspose.imaging.FillMode` в `F:com.aspose.imaging.fillMode.alternate`.

### reverse() {#reverse--}
```
public void reverse()
```


Меняет порядок фигур, форм и точек в каждой форме этого `com.aspose.imaging.graphicsPath` на обратный.

### isVisible(float x, float y) {#isVisible-float-float-}
```
public boolean isVisible(float x, float y)
```


Определяет, находится ли указанная точка внутри этого `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри этого `com.aspose.imaging.GraphicsPath`; в противном случае — false.
### isVisible(PointF point) {#isVisible-com.aspose.imaging.PointF-}
```
public boolean isVisible(PointF point)
```


Определяет, находится ли указанная точка внутри этого `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Объект `com.aspose.imaging.PointF`, представляющий точку для проверки. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри этого `com.aspose.imaging.GraphicsPath`; в противном случае — false.
### isVisible(int x, int y) {#isVisible-int-int-}
```
public boolean isVisible(int x, int y)
```


Определяет, находится ли указанная точка внутри этого `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри этого `com.aspose.imaging.GraphicsPath`; в противном случае — false.
### isVisible(Point point) {#isVisible-com.aspose.imaging.Point-}
```
public boolean isVisible(Point point)
```


Определяет, находится ли указанная точка внутри этого `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Объект `com.aspose.imaging.Point`, представляющий точку для проверки. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри этого `com.aspose.imaging.GraphicsPath`; в противном случае — false.
### isVisible(float x, float y, Graphics graphics) {#isVisible-float-float-com.aspose.imaging.Graphics-}
```
public boolean isVisible(float x, float y, Graphics graphics)
```


Определяет, находится ли указанная точка внутри этого `com.aspose.imaging.GraphicsPath` в видимом клип‑регионе указанного `com.aspose.imaging.graphics`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, для которого необходимо проверить видимость. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри этого `com.aspose.imaging.GraphicsPath`; в противном случае — false.
### isVisible(PointF pt, Graphics graphics) {#isVisible-com.aspose.imaging.PointF-com.aspose.imaging.Graphics-}
```
public boolean isVisible(PointF pt, Graphics graphics)
```


Определяет, находится ли указанная точка внутри этого `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | Объект `com.aspose.imaging.PointF`, представляющий точку для проверки. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, для которого необходимо проверить видимость. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри этого объекта; в противном случае — false.
### isVisible(int x, int y, Graphics graphics) {#isVisible-int-int-com.aspose.imaging.Graphics-}
```
public boolean isVisible(int x, int y, Graphics graphics)
```


Определяет, находится ли указанная точка внутри этого `com.aspose.imaging.GraphicsPath`, используя указанный `com.aspose.imaging.graphics`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, для которого необходимо проверить видимость. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри этого `com.aspose.imaging.GraphicsPath`; в противном случае — false.
### isVisible(Point pt, Graphics graphics) {#isVisible-com.aspose.imaging.Point-com.aspose.imaging.Graphics-}
```
public boolean isVisible(Point pt, Graphics graphics)
```


Определяет, находится ли указанная точка внутри этого `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | Объект `com.aspose.imaging.Point`, представляющий точку для проверки. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, для которого необходимо проверить видимость. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри этого `com.aspose.imaging.GraphicsPath`; в противном случае — false.
### isOutlineVisible(float x, float y, Pen pen) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(float x, float y, Pen pen)
```


Определяет, находится ли указанная точка внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen`, который нужно проверить. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.Pen`; в противном случае — false.
### isOutlineVisible(PointF point, Pen pen) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(PointF point, Pen pen)
```


Определяет, находится ли указанная точка внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [PointF](../../com.aspose.imaging/pointf) | Объект `com.aspose.imaging.PointF`, указывающий местоположение для проверки. |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen`, который нужно проверить. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.Pen`; в противном случае — false.
### isOutlineVisible(float x, float y, Pen pen, Graphics graphics) {#isOutlineVisible-float-float-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(float x, float y, Pen pen, Graphics graphics)
```


Определяет, находится ли указанная точка внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.Pen` и с использованием указанного `com.aspose.imaging.graphics`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | float | Координата x проверяемой точки. |
| y | float | Координата y проверяемой точки. |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen`, который нужно проверить. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, для которого необходимо проверить видимость. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, отрисованного указанным `com.aspose.imaging.Pen`; в противном случае — false.
### isOutlineVisible(PointF pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.PointF-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(PointF pt, Pen pen, Graphics graphics)
```


Определяет, находится ли указанная точка внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.Pen` и с использованием указанного `com.aspose.imaging.graphics`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [PointF](../../com.aspose.imaging/pointf) | Объект `com.aspose.imaging.PointF`, указывающий местоположение для проверки. |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen`, который нужно проверить. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, для которого необходимо проверить видимость. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, отрисованного указанным `com.aspose.imaging.Pen`; в противном случае — false.
### isOutlineVisible(int x, int y, Pen pen) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(int x, int y, Pen pen)
```


Определяет, находится ли указанная точка внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen`, который нужно проверить. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.Pen`; в противном случае — false.
### isOutlineVisible(Point point, Pen pen) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-}
```
public boolean isOutlineVisible(Point point, Pen pen)
```


Определяет, находится ли указанная точка внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| point | [Point](../../com.aspose.imaging/point) | Объект `com.aspose.imaging.Point`, указывающий местоположение для проверки. |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen`, который нужно проверить. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.Pen`; в противном случае — false.
### isOutlineVisible(int x, int y, Pen pen, Graphics graphics) {#isOutlineVisible-int-int-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(int x, int y, Pen pen, Graphics graphics)
```


Определяет, находится ли указанная точка внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.Pen` и с использованием указанного `com.aspose.imaging.graphics`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x проверяемой точки. |
| y | int | Координата y проверяемой точки. |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen`, который нужно проверить. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, для которого необходимо проверить видимость. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри контура этого `com.aspose.imaging.GraphicsPath`, отрисованного указанным `com.aspose.imaging.Pen`; в противном случае — false.
### isOutlineVisible(Point pt, Pen pen, Graphics graphics) {#isOutlineVisible-com.aspose.imaging.Point-com.aspose.imaging.Pen-com.aspose.imaging.Graphics-}
```
public boolean isOutlineVisible(Point pt, Pen pen, Graphics graphics)
```


Определяет, находится ли указанная точка внутри (под) контура этого `com.aspose.imaging.GraphicsPath`, когда он отрисован указанным `com.aspose.imaging.Pen` и с использованием указанного `com.aspose.imaging.graphics`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pt | [Point](../../com.aspose.imaging/point) | Объект `com.aspose.imaging.Point`, указывающий местоположение для проверки. |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen`, который нужно проверить. |
| graphics | [Graphics](../../com.aspose.imaging/graphics) | `com.aspose.imaging.Graphics`, для которого необходимо проверить видимость. |

**Returns:**
boolean - Этот метод возвращает true, если указанная точка находится внутри контура этого `com.aspose.imaging.GraphicsPath`, отрисованного указанным `com.aspose.imaging.Pen`; в противном случае — false.
### flatten() {#flatten--}
```
public void flatten()
```


Преобразует каждую кривую в этом пути в последовательность соединённых отрезков.

### flatten(Matrix matrix) {#flatten-com.aspose.imaging.Matrix-}
```
public void flatten(Matrix matrix)
```


Применяет указанное преобразование, а затем преобразует каждую кривую в этом `com.aspose.imaging.GraphicsPath` в последовательность соединённых отрезков.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `com.aspose.imaging.Matrix`, с помощью которого следует преобразовать этот `com.aspose.imaging.GraphicsPath` перед уплощением. |

### flatten(Matrix matrix, float flatness) {#flatten-com.aspose.imaging.Matrix-float-}
```
public void flatten(Matrix matrix, float flatness)
```


Преобразует каждую кривую в этом `com.aspose.imaging.GraphicsPath` в последовательность соединённых отрезков.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `com.aspose.imaging.Matrix`, с помощью которого следует преобразовать этот `com.aspose.imaging.GraphicsPath` перед уплощением. |
| плоскостность | float | Указывает максимальную допустимую ошибку между кривой и её уплощённым приближением. Значение по умолчанию — 0,25. Уменьшение значения плоскостности увеличит количество отрезков в приближении. |

### widen(Pen pen) {#widen-com.aspose.imaging.Pen-}
```
public void widen(Pen pen)
```


Добавляет дополнительный контур к пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen`, определяющий ширину между оригинальным контуром пути и новым контуром, создаваемым этим методом. |

### widen(Pen pen, Matrix matrix) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-}
```
public void widen(Pen pen, Matrix matrix)
```


Добавляет дополнительный контур к `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen`, определяющий ширину между оригинальным контуром пути и новым контуром, создаваемым этим методом. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `com.aspose.imaging.Matrix`, определяющий преобразование, применяемое к пути перед расширением. |

### widen(Pen pen, Matrix matrix, float flatness) {#widen-com.aspose.imaging.Pen-com.aspose.imaging.Matrix-float-}
```
public void widen(Pen pen, Matrix matrix, float flatness)
```


Заменяет этот `com.aspose.imaging.GraphicsPath` кривыми, которые охватывают область, заполняемую при отрисовке этого пути указанным пером.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pen | [Pen](../../com.aspose.imaging/pen) | `com.aspose.imaging.Pen`, определяющий ширину между оригинальным контуром пути и новым контуром, создаваемым этим методом. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `com.aspose.imaging.Matrix`, определяющий преобразование, применяемое к пути перед расширением. |
| плоскостность | float | Значение, определяющее плоскостность кривых. |

### warp(PointF[] destPoints, RectangleF srcRect) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-}
```
public void warp(PointF[] destPoints, RectangleF srcRect)
```


Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Массив структур `com.aspose.imaging.PointF`, определяющих параллелограмм, в который преобразуется прямоугольник, заданный `srcRect`. Массив может содержать три или четыре элемента. Если массив содержит три элемента, правый нижний угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF`, представляющий прямоугольник, преобразуемый в параллелограмм, определённый `destPoints`. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix)
```


Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Массив структур `com.aspose.imaging.PointF`, определяющих параллелограмм, в который преобразуется прямоугольник, заданный `srcRect`. Массив может содержать три или четыре элемента. Если массив содержит три элемента, правый нижний угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF`, представляющий прямоугольник, преобразуемый в параллелограмм, определённый `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `com.aspose.imaging.Matrix`, определяющий геометрическое преобразование, применяемое к пути. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode)
```


Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Массив структур `com.aspose.imaging.PointF`, определяющих параллелограмм, в который преобразуется прямоугольник, заданный `srcRect`. Массив может содержать три или четыре элемента. Если массив содержит три элемента, правый нижний угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF`, представляющий прямоугольник, преобразуемый в параллелограмм, определённый `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `com.aspose.imaging.Matrix`, определяющий геометрическое преобразование, применяемое к пути. |
| режим искажения | int | Перечисление `com.aspose.imaging.WarpMode`, указывающее, использует ли данная операция искажения перспективный или билинейный режим. |

### warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness) {#warp-com.aspose.imaging.PointF---com.aspose.imaging.RectangleF-com.aspose.imaging.Matrix-int-float-}
```
public void warp(PointF[] destPoints, RectangleF srcRect, Matrix matrix, int warpMode, float flatness)
```


Применяет трансформацию искажения, определённую прямоугольником и параллелограммом, к этому `com.aspose.imaging.graphicsPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| destPoints | [PointF\[\]](../../com.aspose.imaging/pointf) | Массив структур `com.aspose.imaging.PointF`, определяющих параллелограмм, в который преобразуется прямоугольник, заданный `srcRect`. Массив может содержать три или четыре элемента. Если массив содержит три элемента, правый нижний угол параллелограмма подразумевается первыми тремя точками. |
| srcRect | [RectangleF](../../com.aspose.imaging/rectanglef) | `com.aspose.imaging.RectangleF`, представляющий прямоугольник, преобразуемый в параллелограмм, определённый `destPoints`. |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `com.aspose.imaging.Matrix`, определяющий геометрическое преобразование, применяемое к пути. |
| режим искажения | int | Перечисление `com.aspose.imaging.WarpMode`, указывающее, использует ли данная операция искажения перспективный или билинейный режим. |
| плоскостность | float | Значение от 0 до 1, которое определяет, насколько плоским будет полученный путь. Для получения дополнительной информации см. методы `com.aspose.imaging.GraphicsPath.flatten`. |

### addFigure(Figure figure) {#addFigure-com.aspose.imaging.Figure-}
```
public void addFigure(Figure figure)
```


Добавляет новую фигуру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | Фигура для добавления. |


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

### addFigures(Figure[] figures) {#addFigures-com.aspose.imaging.Figure---}
```
public void addFigures(Figure[] figures)
```


Добавляет новые фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Фигуры для добавления. |


**Example: This example creates a new Image and draws a variety of shapes using Figures and GraphicsPath o...**
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

### removeFigure(Figure figure) {#removeFigure-com.aspose.imaging.Figure-}
```
public void removeFigure(Figure figure)
```


Удаляет фигуру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| figure | [Figure](../../com.aspose.imaging/figure) | Фигура для удаления. |

### removeFigures(Figure[] figures) {#removeFigures-com.aspose.imaging.Figure---}
```
public void removeFigures(Figure[] figures)
```


Удаляет фигуры.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| figures | [Figure\[\]](../../com.aspose.imaging/figure) | Фигуры для удаления. |

### addPath(GraphicsPath addingPath) {#addPath-com.aspose.imaging.GraphicsPath-}
```
public void addPath(GraphicsPath addingPath)
```


Добавляет указанный `com.aspose.imaging.GraphicsPath` к этому пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект `com.aspose.imaging.GraphicsPath` для добавления. |

### addPath(GraphicsPath addingPath, boolean connect) {#addPath-com.aspose.imaging.GraphicsPath-boolean-}
```
public void addPath(GraphicsPath addingPath, boolean connect)
```


Добавляет указанный `com.aspose.imaging.GraphicsPath` к этому пути.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| addingPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект `com.aspose.imaging.GraphicsPath` для добавления. |
| соединить | boolean | Булево значение, указывающее, является ли первая фигура в добавленном пути частью последней фигуры в этом пути. Значение true указывает, что первая фигура в добавленном пути является частью последней фигуры в этом пути. Значение false указывает, что первая фигура в добавленном пути отделена от последней фигуры в этом пути. |

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
### deepClone() {#deepClone--}
```
public GraphicsPath deepClone()
```


Выполняет глубокое клонирование этого графического пути.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - A deep clone of the graphics path.
### transform(Matrix transform) {#transform-com.aspose.imaging.Matrix-}
```
public void transform(Matrix transform)
```


Применяет указанное преобразование к форме.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| transform | [Matrix](../../com.aspose.imaging/matrix) | Преобразование, которое следует применить. |

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
