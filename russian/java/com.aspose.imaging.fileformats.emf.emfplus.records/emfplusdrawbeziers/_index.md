---
title: "EmfPlusDrawBeziers"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusDrawBeziers определяет рисование последовательности соединённых кривых Безье."
type: docs
weight: 17
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawbeziers/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawBeziers extends EmfPlusDrawingRecordType
```

Запись EmfPlusDrawBeziers определяет отрисовку последовательности соединённых кривых Безье. Порядок точек данных Безье: начальная точка, контрольная точка 1, контрольная точка 2 и конечная точка. Для получения дополнительной информации см. [MSDN-DrawBeziers].
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusDrawBeziers(EmfPlusRecord source)](#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusDrawBeziers`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCompressed()](#getCompressed--) | Получает или задает значение, указывающее, сжаты ли PointData. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Получает или задает значение, указывающее, сжаты ли PointData. |
| [getRelative()](#getRelative--) | Получает или задает значение, указывающее, является ли PointData относительным. |
| [setRelative(boolean value)](#setRelative-boolean-) | Получает или задает значение, указывающее, является ли PointData относительным. |
| [getObjectId()](#getObjectId--) | Получает или задает идентификатор объекта. |
| [setObjectId(byte value)](#setObjectId-byte-) | Получает или задает идентификатор объекта. |
| [getPointData()](#getPointData--) | Получает или задает данные точек — массив из Count точек, определяющих начальные, конечные и контрольные точки кривых Безье. |
| [setPointData(PointF[] value)](#setPointData-com.aspose.imaging.PointF---) | Получает или задает данные точек — массив из Count точек, определяющих начальные, конечные и контрольные точки кривых Безье. |
### EmfPlusDrawBeziers(EmfPlusRecord source) {#EmfPlusDrawBeziers-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawBeziers(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusDrawBeziers`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getCompressed() {#getCompressed--}
```
public boolean getCompressed()
```


Получает или задает значение, указывающее, сжаты ли данные PointData. Если установлен, PointData задаёт абсолютные координаты в системе координат с 16‑разрядными целочисленными значениями. Если сброшен, PointData задаёт абсолютные координаты с 32‑разрядными числами с плавающей точкой. Примечание: если установлен флаг Relative (ниже), этот флаг не определён и ДОЛЖЕН быть игнорирован.

Значение: `true`, если сжато; иначе `false`.

**Returns:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public void setCompressed(boolean value)
```


Получает или задает значение, указывающее, сжаты ли данные PointData. Если установлен, PointData задаёт абсолютные координаты в системе координат с 16‑разрядными целочисленными значениями. Если сброшен, PointData задаёт абсолютные координаты с 32‑разрядными числами с плавающей точкой. Примечание: если установлен флаг Relative (ниже), этот флаг не определён и ДОЛЖЕН быть игнорирован.

Значение: `true`, если сжато; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getRelative() {#getRelative--}
```
public boolean getRelative()
```


Получает или задает значение, указывающее, является ли PointData относительным. Если установлен, каждый элемент в PointData указывает расположение в системе координат, относительное к расположению, заданному предыдущим элементом массива. Для первого элемента в PointData предполагается предыдущее расположение с координатами (0,0). Если бит сброшен, PointData задаёт абсолютные координаты в соответствии с флагом C. Примечание: если этот флаг установлен, флаг C (выше) не определён и ДОЛЖЕН быть игнорирован.

Значение: `true`, если относительный; иначе `false`.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public void setRelative(boolean value)
```


Получает или задает значение, указывающее, является ли PointData относительным. Если установлен, каждый элемент в PointData указывает расположение в системе координат, относительное к расположению, заданному предыдущим элементом массива. Для первого элемента в PointData предполагается предыдущее расположение с координатами (0,0). Если бит сброшен, PointData задаёт абсолютные координаты в соответствии с флагом C. Примечание: если этот флаг установлен, флаг C (выше) не определён и ДОЛЖЕН быть игнорирован.

Значение: `true`, если относительный; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+, используемый для отрисовки кривых Безье. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusPen (раздел 2.2.1.7) в таблице объектов EMF+, используемый для отрисовки кривых Безье. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getPointData() {#getPointData--}
```
public PointF[] getPointData()
```


Получает или задает данные точек — массив из Count точек, определяющих начальные, конечные и контрольные точки кривых Безье. Конечная координата одной кривой Безье является начальной координатой следующей. Контрольные точки используются для создания эффекта Безье. Тип данных в этом массиве задаётся полем Flags следующим образом: Тип данных Значение EmfPlusPointR объект (раздел 2.2.2.37) Если флаг P установлен в Flags, точки задают относительные положения. EmfPlusPointF объект (раздел 2.2.2.36) Если биты P и C сброшены в Flags, точки задают абсолютные положения. EmfPlusPoint объект (раздел 2.2.2.35) Если бит P сброшен, а бит C установлен в Flags, точки задают относительные положения. Кривая Безье не проходит через свои контрольные точки. Контрольные точки служат как

**Returns:**
com.aspose.imaging.PointF[]
### setPointData(PointF[] value) {#setPointData-com.aspose.imaging.PointF---}
```
public void setPointData(PointF[] value)
```


Получает или задает данные точек — массив из Count точек, определяющих начальные, конечные и контрольные точки кривых Безье. Конечная координата одной кривой Безье является начальной координатой следующей. Контрольные точки используются для создания эффекта Безье. Тип данных в этом массиве задаётся полем Flags следующим образом: Тип данных Значение EmfPlusPointR объект (раздел 2.2.2.37) Если флаг P установлен в Flags, точки задают относительные положения. EmfPlusPointF объект (раздел 2.2.2.36) Если биты P и C сброшены в Flags, точки задают абсолютные положения. EmfPlusPoint объект (раздел 2.2.2.35) Если бит P сброшен, а бит C установлен в Flags, точки задают относительные положения. Кривая Безье не проходит через свои контрольные точки. Контрольные точки служат как

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [PointF\[\]](../../com.aspose.imaging/pointf) |  |

