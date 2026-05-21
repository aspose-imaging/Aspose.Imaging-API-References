---
title: "EmfCommentEmfPlus"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_COMMENT_EMFPLUS содержит встроенные записи EMF."
type: docs
weight: 27
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfplus/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfPlus extends EmfCommentRecordType
```

Запись EMR\_COMMENT\_EMFPLUS содержит встроенные записи EMF+. Примечание: поля, не описанные в этом разделе, указаны в разделе 2.3.3.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfCommentEmfPlus(EmfRecord source)](#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfCommentEmfPlus`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Получает или задает 32‑битное беззнаковое целое, которое идентифицирует эту запись комментария как содержащую записи EMF+. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Получает или задает 32‑битное беззнаковое целое, которое идентифицирует эту запись комментария как содержащую записи EMF+. |
| [getEmfPlusRecords()](#getEmfPlusRecords--) | Получает или задает массив байтов, содержащий одну или несколько записей EMF+ ([MS-EMFPLUS] раздел 2.3.1). |
| [setEmfPlusRecords(EmfPlusRecord[] value)](#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---) | Получает или задает массив байтов, содержащий одну или несколько записей EMF+ ([MS-EMFPLUS] раздел 2.3.1). |
### EmfCommentEmfPlus(EmfRecord source) {#EmfCommentEmfPlus-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfPlus(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfCommentEmfPlus`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Получает или задает 32‑битное беззнаковое целое, которое идентифицирует эту запись комментария как содержащую записи EMF+. Значение 0x2B464D45, которое является ASCII‑строкой "+FME", идентифицирует её как запись EMR\_COMMENT\_EMFPLUS.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Получает или задает 32‑битное беззнаковое целое, которое идентифицирует эту запись комментария как содержащую записи EMF+. Значение 0x2B464D45, которое является ASCII‑строкой "+FME", идентифицирует её как запись EMR\_COMMENT\_EMFPLUS.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getEmfPlusRecords() {#getEmfPlusRecords--}
```
public EmfPlusRecord[] getEmfPlusRecords()
```


Получает или задает массив байтов, содержащий одну или несколько записей EMF+ ([MS-EMFPLUS] раздел 2.3.1).

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord[]
### setEmfPlusRecords(EmfPlusRecord[] value) {#setEmfPlusRecords-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord---}
```
public void setEmfPlusRecords(EmfPlusRecord[] value)
```


Получает или задает массив байтов, содержащий одну или несколько записей EMF+ ([MS-EMFPLUS] раздел 2.3.1).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfPlusRecord\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) |  |

