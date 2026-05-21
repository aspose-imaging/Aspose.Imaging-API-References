---
title: "EmfPlusRestore"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusRestore восстанавливает состояние графики, идентифицированное указанным индексом, из стека сохранённых состояний графики."
type: docs
weight: 49
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusStateRecordType](../../com.aspose.imaging/fileformats.emf.emfplus.records/emfplusstaterecordtype)
```
public final class EmfPlusRestore extends EmfPlusStateRecordType
```

Запись EmfPlusRestore восстанавливает состояние графики, определённое указанным индексом, из стека сохранённых состояний графики.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusRestore(EmfPlusRecord source)](#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusRestore`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getStackIndex()](#getStackIndex--) | Получает или задаёт 32‑битное беззнаковое целое, которое указывает уровень, связанный с состоянием графики. |
| [setStackIndex(int value)](#setStackIndex-int-) | Получает или задаёт 32‑битное беззнаковое целое, которое указывает уровень, связанный с состоянием графики. |
### EmfPlusRestore(EmfPlusRecord source) {#EmfPlusRestore-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRestore(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusRestore`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getStackIndex() {#getStackIndex--}
```
public int getStackIndex()
```


Получает или задаёт 32‑битное беззнаковое целое, которое указывает уровень, связанный с состоянием графики. Значение уровня было присвоено состоянию графики предыдущей записью EmfPlusSave (раздел 2.3.7.5).

Значение: Индекс стека.

**Returns:**
int
### setStackIndex(int value) {#setStackIndex-int-}
```
public void setStackIndex(int value)
```


Получает или задаёт 32‑битное беззнаковое целое, которое указывает уровень, связанный с состоянием графики. Значение уровня было присвоено состоянию графики предыдущей записью EmfPlusSave (раздел 2.3.7.5).

Значение: Индекс стека.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

