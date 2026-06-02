---
title: "ColorBlend"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Определяет массивы цветов и позиций, используемых для интерполяции смешивания цветов в многокрасочном градиенте."
type: docs
weight: 22
url: /ru/java/com.aspose.imaging/colorblend/
---
**Inheritance:**
java.lang.Object
```
public final class ColorBlend
```

Определяет массивы цветов и позиций, используемые для интерполяции смешивания цветов в многокрасочном градиенте. Этот класс не может быть наследован.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [ColorBlend()](#ColorBlend--) | Инициализирует новый экземпляр класса `com.aspose.imaging.ColorBlend`. |
| [ColorBlend(int count)](#ColorBlend-int-) | Инициализирует новый экземпляр класса `com.aspose.imaging.ColorBlend` с указанным количеством цветов и позиций. |
## Методы

| Метод | Описание |
| --- | --- |
| [getColors()](#getColors--) | Получает или задает массив цветов, представляющий цвета, используемые в соответствующих позициях вдоль градиента. |
| [setColors(Color[] value)](#setColors-com.aspose.imaging.Color---) |  |
| [getPositions()](#getPositions--) | Получает или задает позиции вдоль линии градиента. |
| [setPositions(float[] value)](#setPositions-float---) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверяет, является ли указанный объект классом `com.aspose.imaging.ColorBlend` и эквивалентен этому классу `com.aspose.imaging.ColorBlend`. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
### ColorBlend() {#ColorBlend--}
```
public ColorBlend()
```


Инициализирует новый экземпляр класса `com.aspose.imaging.ColorBlend`.

### ColorBlend(int count) {#ColorBlend-int-}
```
public ColorBlend(int count)
```


Инициализирует новый экземпляр класса `com.aspose.imaging.ColorBlend` с указанным количеством цветов и позиций.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| count | int | Количество цветов и позиций в этом `com.aspose.imaging.ColorBlend`. |

### getColors() {#getColors--}
```
public Color[] getColors()
```


Получает или задает массив цветов, представляющий цвета, используемые в соответствующих позициях вдоль градиента.

**Returns:**
com.aspose.imaging.Color[] — массив структур `com.aspose.imaging.Color`, представляющих цвета, используемые в соответствующих позициях вдоль градиента.
### setColors(Color[] value) {#setColors-com.aspose.imaging.Color---}
```
public void setColors(Color[] value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color\[\]](../../com.aspose.imaging/color) |  |

### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Получает или задает позиции вдоль линии градиента.

**Returns:**
float[] — массив значений, указывающих процент расстояния вдоль линии градиента.
### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверяет, является ли указанный объект классом `com.aspose.imaging.ColorBlend` и эквивалентен этому классу `com.aspose.imaging.ColorBlend`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для проверки. |

**Returns:**
boolean — true, если `obj` является классом `com.aspose.imaging.ColorBlend`, эквивалентным этому классу `com.aspose.imaging.ColorBlend`; в противном случае — false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int — хеш-код для этого экземпляра, пригодный для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
