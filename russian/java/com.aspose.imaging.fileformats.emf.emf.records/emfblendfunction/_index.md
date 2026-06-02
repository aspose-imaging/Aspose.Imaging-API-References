---
title: "EmfBlendFunction"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Структура, определяющая операции смешивания для исходных и целевых bitmap."
type: docs
weight: 18
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.lang.Struct
```
public class EmfBlendFunction extends Struct<EmfBlendFunction>
```

Структура, определяющая операции смешивания для исходных и целевых bitmap.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfBlendFunction()](#EmfBlendFunction--) |  |
| [EmfBlendFunction(int dwordData)](#EmfBlendFunction-int-) | Инициализирует новый экземпляр класса `EmfBlendFunction`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBlendOperation()](#getBlendOperation--) | Получает код операции смешивания. |
| [getBlendFlags()](#getBlendFlags--) | Получает флаги смешивания. |
| [getSrcConstantAlpha()](#getSrcConstantAlpha--) | Получает 8-битное беззнаковое целое, которое задает альфа-прозрачность, определяющую смешивание исходного и целевого битмапов. |
| [getAlphaFormat()](#getAlphaFormat--) | Получает структуру, определяющую, как интерпретируются пиксели источника и назначения относительно альфа-прозрачности. |
| [toInt()](#toInt--) | Преобразует строковое представление числа в целое. |
| [CloneTo(EmfBlendFunction that)](#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
| [Clone()](#Clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)](#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-) |  |
### EmfBlendFunction() {#EmfBlendFunction--}
```
public EmfBlendFunction()
```


### EmfBlendFunction(int dwordData) {#EmfBlendFunction-int-}
```
public EmfBlendFunction(int dwordData)
```


Инициализирует новый экземпляр класса `EmfBlendFunction`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| dwordData | int | Данные dword. |

### getBlendOperation() {#getBlendOperation--}
```
public byte getBlendOperation()
```


Получает код операции смешивания. Единственная определённая операция смешивания источника и назначения — 0x00, которая указывает, что исходный битмап ДОЛЖЕН быть объединён с битмапом назначения на основе значений альфа-прозрачности пикселей источника. См. следующие уравнения для подробностей.

**Returns:**
byte
### getBlendFlags() {#getBlendFlags--}
```
public byte getBlendFlags()
```


Получает флаги смешивания. Это значение ДОЛЖНО быть 0x00 и ДОЛЖНО игнорироваться.

**Returns:**
byte
### getSrcConstantAlpha() {#getSrcConstantAlpha--}
```
public byte getSrcConstantAlpha()
```


Получает 8-битное беззнаковое целое, которое задает альфа-прозрачность, определяющую смешивание исходного и целевого битмапов. Это значение ДОЛЖНО применяться ко всему исходному битмапу. Минимальное значение альфа-прозрачности, ноль, соответствует полной прозрачности, максимальное значение, 0xFF, соответствует полной непрозрачности. По сути, значение 0xFF указывает, что пиксельные альфа-значения определяют смешивание исходного и целевого битмапов. См. уравнения позже в этом разделе для подробностей.

**Returns:**
byte
### getAlphaFormat() {#getAlphaFormat--}
```
public byte getAlphaFormat()
```


Получает структуру, определяющую, как интерпретируются пиксели источника и назначения относительно альфа-прозрачности.

**Returns:**
byte
### toInt() {#toInt--}
```
public int toInt()
```


Преобразует строковое представление числа в целое.

**Returns:**
int — значение DWORD структуры.
### CloneTo(EmfBlendFunction that) {#CloneTo-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public void CloneTo(EmfBlendFunction that)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| that | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

### Clone() {#Clone--}
```
public EmfBlendFunction Clone()
```




**Returns:**
[EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction)
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2) {#isEquals-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-com.aspose.imaging.fileformats.emf.emf.records.EmfBlendFunction-}
```
public static boolean isEquals(EmfBlendFunction obj1, EmfBlendFunction obj2)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| obj1 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |
| obj2 | [EmfBlendFunction](../../com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction) |  |

**Returns:**
boolean
