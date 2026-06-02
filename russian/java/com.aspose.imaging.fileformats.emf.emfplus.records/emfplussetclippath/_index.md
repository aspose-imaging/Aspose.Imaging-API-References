---
title: "EmfPlusSetClipPath"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusSetClipPath объединяет текущую область отсечения с графическим путем."
type: docs
weight: 55
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclippath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipPath extends EmfPlusClippingRecordType
```

Запись EmfPlusSetClipPath объединяет текущий регион отсечения с графическим путем. Новый текущий регион отсечения устанавливается в результат операции CombineMode.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusSetClipPath(EmfPlusRecord source)](#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusSetClipPath`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCm()](#getCm--) | Получает или задает CM (4 бита): определяет логическую операцию для объединения двух областей. |
| [setCm(byte value)](#setCm-byte-) | Получает или задает CM (4 бита): определяет логическую операцию для объединения двух областей. |
| [getObjectId()](#getObjectId--) | Получает или задает индекс объекта EmfPlusPath (раздел 2.2.1.6) в таблице объектов EMF+. |
| [setObjectId(byte value)](#setObjectId-byte-) | Получает или задает индекс объекта EmfPlusPath (раздел 2.2.1.6) в таблице объектов EMF+. |
### EmfPlusSetClipPath(EmfPlusRecord source) {#EmfPlusSetClipPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipPath(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusSetClipPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getCm() {#getCm--}
```
public byte getCm()
```


Получает или задает CM (4 бита): определяет логическую операцию для объединения двух областей. См. перечисление CombineMode (раздел 2.1.1.4) для значений.

Значение: cm.

**Returns:**
byte
### setCm(byte value) {#setCm-byte-}
```
public void setCm(byte value)
```


Получает или задает CM (4 бита): определяет логическую операцию для объединения двух областей. См. перечисление CombineMode (раздел 2.1.1.4) для значений.

Значение: cm.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Получает или задает индекс объекта EmfPlusPath (раздел 2.2.1.6) в таблице объектов EMF+. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Получает или задает индекс объекта EmfPlusPath (раздел 2.2.1.6) в таблице объектов EMF+. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

