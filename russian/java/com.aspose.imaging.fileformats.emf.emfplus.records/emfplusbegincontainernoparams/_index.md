---
title: "EmfPlusBeginContainerNoParams"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusBeginContainerNoParams открывает новый контейнер графического состояния."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusbegincontainernoparams/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging/fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusBeginContainerNoParams extends EmfPlusStateRecordType
```

Запись EmfPlusBeginContainerNoParams открывает новый контейнер графического состояния.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusBeginContainerNoParams(EmfPlusRecord source)](#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusBeginContainerNoParams`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Получает или задает 32-битное беззнаковое целое, которое указывает индекс, связываемый с контейнером состояния графики. |
| [setStackIndex(int value)](#setStackIndex-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает индекс, связываемый с контейнером состояния графики. |
### EmfPlusBeginContainerNoParams(EmfPlusRecord source) {#EmfPlusBeginContainerNoParams-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusBeginContainerNoParams(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusBeginContainerNoParams`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Получает или задает 32-битное беззнаковое целое, которое указывает индекс, связываемый с контейнером состояния графики. Индекс ДОЛЖЕН быть использован последующей записью EmfPlusEndContainer (раздел 2.3.7.3) для закрытия контейнера состояния графики.

Значение: Индекс стека.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает индекс, связываемый с контейнером состояния графики. Индекс ДОЛЖЕН быть использован последующей записью EmfPlusEndContainer (раздел 2.3.7.3) для закрытия контейнера состояния графики.

Значение: Индекс стека.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

