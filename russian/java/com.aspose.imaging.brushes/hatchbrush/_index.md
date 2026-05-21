---
title: "HatchBrush"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Определяет прямоугольную кисть с штриховкой, цветом переднего плана и цветом фона."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.brushes/hatchbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.Brush](../../com.aspose.imaging/brush)
```
public final class HatchBrush extends Brush
```

Определяет прямоугольную кисть с штриховкой, цветом переднего плана и цветом фона. Этот класс нельзя наследовать.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [HatchBrush()](#HatchBrush--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getForegroundColor()](#getForegroundColor--) | Возвращает цвет линий штриховки. |
| [setForegroundColor(Color value)](#setForegroundColor-com.aspose.imaging.Color-) | Устанавливает цвет линий штриховки. |
| [getBackgroundColor()](#getBackgroundColor--) | Возвращает цвет промежутков между линиями штриховки. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Устанавливает цвет промежутков между линиями штриховки. |
| [getHatchStyle()](#getHatchStyle--) | Возвращает стиль штриховки этой кисти. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Устанавливает стиль штриховки этой кисти. |

## Example: This example shows the creation and usage Pen objects.
Этот пример показывает создание и использование объектов Pen. Пример создает новый Image и рисует Rectangles на поверхности Image.
``` java

// Создайте экземпляр BmpOptions и задайте его различные свойства
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Создайте экземпляр FileCreateSource и назначьте его в качестве Source для экземпляра BmpOptions
// Второй логический параметр определяет, является ли создаваемый файл временным (IsTemporal) или нет
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Создайте экземпляр Image по указанному пути
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Создайте экземпляр Graphics и инициализируйте его объектом Image
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Очистите поверхность Graphics цветом White Color.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Создайте экземпляр Pen с цветом Red и шириной 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Создайте экземпляр HatchBrush и задайте его свойства
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Создайте экземпляр Pen и инициализируйте его объектом HatchBrush и шириной
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Рисуйте Rectangles, указывая объект Pen
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Рисуйте Rectangles, указывая объект Pen
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Сохранить все изменения.
    image.save();
} finally {
    image.dispose();
}
```

### HatchBrush() {#HatchBrush--}
```
public HatchBrush()
```


### getForegroundColor() {#getForegroundColor--}
```
public Color getForegroundColor()
```


Возвращает цвет линий штриховки.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of hatch lines.
### setForegroundColor(Color value) {#setForegroundColor-com.aspose.imaging.Color-}
```
public void setForegroundColor(Color value)
```


Устанавливает цвет линий штриховки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Цвет линий штриховки. |


**Example: This example shows the creation and usage Pen objects.**
Этот пример показывает создание и использование объектов Pen. Пример создает новый Image и рисует Rectangles на поверхности Image.
``` java

// Создайте экземпляр BmpOptions и задайте его различные свойства
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Создайте экземпляр FileCreateSource и назначьте его в качестве Source для экземпляра BmpOptions
// Второй логический параметр определяет, является ли создаваемый файл временным (IsTemporal) или нет
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Создайте экземпляр Image по указанному пути
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Создайте экземпляр Graphics и инициализируйте его объектом Image
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Очистите поверхность Graphics цветом White Color.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Создайте экземпляр Pen с цветом Red и шириной 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Создайте экземпляр HatchBrush и задайте его свойства
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Создайте экземпляр Pen и инициализируйте его объектом HatchBrush и шириной
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Рисуйте Rectangles, указывая объект Pen
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Рисуйте Rectangles, указывая объект Pen
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Сохранить все изменения.
    image.save();
} finally {
    image.dispose();
}
```

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Возвращает цвет промежутков между линиями штриховки.

**Returns:**
[Color](../../com.aspose.imaging/color) - The color of spaces between the hatch lines.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Устанавливает цвет промежутков между линиями штриховки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Цвет промежутков между линиями штриховки. |


**Example: This example shows the creation and usage Pen objects.**
Этот пример показывает создание и использование объектов Pen. Пример создает новый Image и рисует Rectangles на поверхности Image.
``` java

// Создайте экземпляр BmpOptions и задайте его различные свойства
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

// Создайте экземпляр FileCreateSource и назначьте его в качестве Source для экземпляра BmpOptions
// Второй логический параметр определяет, является ли создаваемый файл временным (IsTemporal) или нет
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

// Создайте экземпляр Image по указанному пути
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    // Создайте экземпляр Graphics и инициализируйте его объектом Image
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    // Очистите поверхность Graphics цветом White Color.
    graphics.clear(com.aspose.imaging.Color.getWhite());

    // Создайте экземпляр Pen с цветом Red и шириной 5
    com.aspose.imaging.Pen pen = new com.aspose.imaging.Pen(com.aspose.imaging.Color.getRed(), 5);

    // Создайте экземпляр HatchBrush и задайте его свойства
    com.aspose.imaging.brushes.HatchBrush brush = new com.aspose.imaging.brushes.HatchBrush();
    brush.setBackgroundColor(com.aspose.imaging.Color.getWheat());
    brush.setForegroundColor(com.aspose.imaging.Color.getRed());

    // Создайте экземпляр Pen и инициализируйте его объектом HatchBrush и шириной
    com.aspose.imaging.Pen brushedpen = new com.aspose.imaging.Pen(brush, 5);

    // Рисуйте Rectangles, указывая объект Pen
    graphics.drawRectangles(pen, new com.aspose.imaging.Rectangle[]
            {
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(210, 210), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 110), new com.aspose.imaging.Size(100, 100)),
                    new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 310), new com.aspose.imaging.Size(100, 100))
            });

    // Рисуйте Rectangles, указывая объект Pen
    graphics.drawRectangles(
            brushedpen,
            new com.aspose.imaging.Rectangle[]
                    {
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(310, 110), new com.aspose.imaging.Size(100, 100)),
                            new com.aspose.imaging.Rectangle(new com.aspose.imaging.Point(110, 310), new com.aspose.imaging.Size(100, 100))
                    });

    // Сохранить все изменения.
    image.save();
} finally {
    image.dispose();
}
```

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Возвращает стиль штриховки этой кисти.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Устанавливает стиль штриховки этой кисти.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

