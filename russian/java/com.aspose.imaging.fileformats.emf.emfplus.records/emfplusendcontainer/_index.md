---
title: "EmfPlusEndContainer"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusEndContainer закрывает контейнер состояния графики, который ранее был открыт операцией начала контейнера."
type: docs
weight: 30
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusendcontainer/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging/fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusEndContainer extends EmfPlusStateRecordType
```

Запись EmfPlusEndContainer закрывает контейнер состояния графики, который ранее был открыт операцией начала контейнера.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusEndContainer(EmfPlusRecord source)](#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusEndContainer`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Получает или задает 32-битное беззнаковое целое, которое указывает индекс контейнера состояния графики. |
| [setStackIndex(int value)](#setStackIndex-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает индекс контейнера состояния графики. |
### EmfPlusEndContainer(EmfPlusRecord source) {#EmfPlusEndContainer-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusEndContainer(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusEndContainer`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Получает или задает 32-битное беззнаковое целое, которое указывает индекс контейнера состояния графики. Индекс MUST должен соответствовать значению, связанному с контейнером состояния графики, открытым предыдущей записью EmfPlusBeginContainer (section 2.3.7.1) или EmfPlusBeginContainerNoParams (section 2.3.7.2).

Значение: Индекс стека.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает индекс контейнера состояния графики. Индекс MUST должен соответствовать значению, связанному с контейнером состояния графики, открытым предыдущей записью EmfPlusBeginContainer (section 2.3.7.1) или EmfPlusBeginContainerNoParams (section 2.3.7.2).

Значение: Индекс стека.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

