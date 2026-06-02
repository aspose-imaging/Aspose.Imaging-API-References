---
title: "Pen"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Определяет объект, используемый для рисования линий, кривых и фигур."
type: docs
weight: 81
url: /ru/java/com.aspose.imaging/pen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.TransparencySupporter](../../com.aspose.imaging/transparencysupporter)
```
public class Pen extends TransparencySupporter
```

Определяет объект, используемый для рисования линий, кривых и фигур.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Pen(Color color)](#Pen-com.aspose.imaging.Color-) | Инициализирует новый экземпляр класса `Pen` с указанным цветом. |
| [Pen(Color color, float width)](#Pen-com.aspose.imaging.Color-float-) | Инициализирует новый экземпляр класса `Pen` с указанными свойствами `Color` и `Pen.Width`. |
| [Pen(Brush brush)](#Pen-com.aspose.imaging.Brush-) | Инициализирует новый экземпляр класса `Pen` с указанным `Brush`. |
| [Pen(Brush brush, float width)](#Pen-com.aspose.imaging.Brush-float-) | Инициализирует новый экземпляр класса `Pen` с указанными `Brush` и `Pen.Width`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getWidth()](#getWidth--) | Возвращает ширину этого `Pen` в единицах объекта Graphics, используемого для рисования. |
| [setWidth(float value)](#setWidth-float-) | Устанавливает ширину этого `Pen` в единицах объекта Graphics, используемого для рисования. |
| [getStartCap()](#getStartCap--) | Возвращает стиль заголовка, используемый в начале линий, рисуемых этим `Pen`. |
| [setStartCap(int value)](#setStartCap-int-) | Устанавливает стиль заголовка, используемый в начале линий, рисуемых этим `Pen`. |
| [getEndCap()](#getEndCap--) | Возвращает стиль заголовка, используемый в конце линий, рисуемых этим `Pen`. |
| [setEndCap(int value)](#setEndCap-int-) | Устанавливает стиль заголовка, используемый в конце линий, рисуемых этим `Pen`. |
| [getDashCap()](#getDashCap--) | Возвращает стиль заголовка, используемый в конце штрихов, составляющих пунктирные линии, рисуемые этим `Pen`. |
| [setDashCap(int value)](#setDashCap-int-) | Устанавливает стиль заголовка, используемый в конце штрихов, составляющих пунктирные линии, рисуемые этим `Pen`. |
| [getLineJoin()](#getLineJoin--) | Возвращает стиль соединения концов двух последовательных линий, рисуемых этим `Pen`. |
| [setLineJoin(int value)](#setLineJoin-int-) | Устанавливает стиль соединения концов двух последовательных линий, рисуемых этим `Pen`. |
| [getCustomStartCap()](#getCustomStartCap--) | Возвращает пользовательский заголовок, используемый в начале линий, рисуемых этим `Pen`. |
| [setCustomStartCap(CustomLineCap value)](#setCustomStartCap-com.aspose.imaging.CustomLineCap-) | Устанавливает пользовательский заголовок, используемый в начале линий, рисуемых этим `Pen`. |
| [getCustomEndCap()](#getCustomEndCap--) | Возвращает пользовательский заголовок, используемый в конце линий, рисуемых этим `Pen`. |
| [setCustomEndCap(CustomLineCap value)](#setCustomEndCap-com.aspose.imaging.CustomLineCap-) | Устанавливает пользовательский заголовок, используемый в конце линий, рисуемых этим `Pen`. |
| [getMiterLimit()](#getMiterLimit--) | Возвращает предел толщины соединения на срезанном угле. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Устанавливает предел толщины соединения на скошенном угле. |
| [getAlignment()](#getAlignment--) | Получает выравнивание для этого `Pen`. |
| [setAlignment(int value)](#setAlignment-int-) | Устанавливает выравнивание для этого `Pen`. |
| [getTransform()](#getTransform--) | Получает копию геометрического преобразования для этого `Pen`. |
| [setTransform(Matrix value)](#setTransform-com.aspose.imaging.Matrix-) | Устанавливает копию геометрического преобразования для этого `Pen`. |
| [getPenType()](#getPenType--) | Получает стиль линий, рисуемых этим `Pen`. |
| [getColor()](#getColor--) | Получает цвет этого `Pen`. |
| [setColor(Color value)](#setColor-com.aspose.imaging.Color-) | Устанавливает цвет этого `Pen`. |
| [getBrush()](#getBrush--) | Получает `Brush`, определяющий атрибуты этого `Pen`. |
| [setBrush(Brush value)](#setBrush-com.aspose.imaging.Brush-) | Устанавливает `Brush`, определяющий атрибуты этого `Pen`. |
| [getDashStyle()](#getDashStyle--) | Получает стиль, используемый для пунктирных линий, рисуемых этим `Pen`. |
| [setDashStyle(int value)](#setDashStyle-int-) | Устанавливает стиль, используемый для пунктирных линий, рисуемых этим `Pen`. |
| [getDashOffset()](#getDashOffset--) | Получает расстояние от начала линии до начала шаблона пунктиров. |
| [setDashOffset(float value)](#setDashOffset-float-) | Устанавливает расстояние от начала линии до начала шаблона пунктиров. |
| [getDashPattern()](#getDashPattern--) | Получает массив пользовательских пунктиров и пробелов. |
| [setDashPattern(float[] value)](#setDashPattern-float---) | Устанавливает массив пользовательских пунктиров и пробелов. |
| [getCompoundArray()](#getCompoundArray--) | Получает массив значений, определяющих составную ручку. |
| [setCompoundArray(float[] value)](#setCompoundArray-float---) | Устанавливает массив значений, определяющих составную ручку. |
| [setLineCap(int startCap, int endCap, int dashCap)](#setLineCap-int-int-int-) | Устанавливает значения, определяющие стиль окончания, используемого для завершения линий, рисуемых этим `Pen`. |
| [resetTransform()](#resetTransform--) | Сбрасывает матрицу геометрического преобразования для этого `Pen` к единичной. |
| [multiplyTransform(Matrix matrix)](#multiplyTransform-com.aspose.imaging.Matrix-) | Умножает матрицу преобразования для этого `Pen` на указанную `Matrix`. |
| [multiplyTransform(Matrix matrix, int order)](#multiplyTransform-com.aspose.imaging.Matrix-int-) | Умножает матрицу преобразования для этого `Pen` на указанную `Matrix` в указанном порядке. |
| [translateTransform(float dx, float dy)](#translateTransform-float-float-) | Смещает локальное геометрическое преобразование на указанные размеры. |
| [translateTransform(float dx, float dy, int order)](#translateTransform-float-float-int-) | Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке. |
| [scaleTransform(float sx, float sy)](#scaleTransform-float-float-) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты. |
| [scaleTransform(float sx, float sy, int order)](#scaleTransform-float-float-int-) | Масштабирует локальное геометрическое преобразование на указанные коэффициенты в указанном порядке. |
| [rotateTransform(float angle)](#rotateTransform-float-) | Поворачивает локальное геометрическое преобразование на указанный угол. |
| [rotateTransform(float angle, int order)](#rotateTransform-float-int-) | Поворачивает локальное геометрическое преобразование на указанный угол в указанном порядке. |
| [equals(Object o)](#equals-java.lang.Object-) | Проверяет, равны ли объекты. |
| [hashCode()](#hashCode--) |  |

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

### Pen(Color color) {#Pen-com.aspose.imaging.Color-}
```
public Pen(Color color)
```


Инициализирует новый экземпляр класса `Pen` с указанным цветом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Структура `Color`, указывающая цвет этого `Pen`. |

### Pen(Color color, float width) {#Pen-com.aspose.imaging.Color-float-}
```
public Pen(Color color, float width)
```


Инициализирует новый экземпляр класса `Pen` с указанными свойствами `Color` и `Pen.Width`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| color | [Color](../../com.aspose.imaging/color) | Структура `Color`, указывающая цвет этого `Pen`. |
| width | float | Значение, указывающее ширину этого `Pen`. |

### Pen(Brush brush) {#Pen-com.aspose.imaging.Brush-}
```
public Pen(Brush brush)
```


Инициализирует новый экземпляр класса `Pen` с указанным `Brush`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `Brush`, определяющая свойства заливки этого `Pen`. |

### Pen(Brush brush, float width) {#Pen-com.aspose.imaging.Brush-float-}
```
public Pen(Brush brush, float width)
```


Инициализирует новый экземпляр класса `Pen` с указанными `Brush` и `Pen.Width`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brush | [Brush](../../com.aspose.imaging/brush) | `Brush`, определяющая характеристики этого `Pen`. |
| width | float | Ширина нового `Pen`. |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Возвращает ширину этого `Pen` в единицах объекта Graphics, используемого для рисования.

**Returns:**
float - Ширина этого `Pen`.
### setWidth(float value) {#setWidth-float-}
```
public void setWidth(float value)
```


Устанавливает ширину этого `Pen` в единицах объекта Graphics, используемого для рисования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Ширина этого `Pen`. |

### getStartCap() {#getStartCap--}
```
public int getStartCap()
```


Возвращает стиль заголовка, используемый в начале линий, рисуемых этим `Pen`.

**Returns:**
int - Одно из значений `LineCap`, представляющее стиль начала линий, нарисованных этим `Pen`.
### setStartCap(int value) {#setStartCap-int-}
```
public void setStartCap(int value)
```


Устанавливает стиль заголовка, используемый в начале линий, рисуемых этим `Pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Одно из значений `LineCap`, представляющее стиль начала линий, нарисованных этим `Pen`. |

### getEndCap() {#getEndCap--}
```
public int getEndCap()
```


Возвращает стиль заголовка, используемый в конце линий, рисуемых этим `Pen`.

**Returns:**
int - Одно из значений `LineCap`, представляющее стиль окончания линий, нарисованных этим `Pen`.
### setEndCap(int value) {#setEndCap-int-}
```
public void setEndCap(int value)
```


Устанавливает стиль заголовка, используемый в конце линий, рисуемых этим `Pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Одно из значений `LineCap`, представляющее стиль окончания линий, нарисованных этим `Pen`. |

### getDashCap() {#getDashCap--}
```
public int getDashCap()
```


Возвращает стиль заголовка, используемый в конце штрихов, составляющих пунктирные линии, рисуемые этим `Pen`.

**Returns:**
int - Одно из значений `DashCap`, представляющее стиль начала и конца тире, составляющих пунктирные линии, нарисованные этим `Pen`.
### setDashCap(int value) {#setDashCap-int-}
```
public void setDashCap(int value)
```


Устанавливает стиль заголовка, используемый в конце штрихов, составляющих пунктирные линии, рисуемые этим `Pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Одно из значений `DashCap`, представляющее стиль начала и конца тире, составляющих пунктирные линии, нарисованные этим `Pen`. |

### getLineJoin() {#getLineJoin--}
```
public int getLineJoin()
```


Возвращает стиль соединения концов двух последовательных линий, рисуемых этим `Pen`.

**Returns:**
int - `LineJoin`, представляющий стиль соединения концов двух последовательных линий, нарисованных этим `Pen`.
### setLineJoin(int value) {#setLineJoin-int-}
```
public void setLineJoin(int value)
```


Устанавливает стиль соединения концов двух последовательных линий, рисуемых этим `Pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Объект `LineJoin`, представляющий стиль соединения концов двух последовательных линий, нарисованных этим `Pen`. |

### getCustomStartCap() {#getCustomStartCap--}
```
public CustomLineCap getCustomStartCap()
```


Возвращает пользовательский заголовок, используемый в начале линий, рисуемых этим `Pen`.

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the beginning of lines drawn with this `Pen`.
### setCustomStartCap(CustomLineCap value) {#setCustomStartCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomStartCap(CustomLineCap value)
```


Устанавливает пользовательский заголовок, используемый в начале линий, рисуемых этим `Pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | Объект `CustomLineCap`, представляющий окончание, используемое в начале линий, нарисованных этим `Pen`. |

### getCustomEndCap() {#getCustomEndCap--}
```
public CustomLineCap getCustomEndCap()
```


Возвращает пользовательский заголовок, используемый в конце линий, рисуемых этим `Pen`.

**Returns:**
[CustomLineCap](../../com.aspose.imaging/customlinecap) - A `CustomLineCap` that represents the cap used at the end of lines drawn with this `Pen`.
### setCustomEndCap(CustomLineCap value) {#setCustomEndCap-com.aspose.imaging.CustomLineCap-}
```
public void setCustomEndCap(CustomLineCap value)
```


Устанавливает пользовательский заголовок, используемый в конце линий, рисуемых этим `Pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [CustomLineCap](../../com.aspose.imaging/customlinecap) | Объект `CustomLineCap`, представляющий окончание, используемое в конце линий, нарисованных этим `Pen`. |

### getMiterLimit() {#getMiterLimit--}
```
public float getMiterLimit()
```


Возвращает предел толщины соединения на срезанном угле.

**Returns:**
float — предел толщины соединения на скошенном угле.
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public void setMiterLimit(float value)
```


Устанавливает предел толщины соединения на скошенном угле.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Предел толщины соединения на скошенном угле. |

### getAlignment() {#getAlignment--}
```
public int getAlignment()
```


Получает выравнивание для этого `Pen`.

**Returns:**
int — объект `PenAlignment`, представляющий выравнивание для этого `Pen`.
### setAlignment(int value) {#setAlignment-int-}
```
public void setAlignment(int value)
```


Устанавливает выравнивание для этого `Pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Объект `PenAlignment`, представляющий выравнивание для этого `Pen`. |

### getTransform() {#getTransform--}
```
public Matrix getTransform()
```


Получает копию геометрического преобразования для этого `Pen`.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix) - A copy of the `Matrix` that represents the geometric transformation for this `Pen`.
### setTransform(Matrix value) {#setTransform-com.aspose.imaging.Matrix-}
```
public void setTransform(Matrix value)
```


Устанавливает копию геометрического преобразования для этого `Pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) | Копия `Matrix`, представляющая геометрическое преобразование для этого `Pen`. |

### getPenType() {#getPenType--}
```
public int getPenType()
```


Получает стиль линий, рисуемых этим `Pen`.

**Returns:**
int — перечисление `PenType`, определяющее стиль линий, нарисованных этим `Pen`.
### getColor() {#getColor--}
```
public Color getColor()
```


Получает цвет этого `Pen`.

**Returns:**
[Color](../../com.aspose.imaging/color) - A `Color` structure that represents the color of this `Pen`.
### setColor(Color value) {#setColor-com.aspose.imaging.Color-}
```
public void setColor(Color value)
```


Устанавливает цвет этого `Pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Структура `Color`, представляющая цвет этого `Pen`. |

### getBrush() {#getBrush--}
```
public Brush getBrush()
```


Получает `Brush`, определяющий атрибуты этого `Pen`.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A `Brush` that determines attributes of this `Pen`.
### setBrush(Brush value) {#setBrush-com.aspose.imaging.Brush-}
```
public void setBrush(Brush value)
```


Устанавливает `Brush`, определяющий атрибуты этого `Pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Brush](../../com.aspose.imaging/brush) | Объект `Brush`, определяющий атрибуты этого `Pen`. |

### getDashStyle() {#getDashStyle--}
```
public int getDashStyle()
```


Получает стиль, используемый для пунктирных линий, рисуемых этим `Pen`.

**Returns:**
int — объект `DashStyle`, представляющий стиль, используемый для пунктирных линий, нарисованных этим `Pen`.
### setDashStyle(int value) {#setDashStyle-int-}
```
public void setDashStyle(int value)
```


Устанавливает стиль, используемый для пунктирных линий, рисуемых этим `Pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Объект `DashStyle`, представляющий стиль, используемый для пунктирных линий, нарисованных этим `Pen`. |

### getDashOffset() {#getDashOffset--}
```
public float getDashOffset()
```


Получает расстояние от начала линии до начала шаблона пунктиров.

**Returns:**
float — расстояние от начала линии до начала шаблона пунктиров.
### setDashOffset(float value) {#setDashOffset-float-}
```
public void setDashOffset(float value)
```


Устанавливает расстояние от начала линии до начала шаблона пунктиров.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Расстояние от начала линии до начала шаблона пунктиров. |

### getDashPattern() {#getDashPattern--}
```
public float[] getDashPattern()
```


Получает массив пользовательских пунктиров и пробелов.

**Returns:**
float[] — массив действительных чисел, задающий длины чередующихся пунктиров и пробелов в пунктирных линиях.
### setDashPattern(float[] value) {#setDashPattern-float---}
```
public void setDashPattern(float[] value)
```


Устанавливает массив пользовательских пунктиров и пробелов.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] | Массив действительных чисел, задающий длины чередующихся пунктиров и пробелов в пунктирных линиях. |

### getCompoundArray() {#getCompoundArray--}
```
public float[] getCompoundArray()
```


Получает массив значений, определяющий составную ручку. Составная ручка рисует составную линию, состоящую из параллельных линий и промежутков.

**Returns:**
float[] — массив действительных чисел, задающий составной массив. Элементы массива должны быть упорядочены по возрастанию, не меньше 0 и не больше 1.
### setCompoundArray(float[] value) {#setCompoundArray-float---}
```
public void setCompoundArray(float[] value)
```


Устанавливает массив значений, определяющий составную ручку. Составная ручка рисует составную линию, состоящую из параллельных линий и промежутков.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] | Массив действительных чисел, задающий составной массив. Элементы массива должны быть упорядочены по возрастанию, не меньше 0 и не больше 1. |

### setLineCap(int startCap, int endCap, int dashCap) {#setLineCap-int-int-int-}
```
public void setLineCap(int startCap, int endCap, int dashCap)
```


Устанавливает значения, определяющие стиль окончания, используемого для завершения линий, рисуемых этим `Pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startCap | int | Объект `LineCap`, представляющий стиль окончания, используемый в начале линий, нарисованных этим `Pen`. |
| endCap | int | Объект `LineCap`, представляющий стиль окончания, используемый в конце линий, нарисованных этим `Pen`. |
| dashCap | int | Объект `LineCap`, представляющий стиль окончания, используемый в начале или в конце пунктирных линий, нарисованных этим `Pen`. |

### resetTransform() {#resetTransform--}
```
public void resetTransform()
```


Сбрасывает матрицу геометрического преобразования для этого `Pen` к единичной.

### multiplyTransform(Matrix matrix) {#multiplyTransform-com.aspose.imaging.Matrix-}
```
public void multiplyTransform(Matrix matrix)
```


Умножает матрицу преобразования для этого `Pen` на указанную `Matrix`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | Объект `Matrix`, которым умножать матрицу преобразования. |

### multiplyTransform(Matrix matrix, int order) {#multiplyTransform-com.aspose.imaging.Matrix-int-}
```
public void multiplyTransform(Matrix matrix, int order)
```


Умножает матрицу преобразования для этого `Pen` на указанную `Matrix` в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| matrix | [Matrix](../../com.aspose.imaging/matrix) | `Matrix`, которым умножать матрицу преобразования. |
| order | int | Порядок, в котором выполнять операцию умножения. |

### translateTransform(float dx, float dy) {#translateTransform-float-float-}
```
public void translateTransform(float dx, float dy)
```


Перемещает локальное геометрическое преобразование на указанные размеры. Этот метод добавляет трансляцию в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |

### translateTransform(float dx, float dy, int order) {#translateTransform-float-float-int-}
```
public void translateTransform(float dx, float dy, int order)
```


Смещает локальное геометрическое преобразование на указанные размеры в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dx | float | Значение трансляции по оси x. |
| dy | float | Значение трансляции по оси y. |
| order | int | Порядок (добавление в начало или в конец), в котором применять трансляцию. |

### scaleTransform(float sx, float sy) {#scaleTransform-float-float-}
```
public void scaleTransform(float sx, float sy)
```


Масштабирует локальное геометрическое преобразование на указанные коэффициенты. Этот метод добавляет матрицу масштабирования в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Коэффициент, на который масштабировать преобразование по оси x. |
| sy | float | Коэффициент, на который масштабировать преобразование по оси y. |

### scaleTransform(float sx, float sy, int order) {#scaleTransform-float-float-int-}
```
public void scaleTransform(float sx, float sy, int order)
```


Масштабирует локальное геометрическое преобразование на указанные коэффициенты в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sx | float | Коэффициент, на который масштабировать преобразование по оси x. |
| sy | float | Коэффициент, на который масштабировать преобразование по оси y. |
| order | int | `MatrixOrder`, указывающий, добавлять ли матрицу масштабирования в конец или в начало. |

### rotateTransform(float angle) {#rotateTransform-float-}
```
public void rotateTransform(float angle)
```


Вращает локальное геометрическое преобразование на указанный угол. Этот метод добавляет вращение в начало преобразования.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения. |

### rotateTransform(float angle, int order) {#rotateTransform-float-int-}
```
public void rotateTransform(float angle, int order)
```


Поворачивает локальное геометрическое преобразование на указанный угол в указанном порядке.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| angle | float | Угол вращения. |
| order | int | `MatrixOrder`, указывающий, добавлять ли матрицу вращения в конец или в начало. |

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
int
