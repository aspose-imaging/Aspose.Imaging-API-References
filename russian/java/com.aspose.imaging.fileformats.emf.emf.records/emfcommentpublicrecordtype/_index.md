---
title: "EmfCommentPublicRecordType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Типы записей EMR_COMMENT_PUBLIC определяют расширения обработки EMF."
type: docs
weight: 31
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public abstract class EmfCommentPublicRecordType extends EmfCommentRecordType
```

Типы записей EMR\_COMMENT\_PUBLIC указывают расширения обработки EMF.
## Методы

| Метод | Описание |
| --- | --- |
| [getCommentIdentifier()](#getCommentIdentifier--) | Получает или задает 32‑битное беззнаковое целое, идентифицирующее эту запись комментария как содержащую публичные данные. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Получает или задает 32‑битное беззнаковое целое, идентифицирующее эту запись комментария как содержащую публичные данные. |
| [getPublicCommentIdentifier()](#getPublicCommentIdentifier--) | Получает или задает 32‑битное беззнаковое целое, определяющее тип публичной записи комментария. |
| [setPublicCommentIdentifier(long value)](#setPublicCommentIdentifier-long-) | Получает или задает 32‑битное беззнаковое целое, определяющее тип публичной записи комментария. |
### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Получает или задает 32‑битное беззнаковое целое, идентифицирующее эту запись комментария как содержащую публичные данные. Значение 0x43494447, которое является ASCII‑строкой \"CIDG\", идентифицирует её как запись EMR\_COMMENT\_PUBLIC.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Получает или задает 32‑битное беззнаковое целое, идентифицирующее эту запись комментария как содержащую публичные данные. Значение 0x43494447, которое является ASCII‑строкой \"CIDG\", идентифицирует её как запись EMR\_COMMENT\_PUBLIC.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getPublicCommentIdentifier() {#getPublicCommentIdentifier--}
```
public long getPublicCommentIdentifier()
```


Получает или задает 32‑битное беззнаковое целое, определяющее тип публичной записи комментария. Оно ДОЛЖНО быть одним из значений, перечисленных в предыдущей таблице, которые указаны в перечислении EmrComment (раздел 2.1.10), если только на сервере печати не реализованы дополнительные типы публичных записей комментариев.

**Returns:**
long
### setPublicCommentIdentifier(long value) {#setPublicCommentIdentifier-long-}
```
public void setPublicCommentIdentifier(long value)
```


Получает или задает 32‑битное беззнаковое целое, определяющее тип публичной записи комментария. Оно ДОЛЖНО быть одним из значений, перечисленных в предыдущей таблице, которые указаны в перечислении EmrComment (раздел 2.1.10), если только на сервере печати не реализованы дополнительные типы публичных записей комментариев.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

