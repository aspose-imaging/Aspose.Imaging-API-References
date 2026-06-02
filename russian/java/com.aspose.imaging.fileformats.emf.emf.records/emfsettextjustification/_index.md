---
title: "EmfSetTextJustification"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_SETTEXTJUSTIFICATION определяет количество дополнительного пространства, добавляемого к разрывным символам для выравнивания текста."
type: docs
weight: 141
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfsettextjustification/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetTextJustification extends EmfStateRecordType
```

Запись EMR\_SETTEXTJUSTIFICATION указывает количество дополнительного пространства, добавляемого к разрывным символам для выравнивания текста.

Вместо использования записи EMR\_SETTEXTJUSTIFICATION реализация ДОЛЖНА использовать запись EMR\_EXTTEXTOUTW (раздел 2.3.5.8) для выполнения этой функции.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfSetTextJustification(EmfRecord source)](#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfSetTextJustification`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getNBreakExtra()](#getNBreakExtra--) | Получает или задает 32-битное знаковое целое, которое указывает общее количество дополнительного пространства в логических единицах, которое следует добавить. |
| [setNBreakExtra(int value)](#setNBreakExtra-int-) | Получает или задает 32-битное знаковое целое, которое указывает общее количество дополнительного пространства в логических единицах, которое следует добавить. |
| [getNBreakCount()](#getNBreakCount--) | Получает или задает 32-битное знаковое целое, которое указывает количество символов разрыва. |
| [setNBreakCount(int value)](#setNBreakCount-int-) | Получает или задает 32-битное знаковое целое, которое указывает количество символов разрыва. |
### EmfSetTextJustification(EmfRecord source) {#EmfSetTextJustification-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetTextJustification(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfSetTextJustification`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getNBreakExtra() {#getNBreakExtra--}
```
public int getNBreakExtra()
```


Получает или задает 32-битное знаковое целое, которое указывает общее количество дополнительного пространства в логических единицах, которое следует добавить.

**Returns:**
int
### setNBreakExtra(int value) {#setNBreakExtra-int-}
```
public void setNBreakExtra(int value)
```


Получает или задает 32-битное знаковое целое, которое указывает общее количество дополнительного пространства в логических единицах, которое следует добавить.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getNBreakCount() {#getNBreakCount--}
```
public int getNBreakCount()
```


Получает или задает 32-битное знаковое целое, которое указывает количество символов разрыва.

**Returns:**
int
### setNBreakCount(int value) {#setNBreakCount-int-}
```
public void setNBreakCount(int value)
```


Получает или задает 32-битное знаковое целое, которое указывает количество символов разрыва.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

