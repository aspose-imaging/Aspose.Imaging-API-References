---
title: "EmfPlusPathPointTypeRle"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusPathPointTypeRle задает типовые значения, связанные с точками на графическом пути, используя RLE‑сжатие."
type: docs
weight: 62
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype)
```
public final class EmfPlusPathPointTypeRle extends EmfPlusBasePointType
```

Объект EmfPlusPathPointTypeRle указывает значения типов, связанные с точками графического пути, используя RLE‑сжатие. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B|1|RunCount | PointType | B (1 бит): Если установлен, точки пути находятся на кривой Безье. Если сброшен, точки пути находятся на графической линии. RunCount (6 бит): количество последовательных точек, которое будет связано с типом в поле PointType. PointType (1 байт): объект EmfPlusPathPointType (раздел 2.2.2.31), который указывает тип, ассоциируемый с точками пути.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getData()](#getData--) | Получает или задаёт данные. |
| [setData(int value)](#setData-int-) | Получает или задаёт данные. |
| [getBezier()](#getBezier--) | Получает или задает значение, указывающее, является ли этот `EmfPlusPathPointTypeRle` кривой Безье. |
| [setBezier(boolean value)](#setBezier-boolean-) | Получает или задает значение, указывающее, является ли этот `EmfPlusPathPointTypeRle` кривой Безье. |
| [getRunCount()](#getRunCount--) | Получает или задает количество последовательных точек. |
| [setRunCount(byte value)](#setRunCount-byte-) | Получает или задает количество последовательных точек. |
| [getPointType()](#getPointType--) | Получает или задает тип точки. |
| [setPointType(EmfPlusPathPointType value)](#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-) | Получает или задает тип точки. |
### EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle--}
```
public EmfPlusPathPointTypeRle()
```


### getData() {#getData--}
```
public int getData()
```


Получает или задаёт данные.

Значение: данные.

**Returns:**
int
### setData(int value) {#setData-int-}
```
public void setData(int value)
```


Получает или задаёт данные.

Значение: данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBezier() {#getBezier--}
```
public boolean getBezier()
```


Получает или задает значение, указывающее, является ли этот `EmfPlusPathPointTypeRle` кривой Безье. Если установлено, точки пути находятся на кривой Безье. Если сброшено, точки пути находятся на графической линии.

Значение: `true`, если кривая Безье; иначе `false`.

**Returns:**
boolean
### setBezier(boolean value) {#setBezier-boolean-}
```
public void setBezier(boolean value)
```


Получает или задает значение, указывающее, является ли этот `EmfPlusPathPointTypeRle` кривой Безье. Если установлено, точки пути находятся на кривой Безье. Если сброшено, точки пути находятся на графической линии.

Значение: `true`, если кривая Безье; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getRunCount() {#getRunCount--}
```
public byte getRunCount()
```


Получает или задает количество последовательных точек. RunCount (6 бит): количество последовательных точек, которое является числом точек пути, связанных с типом в поле PointType

Значение: количество последовательных точек.

**Returns:**
byte
### setRunCount(byte value) {#setRunCount-byte-}
```
public void setRunCount(byte value)
```


Получает или задает количество последовательных точек. RunCount (6 бит): количество последовательных точек, которое является числом точек пути, связанных с типом в поле PointType

Значение: количество последовательных точек.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getPointType() {#getPointType--}
```
public EmfPlusPathPointType getPointType()
```


Получает или задает тип точки. PointType (1 байт): объект EmfPlusPathPointType (раздел 2.2.2.31), который указывает тип, ассоциируемый с точками пути.

Значение: тип точки.

**Returns:**
[EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype)
### setPointType(EmfPlusPathPointType value) {#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-}
```
public void setPointType(EmfPlusPathPointType value)
```


Получает или задает тип точки. PointType (1 байт): объект EmfPlusPathPointType (раздел 2.2.2.31), который указывает тип, ассоциируемый с точками пути.

Значение: тип точки.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype) |  |

