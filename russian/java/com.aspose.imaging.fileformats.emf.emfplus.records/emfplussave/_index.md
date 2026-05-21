---
title: "EmfPlusSave"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusSave сохраняет состояние графики, идентифицированное указанным индексом, в стеке сохранённых состояний графики."
type: docs
weight: 51
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging/fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusSave extends EmfPlusStateRecordType
```

Запись EmfPlusSave сохраняет состояние графики, определённое указанным индексом, в стек сохранённых состояний графики.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusSave(EmfPlusRecord source)](#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusSave`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Получает или задает 32-битное беззнаковое целое число, которое указывает уровень, связанный с состоянием графики. |
| [setStackIndex(int value)](#setStackIndex-int-) | Получает или задает 32-битное беззнаковое целое число, которое указывает уровень, связанный с состоянием графики. |
### EmfPlusSave(EmfPlusRecord source) {#EmfPlusSave-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSave(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusSave`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Получает или задает 32-битное беззнаковое целое число, которое указывает уровень, связанный с состоянием графики. Значение уровня может использоваться последующей записью EmfPlusRestore (раздел 2.3.7.4) для восстановления состояния графики.

Значение: Индекс стека.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Получает или задает 32-битное беззнаковое целое число, которое указывает уровень, связанный с состоянием графики. Значение уровня может использоваться последующей записью EmfPlusRestore (раздел 2.3.7.4) для восстановления состояния графики.

Значение: Индекс стека.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

