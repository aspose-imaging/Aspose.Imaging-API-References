---
title: "SolidBrush"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Сплошная кисть предназначена для непрерывного рисования определённым цветом."
type: docs
weight: 17
url: /ru/java/com.aspose.imaging.brushes/solidbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class SolidBrush extends Brush
```

Кисть SolidBrush предназначена для непрерывного рисования определённым цветом. Этот класс не может быть унаследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SolidBrush()](#SolidBrush--) | Инициализирует новый экземпляр класса `SolidBrush`. |
| [SolidBrush(Color color)](#SolidBrush-com.aspose.imaging.Color-) | Инициализирует новый экземпляр класса `SolidBrush`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getColor()](#getColor--) | Получает или задаёт цвет кисти. |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | Получает или задаёт цвет кисти. |
| [hashCode()](#hashCode--) |  |
| [equals(Object object)](#equals-java.lang.Object-) |  |

## Example: This example uses Graphics class to create primitive shapes on the Image surface.
В этом примере используется класс Graphics для создания простых фигур на поверхности Image. Чтобы продемонстрировать работу, пример создаёт новое изображение в формате PNG и рисует простые фигуры на поверхности Image, используя методы Draw, предоставленные классом Graphics.
``` java
// Создаёт экземпляр FileStream.
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Создайте экземпляр PngOptions и задайте его различные свойства.
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Установите источник для PngOptions.
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Создать экземпляр Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Создать и инициализировать экземпляр класса Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Очистить поверхность Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Нарисуйте дугу, указав объект Pen с чёрным com.aspose.imaging.Color,
        // прямоугольник, окружающий дугу, начальный угол и угол разворота
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Нарисуйте кривую Безье, указав объект Pen с синим com.aspose.imaging.Color и координатными точками.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Нарисуйте кривую, указав объект Pen с зелёным com.aspose.imaging.Color и массив точек.
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Нарисуйте эллипс, используя объект Pen и окружающий его прямоугольник.
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Нарисуйте линию.
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Нарисуйте сектор пирога.
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Нарисуйте многоугольник, указав объект Pen с красным com.aspose.imaging.Color и массив точек.
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Нарисуйте прямоугольник.
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Создайте объект SolidBrush и задайте его различные свойства.
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Нарисуйте строку, используя объект SolidBrush и шрифт Font, в определённой точке.
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Сохранить все изменения.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### SolidBrush() {#SolidBrush--}
```
public SolidBrush()
```


Инициализирует новый экземпляр класса `SolidBrush`.

### SolidBrush(Color color) {#SolidBrush-com.aspose.imaging.Color-}
```
public SolidBrush(Color color)
```


Инициализирует новый экземпляр класса `SolidBrush`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Цвет сплошной кисти. |

### getColor() {#getColor--}
```
public Color getColor()
```


Получает или задаёт цвет кисти.

Значение: Цвет кисти.

**Returns:**
[Color](../../com.aspose.imaging/color)

**Example: This example uses Graphics class to create primitive shapes on the Image surface.**
В этом примере используется класс Graphics для создания простых фигур на поверхности Image. Чтобы продемонстрировать работу, пример создаёт новое изображение в формате PNG и рисует простые фигуры на поверхности Image, используя методы Draw, предоставленные классом Graphics.
``` java
// Создаёт экземпляр FileStream.
com.aspose.imaging.system.io.FileStream stream = new com.aspose.imaging.system.io.FileStream("C:\\temp\\output.png", com.aspose.imaging.system.io.FileMode.Create);
try {
    // Создайте экземпляр PngOptions и задайте его различные свойства.
    com.aspose.imaging.imageoptions.PngOptions pngOptions = new com.aspose.imaging.imageoptions.PngOptions();

    // Установите источник для PngOptions.
    pngOptions.setSource(new com.aspose.imaging.sources.StreamSource(stream));

    // Создать экземпляр Image
    com.aspose.imaging.Image image = com.aspose.imaging.Image.create(pngOptions, 500, 500);
    try {
        // Создать и инициализировать экземпляр класса Graphics
        com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

        // Очистить поверхность Graphics
        graphics.clear(com.aspose.imaging.Color.getWheat());

        // Нарисуйте дугу, указав объект Pen с чёрным com.aspose.imaging.Color,
        // прямоугольник, окружающий дугу, начальный угол и угол разворота
        graphics.drawArc(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlack(), 2),
                new com.aspose.imaging.Rectangle(200, 200, 100, 200),
                0,
                300);

        // Нарисуйте кривую Безье, указав объект Pen с синим com.aspose.imaging.Color и координатными точками.
        graphics.drawBezier(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getBlue(), 2),
                new com.aspose.imaging.Point(250, 100),
                new com.aspose.imaging.Point(300, 30),
                new com.aspose.imaging.Point(450, 100),
                new com.aspose.imaging.Point(235, 25));

        // Нарисуйте кривую, указав объект Pen с зелёным com.aspose.imaging.Color и массив точек.
        graphics.drawCurve(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getGreen(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(100, 200),
                                new com.aspose.imaging.Point(100, 350),
                                new com.aspose.imaging.Point(200, 450)
                        });

        // Нарисуйте эллипс, используя объект Pen и окружающий его прямоугольник.
        graphics.drawEllipse(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getYellow(), 2),
                new com.aspose.imaging.Rectangle(300, 300, 100, 100));

        // Нарисуйте линию.
        graphics.drawLine(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getViolet(), 2),
                new com.aspose.imaging.Point(100, 100),
                new com.aspose.imaging.Point(200, 200));

        // Нарисуйте сектор пирога.
        graphics.drawPie(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getSilver(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(200, 20), new com.aspose.imaging.Size(200, 200)),
                0,
                45);

        // Нарисуйте многоугольник, указав объект Pen с красным com.aspose.imaging.Color и массив точек.
        graphics.drawPolygon(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 2),
                new com.aspose.imaging.Point[]
                        {
                                new com.aspose.imaging.Point(20, 100),
                                new com.aspose.imaging.Point(20, 200),
                                new com.aspose.imaging.Point(220, 20)
                        });

        // Нарисуйте прямоугольник.
        graphics.drawRectangle(
                new com.aspose.imaging.Pen(com.aspose.imaging.Color.getOrange(), 2),
                new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(250, 250), new com.aspose.imaging.Size(100, 100)));

        // Создайте объект SolidBrush и задайте его различные свойства.
        com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush();
        brush.setColor(com.aspose.imaging.Color.getPurple());

        // Нарисуйте строку, используя объект SolidBrush и шрифт Font, в определённой точке.
        graphics.drawString(
                "This image is created by Aspose.Imaging API",
                new com.aspose.imaging.Font("Times New Roman", 16),
                brush,
                new com.aspose.imaging.PointF(50, 400));

        // Сохранить все изменения.
        image.save();
    } finally {
        image.dispose();
    }
} finally {
    stream.dispose();
}
```

### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


Получает или задаёт цвет кисти.

Значение: Цвет кисти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Получает хеш‑код текущего объекта.

**Returns:**
int
### equals(Object object) {#equals-java.lang.Object-}
```
public boolean equals(Object object)
```


Проверяет, равны ли объекты.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| объект | java.lang.Object |  |

**Returns:**
boolean
