---
title: "TextShape"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет текстовую форму."
type: docs
weight: 18
url: /ru/java/com.aspose.imaging.shapes/textshape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.ObjectWithBounds](../../com.aspose.imaging/objectwithbounds), [com.aspose.imaging.Shape](../../com.aspose.imaging/shape), [com.aspose.imaging.shapes.RectangleProjectedShape](../../com.aspose.imaging.shapes/rectangleprojectedshape)
```
public final class TextShape extends RectangleProjectedShape
```

Представляет текстовую форму.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextShape()](#TextShape--) | Инициализирует новый экземпляр класса `TextShape`. |
| [TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)](#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-) | Инициализирует новый экземпляр класса `TextShape`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getText()](#getText--) | Получает или задает отображаемый текст. |
| [setText(String value)](#setText-java.lang.String-) | Получает или задает отображаемый текст. |
| [getFont()](#getFont--) | Получает или задает шрифт, используемый для отображения текста. |
| [setFont(Font value)](#setFont-com.aspose.imaging.Font-) | Получает или задает шрифт, используемый для отображения текста. |
| [getTextFormat()](#getTextFormat--) | Получает или задает формат текста. |
| [setTextFormat(StringFormat value)](#setTextFormat-com.aspose.imaging.StringFormat-) | Получает или задает формат текста. |
| [getCenter()](#getCenter--) | Получает центр фигуры. |
| [getBounds()](#getBounds--) | Получает границы объекта. |
| [getSegments()](#getSegments--) | Получает сегменты фигуры. |
| [hasSegments()](#hasSegments--) | Получает значение, указывающее, есть ли у фигуры сегменты. |
| [getBounds(Matrix matrix)](#getBounds-com.aspose.imaging.Matrix-) | Получает границы объекта. |
| [getBounds(Matrix matrix, Pen pen)](#getBounds-com.aspose.imaging.Matrix-com.aspose.imaging.Pen-) | Получает границы объекта. |
| [transform(Matrix transform)](#transform-com.aspose.imaging.Matrix-) | Применяет указанное преобразование к форме. |
| [equals(Object o)](#equals-java.lang.Object-) | Проверяет, равны ли объекты. |
| [hashCode()](#hashCode--) | Получает хеш‑код текущего объекта. |
### TextShape() {#TextShape--}
```
public TextShape()
```


Инициализирует новый экземпляр класса `TextShape`.

### TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat) {#TextShape-java.lang.String-com.aspose.imaging.RectangleF-com.aspose.imaging.Font-com.aspose.imaging.StringFormat-}
```
public TextShape(String text, RectangleF rectangle, Font font, StringFormat stringFormat)
```


Инициализирует новый экземпляр класса `TextShape`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для отображения. |
| rectangle | [RectangleF](../../com.aspose.imaging/rectanglef) | Прямоугольник текста. |
| font | [Font](../../com.aspose.imaging/font) | Шрифт для использования. |
| stringFormat | [StringFormat](../../com.aspose.imaging/stringformat) | Формат строки. |

### getText() {#getText--}
```
public String getText()
```


Получает или задает отображаемый текст.

Значение: Нарисованный текст.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public void setText(String value)
```


Получает или задает отображаемый текст.

Значение: Нарисованный текст.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getFont() {#getFont--}
```
public Font getFont()
```


Получает или задает шрифт, используемый для отображения текста.

Значение: Шрифт, используемый для рисования текста.

**Returns:**
[Font](../../com.aspose.imaging/font)
### setFont(Font value) {#setFont-com.aspose.imaging.Font-}
```
public void setFont(Font value)
```


Получает или задает шрифт, используемый для отображения текста.

Значение: Шрифт, используемый для рисования текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Font](../../com.aspose.imaging/font) |  |

### getTextFormat() {#getTextFormat--}
```
public StringFormat getTextFormat()
```


Получает или задает формат текста.

Значение: Формат текста.

**Returns:**
[StringFormat](../../com.aspose.imaging/stringformat)
### setTextFormat(StringFormat value) {#setTextFormat-com.aspose.imaging.StringFormat-}
```
public void setTextFormat(StringFormat value)
```


Получает или задает формат текста.

Значение: Формат текста.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [StringFormat](../../com.aspose.imaging/stringformat) |  |

### getCenter() {#getCenter--}
```
public PointF getCenter()
```


Получает центр фигуры.

Значение: Центр формы.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### getBounds() {#getBounds--}
```
public RectangleF getBounds()
```


Получает границы объекта.

Значение: Границы объекта.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef)
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
