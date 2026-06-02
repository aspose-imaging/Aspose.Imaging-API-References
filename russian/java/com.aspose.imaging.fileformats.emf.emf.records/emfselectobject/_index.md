---
title: "EmfSelectObject"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SELECTOBJECT добавляет графический объект в текущий контекст устройства воспроизведения метафайла."
type: docs
weight: 116
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfselectobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public final class EmfSelectObject extends EmfRecord
```

Запись EMR\_SELECTOBJECT добавляет графический объект в текущий контекст устройства воспроизведения метафайла. Объект указывается либо его индексом в таблице объектов EMF (раздел 3.1.1.1), либо его значением из перечисления StockObject (раздел 2.1.31).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSelectObject(EmfRecord record)](#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSelectObject`. |
| [EmfSelectObject()](#EmfSelectObject--) | Инициализирует новый экземпляр класса `EmfSelectObject`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getObjectHandle()](#getObjectHandle--) | Получает или задает 32-битное беззнаковое целое, определяющее либо индекс графического объекта в таблице объектов EMF, либо индекс штатного объекта из перечисления `Consts.EmfStockObject`. |
| [setObjectHandle(int value)](#setObjectHandle-int-) | Получает или задает 32-битное беззнаковое целое, определяющее либо индекс графического объекта в таблице объектов EMF, либо индекс штатного объекта из перечисления `Consts.EmfStockObject`. |
### EmfSelectObject(EmfRecord record) {#EmfSelectObject-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSelectObject(EmfRecord record)
```


Инициализирует новый экземпляр класса `EmfSelectObject`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Запись. |

### EmfSelectObject() {#EmfSelectObject--}
```
public EmfSelectObject()
```


Инициализирует новый экземпляр класса `EmfSelectObject`.

### getObjectHandle() {#getObjectHandle--}
```
public int getObjectHandle()
```


Получает или задает 32-битное беззнаковое целое, определяющее либо индекс графического объекта в таблице объектов EMF, либо индекс штатного объекта из перечисления `Consts.EmfStockObject`.

**Returns:**
int
### setObjectHandle(int value) {#setObjectHandle-int-}
```
public void setObjectHandle(int value)
```


Получает или задает 32-битное беззнаковое целое, определяющее либо индекс графического объекта в таблице объектов EMF, либо индекс штатного объекта из перечисления `Consts.EmfStockObject`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

