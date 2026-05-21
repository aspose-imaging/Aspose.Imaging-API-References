---
title: "Brush"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Базовый класс кисти."
type: docs
weight: 13
url: /ru/java/com.aspose.imaging/brush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject)
```
public abstract class Brush extends DisposableObject
```

Базовый класс кисти.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Brush()](#Brush--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getOpacity()](#getOpacity--) | Получает непрозрачность кисти. |
| [setOpacity(float value)](#setOpacity-float-) | Устанавливает непрозрачность кисти. |
| [deepClone()](#deepClone--) | Создаёт новый глубокий клон текущего `Brush`. |
| [equals(Object o)](#equals-java.lang.Object-) | Проверяет, равны ли объекты. |
| [hashCode()](#hashCode--) | Получает хеш‑код текущего объекта. |
### Brush() {#Brush--}
```
public Brush()
```


### getOpacity() {#getOpacity--}
```
public float getOpacity()
```


Получает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна.

**Returns:**
float — значение непрозрачности кисти.
### setOpacity(float value) {#setOpacity-float-}
```
public void setOpacity(float value)
```


Устанавливает непрозрачность кисти. Значение должно быть от 0 до 1. Значение 0 означает, что кисть полностью видима, значение 1 означает, что кисть полностью непрозрачна.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float | Значение непрозрачности кисти. |

### deepClone() {#deepClone--}
```
public Brush deepClone()
```


Создаёт новый глубокий клон текущего `Brush`.

**Returns:**
[Brush](../../com.aspose.imaging/brush) - A new `Brush` which is the deep clone of this `Brush` instance.
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
