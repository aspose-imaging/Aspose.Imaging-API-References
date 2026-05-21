---
title: "CustomLineCap"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Инкапсулирует пользовательский определённый конец линии."
type: docs
weight: 35
url: /ru/java/com.aspose.imaging/customlinecap/
---
**Inheritance:**
java.lang.Object
```
public class CustomLineCap
```

Инкапсулирует пользовательский определённый конец линии.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-) | Создаёт новый экземпляр класса `CustomLineCap` с указанными контуром и заливкой. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-) | Создаёт новый экземпляр класса `CustomLineCap` из указанного существующего перечисления `LineCap` с указанными контуром и заливкой. |
| [CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)](#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-) | Создаёт новый экземпляр класса `CustomLineCap` из указанного существующего перечисления `LineCap` с указанными контуром, заливкой и отступом. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFillPath()](#getFillPath--) | Возвращает объект, определяющий заливку для кастомного наконечника. |
| [setFillPath(GraphicsPath value)](#setFillPath-com.aspose.imaging.GraphicsPath-) | Устанавливает объект, определяющий заливку для пользовательской насадки. |
| [getStrokePath()](#getStrokePath--) | Получает объект, определяющий контур пользовательской насадки. |
| [setStrokePath(GraphicsPath value)](#setStrokePath-com.aspose.imaging.GraphicsPath-) | Устанавливает объект, определяющий контур пользовательской насадки. |
| [getStrokeJoin()](#getStrokeJoin--) | Получает перечисление `LineJoin`, определяющее, как соединяются линии, составляющие объект `CustomLineCap`. |
| [setStrokeJoin(int value)](#setStrokeJoin-int-) | Устанавливает перечисление `LineJoin`, определяющее, как соединяются линии, составляющие объект `CustomLineCap`. |
| [getBaseCap()](#getBaseCap--) | Получает перечисление `LineCap`, на основе которого построен этот `CustomLineCap`. |
| [setBaseCap(int value)](#setBaseCap-int-) | Устанавливает перечисление `LineCap`, на основе которого построен этот `CustomLineCap`. |
| [getBaseInset()](#getBaseInset--) | Получает расстояние между насадкой и линией. |
| [setBaseInset(float value)](#setBaseInset-float-) | Устанавливает расстояние между насадкой и линией. |
| [getWidthScale()](#getWidthScale--) | Получает величину, на которую следует масштабировать объект класса `CustomLineCap` относительно ширины объекта `System.Drawing.Pen`. |
| [setWidthScale(float value)](#setWidthScale-float-) | Устанавливает величину, на которую следует масштабировать объект класса `CustomLineCap` относительно ширины объекта `System.Drawing.Pen`. |
| [setStrokeCaps(int startCap, int endCap)](#setStrokeCaps-int-int-) | Устанавливает насадки, используемые для начала и окончания линий, составляющих эту пользовательскую насадку. |
| [getStrokeCaps(int[] startCap, int[] endCap)](#getStrokeCaps-int---int---) | Получает насадки, используемые для начала и окончания линий, составляющих эту пользовательскую насадку. |
| [equals(Object o)](#equals-java.lang.Object-) | Проверяет, равны ли объекты. |
| [hashCode()](#hashCode--) | Получает хеш‑код текущего объекта. |
### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath)
```


Создаёт новый экземпляр класса `CustomLineCap` с указанными контуром и заливкой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект `GraphicsPath`, определяющий заливку для пользовательской насадки. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект `GraphicsPath`, определяющий контур пользовательской насадки. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap)
```


Создаёт новый экземпляр класса `CustomLineCap` из указанного существующего перечисления `LineCap` с указанными контуром и заливкой.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект `GraphicsPath`, определяющий заливку для пользовательской насадки. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект `GraphicsPath`, определяющий контур пользовательской насадки. |
| baseCap | int | Насадка линии, из которой создаётся пользовательская насадка. |

### CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset) {#CustomLineCap-com.aspose.imaging.GraphicsPath-com.aspose.imaging.GraphicsPath-int-float-}
```
public CustomLineCap(GraphicsPath fillPath, GraphicsPath strokePath, int baseCap, float baseInset)
```


Создаёт новый экземпляр класса `CustomLineCap` из указанного существующего перечисления `LineCap` с указанными контуром, заливкой и отступом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fillPath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект `GraphicsPath`, определяющий заливку для пользовательской насадки. |
| strokePath | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект `GraphicsPath`, определяющий контур пользовательской насадки. |
| baseCap | int | Насадка линии, из которой создаётся пользовательская насадка. |
| baseInset | float | Расстояние между насадкой и линией. |

### getFillPath() {#getFillPath--}
```
public GraphicsPath getFillPath()
```


Возвращает объект, определяющий заливку для кастомного наконечника.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the fill for the custom cap.
### setFillPath(GraphicsPath value) {#setFillPath-com.aspose.imaging.GraphicsPath-}
```
public void setFillPath(GraphicsPath value)
```


Устанавливает объект, определяющий заливку для пользовательской насадки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект, определяющий заливку для пользовательской насадки. |

### getStrokePath() {#getStrokePath--}
```
public GraphicsPath getStrokePath()
```


Получает объект, определяющий контур пользовательской насадки.

**Returns:**
[GraphicsPath](../../com.aspose.imaging/graphicspath) - The object that defines the outline of the custom cap.
### setStrokePath(GraphicsPath value) {#setStrokePath-com.aspose.imaging.GraphicsPath-}
```
public void setStrokePath(GraphicsPath value)
```


Устанавливает объект, определяющий контур пользовательской насадки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [GraphicsPath](../../com.aspose.imaging/graphicspath) | Объект, определяющий контур пользовательской насадки. |

### getStrokeJoin() {#getStrokeJoin--}
```
public int getStrokeJoin()
```


Получает перечисление `LineJoin`, определяющее, как соединяются линии, составляющие объект `CustomLineCap`.

**Returns:**
int — перечисление `LineJoin`, которое использует объект `CustomLineCap` для соединения линий.
### setStrokeJoin(int value) {#setStrokeJoin-int-}
```
public void setStrokeJoin(int value)
```


Устанавливает перечисление `LineJoin`, определяющее, как соединяются линии, составляющие объект `CustomLineCap`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Перечисление `LineJoin`, которое использует объект `CustomLineCap` для соединения линий. |

### getBaseCap() {#getBaseCap--}
```
public int getBaseCap()
```


Получает перечисление `LineCap`, на основе которого построен этот `CustomLineCap`.

**Returns:**
int — перечисление `LineCap`, на основе которого построен этот `CustomLineCap`.
### setBaseCap(int value) {#setBaseCap-int-}
```
public void setBaseCap(int value)
```


Устанавливает перечисление `LineCap`, на основе которого построен этот `CustomLineCap`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Перечисление `LineCap`, на основе которого построен этот `CustomLineCap`. |

### getBaseInset() {#getBaseInset--}
```
public float getBaseInset()
```


Получает расстояние между насадкой и линией.

**Returns:**
float - Расстояние между началом штриха и концом линии.
### setBaseInset(float value) {#setBaseInset-float-}
```
public void setBaseInset(float value)
```


Устанавливает расстояние между насадкой и линией.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Расстояние между началом штриха и концом линии. |

### getWidthScale() {#getWidthScale--}
```
public float getWidthScale()
```


Получает величину, на которую следует масштабировать объект класса `CustomLineCap` относительно ширины объекта `System.Drawing.Pen`.

**Returns:**
float - Величина, на которую следует масштабировать штрих.
### setWidthScale(float value) {#setWidthScale-float-}
```
public void setWidthScale(float value)
```


Устанавливает величину, на которую следует масштабировать объект класса `CustomLineCap` относительно ширины объекта `System.Drawing.Pen`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Величина, на которую следует масштабировать штрих. |

### setStrokeCaps(int startCap, int endCap) {#setStrokeCaps-int-int-}
```
public void setStrokeCaps(int startCap, int endCap)
```


Устанавливает насадки, используемые для начала и окончания линий, составляющих эту пользовательскую насадку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startCap | int | Перечисление `LineCap`, используемое в начале линии внутри этого штриха. |
| endCap | int | Перечисление `LineCap`, используемое в конце линии внутри этого штриха. |

### getStrokeCaps(int[] startCap, int[] endCap) {#getStrokeCaps-int---int---}
```
public void getStrokeCaps(int[] startCap, int[] endCap)
```


Получает насадки, используемые для начала и окончания линий, составляющих эту пользовательскую насадку.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startCap | int[] | Перечисление `LineCap`, используемое в начале линии внутри этого штриха. |
| endCap | int[] | Перечисление `LineCap`, используемое в конце линии внутри этого штриха. |

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
