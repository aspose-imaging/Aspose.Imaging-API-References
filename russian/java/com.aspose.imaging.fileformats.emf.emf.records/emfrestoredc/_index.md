---
title: "EmfRestoreDc"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_RESTOREDC восстанавливает контекст устройства воспроизведения до указанного состояния."
type: docs
weight: 109
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfrestoredc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfRestoreDc extends EmfStateRecordType
```

Запись EMR\_RESTOREDC восстанавливает контекст устройства воспроизведения до указанного состояния. Контекст устройства воспроизведения восстанавливается снятием информации о состоянии со стека, который был создан предыдущими записями EMR\_SAVEDC (раздел 2.3.11).

Стек может содержать информацию о состоянии для нескольких экземпляров контекста устройства воспроизведения. При восстановлении состояния все более недавно сохранённые экземпляры состояния ДОЛЖНЫ быть отброшены.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfRestoreDc(EmfRecord source)](#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfRestoreDc`. |
| [EmfRestoreDc()](#EmfRestoreDc--) | Инициализирует новый экземпляр класса `EmfRestoreDc`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getSavedDc()](#getSavedDc--) | Получает или задает 32-битное знаковое целое, которое указывает сохраняемое состояние для восстановления относительно текущего состояния. |
| [setSavedDc(int value)](#setSavedDc-int-) | Получает или задает 32-битное знаковое целое, которое указывает сохраняемое состояние для восстановления относительно текущего состояния. |
### EmfRestoreDc(EmfRecord source) {#EmfRestoreDc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRestoreDc(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfRestoreDc`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfRestoreDc() {#EmfRestoreDc--}
```
public EmfRestoreDc()
```


Инициализирует новый экземпляр класса `EmfRestoreDc`.

### getSavedDc() {#getSavedDc--}
```
public int getSavedDc()
```


Получает или задает 32-битное знаковое целое, которое указывает сохраняемое состояние для восстановления относительно текущего состояния. Это значение ДОЛЖНО быть отрицательным; \\u20131 представляет состояние, которое было сохранено последним в стеке, \\u20132 — предыдущее и т.д.

**Returns:**
int
### setSavedDc(int value) {#setSavedDc-int-}
```
public void setSavedDc(int value)
```


Получает или задает 32-битное знаковое целое, которое указывает сохраняемое состояние для восстановления относительно текущего состояния. Это значение ДОЛЖНО быть отрицательным; \\u20131 представляет состояние, которое было сохранено последним в стеке, \\u20132 — предыдущее и т.д.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

