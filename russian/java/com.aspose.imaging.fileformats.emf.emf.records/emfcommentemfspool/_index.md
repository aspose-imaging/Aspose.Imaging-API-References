---
title: "EmfCommentEmfSpool"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_COMMENT_EMFSPOOL содержит встроенные записи EMFSPOOL."
type: docs
weight: 28
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentemfspool/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfCommentEmfSpool extends EmfCommentRecordType
```

Запись EMR\_COMMENT\_EMFSPOOL содержит встроенные записи EMFSPOOL. Примечание: поля, которые не описаны в этом разделе, указаны в разделе 2.3.3.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfCommentEmfSpool(EmfRecord source)](#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfCommentEmfSpool`. |
| [EmfCommentEmfSpool()](#EmfCommentEmfSpool--) | Инициализирует новый экземпляр класса `EmfCommentEmfSpool`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Получает или задает 32-битное беззнаковое целое, которое идентифицирует эту запись комментария как содержащую записи EMFSPOOL. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Получает или задает 32-битное беззнаковое целое, которое идентифицирует эту запись комментария как содержащую записи EMFSPOOL. |
| [getEmfSpoolRecordIdentifier()](#getEmfSpoolRecordIdentifier--) | Получает или задает 32-битное беззнаковое целое, которое идентифицирует тип записи EMR\_COMMENT\_EMFSPOOL. |
| [setEmfSpoolRecordIdentifier(int value)](#setEmfSpoolRecordIdentifier-int-) | Получает или задает 32-битное беззнаковое целое, которое идентифицирует тип записи EMR\_COMMENT\_EMFSPOOL. |
| [getEmfSpoolRecords()](#getEmfSpoolRecords--) | Получает или задает переменного размера массив байтов, который содержит одну или несколько записей определений шрифтов EMFSPOOL (раздел [MS-EMFSPOOL] 2.2.3.3). |
| [setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)](#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---) | Получает или задает переменного размера массив байтов, который содержит одну или несколько записей определений шрифтов EMFSPOOL (раздел [MS-EMFSPOOL] 2.2.3.3). |
### EmfCommentEmfSpool(EmfRecord source) {#EmfCommentEmfSpool-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentEmfSpool(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfCommentEmfSpool`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfCommentEmfSpool() {#EmfCommentEmfSpool--}
```
public EmfCommentEmfSpool()
```


Инициализирует новый экземпляр класса `EmfCommentEmfSpool`.

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Получает или задает 32-битное беззнаковое целое, которое идентифицирует эту запись комментария как содержащую записи EMFSPOOL. Значение 0x00000000 указывает, что это запись EMR\_COMMENT\_EMFSPOOL.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Получает или задает 32-битное беззнаковое целое, которое идентифицирует эту запись комментария как содержащую записи EMFSPOOL. Значение 0x00000000 указывает, что это запись EMR\_COMMENT\_EMFSPOOL.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getEmfSpoolRecordIdentifier() {#getEmfSpoolRecordIdentifier--}
```
public int getEmfSpoolRecordIdentifier()
```


Получает или задает 32-битное беззнаковое целое, которое идентифицирует тип записи EMR\_COMMENT\_EMFSPOOL.

**Returns:**
int
### setEmfSpoolRecordIdentifier(int value) {#setEmfSpoolRecordIdentifier-int-}
```
public void setEmfSpoolRecordIdentifier(int value)
```


Получает или задает 32-битное беззнаковое целое, которое идентифицирует тип записи EMR\_COMMENT\_EMFSPOOL.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getEmfSpoolRecords() {#getEmfSpoolRecords--}
```
public EmfSpoolFontDefinitionRecordType[] getEmfSpoolRecords()
```


Получает или задает переменного размера массив байтов, который содержит одну или несколько записей определений шрифтов EMFSPOOL (раздел [MS-EMFSPOOL] 2.2.3.3).

**Returns:**
com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType[]
### setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value) {#setEmfSpoolRecords-com.aspose.imaging.fileformats.emf.emfspool.records.EmfSpoolFontDefinitionRecordType---}
```
public void setEmfSpoolRecords(EmfSpoolFontDefinitionRecordType[] value)
```


Получает или задает переменного размера массив байтов, который содержит одну или несколько записей определений шрифтов EMFSPOOL (раздел [MS-EMFSPOOL] 2.2.3.3).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfSpoolFontDefinitionRecordType\[\]](../../com.aspose.imaging.fileformats.emf.emfspool.records/emfspoolfontdefinitionrecordtype) |  |

