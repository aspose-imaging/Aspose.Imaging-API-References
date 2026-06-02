---
title: "EmfPlusDrawPath"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusDrawPath определяет рисование графического пути."
type: docs
weight: 25
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawpath/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusDrawPath extends EmfPlusDrawingRecordType
```

Запись EmfPlusDrawPath определяет рисование графического пути.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusDrawPath(EmfPlusRecord source)](#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusDrawPath`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getObjectId()](#getObjectId--) | Получает или задает идентификатор объекта. |
| [setObjectId(byte value)](#setObjectId-byte-) | Получает или задает идентификатор объекта. |
| [getPenId()](#getPenId--) | Получает или задает идентификатор пера. 32-битное беззнаковое целое, которое указывает индекс в таблице объектов EMF+ для объекта EmfPlusPen (раздел 2.2.1.7), используемый для рисования EmfPlusPath. |
| [setPenId(int value)](#setPenId-int-) | Получает или задает идентификатор пера. 32-битное беззнаковое целое, которое указывает индекс в таблице объектов EMF+ для объекта EmfPlusPen (раздел 2.2.1.7), используемый для рисования EmfPlusPath. |
### EmfPlusDrawPath(EmfPlusRecord source) {#EmfPlusDrawPath-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusDrawPath(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusDrawPath`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusPath (раздел 2.2.1.6), который будет отрисован, в таблице объектов EMF+. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Получает или задает идентификатор объекта. Индекс объекта EmfPlusPath (раздел 2.2.1.6), который будет отрисован, в таблице объектов EMF+. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getPenId() {#getPenId--}
```
public int getPenId()
```


Получает или задает идентификатор пера. 32-битное беззнаковое целое, которое указывает индекс в таблице объектов EMF+ для объекта EmfPlusPen (раздел 2.2.1.7), используемый для рисования EmfPlusPath. Значение ДОЛЖНО быть от 0 до 63 включительно.

**Returns:**
int
### setPenId(int value) {#setPenId-int-}
```
public void setPenId(int value)
```


Получает или задает идентификатор пера. 32-битное беззнаковое целое, которое указывает индекс в таблице объектов EMF+ для объекта EmfPlusPen (раздел 2.2.1.7), используемый для рисования EmfPlusPath. Значение ДОЛЖНО быть от 0 до 63 включительно.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

