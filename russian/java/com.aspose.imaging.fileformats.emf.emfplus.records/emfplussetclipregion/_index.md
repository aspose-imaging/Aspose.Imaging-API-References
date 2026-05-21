---
title: "EmfPlusSetClipRegion"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusSetClipRegion объединяет текущую область отсечения с другой графической областью."
type: docs
weight: 57
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetclipregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusClippingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclippingrecordtype)
```
public final class EmfPlusSetClipRegion extends EmfPlusClippingRecordType
```

Запись EmfPlusSetClipRegion объединяет текущую область отсечения с другой графической областью. Новая текущая область отсечения устанавливается в результат выполнения операции CombineMode над предыдущей текущей областью отсечения и указанным объектом EmfPlusRegion.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusSetClipRegion(EmfPlusRecord source)](#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusSetClipRegion`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCm()](#getCm--) | Получает или задает CM (4 бита): определяет логическую операцию для объединения двух областей. |
| [setCm(byte value)](#setCm-byte-) | Получает или задает CM (4 бита): определяет логическую операцию для объединения двух областей. |
| [getObjectId()](#getObjectId--) | Получает или задает индекс объекта EmfPlusRegion (раздел 2.2.1.8) в таблице объектов EMF+. Значение ДОЛЖНО быть от 0 до 63 включительно. |
| [setObjectId(byte value)](#setObjectId-byte-) | Получает или задает индекс объекта EmfPlusRegion (раздел 2.2.1.8) в таблице объектов EMF+. Значение ДОЛЖНО быть от 0 до 63 включительно. |
### EmfPlusSetClipRegion(EmfPlusRecord source) {#EmfPlusSetClipRegion-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetClipRegion(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusSetClipRegion`.

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


Получает или задает индекс объекта EmfPlusRegion (раздел 2.2.1.8) в таблице объектов EMF+. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Получает или задает индекс объекта EmfPlusRegion (раздел 2.2.1.8) в таблице объектов EMF+. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

