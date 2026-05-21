---
title: "EmfPlusObject"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusObject указывает объект для использования в графических операциях."
type: docs
weight: 42
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusObject extends EmfPlusObjectRecordType
```

Запись EmfPlusObject определяет объект для использования в графических операциях. Определение объекта может охватывать несколько записей, что указывается значением поля Flags.

Запись EmfPlusObject является универсальной; она используется для всех типов объектов. Значения, специфичные для конкретных типов объектов, находятся в поле ObjectData. Концептуальная модель управления графическими объектами описана в разделе Управление графическими объектами (раздел 3.1.2).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusObject(EmfPlusRecord source)](#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusObject`. |
## Методы

| Метод | Описание |
| --- | --- |
| [isContinuable()](#isContinuable--) | Получает или задает значение, указывающее, может ли этот экземпляр быть продолжен. |
| [setContinuable(boolean value)](#setContinuable-boolean-) | Получает или задает значение, указывающее, может ли этот экземпляр быть продолжен. |
| [getObjectType()](#getObjectType--) | Получает или задает тип объекта. |
| [setObjectType(byte value)](#setObjectType-byte-) | Получает или задает тип объекта. |
| [getObjectId()](#getObjectId--) | Получает или задает идентификатор объекта. |
| [setObjectId(byte value)](#setObjectId-byte-) | Получает или задает идентификатор объекта. |
| [getTotalObjectSize()](#getTotalObjectSize--) | Получает или задает общий размер объекта. |
| [setTotalObjectSize(int value)](#setTotalObjectSize-int-) | Получает или задает общий размер объекта. |
| [getObjectData()](#getObjectData--) | Получает или задает массив байтов, содержащий данные для типа объекта, указанного в поле Flags. |
| [setObjectData(EmfPlusGraphicsObjectType value)](#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-) | Получает или задает массив байтов, содержащий данные для типа объекта, указанного в поле Flags. |
### EmfPlusObject(EmfPlusRecord source) {#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusObject(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusObject`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### isContinuable() {#isContinuable--}
```
public boolean isContinuable()
```


Получает или задает значение, указывающее, может ли этот экземпляр быть продолжен. Указывает, что определение объекта продолжается в следующей записи EmfPlusObject. Этот флаг никогда не устанавливается в последней записи, определяющей объект.

Значение: `true`, если этот экземпляр сжат; иначе `false`.

**Returns:**
boolean
### setContinuable(boolean value) {#setContinuable-boolean-}
```
public void setContinuable(boolean value)
```


Получает или задает значение, указывающее, может ли этот экземпляр быть продолжен. Указывает, что определение объекта продолжается в следующей записи EmfPlusObject. Этот флаг никогда не устанавливается в последней записи, определяющей объект.

Значение: `true`, если этот экземпляр сжат; иначе `false`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getObjectType() {#getObjectType--}
```
public byte getObjectType()
```


Получает или задает тип объекта.

Значение: тип объекта.

**Returns:**
byte
### setObjectType(byte value) {#setObjectType-byte-}
```
public void setObjectType(byte value)
```


Получает или задает тип объекта.

Значение: тип объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Получает или задает идентификатор объекта. Индекс в таблице EMF+ Object Table, связывающийся с объектом, созданным этой записью. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Получает или задает идентификатор объекта. Индекс в таблице EMF+ Object Table, связывающийся с объектом, созданным этой записью. Значение ДОЛЖНО быть от 0 до 63 включительно.

Значение: идентификатор объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getTotalObjectSize() {#getTotalObjectSize--}
```
public int getTotalObjectSize()
```


Получает или задает общий размер объекта. Если запись может быть продолжена, при установленном бите continue это поле будет присутствовать. Продолжающиеся объекты имеют несколько записей EMF+, начиная с EmfPlusContineudObjectRecord. Каждая запись EmfPlusContinuedObjectRecord будет содержать поле TotalObjectSize. После чтения количества байтов, указанного в TotalObjectSize, следующая запись EMF+ не будет рассматриваться как часть продолжающегося объекта.

Значение: общий размер объекта.

**Returns:**
int
### setTotalObjectSize(int value) {#setTotalObjectSize-int-}
```
public void setTotalObjectSize(int value)
```


Получает или задает общий размер объекта. Если запись может быть продолжена, при установленном бите continue это поле будет присутствовать. Продолжающиеся объекты имеют несколько записей EMF+, начиная с EmfPlusContineudObjectRecord. Каждая запись EmfPlusContinuedObjectRecord будет содержать поле TotalObjectSize. После чтения количества байтов, указанного в TotalObjectSize, следующая запись EMF+ не будет рассматриваться как часть продолжающегося объекта.

Значение: общий размер объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getObjectData() {#getObjectData--}
```
public EmfPlusGraphicsObjectType getObjectData()
```


Получает или задает массив байтов, содержащий данные для типа объекта, указанного в поле Flags. Содержание и формат данных могут различаться для каждого типа объекта. См. отдельные определения объектов в разделе 2.2.1 для получения дополнительной информации.

Значение: данные объекта.

**Returns:**
[EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
### setObjectData(EmfPlusGraphicsObjectType value) {#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-}
```
public void setObjectData(EmfPlusGraphicsObjectType value)
```


Получает или задает массив байтов, содержащий данные для типа объекта, указанного в поле Flags. Содержание и формат данных могут различаться для каждого типа объекта. См. отдельные определения объектов в разделе 2.2.1 для получения дополнительной информации.

Значение: данные объекта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype) |  |

