---
title: "Blend"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Определяет шаблон смешивания."
type: docs
weight: 12
url: /ru/java/com.aspose.imaging/blend/
---
**Inheritance:**
java.lang.Object
```
public final class Blend
```

Определяет шаблон смешивания. Этот класс не может быть наследован.

Типичное использование класса blend заключается в определении шаблона blend для brush. Поэтому свойства blend должны инициализироваться осторожно. Null массивы не допускаются. brush выбросит соответствующее exception, если массивы blend factors или positions пусты или их длина не совпадает. Если в массиве positions два или более элементов, то первый элемент должен быть 0, а последний — 1.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Blend()](#Blend--) | Инициализирует новый экземпляр класса `Blend`. |
| [Blend(int count)](#Blend-int-) | Инициализирует новый экземпляр класса `Blend` с указанным числом факторов и позиций. |
## Методы

| Метод | Описание |
| --- | --- |
| [getFactors()](#getFactors--) | Получает массив blend factors для градиента. |
| [setFactors(float[] value)](#setFactors-float---) | Устанавливает массив blend factors для градиента. |
| [getPositions()](#getPositions--) | Получает массив blend positions для градиента. |
| [setPositions(float[] value)](#setPositions-float---) | Устанавливает массив blend positions для градиента. |
| [equals(Object obj)](#equals-java.lang.Object-) | Проверяет, является ли указанный объект классом `com.aspose.imaging.Blend` и эквивалентен ли этому классу `com.aspose.imaging.Blend`. |
| [hashCode()](#hashCode--) | Возвращает хеш-код для этого экземпляра. |
### Blend() {#Blend--}
```
public Blend()
```


Инициализирует новый экземпляр класса `Blend`. Количество элементов в массивах факторов и массивов смешения будет равно 1.

### Blend(int count) {#Blend-int-}
```
public Blend(int count)
```


Инициализирует новый экземпляр класса `Blend` с указанным числом факторов и позиций.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| count | int | Количество элементов в массивах факторов и позиций. |

### getFactors() {#getFactors--}
```
public float[] getFactors()
```


Получает массив blend factors для градиента.

**Returns:**
float[] — массив коэффициентов смешения, определяющих процентное соотношение начального и конечного цвета, используемое в соответствующей позиции.
### setFactors(float[] value) {#setFactors-float---}
```
public void setFactors(float[] value)
```


Устанавливает массив blend factors для градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] | Массив коэффициентов смешения, определяющих процентное соотношение начального и конечного цвета, используемое в соответствующей позиции. |

### getPositions() {#getPositions--}
```
public float[] getPositions()
```


Получает массив blend positions для градиента.

**Returns:**
float[] — массив позиций смешения, определяющих процентное соотношение расстояния вдоль линии градиента.
### setPositions(float[] value) {#setPositions-float---}
```
public void setPositions(float[] value)
```


Устанавливает массив blend positions для градиента.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float[] | Массив позиций смешения, определяющих процентное соотношение расстояния вдоль линии градиента. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Проверяет, является ли указанный объект классом `com.aspose.imaging.Blend` и эквивалентен ли этому классу `com.aspose.imaging.Blend`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object | Объект для проверки. |

**Returns:**
boolean — true, если `obj` является классом `com.aspose.imaging.Blend`, эквивалентным этому классу `com.aspose.imaging.Blend`; иначе false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Возвращает хеш-код для этого экземпляра.

**Returns:**
int — хеш-код для этого экземпляра, пригодный для использования в алгоритмах хеширования и структурах данных, таких как хеш-таблица.
