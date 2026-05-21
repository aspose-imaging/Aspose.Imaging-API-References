---
title: "EmfDeleteObject"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_DELETEOBJECT удаляет графический объект, указанный его индексом в таблице объектов EMF раздел 3.1.1.1."
type: docs
weight: 43
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfdeleteobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfDeleteObject extends EmfRecord
```

Запись EMR\_DELETEOBJECT удаляет графический объект, который указывается его индексом в таблице объектов EMF (раздел 3.1.1.1).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfDeleteObject(EmfRecord record)](#EmfDeleteObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfDeleteObject`. |
| [EmfDeleteObject()](#EmfDeleteObject--) | Инициализирует новый экземпляр класса `EmfDeleteObject`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getObjectHandle()](#getObjectHandle--) | Получает или задает 32‑битное беззнаковое целое, которое указывает либо индекс графического объекта в таблице объектов EMF, либо индекс предустановленного объекта из перечисления StockObject. |
| [setObjectHandle(int value)](#setObjectHandle-int-) | Получает или задает 32‑битное беззнаковое целое, которое указывает либо индекс графического объекта в таблице объектов EMF, либо индекс предустановленного объекта из перечисления StockObject. |
### EmfDeleteObject(EmfRecord record) {#EmfDeleteObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDeleteObject(EmfRecord record)
```


Инициализирует новый экземпляр класса `EmfDeleteObject`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Запись. |

### EmfDeleteObject() {#EmfDeleteObject--}
```
public EmfDeleteObject()
```


Инициализирует новый экземпляр класса `EmfDeleteObject`.

### getObjectHandle() {#getObjectHandle--}
```
public int getObjectHandle()
```


Получает или задает 32‑битное беззнаковое целое, которое указывает либо индекс графического объекта в таблице объектов EMF, либо индекс предустановленного объекта из перечисления StockObject.

**Returns:**
int
### setObjectHandle(int value) {#setObjectHandle-int-}
```
public void setObjectHandle(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое указывает либо индекс графического объекта в таблице объектов EMF, либо индекс предустановленного объекта из перечисления StockObject.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

